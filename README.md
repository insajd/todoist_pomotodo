# todoist_pomotodo
Todoist synchronization with Pomotodo.

# About
Pomotodo was missing proper synchronization with Todoist. This tool helps you plan tasks with Todoist, and track their progress with Pomotodo.

# Download
 `git clone https://github.com/insajd/todoist_pomotodo.git`

# Configure
1. Edit [thehook.py](thehook.py) file with correct tokens
2. Edit [thehook.py](thehook.py) and [functions.py](functions.py) with correct timezone.

# Running
 ```
 virtualenv --no-site-packages ~/.virtualenvs/todoist_pomotodo
 source ~/.virtualenvs/todoist_pomotodo/bin/activate
 pip install -r requirements.txt
 python thehook.py
 ```
