# 🧩 AEtherX

**Semester-long course project for CSE 316: Software Development**

**Full-stack Q&A website for programmers, similar to Stack Overflow**

* ⚡ App replicates over 15 features of Stack Overflow with a secure RESTful API

* ⚙️ Features voting system, tagging, reputation, pagination, admin moderation, role-based access

* 🔐 Implemented the entire user login system to allow CRUD operations on the users & secured user authentication.

* 💾 Tech Used: Our team wrote 7000+ lines of code using React, Node.js, Express, MongoDB (MERN Stack), & Tailwind CSS.


## Desktop Preview

![image](https://github.com/Aadith2022/fakestack/assets/113648765/0cdf10e6-650b-4db8-8745-651130465d1e)

## Asking a Question

<img width="878" alt="image" src="https://github.com/ylu8888/HistoriaHub/assets/123523291/9a52b2e8-0728-4b1b-b1c9-8c437829e8ca">

## Question Details

![image](https://github.com/Aadith2022/fakestack/assets/113648765/8bb96fa3-1a27-404b-87d0-79c1f2e77d36)

## Answering a Question

![image](https://github.com/Aadith2022/fakestack/assets/113648765/74b88cfe-7ca7-410e-887e-3d5483f84eea)

## Tags Page

![image](https://github.com/Aadith2022/fakestack/assets/113648765/bed3009e-6f65-431c-8421-853010c19841)


![image](https://github.com/Aadith2022/fakestack/assets/113648765/3c59c855-ad10-4414-8f39-8c18660bc996)

## Profile Page

<img width="1361" alt="image" src="https://github.com/ylu8888/HistoriaHub/assets/123523291/c38259e5-b497-4262-ad4c-415fbdf8fae1">

## Edit Question

<img width="798" alt="image" src="https://github.com/ylu8888/HistoriaHub/assets/123523291/6d0c8ca6-6f1a-436a-81fd-955c90ba5bce">

## View Created Tags

![image](https://github.com/Aadith2022/fakestack/assets/113648765/17ffbab0-00ed-49f7-a362-512a9eaac4e1)

## View Answered Questions

![image](https://github.com/Aadith2022/fakestack/assets/113648765/d68efc54-062b-44ab-85fe-adc2d108011c)


## UML Diagram

![uml](https://github.com/Aadith2022/fakestack/assets/113648765/70baf4f8-dff6-49d9-90db-71d9729ef944)


## Database Diagram

![database](https://github.com/Aadith2022/fakestack/assets/113648765/56efdd0d-5b00-41f4-ab7d-aa7482c3b93e)


## Instructions to setup and run project
* Install the dependencies (express, mongoose, axios, cors, nodejs etc) and additional libraries bcrypt and express-sessions. Install MongoDB and make a database called fake_so and start it from the terminal(mongosh). 

* Run two terminals in VSCode, one for the client using npm start, and one for the server using nodemon server.js. 

* From the server terminal, run the script using this command: node init.js mongodb://127.0.0.1:27017/fake_so admin 123

* The command takes in admin username and admin password as the last two arguments. This script will populate the database with some initial values and from there you will be able to access the project from localhost:3000
