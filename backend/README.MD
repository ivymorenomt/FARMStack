## FARM Stack

This is my first attempt to create apps using FARM Stack.
FA - FastAPI - backend
R - React - frontend
M - MongoDB - database

1. To create a pipfile and activate virtual environment, 
run pipenv shell

2. Install dependencies:
pipenv install -r requirements.txt
Pipfile.lock created

3. To execute:
pipenv run uvicorn main:app --reload
4. To execute frontend:
go to frontend directory
npm start
5. To execute MongoDB:
go to MongoDB Compass
Click Connect, or connect to mongodb://localhost:27017/ in the mongodb shell
