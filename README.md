# SFIA1
**Index
Brief
Project Proposal
Trello Board
Initial Board
On-going Changes
Final Board
Risk Assessment
Risk Assessment Revisited
Architecture
Entity Relationship Diagrams
Deployment
Tools, Technologies and Languages
Front-end Design
Home Page
Shoes Page
Updating and Deleting Shoes
Shops Page
Example Shop
Admin Login Page
Testing
PyTest
PyTest Coverage
Project Hindsight
Noteable Accomplishments
Project Drawbacks
Future Improvements
Author
Acknowledgements
License
Brief**
Design a Create, Read, Update and Delete (CRUD) application utilising tools, methodologies, and technologies that illustrate all core modules covered during training so far.

**The requirements are, however not limited too:**

**#Trello Board (or Kanban equivalent).**
A relational MySQL database created on Google Cloud Platform (GCP) - displayed with an Entity Relationship Diagram (ERD).
Clear documentation including architecture design, risk assessment, and so on.
The CRUD application itself, coded in Python, that meets the User Stories on the Trello Board.
Testing the application for validation using Pytest - consistent reports and evidence must be provided to prove a Test Driven Development (TDD) approach.
A fully functioning front-end website with integrated APIs, using Flask.
Code incorporated into a Version Control Machine (VCS), implementing the Feature-Branch model which will then be built through a Continuous Integration (CI) server i.e. Jenkins, before finally being deployed to a cloud-based Virtual Machine (VM).
Project Proposal


**#Trello Board**
To track my project progression, I used a kanban Trello Board. This helped me to have an overview of the different stages of the project. Although this was an individual project, Agile methodology was carried out where possible, regarding the product and sprint (tasks) backlog. The product backlog contained User Stories that the CRUD application had to fulfill, then the tasks broke this down into smaller objectives that had to be completed to meet the end-goal.

**#Tools, Technologies and Languages**
The following are all the tools, technologies and languages used to create and deploy the app:

**Trello: Used for project tracking**
**GitHub: Version Control System, also used in conjunction with Jenkins via Webhook
Google Cloud Platform (GCP): Allows a live, virtual environment for the application, also a host for MySQL database
MySQL: Enables SQL databases and tables, as well as allowing query functions in Python
Jenkins: Continuous Integration (CI) Server - automatically builds the application from pushed code on GitHub
Unit Testing (PyTest): Tests one function at a time with optional coverage
Gunicorn: Deploys application on a Production WSGI server
Visual Studio Code: IDE used for several languages to achieve front-end and back-end development:
CSS: Styling for front-end design
HTML: Front-end design
Python3: Logic and functionality
Flask: Integrates front-end and back-end
Jinja2: Allows for python variables and logic in HTML
Front-end Design
JSON JAVA for button layout
Bootstrap for better CSS layout**
To keep this section concise, rather then showing both the user and admin front-end, only the admin view of the front-end will be shown. Although, keep in mind that the only difference is the user view does not have any of the Create, Update or Delete APIs. Although CCS was not a priority according to the project specification, a small amount has been added to slightly better the user experience (UX). The user interface (UI) has been laid out in a way that is user-friendly.
