1. open xampp start apache and mysql servers
2.before that place this folder in htdocs folder

C:\xampp\htdocs\

3.open your favourite  browser and copy the below link and press enter

https://localhost/phpmyadmin

4.create the database with the exact name loginsystem
5.select loginsystem database then select the SQL tab and copy and paste the below query

CREATE TABLE users (
idUsers int(11) AUTO_INCREMENT PRIMARY KEY NOT NULL,
uidUsers TINYTEXT NOT NULL,
emailUsers TINYTEXT NOT NULL,
pwdUsers LONGTEXT NOT NULL
);

6.this will create the users table with the some attributes 
7.thats it now run your project
8.i hope you guys know how to run projects using this xampp apache server

https://localhost

Thank you...!