# Virtual Environment using "venv" in python

## Windows

### Create a virtual environment

- Create a directory using : mkdir "name"
    - example: $ mkdir venv

- python -m venv "path" 
    - example: $ python -m venv .\venv\

### Create a virtual environment wiht a **specific** python version
- Which python versions are currently installed ? 
    - Windows PowerShell 
        - py -0p
        - Response (* means the current used python):
            -  -3.10-64       C:\Users\adrian\AppData\Local\Programs\Python\Python310\python.exe *
            -  -3.9-64        C:\Users\adrian\AppData\Local\Programs\Python\Python39\python.exe
    - Bash 
        - where python
        - Response: 
            - C:\Users\adrian\AppData\Local\Programs\Python\Python310\python.exe
            - C:\Users\adrian\AppData\Local\Programs\Python\Python39\python.exe
- Choosing python 3.9 from the example above: 
    - C:\Users\adrian\AppData\Local\Programs\Python\Python39\python -m venv .\venv\

### .gitignore file 
- $ touch .gitignore
- $ code .gitignore
- write the name of files or directories that you don't want to incude in your git repo
    - example: /venv

### Activate virtual environment
- "path"/Scripts/Activate.ps1
    - example: $ .\venv\Scripts\Activate.ps1

### List current libraries of a virtual environment activated
- $ pip list 

### Install library
- pip install "library"
    - example: $ pip install ipykernel 

### Deactivate virtual environment
- $ deactivate


# Selecting Python interpreter in VS Code

- Ctrl + Shift + P
- Pyhon: Select Interpreter
- Enter interpreter path ...
- Look for the directory where you created the "venv" -> ./venv/Scripts/python.exe
- Click in "Select Kernel" -> Select the appropriate"venv"

# Create a "requirements.txt" file
- $ pip freeze > requirements.txt



