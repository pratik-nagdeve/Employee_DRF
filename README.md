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

     <img src="https://github.com/tadiparChinese/Employee_DRF/blob/master/images/GET.png">
     
     ![](images/GET_postman.png)


## CREATE API View for Employee Details (POST)
     http://localhost:8000/employee/api/create

     ![](images/POST.png)
     
     ![](images/POST_postman.png)


## UPDATE API View for Employee (PUT or PATCH request)
     http://localhost:8000/employee/api/<employee_id>
     
     example:
     http://localhost:8000/employee/api/1

     ![](images/PUT.png?raw=true "PUT")
     
     ![](images/PUT_postman.png?)

## DELETE API View for Employee Details
     http://localhost:8000/employee/api/<employee_id>/delete

     example:
     http://localhost:8000/employee/api/1/delete

     ![](images/DELETE.png)
     
     ![](images/DELETE_postman.png)
