# Assignment - Online Library Management System

You have to design and implement a working online library management system. You have complete freedom to exercise your imagination and technical skills while adhering to the basic requirements laid out below.

Also note that though you obviously can take the easy route and search online for a solution, this assignment is really about showcasing your own analytical and technical skills, so the more individuality you show, the better shall be your prospects.

Use this opportunity to show us what you have got and that you have what it takes to join us as we build a wonderful product together.

# Functional Requirements
Below are listed the functional requirements that the solution should support. Wherever in doubt, make reasonable assumptions and move forward but please do document those assumptions as well so that we know why you made them.

## Must have features
- Member registration and approval by librarian
- User login and access based on role (Librarian / Member)
- Librarian access to register books and catalogue them
- Searching for desired books by ISBN, Title, Author, etc.
- Ability for any user to see book availability
- For physical books, ability for the member to raise a request for a book if it is available
- For e-books, ability for the member to download a book
- Ability for the librarian to issue a book based on user requests

## Nice to have features
- Take member's requests for new books which are currently not in the library catalogue
- Ability for the librarian to view the list of defaulters who are not returning books within alloted due dates
- Restrictions on the number of books that can be taken / downloaded at a time by a member based on his subscription type (Gold / Silver / Bronze)

# Technical requirements
## Mandatory
- MySQL 5.7 database to store all the master and transactional data for the system
- JPA 2.0 with Hibernate as the provider to persist and retrieve data
- Spring 4.0 as the application development framework and IoC container
- JAX-RS to expose REST APIs for all the functionality mentioned above
- HTML / CSS / JavaScript based UI talking to the backend library system strictly through the exposed REST APIs
- Strictly no Servlet / JSP, etc. based UI. The UI should talk to the backend using the REST APIs only
- Maven to be used as the build system for building the solution
- The solution should result in two web applications, one for the UI and one for the backend
- The solution should be able to run within a Tomcat 7.0 container

## Desirable
- Responsive UI using Bootstrap
- AngularJS as the JavaScript framework
- Single page web application
- Storage of session information in the browser's local storage
 
# How to submit the assignment
## Step 1
Fork this repository, and create a subdirectory titled with your name and any other optional text describing your solution
## Step 2
Complete coding for your solution. Make sure to also include any database scripts, etc. if required.
## Step 3
Submit a pull request to this repository before the stipulated due date for the assignment. Everything related to your solution should be within the subdirectory you created above
## Step 4
Include at a minimum one README file describing your solution along with detailed instructions on how to run it. You can have as many documentation files as you want. Use Markdown for the documentation

# Important
Unless you submit a pull request, we cannot consider your assignment for evaluation, hence make sure that you do submit a pull request. Also ensure that you submit only one pull request and that too only after you are fully ready to share your assignment with us.

We really look forward to getting some bright minds who can show us all their creativity and aptitude through this assignment.

## All the best and happy coding :-)


