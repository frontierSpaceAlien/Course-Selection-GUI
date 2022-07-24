>Code is hidden for academic purposes

# Course Selection System
Developed in Java.
Based on pdc_pc_project1 topic with added GUI and JDBC implementation.

# Login Screen

The software already has sample user data preloaded into the Apache Derby database.

![image](https://user-images.githubusercontent.com/104743984/180635367-8caece1c-fc4e-4546-9161-1bb17e63d239.png)

The software checks for the existing user based on the given login information.

# Validation Check

If the user enters invalid login information, then the software gives an appropriate response.

![image](https://user-images.githubusercontent.com/104743984/180635434-0ff45397-7d0e-4c01-b855-7bbac0462040.png)

# Course Selection Menu 

The course selection menu contains user information and chosen course information.

![image](https://user-images.githubusercontent.com/104743984/180635540-7058bbca-82f6-4d67-ab1e-ddf845c7786b.png)

When the user hits save below the table, then the software saves the selected course information into the Apache Derby database. The tables created in the database have pre-defined relationships between them. (Although there are some errors with the relationships)

This allows for the program to easily find which selected courses are assigned to each user.
