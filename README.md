# Virtual Environment using "venv" in python

## Windows

### Create a virtual environment

- Create a directory using : mkdir "name"
    - example: $ mkdir venv

- python -m venv "path" 
    - example: $ python -m venv .\venv\

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



