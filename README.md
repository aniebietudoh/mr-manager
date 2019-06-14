## To Run the application


### Setup the Backend API
Create an environment using python
```
python -m venv ./env
```

Activate the environment
```
. env/bin/activate
```

Clone the repo
```
git clone https://github.com/ekikoh/mrManager.git
```

Enter the directory
```
cd mrManager
```

Install needed packages
```
pip install django djangorestframework django-cors-headers
```

Migrate the database
```
python manage.py migrate
```

Start the backend server
```
python manage.py runserver
```

#### Setup the frontend
In a new terminal while the previous one is still running

Enter the frontend directory

```
cd frontend
```

npm install the dependencies
```
npm install
```

Start the frontend server
```
npm start
```

Visit the url specified `http://localhost:3000`

Your should now have the app running