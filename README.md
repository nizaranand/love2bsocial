love2bsocial
============

Love2bSocial Social Network Platform
Developed using xampp 1.8.1, Yii 1.1.13 PHP framework, and Aptana Studio 3.3.1 on Windows XP

My directory structure is as follows:

C:\xampp (xampp installation folder)
C:\xampp\htdocs\love2bsocial (webroot)
C:\xampp\love2bsocial\protected (application folder)
C:\xampp\love2bsocial\framework (yii framework folder)

Please Note: make sure you edit C:\xampp\love2bsocial\protected\config\main.php
			 and edit the database connection info with your MySQL database
			 connection info. Also if using a different directory structure then
			 above make sure you edit the main entry script index.php in your
			 webroot folder.

I assume you know how to setup xampp and configure it properly, setup a MySQL
database, and have some experience using the Yii framework.

The easiest way to get this project up and running would be to create a new
skeleton project using the yiic command line tool.
for example assuming we use the exact same directory structure as above.
Open a command prompt and cd C:\xampp\htdocs\
and then issue the following command:
yiic webapp love2bsocial
This should create a new skeleton project in C:\xampp\htdocs\love2bsocial
Then create the following folder to hold the application files and the yii
framework files
C:\xampp\htdocs\love2bsocial
and copy the protected folder from C:\xampp\htdocs\love2bsocial to
C:\xampp\love2bsocial
This way our application files are not accessible from the web because they are
outside the webroot folder.
Following these instructions and keeping this directory structure you should not
have to change any of the configuration other then the database.

Then using Git you can do a pull using the following:
Using http: https://github.com/rodwebdesign/love2bsocial.git
Using SSH: git@github.com:rodwebdesign/love2bsocial.git