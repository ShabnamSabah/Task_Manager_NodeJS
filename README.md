# Task_Manager
It is a task management API using Node.js that allows users to create, manage, and track tasks.

Features:
1. User authentication system that allows users to signup, log in, and manage their profile.
2. Users are able to create, update, and delete tasks. Each task has a title, description, due date, and status (e.g., "in progress," "completed,"
"pending").
3. Users can assign tasks to other users and track the assignment status.
4. All the tasks are sorted based on due date.

## Technology Used
1. Node.JS
2. MySQL (Sequelize)

    ##### 
    Sequelize is a Node. js-based Object Relational Mapper  that makes it easy to work with MySQL, MariaDB, SQLite, PostgreSQL databases, and more. An Object Relational Mapper performs functions like handling database records by representing the data as objects. The benefit of using Sequelize is we can easily avoid writing raw SQL queries.


3. Javascript
4. Express.JS
5. Handlebars for Client Side User-Interface
## Documentation

1. Initialize the project by running the following command in Visual Studio Code.
```
npm init
```

2. Install the dependencies by running the following command in Visual Studio Code.
```
npm install
```
3. Create the databse with a name in Xampp Server/MySQl Workbench
```
your database name
```

4. Create .env file in the project folder and add the following
```
DB_name = "your database name"
DB_user = "usernme of datatabse"
DB_password = 'database password'
JWT_SECRET = secret key for user authentication
```

5. Run the project by using the following command.
```
nodemon app.js
```
After that databse will be created.

6. Open your browser and the following command
```
localhost:8000
```

7. Register some users in the system with the credentials.
8. Login with one user.
9. After that dashboard will open, in dashboard all the assigned task will be dispalyed. Intially it will be empty.
10. Click "Add A New Task" option from side bar.
11. Add a task and assign users for that task.
12. Click "View All Task" option from side bar. Here, it will display the tasks added by loggedIn user.
 a) There are two button here for edit and delete a task respectively. Through with you can edit or delete a task.
13. Then , logout from the system by clickig the person icon from the top-right corner of dashboard.
14. Next, Login with another user to whom you have assigned a task.
15. After that dashboard of that user will open, in dashboard all the assigned task will be dispalyed and it is sorted by due date wise. 
16. Here, for each task, there are three button to represent the status of the task: Pending, In Progress and Completed respectively.
17.  a) If you clicked on Pending, the status of task will become Pending. Then Click on the "View all Pending Task" option from side bar, it will display all the pending task by loggedIn User. Tasks are sorted by due date wise.
  b) If you clicked on In Progress, the status of task will become In Progress. Then Click on the "Task In Progress" option from side bar, it will dispaly all the task-in-progress by loggedIn User. Tasks are sorted by due date wise.
  c) If you clicked on Completed, the status of task will become Completed. Then Click on the "Completed Task" option from side bar, it will display all the completed task by loggedIn User. Tasks are sorted by due date wise.
 18. Click on "View all Pending Task","Task In Progress" and "Completed Task" option from side bar respectively,  then, all the pending task, all the task-in-progress and all the completed task by the loggedIn user will be displayed. Tasks are sorted by due date wise. From there, you can also change the status of a task.
 19. Click on the "Track Assigned Task" option from sidebar, then the status of the all tasks assigned by the user will be displayed.
 20. In the top-right corner of dashboard, there is a person-icon, from there a user can their profile and update it.
 21. Lastly, you can logged out from the system.
 
