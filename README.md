# INTRODUCING PYTHON

## Objective
This project is intended to save my progress while learning Python.

I am using the book "Introducing Python: Modern Computing in Simple Packages" written by Bill Lubanovic and publishe by O'Reilly. As I read the book, I will create a Notebook for my personal annotations, examples and exercise answers.

## About me
Name: Fernando

Twitter: @fahofmeister

Still developing my coding skills.

## Updates

### May 05, 2020
In Chapter 8 of the book is required to install a package through ```pip```. Therefore, to install any package should use the following syntax in any code cell: ```!pip install [package_name]```

Examples:
```python
!pip install sqlalchemy
```

#### Important
Packages installed through virtual terminal are available only during the session. Use only to test a few methods in the terminal.

Reference: <https://docs.microsoft.com/en-us/azure/notebooks/install-packages-jupyter-notebook>

### April 22, 2020
I've noticed that writing to a text file always come up with the same result, it doesn't matter if it is through ```write()``` method or ```print()```, the output file is always considering the spaces and newlines. Don't know yet if this is caused by the Python version or the Azure implementation.

Also, I'm still figuring out the arguments ```sep``` and ```end``` used in ```print()``` and how to apply them.

### March 26, 2020
I've just found that you can create .py files in Azure Notebooks and run them in the virtual terminal. The files are saved inside the folder Library. Linux command applies in the terminal.

Therefore, I decided to reorganize and create a folder for each chapter of the book. This way, I may alternate between .py files and Jupyter Notebooks in the same environment. I don't need to install python locally while learning Python.

Note: The folders in the terminal are case sensitive.