# Variables

## Main info

The application passes variables to the templates for manipulation in the template. Variables may have attributes or elements you can access, too. The visual representation of a variable depends heavily on the application providing it.

Use a dot (.) to access attributes of a variable (methods or properties of a PHP object, or items of a PHP array):

`{{ foo.bar }}`

!!! Note
    It's important to know that the curly braces are not part of the variable but the print statement. When accessing variables inside tags, don't put the braces around them.

If a variable or attribute does not exist, the behavior depends on the strict_variables option value (see environment options):

When `false`, it returns null

When `true`, it throws an exception.

## Implementation

For convenience's sake foo.bar does the following things on the PHP layer:

* check if foo is an array and bar a valid element;
* if not, and if foo is an object, check that bar is a valid property;
* if not, and if foo is an object, check that bar is a valid method (even if bar is the constructor - use __construct() instead);
* if not, and if foo is an object, check that getBar is a valid method;
* if not, and if foo is an object, check that isBar is a valid method;
* if not, and if foo is an object, check that hasBar is a valid method;
* if not, and if strict_variables is false, return null;
* if not, throw an exception.

Twig also supports a specific syntax for accessing items on PHP arrays, foo['bar']:

* check if foo is an array and bar a valid element;
* if not, and if strict_variables is false, return null;
* if not, throw an exception.

## Dynamic attribute
If you want to access a dynamic attribute of a variable, use the attribute function instead.

The attribute function is also useful when the attribute contains special characters (like - that would be interpreted as the minus operator):
``` twig 
{# equivalent to the non-working foo.data-foo #}
{{ attribute(foo, 'data-foo') }}
```


## Global Variables

The following variables are **always available** in templates:

* _self: references the current **template name**;
* _context: references the current **context**;
* _charset: references the current **charset**.
