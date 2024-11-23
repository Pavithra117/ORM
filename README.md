# Ex02 Django ORM Web Application
## Date: 12.11.2024

## AIM
To develop a Django application to store and retrieve data from a Bank database using Object Relational Mapping(ORM).

## Entity Relationship Diagram
<<<<<<< HEAD
![alt text](<Screenshot 2024-11-23 190153.png>)
Include your ER diagram here
=======
![Screenshot 2024-11-15 213410](https://github.com/user-attachments/assets/eb4016c0-1173-4036-b498-8d923a5973ef)


>>>>>>> 027f1b7f0cdf6d33a1215970c8784f5c7fb89bbd

## DESIGN STEPS

### STEP 1:
Clone the problem from GitHub

### STEP 2:
Create a new app in Django project

### STEP 3:
Enter the code for admin.py and models.py

### STEP 4:
Execute Django admin and create details for 10 customers.

## PROGRAM
<<<<<<< HEAD
``` 
models.py
=======
MODELS.PY 
>>>>>>> 027f1b7f0cdf6d33a1215970c8784f5c7fb89bbd
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
<<<<<<< HEAD

admin.py
from django.contrib import admin
from .models import Customer,CustomerAdmin
admin.site.register(Customer,CustomerAdmin)

```
Include your code here

## OUTPUT
![alt text](<Screenshot (1).png>)
Include the screenshot of your admin page.
=======


ADMIN.PY


from django.contrib import admin
from .models import Customer,CustomerAdmin
admin.site.register(Customer,CustomerAdmin)




## OUTPUT

![Screenshot (1)](https://github.com/user-attachments/assets/913bfd91-4896-478b-8cc0-2b6155c6701f)

>>>>>>> 027f1b7f0cdf6d33a1215970c8784f5c7fb89bbd


## RESULT
Thus the program for creating a database using ORM hass been executed successfully
