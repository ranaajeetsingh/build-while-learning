**Objective**
An android application which helps to take notes at anytime and helps to generate a very strong password for security of your account and makes them available whenever you need. It's going to have two major functionalities at the same time.

**Project Stages**
1. Environment Setup
2. Authentication
3. Manage Notes
4. Manage Password

**High-Level Approach**
- The first task, once we get the development environment ready, will be to set up Android Studio & Firebase.
- Once we have everything in place, we can start off with creating the application, which will basically start with the login authentication.
- Next up is the home page building. In this project, we will be keeping it simple by showing two options i.e Notes & Password .
- In our project, we will need to manage three states: Note (to manage notes data), Password (to manage password data), and user (for managing the details of the currently logged in user).
- For showing all the notes or passwords , we will be using Listviews or recycleviews .
- Handling our database and authentication needs to be supported and we will be using Firebase for the same. Basically the database will be used to store the login information for the users , but the resource can be used for storing notes and password information as well.
- Successful implementation of the above requirements will lead to completion of the core implementation of our application. Next up, deploy!

**Primary goals**
- Create a login page for user login.
- Create a home page to display notes & password options.
- Create a note page to display all notes .
- Create a password page to display all passwords .
- Add functionalities like add note or password, delete note or password and update note (if required).