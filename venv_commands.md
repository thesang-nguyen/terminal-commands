# (Python) Virtual Environments with `venv`

## Create:

on Windows (`cmd`):

```shell
py -m venv <venv_name>
```

using a specified version of python, e.g. version 3.7.9:

```shell
C:\Users\<username>\AppData\Local\Programs\Python\Python37\python -m venv <venv_name>
```

or:

```shell
C:\Users\<username>\AppData\Local\Programs\Python\Python37\python.exe -m venv <venv_name>
```

## Activate:

on Windows (`cmd`):

from root directory (directory it was created in):

```shell
<venv_name>\Scripts\activate
```

from anywhere:

```shell
C:\Users\<username>\envs\<venv_name>\Scripts\activate
```

## Deactivate:

on Windows and Linux:

```bash
deactivate
```
