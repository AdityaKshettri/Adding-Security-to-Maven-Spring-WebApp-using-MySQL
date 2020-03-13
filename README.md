# Adding-Security-to-Maven-Spring-WebApp-using-MySQL
In this project, I have worked on Maven Spring Web Application where I have provided Authentication and Authorization security to the web app using MySQL 8.0 in Netbeans 11.3

# How to run this?

1- Download the entire project in your local workspace and open the folder as a Maven Project in Netbeans 11.3

2- Then goto MYSQL Workbench and create 'root' user with password '1234' and open the sql-scripts and open the 'plaintext password' for creating users with plaintext password or 'bcrypt password' for creating users with encrypted password. Run the sql-script. The database and its respective tables will be created.

3- If you want to make any desired changes in the database, do make the changes in properties file in src/resources too.

4- Go to 'Services' in Netbeans and connect your jdbc server to your MYSQL database.

4- Now run the whole maven app. The dependencies will download one by one and then after giving the apache tomcat 9 username and password, your browser will open the login page.

5- Enter the correct username and password as saved in the database and you will be authenticated.
