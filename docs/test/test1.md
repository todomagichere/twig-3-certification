### Twig 3 Certification Exam

**Instructions**: Choose the correct answer(s) for each question. You have 60 minutes to complete this exam. Some questions may have multiple correct answers.

---

#### Topic 1: Basic Concepts

**1. What is the correct syntax to print a variable in Twig?**  
a) `{ variable }`  
b) `{{ variable }}`  
c) `{% variable %}`  
d) `{# variable #}`

**2. How do you escape output to prevent XSS attacks in Twig?**  
a) `{{ variable|escape }}`  
b) `{{ variable|e }}`  
c) `{{ variable|safe }}`  
d) `{{ variable|xss }}`

**3. Which of the following comments is correctly written in Twig?**  
a) `{* This is a comment *}`  
b) `{% This is a comment %}`  
c) `{# This is a comment #}`  
d) `<!-- This is a comment -->`

**4. What is the output of `{{ "Hello <b>World</b>"|escape }}`?**  
a) `Hello <b>World</b>`  
b) `Hello &lt;b&gt;World&lt;/b&gt;`  
c) `Hello &amp;lt;b&amp;gt;World&amp;lt;/b&amp;gt;`  
d) `Hello <b>World</b>`

**5. What does the following Twig code do? `{{ variable|default('default value') }}`**  
a) Sets `variable` to 'default value'  
b) Prints 'default value' if `variable` is not defined or empty  
c) Raises an error if `variable` is not defined  
d) Applies a default filter to `variable`

---

#### Topic 2: Filters

**6. How do you apply a filter to convert a variable to uppercase in Twig?**  
a) `{{ variable|uppercase }}`  
b) `{{ variable|upper }}`  
c) `{{ variable|toUpper }}`  
d) `{{ variable|capitalize }}`

**7. How do you format a date in Twig?**  
a) `{{ date|date('Y-m-d') }}`  
b) `{{ date|format('Y-m-d') }}`  
c) `{{ date|strftime('Y-m-d') }}`  
d) `{{ date|datetime('Y-m-d') }}`

**8. How do you chain multiple filters in Twig?**  
a) `{{ variable|filter1|filter2 }}`  
b) `{{ variable|(filter1, filter2) }}`  
c) `{{ variable|filter1(filter2) }}`  
d) `{{ variable|filter1.filter2 }}`

**9. Which filter would you use to join an array into a string in Twig?**  
a) `{{ array|join(', ') }}`  
b) `{{ array|concat(', ') }}`  
c) `{{ array|implode(', ') }}`  
d) `{{ array|merge(', ') }}`

**10. What is the alternative syntax for applying the `upper` filter to a variable in Twig?**  
a) `{{ upper(variable) }}`  
b) `{{ variable|uppercase }}`  
c) `{% filter upper %}{{ variable }}{% endfilter %}`  
d) `{% apply upper %}{{ variable }}{% endapply %}`

---

#### Topic 3: Tests

**11. How do you check if a variable is defined in Twig?**  
a) `{% if variable is defined %}`  
b) `{% if variable is not empty %}`  
c) `{% if variable exists %}`  
d) `{% if variable is set %}`

**12. Which of the following tests if a variable is empty in Twig?**  
a) `{% if variable is null %}`  
b) `{% if variable is empty %}`  
c) `{% if variable is none %}`  
d) `{% if variable is blank %}`

**13. How do you combine tests to check if a variable is defined and not empty in Twig?**  
a) `{% if variable is defined and variable is not empty %}`  
b) `{% if variable exists and variable is not empty %}`  
c) `{% if variable is defined and not empty %}`  
d) `{% if variable exists and not empty %}`

**14. How do you test if a string contains a specific substring in Twig?**  
a) `{% if "substring" in string %}`  
b) `{% if string contains "substring" %}`  
c) `{% if string has "substring" %}`  
d) `{% if string includes "substring" %}`

**15. Which of the following tests if an array is iterable in Twig?**  
a) `{% if array is iterable %}`  
b) `{% if array is array %}`  
c) `{% if array is traversable %}`  
d) `{% if array is list %}`

---

#### Topic 4: Control Structures

**16. What is the correct structure for a `for` loop in Twig?**  
a) `{% foreach item in items %}`  
b) `{% while item in items %}`  
c) `{% loop item in items %}`  
d) `{% for item in items %}`

**17. Which of the following statements correctly create an `if` condition in Twig?**  
a) `{% if condition %} ... {% endif %}`  
b) `{% if condition then %} ... {% end %}`  
c) `{% if (condition) %} ... {% endif %}`  
d) `{% if (condition) then %} ... {% endif %}`

**18. How do you write an `else if` condition in Twig?**  
a) `{% else if condition %}`  
b) `{% elseif condition %}`  
c) `{% elif condition %}`  
d) `{% ifelse condition %}`

**19. What is the correct way to use a `for` loop with an index in Twig?**  
a) `{% for item in items with index %}`  
b) `{% for item, index in items %}`  
c) `{% for index, item in items %}`  
d) `{% for item in items, index %}`

**20. How do you combine a `for` loop and an `if` condition in Twig?**  
a) `{% for item in items if condition %}`  
b) `{% for item in items %} {% if condition %}`  
c) `{% if condition %} {% for item in items %}`  
d) `{% for item in items %} {% if condition %} ... {% endif %} {% endfor %}`

---

#### Topic 5: Variables and Expressions

**21. How do you define a variable in Twig?**  
a) `{% set variable = value %}`  
b) `{% define variable = value %}`  
c) `{% var variable = value %}`  
d) `{% let variable = value %}`

**22. How do you access an element of an array in Twig?**  
a) `{{ array.element }}`  
b) `{{ array[element] }}`  
c) `{{ array->element }}`  
d) `{{ array:element }}`

**23. How do you access a property of an object in Twig?**  
a) `{{ object.property }}`  
b) `{{ object[property] }}`  
c) `{{ object->property }}`  
d) `{{ object:property }}`

**24. Which of the following is the correct syntax to increment a variable in Twig?**  
a) `{% set variable = variable + 1 %}`  
b) `{% increment variable %}`  
c) `{% variable++ %}`  
d) `{% var variable = variable + 1 %}`

**25. How do you use a ternary operator in Twig?**  
a) `{{ condition ? 'true value' : 'false value' }}`  
b) `{{ condition ? 'true value' else 'false value' }}`  
c) `{% if condition ? 'true value' : 'false value' %}`  
d) `{% condition ? 'true value' : 'false value' %}`

---

#### Topic 6: Functions

**26. Which function is used to cycle through values in Twig?**  
a) `{{ cycle(['odd', 'even'], loop.index) }}`  
b) `{{ loop(['odd', 'even'], index) }}`  
c) `{{ iterate(['odd', 'even'], loop.index) }}`  
d) `{{ rotate(['odd', 'even'], loop.index) }}`

**27. How do you include another template in Twig?**  
a) `{% include 'template.html.twig' %}`  
b) `{% import 'template.html.twig' %}`  
c) `{% embed 'template.html.twig' %}`  
d) `{% extend 'template.html.twig' %}`

**28. Which function is used to dump information about a variable for debugging purposes in Twig?**  
a) `{{ dump(variable) }}`  
b) `{{ var_dump(variable) }}`  
c) `{{ debug(variable) }}`  
d) `{{ print_r(variable) }}`

**29. How do you create a range of numbers in Twig?**  
a) `{{ range(1, 10)

}}`  
b) `{{ 1..10 }}`  
c) `{{ 1 to 10 }}`  
d) `{{ sequence(1, 10) }}`

**30. Which function is used to get the length of an array or string in Twig?**  
a) `{{ length(variable) }}`  
b) `{{ count(variable) }}`  
c) `{{ size(variable) }}`  
d) `{{ variable.length }}`

---

#### Topic 7: Operators

**31. What is the correct way to compare if two variables are equal in Twig?**  
a) `{% if variable1 == variable2 %}`  
b) `{% if variable1 === variable2 %}`  
c) `{% if variable1 eq variable2 %}`  
d) `{% if variable1 equal variable2 %}`

**32. Which of the following are logical operators in Twig?**  
a) `and`  
b) `&&`  
c) `or`  
d) `||`

**33. How do you perform a modulo operation in Twig?**  
a) `{% set result = variable % 2 %}`  
b) `{% set result = variable mod 2 %}`  
c) `{% set result = variable % 2 %}`  
d) `{% set result = variable % 2 %}`

**34. Which of the following operators can be used to concatenate strings in Twig?**  
a) `~`  
b) `+`  
c) `&`  
d) `.`

**35. How do you negate a condition in Twig?**  
a) `{% if not condition %}`  
b) `{% if !condition %}`  
c) `{% if ~condition %}`  
d) `{% if -condition %}`

---

#### Topic 8: Template Re-use

**36. What is the correct way to extend a template in Twig?**  
a) `{% extend 'base.html.twig' %}`  
b) `{% include 'base.html.twig' %}`  
c) `{% inherit 'base.html.twig' %}`  
d) `{% extends 'base.html.twig' %}`

**37. How do you define a block in a Twig template?**  
a) `{% block blockname %}...{% endblock %}`  
b) `{% section blockname %}...{% endsection %}`  
c) `{% define blockname %}...{% enddefine %}`  
d) `{% part blockname %}...{% endpart %}`

**38. Which of the following is the correct syntax to embed a template within another template in Twig?**  
a) `{% include 'template.html.twig' %}`  
b) `{% import 'template.html.twig' %}`  
c) `{% embed 'template.html.twig' %}`  
d) `{% extend 'template.html.twig' %}`

**39. How do you include a template fragment in Twig?**  
a) `{% include 'fragment.html.twig' %}`  
b) `{% import 'fragment.html.twig' %}`  
c) `{% embed 'fragment.html.twig' %}`  
d) `{% extend 'fragment.html.twig' %}`

**40. How do you use multi-level inheritance in Twig?**  
a) `{% extends 'grandparent.html.twig' %}` in parent and `{% extends 'parent.html.twig' %}` in child  
b) `{% include 'grandparent.html.twig' %}` in parent and `{% include 'parent.html.twig' %}` in child  
c) `{% inherit 'grandparent.html.twig' %}` in parent and `{% inherit 'parent.html.twig' %}` in child  
d) `{% embed 'grandparent.html.twig' %}` in parent and `{% embed 'parent.html.twig' %}` in child

**41. Which of the following can be used to include a template fragment with a context?**  
a) `{% include 'fragment.html.twig' with { 'var': value } %}`  
b) `{% import 'fragment.html.twig' with { 'var': value } %}`  
c) `{% embed 'fragment.html.twig' with { 'var': value } %}`  
d) `{% extend 'fragment.html.twig' with { 'var': value } %}`

**42. What is the purpose of the `{% parent %}` tag in Twig?**  
a) To refer to the parent block in a child template  
b) To extend the parent template  
c) To include the parent template  
d) To import the parent template

**43. How do you use `super()` to refer to the parent block content in Twig?**  
a) `{{ super() }}`  
b) `{% super() %}`  
c) `{{ parent() }}`  
d) `{% parent() %}`

**44. How do you prevent a block from being overridden in child templates in Twig?**  
a) `{% block blockname final %}...{% endblock %}`  
b) `{% block blockname readonly %}...{% endblock %}`  
c) `{% block blockname %}...{% endblock %}` with `{% parent() %}` in the block  
d) `{% block blockname %}...{% endblock %}` with `{% final %}` inside the block

**45. Which of the following statements correctly define a block in a parent template and override it in a child template?**  
a) `{% block blockname %}...{% endblock %}` in parent and `{% block blockname %}...{% endblock %}` in child  
b) `{% block blockname %}...{% endblock %}` in parent and `{% override blockname %}...{% endoverride %}` in child  
c) `{% section blockname %}...{% endsection %}` in parent and `{% section blockname %}...{% endsection %}` in child  
d) `{% define blockname %}...{% enddefine %}` in parent and `{% define blockname %}...{% enddefine %}` in child

---

### Key Answers

### Answers for the Twig 3 Certification Exam

**1.** b) `{{ variable }}`  
**2.** a) `{{ variable|escape }}` and b) `{{ variable|e }}`  
**3.** c) `{# This is a comment #}`  
**4.** b) `Hello &lt;b&gt;World&lt;/b&gt;`  
**5.** b) Prints 'default value' if `variable` is not defined or empty

**6.** b) `{{ variable|upper }}`  
**7.** a) `{{ date|date('Y-m-d') }}`  
**8.** a) `{{ variable|filter1|filter2 }}`  
**9.** a) `{{ array|join(', ') }}`  
**10.** c) `{% filter upper %}{{ variable }}{% endfilter %}`

**11.** a) `{% if variable is defined %}`  
**12.** b) `{% if variable is empty %}`  
**13.** a) `{% if variable is defined and variable is not empty %}`  
**14.** a) `{% if "substring" in string %}`  
**15.** a) `{% if array is iterable %}`

**16.** d) `{% for item in items %}`  
**17.** a) `{% if condition %} ... {% endif %}`  
**18.** b) `{% elseif condition %}`  
**19.** c) `{% for index, item in items %}`  
**20.** d) `{% for item in items %} {% if condition %} ... {% endif %} {% endfor %}`

**21.** a) `{% set variable = value %}`  
**22.** b) `{{ array[element] }}`  
**23.** a) `{{ object.property }}`  
**24.** a) `{% set variable = variable + 1 %}`  
**25.** a) `{{ condition ? 'true value' : 'false value' }}`

**26.** a) `{{ cycle(['odd', 'even'], loop.index) }}`  
**27.** a) `{% include 'template.html.twig' %}`  
**28.** a) `{{ dump(variable) }}`  
**29.** a) `{{ range(1, 10) }}`  
**30.** a) `{{ length(variable) }}`

**31.** a) `{% if variable1 == variable2 %}`  
**32.** a) `and` and c) `or`  
**33.** b) `{% set result = variable mod 2 %}`  
**34.** a) `~`  
**35.** a) `{% if not condition %}`

**36.** d) `{% extends 'base.html.twig' %}`  
**37.** a) `{% block blockname %}...{% endblock %}`  
**38.** c) `{% embed 'template.html.twig' %}`  
**39.** a) `{% include 'fragment.html.twig' %}`  
**40.** a) `{% extends 'grandparent.html.twig' %}` in parent and `{% extends 'parent.html.twig' %}` in child

**41.** a) `{% include 'fragment.html.twig' with { 'var': value } %}`  
**42.** a) To refer to the parent block in a child template  
**43.** a) `{{ super() }}`  
**44.** a) `{% block blockname final %}...{% endblock %}`  
**45.** a) `{% block blockname %}...{% endblock %}` in parent and `{% block blockname %}...{% endblock %}` in child
