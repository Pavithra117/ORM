# Ex02 Django ORM Web Application
## Date: 12.11.2024

## AIM
To develop a Django application to store and retrieve data from a bank loan database using Object Relational Mapping(ORM).

## ENTITY RELATIONSHIP DIAGRAM
![Screenshot 2024-11-15 213410](https://github.com/user-attachments/assets/fb3ea039-c9ec-4bf5-b13b-50c347003351)



## DESIGN STEPS

### STEP 1:
Clone the problem from GitHub

### STEP 2:
Create a new app in Django project

### STEP 3:
Enter the code for admin.py and models.py

### STEP 4:
Execute Django admin and create details for 10 books

## PROGRAM
admin.py 

from django.contrib import admin
from .models import Customer,CustomerAdmin
admin.site.register(Customer,CustomerAdmin)

model.py

from django.db import models
from django.contrib import admin
class Customer (models.Model):
    eid=models.IntegerField(primary_key=True)
    name=models.CharField(max_length=100)
    salary=models.IntegerField()
    age=models.IntegerField()
    email=models.EmailField()
 
class CustomerAdmin(admin.ModelAdmin):
    list_display=('eid','name','salary','age','email')





## OUTPUT

![Screenshot (1)](https://github.com/user-attachments/assets/398d1aaf-19da-437c-b87c-ef684ed462bb)



## RESULT
Thus the program for creating a database using ORM hass been executed successfully
