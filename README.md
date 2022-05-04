# User-Management-System-using-PHP-MySQLi
This is a Database Management System Project, that involves PHP and MySQL to create a frontend and connect it with the backend and database.

This Project involves Role Based Access control concepts.

What is Access Control?

In a multi-user application which is deployed over numerous devices which are linked together in a network it is more than likely that not all functionality will be available to all users. There are several components of this system:

A list of all funcitons that are available within the system. These 'functions' are sometimes referred to as transactions or tasks
A list of all persons who are allowed to access the application as a whole. These persons are sometimes referred to as users.
A list of permissions which identifies which functions are accessible by which users.


What is role based?


Level based: In this system each TASK is given a security level number in the range 1 to 99, with 1 being the lowest level and 99 the highest. Each USER is then given a security level number and is allowed to access only those TASKs which have a security level which is the same or lower.

User based: In this system permissions are defined for individual users. This involves a many-to-many relationship between USERS and TASKS with PERMISSIONS being the link or intersection table.

Group based: In this design the users are split into groups and permissions are assigned to the group, not the individual user.

Responsibility based: In this design it is possible for a user to belong to more than one group at the same time. This involves two many-to-many relationships.

