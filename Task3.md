## Setting up a Python Environment
1. Download Python and install the lastest version from the Offical website.

1. Install virtual environment using the command :
    ```cmd
    python -m pip install virtualenv
    ```
1.  Create virtual environment in a new folder using the command:
    ```cmd
    python -m venv /pathto/folder
    ```
1. We can activate the Virtual environment using the scripts:
    ```cmd
    /pathto/folder/Scripts/activate.bat

    ::After Activating the Virtual Environment the CMD will look like this.

    (virtual_environment)D:\Task_3\virtual_environment>
    ```
1. Now we check the python version in the virtual environment using the command:
    ```cmd
    python --version
    3.11.4
    ```
1. To use a different version of python repeat Step 1.

1. Now to use the different version in the virtual environment modify the pyvenv.cfg file in folder.
    ```cmd
    home = /pathto/pythonXX
    include-system-site-packages = false
    version = 3.x.x
    executable = /pathto/pythonXX/python.exe
    command = /pathto/pythonXX/python.exe -m venv D:\Assignments\Task_3\virtual_environment

    ```
1. After modifying the pyvenv.cfg with configurations for the required version repeat the steps 4 and 5 :
    ```cmd
    /pathto/folder/Scripts/activate.bat

    ::After Activating the Virtual Environment the CMD will look like this.

    (virtual_environment)D:\Task_3\virtual_environment>python --version
    3.8.7
    ```
1. We have successfully setup to work with different versions of python using virtual environment.

<br>

## Working With Packages using pip

1. To install a package using pip use the command :
    ```cmd
    python -m pip install package_name
    ```
1. To update a package using pip use the command :
    ```cmd
    python -m pip install --upgrade package_name
    ```
1. To remove a package using pip use the command :
    ```cmd
    python -m pip uninstall package_name
    ```
