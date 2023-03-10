In this project you will be tasked to prepare storage infrastructure on two Linux servers and implement a basic web solution using WordPress.
WordPress is a free and open-source content management system written in PHP and paired with MySQL or MariaDB as its backend Relational Database Management
System (RDBMS).

### This project consist of two parts

1. Configure storage subsystem for Web and Database servers based on Linux OS. The focus of this part is to give you practical 
experience of working with disks, partitions and volumes in Linux.

2. Install WordPress and connect it to a remote MySQL database server. This part of the project will solidify your skills of deploying
 Web and DB tiers of Web solution.

As a DevOps engineer, your deep understanding of core components of web solutions and ability to troubleshoot them will play 
essential role in your further progress and development.

### Three-tier Architecture

Generally, web, or mobile solutions are implemented based on what is called the Three-tier Architecture.

Three-tier Architecture is a client-server software architecture pattern that comprise 3 separate layers.

![image](https://user-images.githubusercontent.com/38444929/221984063-f2b56a20-f1f2-476a-b0b6-9dad47ce4d84.png)

1. Presentation Layer (PL): This is the user interface such as the client server or browser on your laptop.
2. Business Layer (BL): This is the backend program that implements business logic. Application or Webserver
3. Data Access or Management Layer (DAL): This is the layer for computer data storage and data access. Database Server or File System Server such as FTP server, or NFS Server

In this project, you will have the hands-on experience that showcases Three-tier Architecture while also ensuring that the disks used to store files on the Linux servers are adequately partitioned and managed through programs such as gdisk and LVM respectively.



### Your 3-Tier Setup

1. A Laptop or PC to serve as a client
2. An EC2 Linux Server as a web server (This is where you will install WordPress)
3. An EC2 Linux server as a database (DB) server

Use RedHat OS for this project

By now you should know how to spin up an EC2 instanse on AWS, but if you forgot ??? refer to Project1 Step 0. In previous projects we used ???Ubuntu???, but it is better to be well-versed with various Linux distributions, thus, for this projects we will use very popular distribution called ???RedHat??? (it also has a fully compatible derivative ??? CentOS)

Note: for Ubuntu server, when connecting to it via SSH/Putty or any other tool, we used ubuntu user, but for RedHat you will need to use ec2-user user. Connection string will look like ec2-user@

Let us get started!

