## constant

`constant` checks if a variable has the exact same value as a constant. You can use either global constants or class constants:

    {% if post.status is constant('Post::PUBLISHED') %}
        the status attribute is exactly the same as Post::PUBLISHED
    {% endif %}

You can test constants from object instances as well:

    {% if post.status is constant('PUBLISHED', post) %}
        the status attribute is exactly the same as Post::PUBLISHED
    {% endif %}

## defined

`defined` checks if a variable is defined in the current context. This is very useful if you use the `strict_variables` option:

    {# defined works with variable names #}
    {% if foo is defined %}
    ...
    {% endif %}
    
    {# and attributes on variables names #}
    {% if foo.bar is defined %}
    ...
    {% endif %}
    
    {% if foo['bar'] is defined %}
    ...
    {% endif %}

When using the `defined` test on an expression that uses variables in some method calls, be sure that they are all defined first:

    {% if var is defined and foo.method(var) is defined %}
    ...
    {% endif %}

## divisible by

`divisible by` checks if a variable is divisible by a number:

    {% if loop.index is divisible by(3) %}
    ...
    {% endif %}

## empty

`empty` checks if a variable is an empty string, an empty array, an empty hash, exactly false, or exactly null.

For objects that implement the Countable interface, `empty` will check the return value of the `count()` method.

For objects that implement the `__toString()` magic method (and not Countable), it will check if an empty string is returned.

    {% if foo is empty %}
    ...
    {% endif %}

## even

`even` returns true if the given number is even:

    {{ var is even }}

## iterable

`iterable` checks if a variable is an array or a traversable object:

    {# evaluates to true if the foo variable is iterable #}
    {% if users is iterable %}
        {% for user in users %}
            Hello {{ user }}!
        {% endfor %}
    {% else %}
        {# users is probably a string #}
        Hello {{ users }}!
    {% endif %}

## null

`null` returns true if the variable is null:

    {{ var is null }}

!!! note
    none is an alias for null.

## odd

`odd` returns true if the given number is odd:

    {{ var is odd }}

## same as

`same as` checks if a variable is the same as another variable. This is equivalent to `===` in PHP:

    {% if foo.attribute is same as(false) %}
        the foo attribute really is the 'false' PHP value
    {% endif %}
