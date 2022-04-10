# (Python) Virtual Environments with `venv`

## Create:
on Windows (`cmd`):
    
    py -m venv <venv_name>
    
    # using a specified version of python, e.g. version 3.7.9:
    C:\Users\thesa\AppData\Local\Programs\Python\Python37\python -m venv <venv_name>
    # or
    C:\Users\thesa\AppData\Local\Programs\Python\Python37\python.exe -m venv <venv_name>

on Linux:

    ...

## Activate:
on Windows (`cmd`):

    # from root directory (directory it was created in)
    <venv_name>\Scripts\activate

    # from anywhere
    C:\Users\thesa\envs\<venv_name>\Scripts\activate

on Linux:

    ...

## Deactivate:
on Windows and Linux:

    deactivate