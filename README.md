# Catalog project hosted on LightSail

### IP Address
+ **34.199.47.66**

### IP Address
+ **http://ec2-34-199-47-66.compute-1.amazonaws.com**

### Summary of software installed
+ Apache2
+ mod_wsgi
+ virtualenv
+ oauth2client
+ httplib2
+ libpq-dev
+ git
+ pip
+ python requests
+ PostgreSQL
+ psycopg2
+ SQLAlchemy
+ Flask

### Summary of configurations made
+ Create Amazon LightSail instance
+ Setup **ssh** key pair and connect to the instance from local machine
+ Upgrade software packages of linux server
+ Configure server firewall using **ufw**
    + Disallow all incoimg and allow all outgoing
    + allow http and ntp
    + allow ssh on port 2200 and deny on port 22
+ Create user **grader**
    + setup up ssh key pair for **grader**
    + configure to allow **grader** to execute commands as **sudo**
+  Install **mod_wsgi**
+ Verify **Python** is installed
+ Install **PostgreSQL**
    + create **PostgreSQL** user **catalog**
    + create database **catalog**
+ Install **git**
+ Download Google Auth credentials json file
* Clone **catalog** project
    + update **client_secrets.json** file
    + update **login.html**
    + use **PostgreSQL** in **create_engine**
+  Setup up virtual environment
    + install software listed above
    + update virtual env configuration file
    + populate database with seed data
+ Setup **wsgi**
+ Restart **apache2** server
