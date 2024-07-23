# Twig 3 Certification Test 3

## Instructions

This test consists of 45 new questions about Twig 3. It covers various topics and has a time limit of 60 minutes. Choose the best answer for each question.

## Questions

### Basic Concepts

1. **What is the main advantage of using Twig over plain PHP for templating?**
    - A) Twig is faster than PHP
    - B) Twig provides a cleaner syntax and better separation of logic and presentation
    - C) Twig supports more programming languages
    - D) Twig is built into PHP

2. **Which of the following is a valid way to comment in Twig?**
    - A) `// This is a comment`
    - B) `/* This is a comment */`
    - C) `{# This is a comment #}`
    - D) `<!-- This is a comment -->`

3. **What is the purpose of the `|striptags` filter?**
    - A) To remove all HTML tags from a string
    - B) To escape HTML tags
    - C) To format a string as HTML
    - D) To convert a string to uppercase

### Filters

4. **Which filter would you use to format a number as currency?**
    - A) `format_currency`
    - B) `currency_format`
    - C) `number_format`
    - D) `money_format`

5. **What does the `|replace` filter do?**
    - A) Replaces all occurrences of a substring with another string
    - B) Replaces the first occurrence of a substring
    - C) Replaces a string with a number
    - D) None of the above

6. **How do you apply multiple filters to a variable?**
    - A) `{{ variable|filter1|filter2|filter3 }}`
    - B) `{{ filter1(filter2(filter3(variable))) }}`
    - C) `{{ variable|filter1(filter2(filter3)) }}`
    - D) Both A and B

### Tests

7. **What test can be used to check if a variable is a string?**
    - A) `is_string`
    - B) `string`
    - C) `is iterable`
    - D) `is defined`

8. **How do you combine multiple tests in a single condition?**
    - A) Using `&&` and `||`
    - B) Using `and` and `or`
    - C) Using `&` and `|`
    - D) Both A and B

### Control Structures

9. **What is the correct syntax for a `for` loop that iterates over an array in Twig?**
    - A) `{% for item in array %}`
    - B) `{% loop item in array %}`
    - C) `{% each item in array %}`
    - D) None of the above

10. **How do you create an `if` statement with multiple conditions in Twig?**
    - A) `{% if condition1 and condition2 %}`
    - B) `{% if condition1 or condition2 %}`
    - C) `{% if condition1 and condition2 or condition3 %}`
    - D) All of the above

### Variables and Expressions

11. **What is the output of `{{ variable is not defined ? 'No' : 'Yes' }}` if `variable` is defined?**
    - A) `No`
    - B) `Yes`
    - C) `Error`
    - D) `null`

12. **How do you access an array element in Twig?**
    - A) `{{ array[index] }}`
    - B) `{{ array->index }}`
    - C) `{{ array.index }}`
    - D) Both A and C

### Functions

13. **Which function is used to get the size of an array in Twig?**
    - A) `count()`
    - B) `size()`
    - C) `length()`
    - D) All of the above

14. **What is the purpose of the `dump` function in Twig?**
    - A) To output a variable's value for debugging
    - B) To clear the output buffer
    - C) To format a string
    - D) To include a template

### Operators

15. **What does the `not` operator do in Twig?**
    - A) Negates a boolean value
    - B) Checks if a variable is not defined
    - C) Both A and B
    - D) None of the above

16. **Which of the following is a valid comparison operator in Twig?**
    - A) `!=`
    - B) `!==`
    - C) `>`
    - D) All of the above

### Template Re-use

17. **What is the purpose of the `extends` tag in Twig?**
    - A) To include a template
    - B) To define a base template
    - C) To create a macro
    - D) To define a block

18. **How do you embed a template in another template in Twig?**
    - A) `{% include 'template.twig' %}`
    - B) `{% embed 'template.twig' %}`
    - C) `{% import 'template.twig' %}`
    - D) `{% extend 'template.twig' %}`

### Mixed Questions

19. **What is the output of `{{ 'Hello World'|striptags }}` if the input is `<b>Hello</b> World`?**
    - A) `Hello World`
    - B) `<b>Hello</b> World`
    - C) `Hello`
    - D) `Error`

20. **How do you create a conditional statement that checks if a variable is an array?**
    - A) `{% if variable is iterable %}`
    - B) `{% if variable is array %}`
    - C) `{% if variable is defined and variable is not null %}`
    - D) All of the above

21. **Which of the following is a valid way to define a block in Twig?**
    - A) `{% block name %}`
    - B) `{% define block name %}`
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

26. **How do you check if an array contains a specific value in Twig?**
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

29. **How do you create a custom filter in Twig?**
    - A) `{% filter name %}`
    - B) `{% define filter name %}`
    - C) `{% filter name(value) %}`
    - D) `{% filter(name) %}`

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

32. **How do you create a loop that iterates over a hash in Twig?**
    - A) `{% for key, value in hash %}`
    - B) `{% for value in hash %}`
    - C) `{% for key => value in hash %}`
    - D) `{% for item in hash %}`

33. **What does the `|merge` filter do?**
    - A) Merges two arrays
    - B) Merges two hashes
    - C) Merges two strings
    - D) Both A and B

34. **What is the purpose of the `|reverse` filter?**
    - A) To reverse a string
    - B) To reverse an array
    - C) To reverse a hash
    - D) All of the above

35. **How do you create a loop that iterates over a hash and preserves the keys?**
    - A) `{% for key, value in hash %}`
    - B) `{% for value in hash %}`
    - C) `{% for key => value in hash %}`
    - D) `{% for item, value in hash %}`

36. **What is the output of `{{ 'Hello World'|slice(6, 5) }}`?**
    - A) `Hello`
    - B) `World`
    - C) `Hello World`
    - D) `Error`

37. **How do you create a conditional statement that checks if a variable is an object?**
    - A) `{% if variable is iterable %}`
    - B) `{% if variable is object %}`
    - C) `{% if variable is defined and variable is not null %}`
    - D) All of the above

38. **What is the purpose of the `|sort` filter?**
    - A) To sort an array in ascending order
    - B) To sort a hash by keys
    - C) To sort a hash by values
    - D) All of the above

39. **How do you create a loop that iterates over an array and skips every second element?**
    - A) `{% for item in array|slice(2) %}`
    - B) `{% for item in array|batch(2) %}`
    - C) `{% for item in array|slice(0, 2) %}`
    - D) `{% for item in array|slice(1, 2) %}`

40. **What does the `|join` filter do?**
    - A) Joins two strings
    - B) Joins an array into a string
    - C) Joins two arrays
    - D) Joins two hashes

41. **What is the output of `{{ 10 % 3 }}`?**
    - A) `3`
    - B) `1`
    - C) `0`
    - D) `Error`

42. **What is the purpose of the `|first` filter?**
    - A) To get the first element of an array
    - B) To get the first character of a string
    - C) To get the first key of a hash
    - D) All of the above

43. **How do you create a loop that iterates over a hash and preserves the keys as variables?**
    - A) `{% for key, value in hash %}`
    - B) `{% for value in hash %}`
    - C) `{% for key => value in hash %}`
    - D) `{% for key, value in hash with keys %}`

44. **What is the purpose of the `|batch` filter?**
    - A) To batch an array into smaller arrays
    - B) To batch a hash into smaller hashes
    - C) To batch a string into smaller strings
    - D) To batch a number into smaller numbers

45. **What is the output of `{{ 'Twig'|upper }}`?**
    - A) `Twig`
    - B) `TWIG`
    - C) `twig`
    - D) `Error`

## Answers

### Basic Concepts

1. **B)** Twig provides a cleaner syntax and better separation of logic and presentation
2. **C)** `{# This is a comment #}`
3. **A)** To remove all HTML tags from a string

### Filters

4. **C)** `number_format`
5. **A)** Replaces all occurrences of a substring with another string
6. **D)** Both A and B

### Tests

7. **A)** `is_string`
8. **D)** Both A and B

### Control Structures

9. **A)** `{% for item in array %}`
10. **D)** All of the above

### Variables and Expressions

11. **B)** `Yes`
12. **D)** Both A and C

### Functions

13. **D)** All of the above
14. **A)** To output a variable's value for debugging

### Operators

15. **C)** Both A and B
16. **D)** All of the above

### Template Re-use

17. **B)** To define a base template
18. **B)** `{% embed 'template.twig' %}`

### Mixed Questions

19. **A)** `Hello World`
20. **D)** All of the above
21. **A)** `{% block name %}`
22. **A)** Formats a date string
23. **C)** Both A and B
24. **B)** To join an array into a string
25. **C)** Both A and B

### Advanced Questions

26. **A)** `value in array`
27. **A)** `3`
28. **A)** `{% block outer %}{% block inner %}{% endblock %}{% endblock %}`
29. **A)** `{% filter name %}`
30. **A)** To provide a default value if a variable is undefined
31. **C)** `4`
32. **A)** `{% for key, value in hash %}`
33. **D)** Both A and B
34. **B)** To reverse an array
35. **A)** `{% for key, value in hash %}`

36. **B)** `World`
37. **D)** All of the above
38. **D)** All of the above
39. **B)** `{% for item in array|batch(2) %}`
40. **B)** Joins an array into a string
41. **B)** `1`
42. **D)** All of the above
43. **A)** `{% for key, value in hash %}`
44. **A)** To batch an array into smaller arrays
45. **B)** `TWIG`

Feel free to review your answers and see how well you understand Twig 3!
