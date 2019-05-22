# sample-py-module
Sample wheel package module to create py module for pip

Step 1: Source Logic

You should write your source Logic inside ./deepak/__init__.py 
You can create any method on your own which needs to be called after importing the package.

Step 2: Should compile the python using sdist

You should be in the directory parallel to setup.py
should type the command "python setup.py sdist"

Step 3: Uploading Wheel Package

To upload the wheel package you should have "twine" installed in your machine(if Ubunty you can get twine using "apt-get install twine") 
you can use the command "twine upload dist/\*" to upload the package.

How to use the uploaded module.

Step 1: pip install {Module name}
Step 2: Inside Python Script "import {module name}"
Step 3: calling a method inside module using [{module name}.sample()]
