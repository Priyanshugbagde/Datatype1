# Datatype1
Task 1--To create int,float and boolean variables in module1 and print them into module 2.

✅ Objective:
To demonstrate **variable creation and cross-module import in Python**.

📚 Theory:
In Python, a *module* is simply a `.py` file containing Python code (functions, variables, etc.). This task involves two modules:
Module1.py creates three variables:
    `a` → integer
    `b` → boolean
    `f` → float
    It also prints their data types and values using the `type()` function.

Module2.py imports these variables from `Module1.py` and prints their values.

This helps us to understand:

* How to define basic data types in Python.
* How to import variables from one module into another using `from Module1 import ...`.

Output

When **Module2.py** is run, Python will execute **Module1.py** first (due to the import), and then print the values again in **Module2**.

### Output:

```
<class 'int'> 10
<class 'bool'> True
<class 'float'> 25.5
10
True
25.5
```
