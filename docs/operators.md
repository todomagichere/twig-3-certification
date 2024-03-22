# Operators

## In

The `in` operator performs containment test. It returns true if the left operand is contained in the right:

``` twig
{{ 1 in [1, 2, 3] }}

{{ 'cd' in 'abcde' }}

{# both returns true #}

```

!!! tip
    You can use this filter to perform a containment test on strings, arrays, or objects implementing the Traversable interface.

To perform a negative test, use the `not in` operator:
``` html
{% if 1 not in [1, 2, 3] %}

{# is equivalent to #}
{% if not (1 in [1, 2, 3]) %}
```

## Is (Test operator)

The is operator performs tests. Tests can be used to test a variable against a common expression. The right operand is name of the test:

```
{# find out if a variable is odd #}

{{ name is odd }}
```

Go to the [tests](https://twig.symfony.com/doc/3.x/tests/index.html) page to learn more about the built-in tests.

## |
Applies a filter
```
{% set myVariable = "foobar" %}
{{ myVariable|upper }}

{# displays FOOBAR #}
```
## ..
Creates a sequence based on the operand before and after the operator (this is syntactic sugar for the range function):
```
{% for i in 1..5 %}{{ i }}{% endfor %}

{# is equivalent to #}
{% for i in range(1, 5) %}{{ i }}{% endfor %}
```

## ~
Converts all operands into strings and concatenates them.
```
{% set name = "John" %}
{{ "Hello" ~ name ~ "!" }} 

{# displays Hello John!. #}
```

## . or []
Gets an attribute of a variable.
```
{{ array.name }} 
{{ array['name'] }} 
```

## ?:
Ternary operator:
```
{{ foo ? 'yes' : 'no' }}
{{ foo ?: 'no' }} is the same as {{ foo ? foo : 'no' }}
{{ foo ? 'yes' }} is the same as {{ foo ? 'yes' : '' }}
```

## ??
Null-coalescing operator:
```
{# returns the value of foo if it is defined and not null, 'no' otherwise #}
{{ foo ?? 'no' }}
```

## ...
The spread operator can be used to expand arrays or hashes (it cannot be used to expand the arguments of a function call):
```
{% set numbers = [1, 2, ...moreNumbers] %}
{% set ratings = { 'foo': 10, 'bar': 5, ...moreRatings } %}
```

## Math
Twig allows you to do math in templates; the following operators are supported:

### +
Adds two numbers together (the operands are casted to numbers). {{
1 + 1 }} is 2.

### -
Subtracts the second number from the first one. {{ 3 - 2 }} is 1.

### /
Divides two numbers. The returned value will be a floating point number. {{ 1 / 2 }} is {{ 0.5 }}.

### %
Calculates the remainder of an integer division. {{ 11 % 7 }} is 4.

### //
Divides two numbers and returns the floored integer result. {{ 20 // 7 }} is 2, {{ -20  // 7 }} is -3 (this is just syntactic sugar for the round filter).

### *
Multiplies the left operand with the right one. {{ 2 * 2 }} would return 4.

### **
Raises the left operand to the power of the right operand. {{ 2 ** 3 }} would return 8.
