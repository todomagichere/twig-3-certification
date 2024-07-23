# Twig 3 Certification Test 5

## Instructions

This test consists of 45 new questions about Twig 3. It covers various topics and has a time limit of 60 minutes. Choose the best answer for each question.

## Questions

### Basic Concepts

1. **What is the purpose of the `|raw` filter in Twig?**
    - A) To remove all HTML tags from a string
    - B) To escape HTML characters
    - C) To output unescaped HTML
    - D) To convert a string to uppercase

2. **How do you define a variable in Twig?**
    - A) `{% set variable = value %}`
    - B) `{{ variable = value }}`
    - C) `<< variable = value >>`
    - D) `[set variable = value]`

3. **What is the purpose of the `|format` filter?**
    - A) To format a string with placeholders
    - B) To format a date
    - C) To format a number
    - D) To format a boolean

### Filters

4. **Which filter would you use to convert a string to lowercase?**
    - A) `lower`
    - B) `lowercase`
    - C) `toLower`
    - D) `downcase`

5. **What does the `|split` filter do?**
    - A) Splits a string into an array based on a delimiter
    - B) Splits an array into smaller arrays
    - C) Splits a hash into smaller hashes
    - D) None of the above

6. **How do you apply multiple filters to a variable using the pipe syntax?**
    - A) `{{ variable|filter1|filter2|filter3 }}`
    - B) `{{ filter1(filter2(filter3(variable))) }}`
    - C) `{{ variable|filter1(filter2(filter3)) }}`
    - D) `{{ variable|filter1(variable|filter2(variable|filter3)) }}`

### Tests

7. **What test can be used to check if a variable is an array?**
    - A) `is_array`
    - B) `array`
    - C) `is iterable`
    - D) `is defined`

8. **How do you combine multiple tests in a single condition using the pipe syntax?**
    - A) `{% if variable is defined and variable is not null %}`
    - B) `{% if variable is defined or variable is not null %}`
    - C) `{% if variable is defined & variable is not null %}`
    - D) `{% if variable is defined | variable is not null %}`

### Control Structures

9. **What is the correct syntax for a `for` loop that iterates over a range of numbers in Twig?**
    - A) `{% for i in 1..10 %}`
    - B) `{% for i from 1 to 10 %}`
    - C) `{% for i in range(1, 10) %}`
    - D) All of the above

10. **How do you create a nested `if` statement in Twig?**
    - A) `{% if condition1 %}{% if condition2 %}{% endif %}{% endif %}`
    - B) `{% if condition1 and condition2 %}`
    - C) `{% if condition1 or condition2 %}`
    - D) `{% if condition1 %}{% elseif condition2 %}{% endif %}`

### Variables and Expressions

11. **What is the output of `{{ variable is defined ? 'Yes' : 'No' }}` if `variable` is defined?**
    - A) `Yes`
    - B) `No`
    - C) `Error`
    - D) `null`

12. **How do you access a property of an object in Twig?**
    - A) `{{ object.property }}`
    - B) `{{ object->property }}`
    - C) `{{ object[property] }}`
    - D) Both A and C

### Functions

13. **Which function is used to get the current timestamp in Twig?**
    - A) `date()`
    - B) `now()`
    - C) `time()`
    - D) `timestamp()`

14. **What is the purpose of the `include` function in Twig?**
    - A) To include a template
    - B) To embed a template
    - C) To extend a template
    - D) To import a template

### Operators

15. **What does the `starts with` operator do in Twig?**
    - A) Checks if a string starts with a specific substring
    - B) Checks if a hash starts with a specific key
    - C) Checks if an array starts with a specific element
    - D) None of the above

16. **Which of the following is a valid logical operator in Twig?**
    - A) `and`
    - B) `or`
    - C) `not`
    - D) All of the above

### Template Re-use

17. **What is the purpose of the `extends` tag in Twig?**
    - A) To include a template
    - B) To define a base template
    - C) To create a macro
    - D) To define a block

18. **How do you import a macro from another template in Twig?**
    - A) `{% include 'template.twig' %}`
    - B) `{% embed 'template.twig' %}`
    - C) `{% import 'template.twig' as macros %}`
    - D) `{% extend 'template.twig' %}`

### Mixed Questions

19. **What is the output of `{{ 'Hello World'|replace({'Hello': 'Hi'}) }}` if the input is `Hello World`?**
    - A) `Hello World`
    - B) `Hi World`
    - C) `Hello`
    - D) `Hi`

20. **How do you create a conditional statement that checks if a variable is an array using the `is` operator?**
    - A) `{% if variable is iterable %}`
    - B) `{% if variable is array %}`
    - C) `{% if variable is defined and variable is not null %}`
    - D) All of the above

21. **Which of the following is a valid way to define a macro with arguments in Twig?**
    - A) `{% macro name(arg1, arg2) %}`
    - B) `{% define macro name(arg1, arg2) %}`
    - C) `{% function name(arg1, arg2) %}`
    - D) `{% template name(arg1, arg2) %}`

22. **What does the `|date` filter do with the `'Y-m-d'` format?**
    - A) Formats a date string in the `YYYY-MM-DD` format
    - B) Converts a string to a date object
    - C) Returns the current date in the `YYYY-MM-DD` format
    - D) None of the above

23. **How do you create a loop that iterates over a range of numbers with a custom step size in Twig?**
    - A) `{% for i in 1..10 step 2 %}`
    - B) `{% for i from 1 to 10 step 2 %}`
    - C) `{% for i in range(1, 10, 2) %}`
    - D) All of the above

24. **What is the purpose of the `|join` filter in Twig?**
    - A) To join two strings
    - B) To join an array into a string
    - C) To join two arrays
    - D) To join two hashes

25. **What does the `|slice` filter do with a single argument?**
    - A) Extracts a substring from the beginning of a string
    - B) Returns a portion of an array starting from a specific index
    - C) Both A and B
    - D) None of the above

### Advanced Questions

26. **How do you check if a string contains a specific substring using the `matches` test in Twig?**
    - A) `{% if 'string' matches '/substring/' %}`
    - B) `{% if 'string' matches 'substring' %}`
    - C) `{% if 'string' matches ['substring'] %}`
    - D) `{% if 'string' matches 'substring' ignorecase %}`

27. **What is the output of `{{ [1, 2, 3]|reverse }}`?**
    - A) `[1, 2, 3]`
    - B) `[3, 2, 1]`
    - C) `1, 2, 3`
    - D) `3, 2, 1`

28. **Which of the following is a valid way to create a nested block with a parent block name in Twig?**
    - A) `{% block outer %}{% block inner %}{% endblock %}{% endblock %}`
    - B) `{% block outer %}{% endblock inner %}`
    - C) `{% block outer %}{% block inner %}{% endblock inner %}{% endblock outer %}`
    - D) `{% block outer %}{% block inner %}{% endblock outer %}{% endblock inner %}`

29. **How do you create a custom filter in Twig using the pipe syntax?**
    - A) `{{ 'string'|myfilter }}`
    - B) `{{ myfilter('string') }}`
    - C) `{{ 'string'|myfilter('arg') }}`
    - D) Both A and C

30. **What is the purpose of the `|default` filter?**
    - A) To provide a default value if a variable is undefined
    - B) To format a date
    - C) To convert a string to lowercase
    - D) To escape HTML

31. **What is the output of `{{ 'Twig'|length }}`?**
    - A) `4`
    - B) `3`
    - C) `5`
    - D) `Error`

32. **How do you create a loop that iterates over a hash and preserves the keys using the `keys` keyword?**
    - A) `{% for key, value in hash %}`
    - B) `{% for value in hash %}`
    - C) `{% for key => value in hash %}`
    - D) `{% for key, value in hash with keys %}`

33. **What does the `|merge` filter do with arrays?**
    - A) Merges two arrays into a single array
    - B) Merges two hashes into a single hash
    - C) Merges two strings into a single string
    - D) None of the above

34. **What is the purpose of the `|reverse` filter?**
    - A) To reverse a string
    - B) To reverse an array
    - C) To reverse a hash
    - D) All of the above

35. **How do you create a loop that iterates over a hash and preserves the keys as variables using the `keys` keyword?**
    - A) `{% for key, value in hash %}`
    - B) `{% for value in hash %}`
    - C) `{% for key => value in hash %}`
    - D) `{% for key, value in hash with keys %}`

36. **What is the output of `{{ 'Hello World'|slice(6, 5) }}`?**
    - A) `Hello`
    - B) `World`
    - C) `Hello World`
    - D) `Error`

37. **How do you create a conditional statement that checks if a variable is an object using the `is` operator?**
    - A) `{% if variable is iterable %}`
    - B) `{% if variable is object %}`
    - C) `{% if variable is defined and variable is not null %}`
    - D) All of the above

38. **What is the purpose of the `|sort` filter?**
    - A) To sort an array in ascending order
    - B) To sort a hash by keys
    - C) To sort a hash by values
    - D) All of the above

39. **How do you create a loop that iterates over an array in reverse order using the `|reverse` filter?**
    - A) `{% for item in array|reverse %}`
    - B) `{% for item in reverse(array) %}`
    - C) `{% for item in array|sort('desc') %}`
    - D) Both A and B

40. **What does the `|batch` filter do?**
    - A) Batches an array into smaller arrays
    - B) Batches a hash into smaller hashes
    - C) Batches a string into smaller strings
    - D) Batches a number into smaller numbers

41. **What is the output of `{{ 10 / 3 }}`?**
    - A) `3`
    - B) `3.33`
    - C) `3.3333333333`
    - D) `Error`

42. **What is the purpose of the `|first` filter?**
    - A) To get the first element of an array
    - B) To get the first character of a string
    - C) To get the first key of a hash
    - D) All of the above

43. **How do you create a loop that iterates over an array and skips every second element using the `|batch` filter with a step size?**
    - A) `{% for item in array|slice(2) %}`
    - B) `{% for item in array|batch(2, true) %}`
    - C) `{% for item in array|slice(0, 2) %}`
    - D) `{% for item in array|slice(1, 2) %}`

44. **What is the purpose of the `|abs` filter?**
    - A) To get the absolute value of a number
    - B) To format a date
    - C) To format a number
    - D) To format a boolean

45. **What is the output of `{{ 'twig'|capitalize }}`?**
    - A) `Twig`
    - B) `TWIG`
    - C) `twig`
    - D) `Error`

## Answers

### Basic Concepts

1. **C)** To output unescaped HTML
2. **A)** `{% set variable = value %}`
3. **A)** To format a string with placeholders

### Filters

4. **A)** `lower`
5. **A)** Splits a string into an array based on a delimiter
6. **A)** `{{ variable|filter1|filter2|filter3 }}`

### Tests

7. **C)** `is iterable`
8. **D)** `{% if variable is defined | variable is not null %}`

### Control Structures

9. **D)** All of the above
10. **A)** `{% if condition1 %}{% if condition2 %}{% endif %}{% endif %}`

### Variables and Expressions

11. **A)** `Yes`
12. **D)** Both A and C

### Functions

13. **C)** `time()`
14. **A)** To include a template

### Operators

15. **A)** Checks if a string starts with a specific substring
16. **D)** All of the above

### Template Re-use

17. **B)** To define a base template
18. **C)** `{% import 'template.twig' as macros %}`

### Mixed Questions

19. **B)** `Hi World`
20. **D)** All of the above
21. **A)** `{% macro name(arg1, arg2) %}`
22. **A)** Formats a date string in the `YYYY-MM-DD` format
23. **D)** All of the above
24. **B)** To join an array into a string
25. **C)** Both A and B

### Advanced Questions

26. **A)** `{% if 'string' matches '/substring/' %}`
27. **B)** `[3, 2, 1]`
28. **A)** `{% block outer %}{% block inner %}{% endblock %}{% endblock %}`
29. **D)** Both A and C
30. **A)** To provide a default value if a variable is undefined
31. **A)** `4`
32. **D)** `{% for key, value in hash with keys %}`
    33
