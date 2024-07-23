# Twig 3 Certification Test 8

## Instructions

This test consists of 45 new questions about Twig 3. It covers various topics and has a time limit of 60 minutes. Choose the best answer for each question.

## Questions

### Basic Concepts

1. **What is the purpose of the `|escape` filter in Twig?**
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

4. **Which filter would you use to format a number with thousands separators?**
    - A) `format_number`
    - B) `number_format`
    - C) `format_thousands`
    - D) `thousands_format`

5. **What does the `|trim` filter do?**
    - A) Trims whitespace from the beginning and end of a string
    - B) Trims a specific character from a string
    - C) Trims a string to a specific length
    - D) None of the above

6. **How do you apply multiple filters to a variable with alternative syntax?**
    - A) `{{ variable|filter1|filter2|filter3 }}`
    - B) `{{ filter1(filter2(filter3(variable))) }}`
    - C) `{{ variable|filter1(filter2(filter3)) }}`
    - D) `{{ variable|filter1(variable|filter2(variable|filter3)) }}`

### Tests

7. **What test can be used to check if a variable is a number?**
    - A) `is_number`
    - B) `number`
    - C) `is iterable`
    - D) `is defined`

8. **How do you combine multiple tests in a single condition using the alternative syntax?**
    - A) `{{ variable is defined and variable is not null }}`
    - B) `{{ variable is defined or variable is not null }}`
    - C) `{{ variable is defined & variable is not null }}`
    - D) `{{ variable is defined | variable is not null }}`

### Control Structures

9. **What is the correct syntax for a `for` loop that iterates over a hash in Twig?**
    - A) `{% for key, value in hash %}`
    - B) `{% loop key, value in hash %}`
    - C) `{% each key, value in hash %}`
    - D) None of the above

10. **How do you create an `if-elseif-else` statement in Twig?**
    - A) `{% if condition1 %}{% elseif condition2 %}{% else %}{% endif %}`
    - B) `{% if condition1 %}{% elif condition2 %}{% else %}{% endif %}`
    - C) `{% if condition1 %}{% elseif condition2 %}{% elseif condition3 %}{% else %}{% endif %}`
    - D) All of the above

### Variables and Expressions

11. **What is the output of `{{ variable is defined ? 'Yes' : 'No' }}` if `variable` is not defined?**
    - A) `Yes`
    - B) `No`
    - C) `Error`
    - D) `null`

12. **How do you access a nested array element in Twig?**
    - A) `{{ array[index1][index2] }}`
    - B) `{{ array->index1->index2 }}`
    - C) `{{ array.index1.index2 }}`
    - D) Both A and C

### Functions

13. **Which function is used to get the current date and time in Twig?**
    - A) `date()`
    - B) `now()`
    - C) `today()`
    - D) `time()`

14. **What is the purpose of the `dump` function in Twig?**
    - A) To output a variable's value for debugging
    - B) To clear the output buffer
    - C) To format a string
    - D) To include a template

### Operators

15. **What does the `is` operator do in Twig?**
    - A) Checks if a variable is defined
    - B) Checks if a variable is null
    - C) Both A and B
    - D) None of the above

16. **Which of the following is a valid comparison operator in Twig?**
    - A) `>=`
    - B) `<=`
    - C) `<>`
    - D) All of the above

### Template Re-use

17. **What is the purpose of the `block` tag in Twig?**
    - A) To include a template
    - B) To define a base template
    - C) To create a reusable template section
    - D) To define a macro

18. **How do you embed a template in another template in Twig?**
    - A) `{% include 'template.twig' %}`
    - B) `{% embed 'template.twig' %}`
    - C) `{% import 'template.twig' %}`
    - D) `{% extend 'template.twig' %}`

### Mixed Questions

19. **What is the output of `{{ 'Hello World'|upper }}` if the input is `Hello World`?**
    - A) `Hello World`
    - B) `HELLO WORLD`
    - C) `hello world`
    - D) `Error`

20. **How do you create a conditional statement that checks if a variable is an object using the `is` operator?**
    - A) `{% if variable is iterable %}`
    - B) `{% if variable is object %}`
    - C) `{% if variable is defined and variable is not null %}`
    - D) All of the above

21. **Which of the following is a valid way to define a macro in Twig?**
    - A) `{% macro name() %}`
    - B) `{% define macro name() %}`
    - C) `{% function name() %}`
    - D) `{% template name() %}`

22. **What does the `|date` filter do?**
    - A) Formats a date string
    - B) Converts a string to a date
    - C) Returns the current date
    - D) None of the above

23. **How do you create a loop that iterates over a range of numbers in Twig?**
    - A) `{% for i in 1..10 %}`
    - B) `{% for i from 1 to 10 %}`
    - C) Both A and B
    - D) None of the above

24. **What is the purpose of the `|join` filter in Twig?**
    - A) To join two strings
    - B) To join an array into a string
    - C) To join two arrays
    - D) To join two hashes

25. **What does the `|slice` filter do?**
    - A) Extracts a substring
    - B) Returns a portion of an array
    - C) Both A and B
    - D) None of the above

### Advanced Questions

26. **How do you check if an array contains a specific value using the `in` operator in Twig?**
    - A) `value in array`
    - B) `array.contains(value)`
    - C) `array.includes(value)`
    - D) `array.has(value)`

27. **What is the output of `{{ [1, 2, 3]|length }}`?**
    - A) `3`
    - B) `2`
    - C) `1`
    - D) `Error`

28. **Which of the following is a valid way to create a nested block in Twig?**
    - A) `{% block outer %}{% block inner %}{% endblock %}{% endblock %}`
    - B) `{% block outer %}{% endblock inner %}`
    - C) `{% block outer %}{% block inner %}{% endblock inner %}{% endblock outer %}`
    - D) `{% block outer %}{% block inner %}{% endblock outer %}{% endblock inner %}`

29. **How do you create a custom filter in Twig using the alternative syntax?**
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

36. **What is the output of `{{ 'Hello World'|slice(6) }}`?**
    - A) `Hello`
    - B) `World`
    - C) `Hello World`
    - D) `Error`

37. **How do you create a conditional statement that checks if a variable is an array using the `is` operator?**
    - A) `{% if variable is iterable %}`
    - B) `{% if variable is array %}`
    - C) `{% if variable is defined and variable is not null %}`
    - D) All of the above

38. **What is the purpose of the `|batch` filter?**
    - A) Batches an array into smaller arrays
    - B) Batches a hash into smaller hashes
    - C) Batches a string into smaller strings
    - D) Batches a number into smaller numbers

39. **How do you create a loop that iterates over an array in reverse order using the `|reverse` filter?**
    - A) `{% for item in array|reverse %}`
    - B) `{% for item in reverse(array) %}`
    - C) `{% for item in array|sort('desc') %}`
    - D) Both A and B

40. **What does the `|abs` filter do?**
    - A) Returns the absolute value of a number
    - B) Formats a date
    - C) Formats a number
    - D) Formats a boolean

41. **What is the output of `{{ 10 / 3 }}`?**
    - A) `3`
    - B) `3.33`
    - C) `3.3333333333`
    - D) `Error`

42. **What is the purpose of the `|last` filter?**
    - A) To get the last element of an array
    - B) To get the last character of a string
    - C) To get the last key of a hash
    - D) All of the above

43. **How do you create a loop that iterates over an array and skips every second element using the `|batch` filter with a step size?**
    - A) `{% for item in array|slice(2) %}`
    - B) `{% for item in array|batch(2, true) %}`
    - C) `{% for item in array|slice(0, 2) %}`
    - D) `{% for item in array|slice(1, 2) %}`

44. **What is the purpose of the `|format` filter with the `'%d'` format?**
    - A) To format a string with placeholders
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

1. **B)** To escape HTML characters
2. **A)** `{% set variable = value %}`
3. **A)** To format a string with placeholders

### Filters

4. **B)** `number_format`
5. **A)** Trims whitespace from the beginning and end of a string
6. **D)** `{{ variable|filter1(variable|filter2(variable|filter3)) }}`

### Tests

7. **A)** `is_number`
8. **A)** `{{ variable is defined and variable is not null }}`

### Control Structures

9. **A)** `{% for key, value in hash %}`
10. **D)** All of the above

### Variables and Expressions

11. **B)** `No`
12. **D)** Both A and C

### Functions

13. **B)** `now()`
14. **A)** To output a variable's value for debugging

### Operators

15. **C)** Both A and B
16. **D)** All of the above

### Template Re-use

17. **C)** To create a reusable template section
18. **B)** `{% embed 'template.twig' %}`

### Mixed Questions

19. **B)** `HELLO WORLD`
20. **D)** All of the above
21. **A)** `{% macro name() %}`
22. **A)** Formats a date string
23. **C)** Both A and B
24. **B)** To join an array into a string
25. **C)** Both A and B

### Advanced Questions

26. **A)** `value in array`
27. **A)** `3`
28. **A)** `{% block outer %}{% block inner %}{% endblock %}{% endblock %}`
29. **D)** Both A and C
30. **A)** To provide a default value if a variable is undefined
31. **A)** `4`
32. **D)** `{% for key, value in hash with keys %}`
33. **A)** Merges two arrays into a single array
34. **B)** To reverse an array
35. **A)** `{% for key, value in hash %}`
36. **B)** `World`
37. **D)** All of the above
38. **A)** Batches an array into smaller arrays
39. **A)** `{% for item in array|reverse %}`
40. **A)** Returns the absolute value of a number
41. **C)** `3.3333333333`
42. **D)** All of the above
43. **B)** `{% for item in array|batch(2, true) %}`
44. **C)** To format a number
45. **A)** `Twig`

Feel free to review your
