<h1 align="center">Work With Us!</h1>

<p align="center">
  <img alt="Resh Logo" src="https://resh.com.br/wp-content/uploads/2021/01/logo-dark-novo-1.png" width="15%" height="15%" />
</p>

# Resh - Rest API BackEnd Challenge


## Your Task
Your task is to create a simple application using the Python web framework `Django`. 
We estimate this will take 2-3 hours for a person who is familiar with 
the technology stack. However, expect extra 3-4 hours if you are not familiar
with `Django` and `Django Rest Framework`. The technology stack is the same that you will be using
in when working us.

#### Functional requirements
 - Create a REST API that allows to send a `CSV` file and store it in a database;
 - The file should be validated before being stored in the database;
 - If the file contains one incorrect row, the whole file should be rejected and 
all the data must be thrown away;
 - If the file is correct, it should be stored in the database;
 - The API should be able to return the data stored in the database.

You must use `Django` and `Django Rest Framework` to implement the API.

## Back-end
You should develop the back-end using `Django`. APIs can be served through `Django 
Rest Framework`, feel free to choose what you think it's better. Your Django App 
should be able to receive requests to support all the requirements.

It's important to you follow the REST principles, respecting HTTP protocol and 
using properly return codes and HTTP methods. Also, all communications should 
be done using JSON. Although it's important to fill the `requirements.txt`
file with the dependencies needed to run this project.


## Front-end
You can use `Django Rest Framework` default interface to send the file to the API.


## Populate the database
You must use the file `data.csv` to populate the database. The file contains
a list with random CVEs (Common Vulnerabilities and Exposures) and their respective
information, just like the example below:
- Nome: CVE-2019-0001
- Descrição: A description of the CVE
- Severidade: High
- CVSS: 7.5

The file contains 50 CVEs. You can use the file to test your application.

## Optional tasks
* Optimize you code to be fast and efficient;
* Also you can optimize the API to handle large files consuming less memory;
* Write tests for your code.

## How your exercise submission will be ranked

We will look:

* If the task was correctly completed;
* Clean code;
* Visual quality of the user interface changes - the layouts must look 
professional, not broken;
* Unit Testing and Integration Testing;
* Documentation (README and code comments).

## Delivery

Please upload your code to a repository we can access and let us know when 
it's ready. If possible, deploy the code onto some remote server so it's 
working too.

Don't worry about getting everything pixel perfect, the goal is to make 
sure you can handle tools and build custom interfaces, navigation, state
management and have the general engineering knowledge to solve the problems
at hand.
