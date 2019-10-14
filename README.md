# AWS-EC2-static-website

EC2 is a self-managed service in AWS.

We can easily createa static website using EC2 acting as a webserver, with installed Apache.In this lab, you will 

•Use EC2 to create the same website for Lab 1.1.

Steps:1.Follow the bootstrap.txt to install required package

             2.Make sure your security group allow HTTP(port 80)requests.
             
             3.Scp the three files to your /var/www/html. scp -i "lab1_demo.pem" style.css ec2-user@ec2-13-114-210-254.ap-northeast-1.compute.amazonaws.com:/var/www/html
