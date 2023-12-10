# Test Holiday Functions

In this folder there are two files:

1. `test_purple_holiday_functions.py`
2. `test_orange_holiday_functions.py`

Your assignment is to add **two** test assertions to the file belonging to your
section, following the pattern established in the file.

For the test cases that you add, you must not re-use a test case already used by
another student. In other words, you must contribute **unique** test cases to
the test file. 

You should also try to make your contributions distinct. What this means is, for
example, if you were testing a function like `greater_than(a, b)` and one of your
classmates tested `greater_than(10, 1)`, and another tested `(11,
1)` then you shouldn't add the test `(12, 1)`. You should instead
test a different condition, like `(1, 10)`.

These test files use assert statements. If the expression in an assert statement
is false, then the program throws an error and stops executing immediately. 

All of these assert statements are good:

```py
# Good 👍
assert True
assert not False
assert 1 + 1 == 2
assert not 1 > 2
```

Whereas these assert statements are bad. They will cause the program to exit
with an error message:

```py
# Bad 👎
assert not True
assert False
assert 1 + 1 != 2
assert 1 > 2
```

## How to add your tests, step by step

### Step 1

Click on the test file corresponding to your section (orange or purple).

### Step 2

Click the "Edit this file" button, shown in the screen shot below (on the right):

![](https://github.com/gabalafou/zebracorn/assets/317883/4fecb852-a390-43fd-ada9-30c9b14ffc08)

This will open the file in a text editor in your browser.

### Step 3

Find your name and fill two lines below your name, each with one assert statement. 

Do not change the number of lines below your name. There should be exactly three 
lines below your name. The first two lines are for your two assert statements, 
each on a separate line. The third line is meant to be left blank.

Then click the green "Commit changes..." button in the upper right, shown in the 
following screenshot:

![](https://github.com/gabalafou/zebracorn/assets/317883/ea0bb76b-9e35-4522-bb34-f51813fcab83)

### Step 4

Add a commit message, then press "Commit changes"

![screenshot commit message modal](https://github.com/gabalafou/zebracorn/assets/317883/706b3e52-671c-4d7b-8662-8a8fce455b0e)

If all went well, your changes should be saved to the file.
