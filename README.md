# GrowthPlug-Machine-Test-Task
This is a Machine Test Task to create a small ebook management REST API with Django and SQLite to show CRUD operations.

# Run the code
To run the code, i used POSTMAN to test the API. Following steps are required to run code.
Requirements are mentioned aa requirements.txt.

Please download and install the requirements using the code : **pip install -r requirements.txt** 

Then activate the Virtual Environment, makemigrations and migrate. Then run the code.
Steps are given as codes :
1) **..\Ebook\venv> Scripts/activate**
2) **(venv) PS D:\PROJECT\Ebook\venv> cd..**
3) **(venv) PS D:\PROJECT\Ebook> cd .\Ebook**
4) **(venv) PS D:\PROJECT\Ebook\Ebook> py manage.py makemigrations**
5) **(venv) PS D:\PROJECT\Ebook\Ebook> py manage.py migrate**
6) **(venv) PS D:\PROJECT\Ebook\Ebook> py manage.py runserver**

After completing these steps, you'll be given a URL as : **http://127.0.0.1:8000/**
Copy the link and run that in your browser to run the code.

The provided URL have to be followed with the app name Ebook as : **http://127.0.0.1:8000/ebook**
There you can see the Ebookviewset List and we can scroll down the page to where you can input the book details.

# API TESTING with CRUD Operations
Here we have used the API, POSTMAN for build, test and modify APIs.  
#ADD
There we can add the inputs with the parameter as : **POST** with the URL : **http://localhost:8000/ebook/**
#VIEW
We can see all the datas given with the parameters as : **GET** with the URL : **http://127.0.0.1:8000/ebook/**  
Here you can also call the n^th input by specifying the position_number in the position of n in the URL as : **http://127.0.0.1:8000/ebook/n/** 
#UPDATE
We can also update the data in the database by using the paramenter as : **PATCH** with the URL : **http://127.0.0.1:8000/update/n/** in which we have to mention the 
position_number in the place of 'n' in the URL.
