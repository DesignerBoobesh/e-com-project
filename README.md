<br/>
  <h1 align="center">
    Django E-Commerce Project - DEBO 
  </h1>
<br/>

# Installation guide:

- ## Create a virtualenv
```Shell
pip install virtualenv
```
```Shell
virtualenv venv
```

- ## Activate venv
- Linux - ``` source venv/bin/activate ```
- Windows - ``` .venv\Scripts\activate ```

- ## Clone & Install
- ``` https://github.com/DesignerBoobesh/e-com-project.git ```
- (venv) ``` pip install -r requirements.txt ```

- ## Migrate & User & Run
- ``` create .env file (same as .env_sample and fill the required fields) ```
- Make Migrations
  ```Shell
  python manage.py makemigrations
  ```
- Migrate all the tables to the DB
  ```Shell
   python manage.py migrate
  ```
- Create SuperUser
  ```Shell
   python manage.py createsuperuser
  ```
- Run Server
  ```Shell
   python manage.py runserver
   ```
