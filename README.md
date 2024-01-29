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
- Windows - ``` venv\Scripts\activate ```

- ## Clone & Install
- ``` https://github.com/DesignerBoobesh/e-com-project.git ```
- (venv) ``` pip install -r requirements.txt ```

- ## Migrate & User & Run
- (venv) ``` python manage.py migrate ```
- (venv) ``` python manage.py createsuperuser ```
- (venv) ``` python manage.py runserver ```
