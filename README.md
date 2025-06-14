# Doctor-Appointment-MultiAgent-System

## How to run??
STEPS:
Clone the repository
```
https://github.com/mayanksharma45/Doctor-Appointment-MultiAgent-System.git
```
### STEP 01- Create a conda virtual environment after opening the repository
```
conda create -p venv python=3.10 -y
```
Then open your git bash terminal and run:
```
source activate ./venv
```
### STEP 02- install the requirements
```
pip install -r requirements.txt
```
At the end run,
```
streamlit run streamlit_ui.py
```
After this also run parallely with
```
uvicorn main:app --relaod --port 8003
```
