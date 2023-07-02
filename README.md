# AWS-Lift-and-Shift-Workload
This is a project for production-based deployment. As a result, we are deploying the Vprofile project on a live server utilising the Amazon services EC2, ELB, Cloudwatch, Autoscaling, and S3 bucket. In addition, various Bash scripts are utilised to provision the virtual machines.

# Prerequisites
#
- JDK 1.8 or later
- Maven 3 or later
- MySQL 5.6 or later

# Technologies 
- Spring MVC
- Spring Security
- Spring Data JPA
- Maven
- JSP
- MySQL
# Database
Here,we used Mysql DB 
MSQL DB Installation Steps for Linux ubuntu 14.04:
- $ sudo apt-get update
- $ sudo apt-get install mysql-server

Then look for the file :
- /src/main/resources/accountsdb
- accountsdb.sql file is a mysql dump file.we have to import this dump to mysql db server
- > mysql -u <user_name> -p accounts < accountsdb.sql

