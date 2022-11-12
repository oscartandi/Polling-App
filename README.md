# The_Poll_App
Designed Using Django:
  Django is a free and open-source, Python-based web framework that follows the model–template–views architectural pattern. It is maintained by the Django Software   Foundation, an independent organization established in the US as a 501 non-profit.
  
## How To Run ?

To Run save code to your local machine and start the development server.

## The development server
Let’s verify your Django project works. Change into the outer mysite directory, if you haven’t already, and run the following commands:

## Setting up in Local Machine

#### Step-1 
  Open a `terminal`, clone the `The_Poll_App` repository and go into the directory using the command `cd`.
  ```bash
  https://github.com/oscartandi/The_Poll_App/

  ```
  #### Step-2
  Check `python-3` is installed then install `pip` manager for python-3 and install `Django`.
  ```bash
  #Checking python is installed
  python3 --version 

  #Install Django
  python -m pip install Django

  #Verifying Django installation
  >>> import django
  >>> print(django.get_version())
  4.1
  ```

#### Step-3 
Start the `server`
```bash
python manage.py runserver
```
![image](https://user-images.githubusercontent.com/98871819/201474698-1d5a45ba-966d-4572-8c50-906db48592c4.png)

#### Step-4
```
Open your browser and go to `localhost:8000/index` we can see our application running in the localhost.
```
![image](https://user-images.githubusercontent.com/98871819/201474901-144eb854-3bca-4986-a3ff-3ca1e34c96ef.png)

#### Step-5 

For Poll add `/polls/` local host link 
```
http://127.0.0.1:8000/polls/
```

#### Step-6

Visit Questions and poll your options

#### Step -7 

To Visit Server Side use localhost and add `/admin/`

```
http://127.0.0.1:8000/admin/login/?next=/admin/
```

Sign-in to Admin and use the app.

Reference ``` https://docs.djangoproject.com/en/4.1/ref/django-admin/#django-admin-createsuperuser```

