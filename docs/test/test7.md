# Twig 3 Certification Test 7

## Instructions

This test consists of 45 new questions about Twig 3. It covers various topics and has a time limit of 60 minutes. Choose the best answer for each question.

## Questions

### Basic Concepts

1. **What is the main function of Twig as a template engine?**
    - A) To manage databases
    - B) To render HTML templates with dynamic content
    - C) To handle HTTP requests
    - D) To create web applications

2. **Which of the following is the correct syntax to include a template in Twig?**
    - A) `{% include 'template.twig' %}`
    - B) `{% import 'template.twig' %}`
    - C) `{% require 'template.twig' %}`
    - D) `{% extend 'template.twig' %}`

3. **What does the `|nl2br` filter do?**
    - A) Converts newline characters to `<br>` tags
    - B) Removes all line breaks from a string
    - C) Formats a string as a list
    - D) None of the above

### Filters

4. **Which filter would you use to format a date in Twig?**
    - A) `date_format`
    - B) `format_date`
    - C) `date`
    - D) `format`

5. **What does the `|length` filter return?**
    - A) The number of characters in a string
    - B) The number of elements in an array
    - C) The number of keys in a hash
    - D) All of the above

6. **How do you apply multiple filters to a variable using the pipe syntax?**
    - A) `{{ variable|filter1|filter2|filter3 }}`
    - B) `{{ filter1(filter2(filter3(variable))) }}`
    - C) `{{ variable|filter1(filter2(filter3)) }}`
    - D) All of the above

### Tests

7. **What test can be used to check if a variable is defined?**
    - A) `is_defined`
    - B) `defined`
    - C) `is defined`
    - D) `exists`

8. **How do you combine multiple tests in a single condition?**
    - A) Using `&&` and `||`
    - B) Using `and` and `or`
    - C) Using `&` and `|`
    - D) All of the above

### Control Structures

9. **What is the correct syntax for a `for` loop that iterates over an array in Twig?**
    - A) `{% for item in array %}`
    - B) `{% loop item in array %}`
    - C) `{% each item in array %}`
    - D) None of the above

10. **How do you create a nested loop in Twig?**
    - A) `{% for item in items %}{% for subitem in subitems %}{% endfor %}{% endfor %}`
    - B) `{% loop item in items %}{% loop subitem in subitems %}{% endloop %}{% endloop %}`
    - C) `{% each item in items %}{% each subitem in subitems %}{% endeach %}{% endeach %}`
    - D) None of the above.

### Variables and Expressions

11. **What is the output of `{{ variable is defined ? 'Yes' : 'No' }}` if `variable` is not defined?**
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

13. **Which function is used to get the current date in Twig?**
    - A) `current_date()`
    - B) `date()`
    - C) `now()`
    - D) `today()`

14. **What is the purpose of the `dump` function in Twig?**
    - A) To output a variable's value for debugging
    - B) To clear the output buffer
    - C) To format a string
    - D) To include a template

### Operators

15. **What does the `in` operator do in Twig?**
    - A) Checks if a value exists in an array
    - B) Checks if a variable is defined
    - C) Checks if a string contains a substring
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

19. **What is the output of `{{ 'Hello World'|upper }}`?**
    - A) `Hello World`
    - B) `HELLO WORLD`
    - C) `hello world`
    - D) `Error`

20. **How do you create a conditional statement that checks if a variable is an array?**
    - A) `{% if variable is iterable %}`
    - B) `{% if variable is array %}`
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

26. **How do you check if a string contains a specific substring using the `contains` test in Twig?**
    - A) `{% if 'string' contains 'substring' %}`
    - B) `{% if 'string' matches 'substring' %}`
    - C) `{% if 'string' includes 'substring' %}`
    - D) None of the above

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

37. **How do you create a conditional statement that checks if a variable is a string using the `is` operator?**
    - A) `{% if variable is string %}`
    - B) `{% if variable is defined and variable is not null %}`
    - C) `{% if variable is iterable %}`
    - D) `{% if variable is not empty %}`

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

44. **What is the purpose of the `|date` filter with the `'U'` format?**
    - A) Formats a date string in the Unix timestamp format
    - B) Converts a string to a date object
    - C) Returns the current date and time in the Unix timestamp format
    - D) None of the above

45. **What is the output of `{{ 'twig'|capitalize }}`?**
    - A) `Twig`
    - B) `TWIG`
    - C) `twig`
    - D) `Error`

## Answers

### Basic Concepts

1. **C)** To output unescaped HTML
2. **A)** `{% block name %}`
3. **A)** To format a string with placeholders

### Filters

4. **A)** `upper`
5. **D)** All of the above
6. **A)** `{{ variable|filter1|filter2|filter3 }}`

### Tests

7. **C)** `is iterable`
8. **A)** `{% if variable is defined and variable is not null %}`

### Control Structures

9. **A)** `{% for key, value in hash %}`
10. **D)** All of the above

### Variables and Expressions

11. **B)** `Yes`
12. **D)** All of the above

### Functions

13. **B)** `now()`
14. **A)** To output a variable's value for debugging

### Operators

15. **A)** Checks if a string starts with a specific substring
16. **D)** All of the above

### Template Re-use

17. **D)** To embed a template
18. **C)** `{% import 'template.twig' as macros %}`

### Mixed Questions

19. **B)** `Hi Twig`
20. **D)** All of the above
21. **A)** `{% macro name(arg1, arg2) %}`
22. **A)** Formats a date string in the `YYYY-MM-DD HH:mm:ss` format
23. **D)** All of the above
24. **B)** To join an array into a string
25. **C)** Both A and B

### Advanced Questions

26. **A)** `{% if 'string' matches '/pattern/' %}`
27. **B)** `[3, 2, 1]`
28. **A)** `{% block outer %}{% block inner %}{% endblock %}{% endblock %}`
29. **D)** Both A and C
30. **A)** To provide a default value if a variable is undefined
31. **A)** `4`
32. **A)** `{% for key, value in hash %}`
33. **A)** Merges two arrays into a single array
34. **B)** To reverse an array
35. **A)** `{% for key, value in hash %}`
36. **B)** `World`
37. **A)** `{% if variable is number %}`
38. **A)** Batches an array into smaller arrays
39. **A)** `{% for item in array|reverse %}`
40. **A)** Returns the absolute value of a number
41. **C)** `3.3333333333`
42. **D)** All of the above
43. **B)** `{% for item in array|batch(2, true) %}`
44. **A)** Formats a date string in the Unix timestamp format
45. **A)** `Twig`

Feel free to review your answers and see how well you understand Twig 3!
