# social-auth-example-django
Implementing python-social-auth in Django



## The development server[¶](https://docs.djangoproject.com/en/4.2/intro/tutorial01/#the-development-server)

Let’s verify your Django project works. Change into the outer `social-auth-example-django` directory, if you haven’t already, and run the following commands:

Create super user

```bash
$ python manage.py createsuperuser
```



Migrate

```bash
$ python manage.py migrate
```



Run server

```bash
$ python manage.py runserver 0.0.0.0:8000
```



Now that the server’s running, visit http://127.0.0.1:8000/ with your web browser. You’ll see a “Congratulations!” page, with a rocket taking off. It worked!
