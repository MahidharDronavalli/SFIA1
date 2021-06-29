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

****#Tools, Technologies and Languages****

![image](https://user-images.githubusercontent.com/85611645/123757118-8e1ede80-d8b5-11eb-9252-51ac4834db28.png)

The following are all the tools, technologies and languages used to create and deploy the app:

Trello: Used for project tracking

GitHub: Version Control System, also used in conjunction with Jenkins via Webhook

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



**Risk Assessment**

Due to the size of my risk assessment being too big to turn into a .PNG, the link for it can be found here. The 'Likelihood' and 'Impact' columns are rated on a scale of 1 (low) to 5 (high). The assessment encompasses the following types of risks: Time Management, Computer-related Injuries, Security and Other.

Risk Assessment Revisited

The link for this assessment can be found here. During the project, I revisited my initial risk assessment and added an 'Update' column. This was filled with new considerations and discussed how effective the original solutions were.

Note: Both Risk Assessments are also located within the Documentation folder of this repository.

**Front-end Design**

To keep this section concise, rather then showing both the user and admin front-end, only the admin view of the front-end will be shown. Although, keep in mind that the only difference is the user view does not have any of the Create, Update or Delete APIs. Although CCS was not a priority according to the project specification, a small amount has been added to slightly better the user experience (UX). The user interface (UI) has been laid out in a way that is user-friendly.
![Signup](https://user-images.githubusercontent.com/85611645/123758614-05a13d80-d8b7-11eb-82ec-368a36af61a9.png)
![Login](https://user-images.githubusercontent.com/85611645/123758631-0934c480-d8b7-11eb-96e6-e674cbf2f0b2.png)
![Signupemailexists](https://user-images.githubusercontent.com/85611645/123758644-0b971e80-d8b7-11eb-9a53-d64157c86698.png)
![Passwordwrong](https://user-images.githubusercontent.com/85611645/123758650-0f2aa580-d8b7-11eb-984a-4b83b39d9183.png)
![notes](https://user-images.githubusercontent.com/85611645/123758665-118cff80-d8b7-11eb-8881-0425111d7069.png)
![image](https://user-images.githubusercontent.com/85611645/123759108-819b8580-d8b7-11eb-8992-22f20e48b19a.png)
![image](https://user-images.githubusercontent.com/85611645/123759269-a5f76200-d8b7-11eb-826a-bb3f61aab047.png)


