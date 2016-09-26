# sunderDemo
Assignment 

Step 1 : Designed the cloud infrastructure by following Template_VPC.


Step 2 : Using aws console configured the VPC,Subnet,RouteTable,InternetGateway, SecurityGroups.


Step 3 : Using cloud former tool , I have created the complete template.


step 4 : http://54.224.53.177/mywelcome.php  click the URL to view the sample page. Which is running in my AWS account.


used the following script to install apache , php , git 

#!/bin/bash
yum update -y
yum install httpd24 php56 git -y
service httpd start
chkconfig httpd on
cd /var/www/html


