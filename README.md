### To Run the application


#### Setup the Backend API
Creat and environment using python
`python -m venv ./env`

Activate the env
`. env/bin/activate`

Clone the repo
`git clone https://github.com/ekikoh/mrManager.git`

Enter the directory
`cd mrManager`

Install Needed packages
`pip install django djangorestframework django-cors-headers`

Migrate the database
`python manage.py migrate`

Start the server
`python manage.py runserver`

# Setup the frontend
In a new terminal while the previous one is still running

Enter the frontend directory
`cd frontend`

npm install the dependencies
`npm install`

Start the server
`npm start`

then visit the url specified http://localhost:3000

You should now have the app running