# 0x03. User authentication service
![Authentication](https://camo.githubusercontent.com/fec91e1baa51611c12e5aed82c72e403c198528f66fbadd9dfd8d79fec851435/68747470733a2f2f63646e2d6270706c6d2e6e6974726f63646e2e636f6d2f4d4a656652774f52766c477a626c657045495249677271514643476c694769472f6173736574732f7374617469632f6f7074696d697a65642f7265762d373266393461652f77702d636f6e74656e742f75706c6f6164732f323032302f30372f557365722d41757468656e7469636174696f6e5f2d556e6465727374616e64696e672d7468652d4261736963732d546f702d546970732e6a7067)

In the industry, you should not implement your own authentication system and use a module or framework that doing it for you (like in Python-Flask: [Flask-User](https://flask-user.readthedocs.io/en/latest/). Here, for the learning purpose, we will walk through each step of this mechanism to understand it by doing.
## Resources

### Read or watch:
+ [Flask documentation](https://flask.palletsprojects.com/en/1.1.x/quickstart/)
+ [Requests module](https://requests.kennethreitz.org/en/latest/user/quickstart/)
+ [HTTP status codes](https://www.w3.org/Protocols/rfc2616/rfc2616-sec10.html) or [this URL](https://www.rfc-editor.org/rfc/rfc9110.html)

## Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, **without the help of Google:**

+ How to declare API routes in a Flask app
+ How to get and set cookies
+ How to retrieve request form data
+ How to return various HTTP status codes

## Requirements
+ Allowed editors: `vi`, `vim`, `emacs`
+ All your files will be interpreted/compiled on Ubuntu 18.04 LTS using `python3` (version 3.7)
+ All your files should end with a new line
+ The first line of all your files should be exactly `#!/usr/bin/env python3`
+ A `README.md` file, at the root of the folder of the project, is mandatory
+ Your code should use the `pycodestyle` style (version 2.5)
+ You should use `SQLAlchemy` 1.3.x
+ All your files must be executable
+ The length of your files will be tested using `wc`
+ All your modules should have a documentation (`python3 -c 'print(__import__("my_module").__doc__)'`)
+ All your classes should have a documentation (`python3 -c 'print(__import__("my_module").MyClass.__doc__)'`)
+ All your functions (inside and outside a class) should have a documentation (`python3 -c 
 'print(__import__("my_module").my_function.__doc__)'` and `python3 -c 'print(__import__("my_module").MyClass.my_function.__doc__)'`)
+ A documentation is not a simple word, it’s a real sentence explaining what’s the purpose of the module, class or method (the length of 
 it will be verified)
+ All your functions should be type annotated
+ The flask app should only interact with `Auth` and never with `DB` directly.
+ Only public methods of `Auth` and `DB` should be used outside these classes
