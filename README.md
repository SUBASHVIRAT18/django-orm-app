# Django ORM Web Application

## AIM
To develop a Django application to store and retrieve data from a database using Object Relational Mapping(ORM).

## Entity Relationship Diagram

Include your ER diagram here

## DESIGN STEPS

### STEP 1:

Install myapp using command prompt

### STEP 2:

Edit settings.py and model.py

### STEP 3:

create a username and password using for your django 'python Createsuperuser' and then run the program using python manage.py runserver [your port number]

## PROGRAM

```
admin.py
 from django.contrib inport admin
from.models import Football_player,Football_playerAdmin
 admin.site.register(football_player, Football_playerAdmin)

model.py
from django.db import models
from django.contrib import admin
class Football_player (models.Model):
     Name-models.CharField(max_length=20)
     Dob models.DateField()
     Height models. IntegerField()
     Address-models.CharField(max_length=100)
     MobileNo=models. IntegerField()
class Football_player (admin.ModelAdmin):
     list_display=["Name", "Bob", "Height", "Address","MobileNo"]
```


## OUTPUT

![django orm](https://github.com/SUBASHVIRAT18/django-orm-app/assets/147473303/086f7099-13e3-4d86-ab3d-47ca464b9d16)


## RESULT

Thus the program for creating a database using ORM has been executed successfully
