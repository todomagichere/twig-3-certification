# Twig 3 Certification Test

## Instructions

This test consists of 45 questions about Twig 3. It covers 8 topics and has a time limit of 60 minutes. Choose the best answer for each question.

## Questions

### Basic Concepts

1. **What is the default file extension for Twig templates?**
    - A) .twig
    - B) .tpl
    - C) .html
    - D) .php

2. **What syntax is used to display a variable in Twig?**
    - A) `{% variable %}`
    - B) `{{ variable }}`
    - C) `[[ variable ]]`
    - D) `<< variable >>`

3. **How do you escape output in Twig?**
    - A) `{{ variable|escape }}`
    - B) `{{ escape(variable) }}`
    - C) `{% escape variable %}`
    - D) `{{ variable|safe }}`

### Filters

4. **Which of the following is NOT a valid Twig filter?**
    - A) `trim`
    - B) `replace`
    - C) `capitalize`
    - D) `substring`

5. **What does the `|raw` filter do in Twig?**
    - A) Escapes HTML
    - B) Outputs unescaped HTML
    - C) Converts to string
    - D) Formats dates

6. **Which filter would you use to convert a string to lowercase in Twig?**
    - A) `lower`
    - B) `lowercase`
    - C) `toLower`
    - D) `downcase`

### Tests

7. **Which of the following is a valid Twig test?**
    - A) `even`
    - B) `odd`
    - C) `divisibleby`
    - D) All of the above

8. **How do you check if a variable is defined using a test in Twig?**
    - A) `{% if variable is defined %}`
    - B) `{% if defined(variable) %}`
    - C) `{% if variable exists %}`
    - D) `{% if variable is set %}`

### Control Structures

9. **What is the correct syntax for a Twig `for` loop?**
    - A) `{% for item in items %}`
    - B) `{% loop item in items %}`
    - C) `{% each item in items %}`
    - D) `{% iterate items %}`

10. **How do you create an `if-else` statement in Twig?**
    - A) `{% if condition %}{% else %}{% endif %}`
    - B) `{% if condition %}{% elseif condition %}{% else %}{% endif %}`
    - C) `{% if condition %}{% elif condition %}{% else %}{% endif %}`
    - D) Both B and C

### Variables and Expressions

11. **How do you define a variable in Twig?**
    - A) `{% set variable = value %}`
    - B) `{{ variable = value }}`
    - C) `<< variable = value >>`
    - D) `[set variable = value]`

12. **What is the output of `{{ 5 + 5 }}`?**
    - A) `10`
    - B) `55`
    - C) `5 + 5`
    - D) `Error`

### Functions

13. **Which of the following is a valid Twig function?**
    - A) `date()`
    - B) `length()`
    - C) `json_encode()`
    - D) All of the above

14. **What function would you use to include a template and pass variables to it?**
    - A) `include()`
    - B) `render()`
    - C) `include_with()`
    - D) `render_with()`

### Operators

15. **What operator is used to concatenate strings in Twig?**
    - A) `+`
    - B) `.`
    - C) `&`
    - D) `,`

16. **Which of the following is a valid Twig operator?**
    - A) `==`
    - B) `===`
    - C) `!=`
    - D) All of the above

### Template Re-use

17. **How do you extend a parent template in Twig?**
    - A) `{% extends 'parent.twig' %}`
    - B) `{% inherit 'parent.twig' %}`
    - C) `{% include 'parent.twig' %}`
    - D) `{% use 'parent.twig' %}`

18. **What is the purpose of the `include` tag in Twig?**
    - A) To include a template fragment
    - B) To embed a template
    - C) To extend a parent template
    - D) To define a macro

### Mixed Questions

19. **What is the output of `{{ [1, 2, 3]|join(', ') }}`?**
    - A) `1, 2, 3`
    - B) `[1, 2, 3]`
    - C) `"1, 2, 3"`
    - D) `1 2 3`

20. **How do you create a Twig environment?**
    - A) `new Twig_Environment()`
    - B) `new Twig\Environment()`
    - C) `Twig::createEnvironment()`
    - D) `Twig\Environment::new()`

21. **What is the purpose of the `with` keyword in Twig?**
    - A) To define a variable
    - B) To pass variables to included templates
    - C) To create a loop
    - D) To filter output

22. **How do you define a macro in Twig?**
    - A) `{% macro name() %}`
    - B) `{% define macro name() %}`
    - C) `{% function name() %}`
    - D) `{% template name() %}`

23. **What is the correct syntax for a Twig comment?**
    - A) `{# This is a comment #}`
    - B) `<!-- This is a comment -->`
    - C) `{% comment %} This is a comment {% endcomment %}`
    - D) `// This is a comment`

24. **How do you create a loop that iterates over a range of numbers in Twig?**
    - A) `{% for i in 1..10 %}`
    - B) `{% for i from 1 to 10 %}`
    - C) `{% for i in range(1, 10) %}`
    - D) All of the above

25. **What is the purpose of the `|slice` filter in Twig?**
    - A) To extract a substring
    - B) To format a string
    - C) To split a string
    - D) To remove whitespace

### Advanced Questions

26. **How do you create a custom filter in Twig?**
    - A) `{% filter name %}`
    - B) `{% define filter name %}`
    - C) `{% filter name(value) %}`
    - D) `{% filter(name) %}`

27. **What is the output of `{{ "Hello"|upper }}`?**
    - A) `Hello`
    - B) `hello`
    - C) `HELLO`
    - D) `hElLo`

28. **How do you create a conditional statement that checks if a variable is empty?**
    - A) `{% if variable is empty %}`
    - B) `{% if empty(variable) %}`
    - C) `{% if variable == null %}`
    - D) `{% if variable is defined and variable is not null %}`

29. **What is the purpose of the `|join` filter in Twig?**
    - A) To join two strings
    - B) To join an array into a string
    - C) To join two arrays
    - D) None of the above

30. **How do you create a nested block in Twig?**
    - A) `{% block outer %}{% block inner %}{% endblock %}{% endblock %}`
    - B) `{% block outer %}{% block inner %}`
    - C) `{% block outer %}{% endblock %}{% block inner %}{% endblock %}`
    - D) `{% block outer %}{% endblock inner %}`

31. **What is the output of `{{ 5 / 2 }}`?**
    - A) `2`
    - B) `2.5`
    - C) `2.0`
    - D) `2.50`

32. **How do you create a loop that iterates over a hash in Twig?**
    - A) `{% for key, value in hash %}`
    - B) `{% for value in hash %}`
    - C) `{% for key => value in hash %}`
    - D) `{% for item in hash %}`

33. **What is the purpose of the `|default` filter in Twig?**
    - A) To provide a default value if a variable is undefined or null
    - B) To format a date
    - C) To convert a string to lowercase
    - D) To escape HTML

34. **How do you create a nested `if` statement in Twig?**
    - A) `{% if condition1 %}{% if condition2 %}{% endif %}{% endif %}`
    - B) `{% if condition1 and condition2 %}`
    - C) `{% if condition1 or condition2 %}`
    - D) `{% if condition1 %}{% elseif condition2 %}{% endif %}`

35. **What is the purpose of the `|format` filter in Twig?**
    - A) To format a string with placeholders
    - B) To format a date
    - C) To format a number
    - D) To format a boolean

### Advanced Questions (continued)

36. **How do you create a loop that iterates over a hash and preserves the keys?**
    - A) `{% for key, value in hash %}`
    - B) `{% for value in hash %}`
    - C) `{% for key => value in hash %}`
    - D) `{% for item, value in hash %}`

37. **What is the purpose of the `|merge` filter in Twig?**
    - A) To merge two arrays
    - B) To merge two hashes
    - C) To merge two strings
    - D) To merge two variables

38. **How do you create a loop that iterates over a hash and preserves the keys as variables?**
    - A) `{% for key, value in hash %}`
    - B) `{% for value in hash %}`
    - C) `{% for key => value in hash %}`
    - D) `{% for key, value in hash with keys %}`

39. **What is the purpose of the `|sort` filter in Twig?**
    - A) To sort an array in ascending order
    - B) To sort an array in descending order
    - C) To sort a hash by keys
    - D) To sort a hash by values

40. **How do you create a loop that iterates over a hash and preserves the keys as variables with a custom separator?**
    - A) `{% for key, value in hash %}`
    - B) `{% for value in hash %}`
    - C) `{% for key => value in hash %}`
    - D) `{% for key, value in hash with keys using separator '.' %}`

41. **What is the purpose of the `|reverse` filter in Twig?**
    - A) To reverse a string
    - B) To reverse an array
    - C) To reverse a hash
    - D) To reverse a number

42. **How do you create a loop that iterates over a hash and preserves the keys as variables with a custom separator and a custom key format?**
    - A) `{% for key, value in hash %}`
    - B) `{% for value in hash %}`
    - C) `{% for key => value in hash %}`
    - D) `{% for key, value in hash with keys using separator '.' and format 'key_%s' %}`

43. **What is the purpose of the `|batch` filter in Twig?**
    - A) To batch an array into smaller arrays
    - B) To batch a hash into smaller hashes
    - C) To batch a string into smaller strings
    - D) To batch a number into smaller numbers

44. **How do you create a loop that iterates over a hash and preserves the keys as variables with a custom separator, a custom key format, and a custom value format?**
    - A) `{% for key, value in hash %}`
    - B) `{% for value in hash %}`
    - C) `{% for key => value in hash %}`
    - D) `{% for key, value in hash with keys using separator '.' and format 'key_%s', value using format 'value_%s' %}`

45. **What is the purpose of the `|map` filter in Twig?**
    - A) To map an array to a new array based on a callback function
    - B) To map a hash to a new hash based on a callback function
    - C) To map a string to a new string based on a callback function
    - D) To map a number to a new number based on a callback function

# Twig 3 Certification Test Answers

Here are the correct answers for the Twig 3 Certification Test questions:

## Answers

### Basic Concepts

1. **A)** .twig
2. **B)** `{{ variable }}`
3. **A)** `{{ variable|escape }}`

### Filters

4. **D)** `substring`
5. **B)** Outputs unescaped HTML
6. **A)** `lower`

### Tests

7. **D)** All of the above
8. **A)** `{% if variable is defined %}`

### Control Structures

9. **A)** `{% for item in items %}`
10. **D)** Both B and C

### Variables and Expressions

11. **A)** `{% set variable = value %}`
12. **B)** `10`

### Functions

13. **D)** All of the above
14. **A)** `include()`

### Operators

15. **B)** `.`
16. **D)** All of the above

### Template Re-use

17. **A)** `{% extends 'parent.twig' %}`
18. **A)** To include a template fragment

### Mixed Questions

19. **A)** `1, 2, 3`
20. **B)** `new Twig\Environment()`
21. **B)** To pass variables to included templates
22. **A)** `{% macro name() %}`
23. **A)** `{# This is a comment #}`
24. **D)** All of the above
25. **A)** To extract a substring

### Advanced Questions

26. **A)** `{% filter name %}`
27. **C)** `HELLO`
28. **A)** `{% if variable is empty %}`
29. **B)** To join an array into a string
30. **A)** `{% block outer %}{% block inner %}{% endblock %}{% endblock %}`
31. **B)** `2.5`
32. **A)** `{% for key, value in hash %}`
33. **A)** To provide a default value if a variable is undefined or null
34. **A)** `{% if condition1 %}{% if condition2 %}{% endif %}{% endif %}`
35. **A)** To format a string with placeholders

### Advanced Questions (continued)

36. **A)** `{% for key, value in hash %}`
37. **A)** To merge two arrays
38. **A)** `{% for key, value in hash %}`
39. **A)** To sort an array in ascending order
40. **D)** `{% for key, value in hash with keys using separator '.' %}`
41. **B)** To reverse an array
42. **D)** `{% for key, value in hash with keys using separator '.' and format 'key_%s', value using format 'value_%s' %}`
43. **A)** To batch an array into smaller arrays
44. **D)** `{% for key, value in hash with keys using separator '.' and format 'key_%s', value using format 'value_%s' %}`
45. **A)** To map an array to a new array based on a callback function

Feel free to review your answers and see how well you understand Twig 3!

