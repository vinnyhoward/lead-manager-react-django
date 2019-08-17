# Getting Started
Start shell

`pipenv shell`

Create folder

`django-admin startproject leadmanager`

Start

`python manage.py startapp leads`

Create migration files

`python manage.py makemigrations leads`

Run migration files

`python manage.py migrate`

# Creating our `serializer`

__What is a serializer?__

Serializers allow complex data such as `querysets` and model instances to be converted to native Python data types that can then be easily rendered into `JSON`, `XML` or other content types. `Serializers` also provide `deserialization`, allowing parsed data to be converted back into complex types, after first validating the incoming data.

The `serializers` in REST framework work very similarly to Django's `Form` and `ModelForm` classes. We provide a `Serializer` class which gives you a powerful, generic way to control the output of your responses, as well as a `ModelSerializer` class which provides a useful shortcut for creating `serializers` that deal with model instances and `querysets`.