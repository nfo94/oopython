### Object oriented programming with Python

[Future Learn](https://www.futurelearn.com/info/courses/python-in-hpc/0/steps/65121#:~:text=Python%20is%20both%20a%20strongly,is%20determined%20only%20during%20runtime.) and [Real Python](https://realpython.com/lessons/dynamic-vs-static/)

-   Python is both a strongly typed and a dynamically typed language.
-   Strong typing means that variables do have a type and that the type matters when performing
    operations on a variable. Dynamic typing means that the type of the variable is determined only
    during runtime.
-   Due to strong typing, types need to be compatible with respect to the operand when performing
    operations. For example Python allows one to add an integer and a floating point number, but
    adding an integer to a string produces error.
-   Python is a dynamically typed language. This means that the Python interpreter does type
    checking only as code runs, and the type of a variable is allowed to change over its lifetime.

Obs: just for comparison, JavaScript is dynamically and weakly typed

[Python Object-oriented programming](https://www.amazon.com/Python-Object-Oriented-Programming-maintainable-object-oriented/dp/1801077266/ref=sr_1_2_sspa?keywords=python+object+oriented+programming&qid=1677491596&sprefix=python+object%2Caps%2C205&sr=8-2-spons&psc=1&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUEyTzQzRTJQOVE3NE5OJmVuY3J5cHRlZElkPUEwMDUxOTAzM0lPRTA3TTlJQ0xDUiZlbmNyeXB0ZWRBZElkPUEwODkwNTI0MVVMOU9ZUFNOQ0wzNSZ3aWRnZXROYW1lPXNwX2F0ZiZhY3Rpb249Y2xpY2tSZWRpcmVjdCZkb05vdExvZ0NsaWNrPXRydWU=)

-   Everything in Python is an object
-   Every object is defined by being an instance of at least one class. What's the distinction
    between class and type? The class statement lets us define new types
-   When we check the type of a variable with `type()`, we see the type of the object the variable
    currently references
-   While the hints consume some storage, they have no runtime impact. Python politely ignores these
    hints; this means they're optional. People reading your code, however, will be more than
    delighted to see them. They are a great way to inform the reader of your intent. You can omit
    them while you're learning, but you'll love them when you go back to expand something you wrote
    earlier
-   The one difference, syntactically, between methods of classes and functions outside classes is
    that methods have one required argument. This argument is conventionally named `self`
