In this folder there are two files:

1. `test_purple_holiday_functions.py`
2. `test_orange_holiday_functions.py`

Your assignment is to add **two** test assertions to the file belonging to your
section, following the pattern established in the file.

For the test cases that you add, you must not re-use a test case already used by
another student. In other words, you must contribute **unique** test cases to
the test file. 

You should also try to make your contributions distinct. What this means is, for
example, if you were testing a function like `greater_than(a, b)` and one your
classmates tested `greater_than(10, 1)`, and another tested `greater_than(11,
1)` then you shouldn't add the test `greater_than(12, 1)`. You should instead
test a different condition, like `greater_than(1, 10)`.

These test files use assert statements. If the expression in an assert statement
is false, then the program throws an error and stops executing immediately. 

All of these assert statements are good:

```py
# Good
assert True
assert not False
assert 1 + 1 == 2
assert not 1 > 2
```

Whereas these assert statements are bad. They will cause the program to exit
with an error message:

```py
# Bad
assert not True
assert False
assert 1 + 1 != 2
assert 1 > 2
```
