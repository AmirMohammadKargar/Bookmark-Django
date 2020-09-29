# Bookmark-Django
<h3>Description</h3>
It's Django social app that user can follow other users and share image and bookmark image from other site to his account.

<h3>Requirements</h3>
First install virtualenv for python

```
$ pip install --upgrade virtualenv
```

then create virtualenv and active it.

```
$ virtualenv name
$ source bin/activate
```
install requirement

```
$ pip install -r requirements.txt
```
<h3>Run</h3>
First makemigrations and migrate to create database.

```
$ python manage.py makemigrations
$ python manage.py migrate
```

Create super user

```
$ python manage.py createsupeuser
```
Run Redis

``` 
$ redis-server
```

Run server

``` 
$ python manage.py runserver
```
