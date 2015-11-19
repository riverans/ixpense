Regular Expense Management System in php

# Introduction #

iXpense is built on the idea that expense management can be more intuitive, efficient, easy and useful. And anybody can use it. Because iXpense is:

1. Free and open source

2. Access from anywhere and anytime

3. Easy to handle and feature rich

4. No need to learn accounting softwares for managing your regular expenses

5. Keeps track of your income and expenses

6. One click summary with graphs, charts and more......



# Details #

Installation Requirements:
iXpense is purely written in Yii PHP framework ver 1.1.8. So it can run on any apache/php/mysql server, which fulfills the below version requirements. But I prefer to use XAMPP server 1.1.7 which contains


> Apache 2.2.21

> MySQL 5.5.16

> PHP 5.3.8

> phpMyAdmin 3.4.5

> FileZilla  FTP Server 0.9.39

> Tomcat 7.0.21 (with mod\_proxy\_ajp as connector)



Instruction for Installation:

1.  Extract the zip file into your webroot directory. If you are using XAMPP(windows) with default installation then your webroot directory might be C:\xampp\htdocs\

2.  Make sure that you have both the folder a) ixpense & b) yii in your web root directory

3.  Import the database schema file SQL Schema.txt, present in the same folder, using phpMyAdmin http://localhost/phpmyadmin

4.  Create a database user in your mysql database and change the database configuration settings in C:\xampp\htdocs\ixpense\protected\config\main.php

> 'db'=>array(

> 'connectionString' => 'mysql:host=localhost;dbname=ixpense',  // your host name & database name

> 'emulatePrepare' => true,

> 'username' => 'username',        //your database username

> 'password' => 'password',        //your database password

> 'charset' => 'utf8',

> ),
5.  Open the web browser and type the relevant URL e.g. http://localhost/ixpense

Working Demo: http://www.ixpense.net