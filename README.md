# Flask App

#### Create env
```commandline
py -m venv env
```
***
#### Activate env
```commandline
env\scripts\activate
```
***
#### Install the requirements
```commandline
pip install -r requirements.txt
```
***
#### Create DB tables
_Note: *one time setup*_
###### Open python shell and run the following command
```commandline
from project import db, create_app, models
db.create_all()
```
***
#### Set the environment variables
```commandline
set FLASK_APP=project
set FLASK_DEBUG=1
```
***
#### Run the service
```commandline
flask run
```
***
# Happy Coding!