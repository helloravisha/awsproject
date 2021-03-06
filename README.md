EzTouchMenu App

The repository contains the code for EzTouchMenu application, written leveraging Spring Boot and deployed in AWS.
It is a custom application built to present a digital menu.


Idea

The   project   idea   is   about   digital   menu   over   a   mobile/Tab      application,   
The   current   scope   of   this   project-1   is   to   just   cover   the   web   part   of   it where   the   administrator   of   the         application   will   try   to   add   the   menu   into   the   system.  
The   same   menu   will be   later   be   consumed   by   mobile   and   tab   devices.
Solution



Features
•   Login:<br>
        User   can   login   with   two   predefined   credentials.<br>
•   Upload:<br>
        User   can   upload   images   of   his   choice.<br>
•   Download:<br>
        User   can   download   the   image   of   his   choice.<br>
•   Delete:<br>
        User   can   delete   the   image   of   his   choice.<br>
•   Modify:<br>
      User   can   upload   images   of   his   choice   where   he   can   modify   the   description   and   image.<br> •   Logout:<br>
      User   can   logout<br>



Prerequisites

AWSComponents

EC2<br>
ELB<br>
Lambda<br>
AutoScaling Group<br>
Single AZ RDS<br>
CloudFront<br>
S3<br>
S3 Transfer Acceleration<br>
R53<br>
CloudWatch<br>
SNS<br>
AWS SDK<br>

LocalSetup

Tools that need to be installed in local environment

Maven
MySQL 
JDK
IDE (Eclipse/IntelliJ IDEA)
Tomcat

Frameworks

Spring Boot
Spring MVC
Spring JPA
Bootstrap
jquery
Runconfig

We need to checkout the repository code and add the required credentials in DB.


Run the following in the project root folder, to deploy to maven repository

    $ mvn clean install
You can import the project as a maven in Eclipse or IntelliJ IDEA and run the application as SpringBoot App

You can run the application using the following maven command

    $ mvn spring-boot:run
    
Profile
LinkedIn: www.linkedin.com/in/ravi-shanker-katta
