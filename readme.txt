Module: Python modules
https://www.tutorialspoint.com/python/python_modules.htm

1 import  statement
2 from ...import  statement
  from ...import * statement
  
3 Loading modules:
The module search path is stored in the system module sys as the sys.path variable. 
The sys.path variable contains 1)the current directory, 2)PYTHONPATH, and 3)the installation-dependent default.

4 namespace and scoping
Variables are names (identifiers) that map to objects. A namespace is a dictionary of variable names (keys) and their corresponding objects (values).
A Python statement can access variables in a local namespace and in the global namespace. If a local and a global variable have the same name, the local variable shadows the global variable.
in order to assign a value to a global variable within a function, you must first use the global statement.The default scope is in local namespace.

5 dir() Function
6 globals()&& locals() Function

7 reload() Function
8 Packages in python
A package is a hierarchical file directory structure that defines a single Python application environment that consists of modules and subpackages and sub-subpackages, and so on.

and Here are the package instance using model.