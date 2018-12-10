# Udacity Linux Project

## Introduction
In this project, I configured a Linux server to host an application written in
a pevious section. I had to configure the server's firewall, configure PSQL, and
Apache 2 to cooperate with Python 3. 

## Web Location
http://54.243.26.55.xip.io/

## Server IP
`54.243.26.55`
#### SSH Port
`2200`

## Software Installed & Changes
* Apache 2
* Python 3
* pip3
* Git
* libapache2-mod-wsgi-py3
* Ports for SSH on 2200
* HTTP on port 80
* root user disabled
* PSQL password set

## Steps Taken

* Followed Udacity prject guidelines to configure server
* Changed SSH port to 2200 instead of 22
* Allowed HTTP on port 80 inbound, and NTP on 123 inbound.
* Created user "grader" and gave it ssh access with a public/private key.
* Installed Configured PSQL
* Installed Apache 2 & WSGI py3
* Installed Git & Cloned Repository
* Refactored Code to work with python 3. Had issues running python 2 with
the WSGI python 2 library.
* Configured Oauth2 Security on Google Dev Console
* Software was ready!
