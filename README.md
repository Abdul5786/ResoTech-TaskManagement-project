# ResoTech-TaskManagement-project
# this is a Task Management project created using spring boot,spring security 6,JWT TOKEN ,database(mysql)
# key features 
Models:

1)User Model:

Roles: The User model supports two roles: "ADMIN" and "USER."
Role-Based Access: Administrators and Users have distinct access privileges based on their roles.

 Tasks Model:
       Task Management: Supports functionalities for adding tasks, retrieving assigned tasks, and updating task statuses.
       Role-Based Operations: Administrators and Users can interact with the Tasks model based on their roles.

3)User Role-Based Access Control:

  Administrator: Has access to APIs for adding tasks, retrieving all tasks, and viewing completed tasks.
  User: Can call APIs to get tasks, update task status, and perform user-specific operations.
   
4)Spring Security 6:

Utilizes the latest version of Spring Security for robust authentication and authorization mechanisms, safeguarding sensitive URLs and functionalities.
JWT Token Implementation:

5)Implements JSON Web Tokens (JWT) for secure and stateless communication between the client and server, enhancing overall system security.
MySQL Database:

6)Utilizes a MySQL database to store and manage user information, task details, and related data.
