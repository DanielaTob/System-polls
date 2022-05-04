# System-polls

> Built with python, postgres y django

## 💻 previous requirements

Before starting, verify that you have the following requirements:
* Python installed
* Visual Studio Code


##  Installing

To install the project locally, follow these steps:


<img src="https://img.shields.io/badge/Windows-017AD7?style=for-the-badge&logo=windows&logoColor=white" />

enter your command window and run the following to clone the repository
```
git clone https://github.com/danielatob/System-polls.git
```
Install the dependencies found in the file requeriments.txt for that start the virtual environment of Python accedion with the following command
```
 .\env\Scripts\activate 
```
then run the following command to install the dependencies
```
use the command "pip install requeriments.txt" 
```
Configure the settings file to add the connection to the database. 

settings.py
```
DATABASES = {
    'default': {
        'ENGINE': 'here is the configuration of the database to use either postgres, mysql or django, etc.',
        'CLIENT': {
            "host":"get here the host name",
            "name":"name databases",
            "port": "name port",
            "user": "database user",
            "password": "password to the database"
        },
    }
}
```

finally run the command to start the server locally

```
py manage.py runserver
```

## ☕ Using
<img  src="https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white"/>

<img  src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white"/>

<img  src="https://img.shields.io/badge/Heroku-430098?style=for-the-badge&logo=heroku&logoColor=white"/>

##  Views

![image](https://raw.githubusercontent.com/DanielaTob/img/main/home.png)

![image](https://raw.githubusercontent.com/DanielaTob/img/main/create.png)

![image](https://raw.githubusercontent.com/DanielaTob/img/main/vote.png)

![image](https://raw.githubusercontent.com/DanielaTob/img/main/results.png)

## Deploy 


<img  src="https://img.shields.io/badge/Heroku-430098?style=for-the-badge&logo=heroku&logoColor=white"/>


Click on the following link to see the display [Link here!](https://syspoll.herokuapp.com/)

## Developers 😺

* **Daniela Tobar Moreno** [GitHub](https://github.com/DanielaTob)
