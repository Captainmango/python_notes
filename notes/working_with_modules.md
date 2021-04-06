## modules
* used to manage code in different files
* can be used to import standard libraries like numpy and re
* Can also transport code across other files in the python project

done with the following syntax

```python

from <location> from <file> as <alias>

```

if the file is local to the project and directory, you can use the from syntax as this is a relative import. If the file is outside of the dir, you can just use import as this is a static import. Aliases are used to make it easier to manage files as the classes and variables will be accessible by using the file name and dot notation. This is basically the same as Ruby's import system but smarter as it will scan across all namespaces and handles the imports better.

We need to make sure we use an init.py file inside of the directory or it will not be recognised as a module by Python.

```
it needs to be written like this

__init__.py

```

Nothing needs to be in the init.py file, but it can contain global variables like version or names for the module.