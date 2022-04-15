# Alpha
For Project Alpha
=================

1.Kanban Board.
2. Risk ASsessment.
3.Database.
4.Jave program to interact with the database. (Buttons etc at a guess).


My First aim is to make a MVP. Make sure it works then add any bells and whistles later.

We will need to make a database with a minimumm of 3 Tables (Users as a 4th if we have the extra time.)

The relationship will be shown in a diagram for the customer.
Similiar to the below.

[Customers] --1--<--[Orders]---1---<--[Items]

[Users] would be the person who is editing the database.

We would want an Admin (at least 1) and the rest users who can add edit (maybe not delete unless admin).



===================================================================================================================================

Software Core Fundamental Project Specification

Introduction

The purpose of this document is to outline the individual project specification that you will be working on during the training.
This project will involve concepts from all core training modules; more specifically, this will involve:

Agile & Project Management
Databases
Cloud Fundamentals
Programming Fundamentals
The individual project must encapsulate all aspects of the aforementioned modules.
You will be provided with a domain to work with however creativity is encouraged as long as you meet the minimum requirement.

Objective
The overall objective of the project is the following:

To create an application with utilisation of supporting tools, methodologies and technologies that encapsulate all fundamental modules covered during training.
Specifically, you are required to create an application using the language from your Programming Fundamentals Module which interacts with a Managed Database.
You must plan the approach you will take to complete this project using the design techniques learnt, and also create a CI Pipeline that can automate the building and deployment of your artifact.

Domain
You are required to build an application that an end user can interact with via a CLI (Command Line Interface).
The application needs to be an inventory management system that needs to be able to:

Add a customer to the system
View all customers in the system
Update a customer in the system
Delete a customer in the system.
Add an item to the system
View all items in the system
Update an item in the system
Delete an item in the system
Create an order in the system.
View all orders in the system.
Delete an order in the system
Add an item to an order.
Calculate a cost for an order.
Delete an item in an order
When considering the entities in this domain:

A customer needs to have a name.
An item needs to have a name and a value.
An order needs to have a customer and contains items.
Extension (unmarked):
Add a user to the system
List all users
Changes to customers, items and orders need to be tied to a user.
A user should have a username and password
You must be able to log in as a user within the system to make any changes.
Scope
The requirements set for the project are below. Note that these are a minimum set of requirements and can be added onto during the duration of the project.

The requirements of the project are as follows:

A Kanban board with full expansion on user stories and tasks needed to complete the project. It should also provide a record of any issues or risks that you faced creating your project.
A relational database used to store data persistently for the project, this database needs to have at least 3 tables in it, to demonstrate your understanding, you are also required to model a relationship.
A functional application, following best practices and design principles, in a language that you have covered during training that meets the requirements set on your Kanban Board.
Unit tests and integration tests for validation of the application. You should strive to reach an industry standard coverage of 80%
Code fully integrated into a Version Control System (GitHub) using the Feature Branch Model: main/dev/features
A Risk assessment which outlines the issues and risks faced during the project time frame.
You should consider the concept of MVP (Minimum Viable Product) as you plan your project, complete all the requirements above before you add extra functionality that is not specified above.
If you wish to use any technologies which have not been covered with the training, you must consult with your trainer first.

Constraints
The time constraint of this application will be discussed when the specification is given out, as this can fluctuate based on several factors.

The other constraint for this is certain technology that needs to be used. The application needs to utilise the technology discussed during the training modules. The tech stack required would be the following:

Version Control System - Git
Source Code Management - GitHub
Kanban Board - Jira
Database - MySQL Server 5.7+ (local or cloud hosted)
Back-end Programming Language - Java
Build Tool - Maven
Unit Testing - JUnit
Deliverable
The final deliverable for this project is the completed application with full documentation around utilisation of supporting tools, this will require a fully functional application.

You will be required to present your work to at least one trainer; this may be your course leader, another trainer or several trainers. This will take the form of a presentation of work lasting 15 minutes, plus a 5-minute Q&A session.

You will be required to utilise the Feature-Branch Model and to push a working copy of your code to main branch for the marking of this project.

You will be required to include all supporting documentation for your project within your remote repository at close-of-business (17:30) on the day of presenting your project.

Marking Scheme
Below are the skills that we will be evaluating for this assessment.
These skills are as described in the SFIA 7 framework; please see below
if you wish to have more information:

https://www.sfia-online.org/en/framework

The skills this assessment will discussed are the following:

Programming/software development
Systems integration and build
Software Design
Testing
Software Design

