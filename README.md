## Intructions to Install the Employeed DRF project

clone the repository


1. Create Virtual Environment and activate it

2. Install required libraries with Requirements.txt file
    > pip install -r requirements.txt

3. Creating a new Django Project and Initial setup for DRF
    > cd drf

    python manage.py makemigrations

    python manage.py migrate

    python manage.py runserver

## LIST API View for Employee Details
     http://localhost:8000/employee/api

     ![Screenshot](GET.png)

     <img src="images/GET.png"> | <img src="images/GET_postman.png">


## CREATE API View for Employee Details (POST)
     http://localhost:8000/employee/api/create

     <img src="images/POST.png"> | <img src="images/POST_postman.png">


## UPDATE API View for Employee (PUT or PATCH request)
     http://localhost:8000/employee/api/<employee_id>
     
     example:
     http://localhost:8000/employee/api/1

     <img src="images/PUT.png"> | <img src="images/PUT_postman.png">

## DELETE API View for Employee Details
     http://localhost:8000/employee/api/<employee_id>/delete

     example:
     http://localhost:8000/employee/api/1/delete

     <img src="images/DELETE.png"> | <img src="images/DELETE_postman.png">