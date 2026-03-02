Unit 1
======

Question 1
----------

What is the result of `5 * 8 + 40 / 2`?

- [x] `60.0`
- [ ] `40.0`
- [ ] `120`


Question 2
----------

What is the result of `10 / 5`?

- [ ] `0.5`
- [ ] `2`
- [ ] `DivisionError`
- [x] `2.0`


Question 3
----------

What is the result of `f"Ciao, {name * 3}!"` given that `name = "Pedro"`?

- [ ] `'Ciao, Pedro!Ciao, Pedro!Ciao, Pedro!'`
- [x] `'Ciao, PedroPedroPedro!'`
- [ ] `'Ciao, Pedro!Pedro!Pedro!'`
- [ ] `FormattingError`


Question 4
----------

What is the result of `(1 == 2) == False`?

- [x] `True`
- [ ] `False`
- [ ] `SyntaxError`


Question 5
----------

Given the list of colors defined above, what is the result of `colors[2][1]`?

- [ ] `'red'`
- [ ] `'green'`
- [x] `'r'`
- [ ] `True`


Question 6
----------

What's the difference between lists and dictionaries?

- [ ] Only dictionaries have indexes.
- [ ] Dictionaries can hold strings, while lists can only hold numbers.
- [ ] Lists and dictionaries are essentially the same.
- [x] Dictionary items are accessed by key and list items are accessed by index.


Question 7
----------

Which of these statements is wrong?

- [x] Each if-statement needs to be completed with an else clause.
- [ ] If-statements restrict a block of code to running only under certain conditions.
- [ ] If-statements modify the sequential flow of the program.
- [ ] Every if-statement contains an expression that is evaluated.


Question 8
----------

Given the for-loop `for number in range(10, 20):`, how many times would its associated code block be executed?

- [ ] 9
- [ ] 20
- [x] 10
- [ ] 2
- [ ] Unknown/unpredictable


Question 9
----------

In the first line, why is there a set of empty brackets?

- [ ] The brackets indicate that `numbers_divisible_by_3_and_7` is comprised of ints.
- [ ] The brackets are a requirement of while-loops.
- [x] The brackets create an empty list.


Question 10
-----------

How many times does the while-loop run?

- [ ] 100
- [x] 2100
- [ ] 99
- [ ] 2099
- [ ] Unknown/unpredictable


Question 11
-----------

Why is `current_number += 1` not inside the if-statement? (warning: putting this line inside the if-statement will result in an infinite loop! Why?)

- [ ] The `+=` operator is syntactically part of the while-loop, so it cannot appear within the if-statement.
- [x] We want to increment `number_to_check` on every iteration of the while-loop, regardless of whether the if-statement's condition is met.
- [ ] Placing `current_number += 1` inside the if-statement is optional and a matter of personal preference.


Question 12
-----------

What happens if you change `and` to `or` in the if-statement? How does this change the resulting numbers?

- [x] The `or` condition is less restrictive than `and`, so we find 100 numbers more quickly.
- [ ] While-loops cannot be used with an `or`-based condition.
- [ ] Using `or` results in an infinite loop because it's possible for both conditions to be true at the same time.


Question 13
-----------

How would you modify the code to find numbers that are also divisible by five?

- [ ] `if number_to_check % 3 == 0 and % 7 == 0 and % 5 == 0:`
- [ ] `if number_to_check % 3 == 0 or number_to_check % 7 == 0 or number_to_check % 5 == 0:`
- [ ] `if number_to_check % 3 == 0 and number_to_check % 7 == 0 or number_to_check % 5 == 0:`
- [x] `if number_to_check % 3 == 0 and number_to_check % 7 == 0 and number_to_check % 5 == 0:`

