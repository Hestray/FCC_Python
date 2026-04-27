This repository contains the exercises from [FreeCodeCamp's Python Course](https://www.freecodecamp.org/learn/python-v9).

# Notes
1. Type errors are only detected at run-time.
2. Variable naming convention: `snake_convention` and `PascalCase` for classes
3. `__` cannot be accessed from outside, while `_` shows it's supposed to be private
```
def __init__(self):
    self._internal = 'I can be accessed from outside the class, but should not'
    self.__private = 'You cannot access me directly from outside the class'
```