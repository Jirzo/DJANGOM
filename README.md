﻿<h1 align="center">DJANGO</h1>

## 🏁 Getting Started <a name = "getting_started"></a>

These instructions will help you get started with the Django environment. <br>
So, first clone the repository from Github and switch to the new directory:

## Prerequisites

- [Python](https://www.python.org/downloads/)
- [VSCODE](https://code.visualstudio.com/download) - ( Only if you want )



## Virtual enviroment

To activate the virtual environment for your project, begin by running the command line as an administrator, then navigate to the directory where you've cloned the repository. Once you're in the correct folder, execute the following command: `.\venv\Scripts\activate` and press enter.

## Install requirementgs

Upon activating the virtual environment, to install the necessary project requirements, simply enter the command `pip install -r requirements.txt` and patiently await the completion.

## Run server

Before to run sever we have to type two commands. <br>
- Fist one: `python manage.py makemigrations`, this command is tasked with generating new migrations that reflect the modifications you've applied to your models.
- Second one `python manage.py migrate`, this command is in charge of applying and reverting migrations as needed.

These commands will introduce additional tables to our database, enhancing the relationship between Django and MariaDB.

Now the only thing that you have to do it to run the server is type this `python manage.py runserver`
After that you have to go to this addrees `http://127.0.0.1:8000/categories/` so if everything is correct you will see this:
![Django REST framework image](https://imgur.com/1VlORiB.png)

There are two paths that you can visit
- `http://127.0.0.1:8000/admin/` you'll require a username and password. Please utilize the following credentials: `Username: root` and `Password: admin` should those credentials fail, you'll need to create a superuser utilizing the following command: 
- `http://127.0.0.1:8000/docs` and this command will provide you with documentation detailing the HTTP request methods available.
<hr/>