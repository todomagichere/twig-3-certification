# Twig 3 Certification Test 2

## Instructions

This test consists of 45 new questions about Twig 3. It covers various topics and has a time limit of 60 minutes. Choose the best answer for each question.

## Questions

### Basic Concepts

1. **What is the main purpose of Twig?**
    - A) To manage databases
    - B) To create web applications
    - C) To serve as a template engine for PHP
    - D) To handle HTTP requests

2. **Which of the following is a valid Twig syntax for a variable?**
    - A) `{{ variable }}`
    - B) `{% variable %}`
    - C) `<< variable >>`
    - D) `[variable]`

3. **What is the purpose of the `|escape` filter?**
    - A) To remove whitespace
    - B) To convert a string to lowercase
    - C) To escape HTML characters
    - D) To format a date

### Filters

4. **Which filter would you use to capitalize the first letter of a string?**
    - A) `capitalize`
    - B) `upper`
    - C) `title`
    - D) `first`

5. **What does the `|length` filter do?**
    - A) Returns the length of a string
    - B) Returns the number of elements in an array
    - C) Both A and B
    - D) None of the above

6. **Which of the following is a valid way to chain filters in Twig?**
    - A) `{{ variable|filter1|filter2 }}`
    - B) `{{ filter1(filter2(variable)) }}`
    - C) `{{ variable|filter1(filter2) }}`
    - D) `{{ filter1|filter2(variable) }}`

### Tests

7. **Which test checks if a variable is empty?**
    - A) `empty`
    - B) `null`
    - C) `defined`
    - D) `exists`

8. **How do you combine tests in Twig?**
    - A) Using `and` and `or`
    - B) Using `&&` and `||`
    - C) Using `&` and `|`
    - D) All of the above

### Control Structures

9. **What is the correct syntax for a `while` loop in Twig?**
    - A) `{% while condition %}`
    - B) `{% for condition %}`
    - C) `{% loop condition %}`
    - D) Twig does not support `while` loops.

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

14. **What is the purpose of the `include` function in Twig?**
    - A) To include a file
    - B) To include a template
    - C) To include a variable
    - D) To include a string

### Operators

15. **What does the `in` operator do in Twig?**
    - A) Checks if a value exists in an array
    - B) Checks if a variable is defined
    - C) Checks if a string contains a substring
    - D) None of the above

16. **Which of the following is a valid operator for string comparison in Twig?**
    - A) `=`
    - B) `==`
    - C) `===`
    - D) Both B and C

### Template Re-use

17. **What is the purpose of the `block` tag in Twig?**
    - A) To define a variable
    - B) To create a reusable template section
    - C) To include a template
    - D) To extend a template

18. **How do you include a template fragment in Twig?**
    - A) `{% include 'fragment.twig' %}`
    - B) `{% embed 'fragment.twig' %}`
    - C) `{% import 'fragment.twig' %}`
    - D) `{% extend 'fragment.twig' %}`

### Mixed Questions

19. **What is the output of `{{ 'Hello'|upper }}`?**
    - A) `Hello`
    - B) `hello`
    - C) `HELLO`
    - D) `hElLo`

20. **How do you create a conditional statement that checks if a variable is not null?**
    - A) `{% if variable is not null %}`
    - B) `{% if variable != null %}`
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

36. **What is the output of `{{ 'Hello World'|slice(0, 5) }}`?**
    - A) `Hello`
    - B) `Hello World`
    - C) `World`
    - D) `Error`

37. **How do you create a conditional statement that checks if a variable is an array?**
    - A) `{% if variable is iterable %}`
    - B) `{% if variable is array %}`
    - C) `{% if variable is defined and variable is not null %}`
    - D) All of the above

38. **What is the purpose of the `|sort` filter?**
    - A) To sort an array in ascending order
    - B) To sort a hash by keys
    - C) To sort a hash by values
    - D) All of the above

39. **How do you create a loop that iterates over an array in reverse order?**
    - A) `{% for item in array|reverse %}`
    - B) `{% for item in array %}{% endfor %}`
    - C) `{% for item in reverse(array) %}`
    - D) `{% for item in array|sort('desc') %}`

40. **What is the purpose of the `|batch` filter?**
    - A) To batch an array into smaller arrays
    - B) To batch a hash into smaller hashes
    - C) To batch a string into smaller strings
    - D) To batch a number into smaller numbers

41. **How do you create a loop that iterates over a hash and preserves the keys as variables?**
    - A) `{% for key, value in hash %}`
    - B) `{% for value in hash %}`
    - C) `{% for key => value in hash %}`
    - D) `{% for key, value in hash with keys %}`

42. **What is the output of `{{ 10 % 3 }}`?**
    - A) `3`
    - B) `1`
    - C) `0`
    - D) `Error`

43. **What is the purpose of the `|first` filter?**
    - A) To get the first element of an array
    - B) To get the first character of a string
    - C) To get the first key of a hash
    - D) All of the above

44. **How do you create a loop that iterates over an array and skips every second element?**
    - A) `{% for item in array|slice(2) %}`
    - B) `{% for item in array|batch(2) %}`
    - C) `{% for item in array|slice(0, 2) %}`
    - D) `{% for item in array|slice(1, 2) %}`

45. **What does the `|join` filter do?**
    - A) Joins two strings
    - B) Joins an array into a string
    - C) Joins two arrays
    - D) Joins two hashes

## Answers

### Basic Concepts

1. **C)** To serve as a template engine for PHP
2. **A)** `{{ variable }}`
3. **C)** To escape HTML characters

### Filters

4. **A)** `capitalize`
5. **C)** Both A and B
6. **A)** `{{ variable|filter1|filter2 }}`

### Tests

7. **A)** `empty`
8. **A)** Using `and` and `or`

### Control Structures

9. **D)** Twig does not support `while` loops.
10. **A)** `{% for item in items %}{% for subitem in subitems %}{% endfor %}{% endfor %}`

### Variables and Expressions

11. **B)** `No`
12. **A)** `{{ object.property }}`

### Functions

13. **C)** `now()`
14. **B)** To include a template

### Operators

15. **A)** Checks if a value exists in an array
16. **D)** Both B and C

### Template Re-use

17. **B)** To create a reusable template section
18. **A)** `{% include 'fragment.twig' %}`

### Mixed Questions

19. **C)** `HELLO`
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
29. **A)** `{% filter name %}`
30. **A)** To provide a default value if a variable is undefined
31. **A)** `4`
32. **A)** `{% for key, value in hash %}`
33. **D)** Both A and B
34. **B)** To reverse an array
35. **A)** `{% for key, value in hash %}`

36. **A)** `Hello`
37. **A)** `{% if variable is iterable %}`
38. **D)** All of the above
39. **A)** `{% for item in array|reverse %}`
40. **A)** To batch an array into smaller arrays
41. **A)** `{% for key, value in hash %}`
42. **B)** `1`
43. **A)** To get the first element of an array
44. **B)** `{% for item in array|batch(2) %}`
45. **B)** Joins an array into a string

Feel free to review your answers and see how well you understand Twig 3!
