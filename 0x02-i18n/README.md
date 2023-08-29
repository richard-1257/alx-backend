![i18N](https://github.com/richard-1257/alx-backend/assets/83041703/3390c4d7-d635-49f2-8cfd-42467df8dd9a)

# i18n
`Back-end` This project contains tasks for learning to create internationalized web pages with Flask.

- By: Emmanuel Turlay, Staff Software Engineer at Cruise
## Resources
**Read or watch:**
- [Flask-Babel](https://flask-babel.tkte.ch/)
- [Flask i18n tutorial](https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-xiii-i18n-and-l10n)
- [pytz](https://pytz.sourceforge.net/)

## Learning Objectives
- Learn how to parametrize Flask templates to display different languages
- Learn how to infer the correct locale based on URL parameters, user settings or request headers
- Learn how to localize timestamps

## Requirements
- All your files will be interpreted/compiled on Ubuntu 18.04 LTS using python3 (version 3.7)
- All your files should end with a new line
- A `README.md` file, at the root of the folder of the project, is mandatory
- Your code should use the pycodestyle style (version 2.5)
- The first line of all your files should be exactly `#!/usr/bin/env python3`
- All your `*.py` files should be executable
- All your modules should have a documentation (`python3 -c 'print(__import__("my_module").__doc__)'`)
- All your classes should have a documentation (`python3 -c 'print(__import__("my_module").MyClass.__doc__)'`)
- All your functions and methods should have a documentation (`python3 -c 'print(__import__("my_module").my_function.__doc__)'` and `python3 -c 'print(__import__("my_module").MyClass.my_function.__doc__)'`)
- A documentation is not a simple word, it’s a real sentence explaining what’s the purpose of the module, class or method (the length of it will be verified)
- All your functions and coroutines must be type-annotated.

## Tasks To Complete
+ [x] 1. **Basic Flask app**<br/>[test_utils.py](https://github.com/richard-1257/alx-backend-python/blob/master/0x03-Unittests_and_integration_tests/test_utils.py) contains a python module that meets the following requirements:
  + Implement `TestAccessNestedMap.test_access_nested_map_exception`. Use the `assertRaises` context manager to test that a `KeyError` is raised for the following inputs (use `@parameterized.expand`):
    ```python
    nested_map={}, path=("a",)
    nested_map={"a": 1}, path=("a", "b")
    ``` 
  + Also make sure that the exception message is as expected.






