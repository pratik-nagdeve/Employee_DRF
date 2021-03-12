#Intructions to Install the Employeed DRF project

clone the repository


1. Create Virtual Environment and activate it

2. Install required libraries with Requirements.txt file
    > pip install -r requirements.txt

3. Creating a new Django Project and Initial setup for DRF
    > cd drf
    > python manage.py makemigrations
    > python manage.py migrate
    > python manage.py runserver


## CREATE API View for Employee Details
    > http://localhost:8000/employee/api/create
    

## LIST API View for Employee Details
    > http://localhost:8000/employee/api


## UPDATE API View for Employee (PUT or PATCH request)
    > http://localhost:8000/employee/api/1     
    
    <note: here your_employee_id = 1>

## DELETE API View for Employee Details
    > http://localhost:8000/employee/api/1/delete

    <note: here your_employee_id = 1>