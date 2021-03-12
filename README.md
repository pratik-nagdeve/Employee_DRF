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

     ![Alt text](images/GET.png?raw=true "GET") | ![Alt text](images/GET_postman.png?raw=true "GET_postman")


## CREATE API View for Employee Details (POST)
     http://localhost:8000/employee/api/create

     ![Alt text](images/POST.png?raw=true "POST") | ![Alt text](images/POST_postman.png?raw=true "POST_postman")


## UPDATE API View for Employee (PUT or PATCH request)
     http://localhost:8000/employee/api/<employee_id>
     
     example:
     http://localhost:8000/employee/api/1

     ![Alt text](images/PUT.png?raw=true "PUT") | ![Alt text](images/PUT_postman.png?raw=true "PUT_postman")

## DELETE API View for Employee Details
     http://localhost:8000/employee/api/<employee_id>/delete

     example:
     http://localhost:8000/employee/api/1/delete

     ![Alt text](images/DELETE.png?raw=true "DELETE") | ![Alt text](images/DELETE_postman.png?raw=true "DELETE_postman")