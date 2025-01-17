# drupal-webapp-rds

YouTube Video URL:

This project demonstrates how to connect a drupal-php-apache based web application to an AWS RDS Instance (mysql engine).
Also, we visualize the data in a database in real with mysql client application.

Application Architecture:

![image](https://github.com/user-attachments/assets/7c134135-63e4-4872-95d5-13e0d40ca58f)

Important Points: 

1. In this video, I have deployed both EC2 instance and the RDS instance in a public subnet but in an enterprise (real world scenario), please remember that RDS DB Instances are provisioned in a private subnet.
2. Even though the RDS instance was deployed in a public subnet, the Public Access feature was set to No. This means that the RDS instance still did not have any public IP assigned to it.
