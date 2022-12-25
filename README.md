# Basics of setting up a FastAPI server


## Installation

It is recommended that you create a virutalenv first before installing the requirements like so

```sh
python3 -m venv fastapi-env
source fastapi-env/bin/activate
```
And then install the required packages to run the server
```sh
pip install -r requirements.txt
```
To run the server for development
```sh
uvicorn main:app --reload
```
To view the docs head to `localhost:8000/docs`