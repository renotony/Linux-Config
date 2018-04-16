# Linux-Config

## The IP address for my server is 54.218.217.254

## The SSH port is 2200

## The URL for my server is http://ec2-54-218-217-254.us-west-2.compute.amazonaws.com/

## The configuration changes I made to the server were:
- update and upgrade all software
- create the grader user id
- enable sudo access for grader
- add my server's IP addresses to /etc/hosts
- add port 2200 to /etc/ssh/sshd_config
- remove password access from /etc/ssh/sshd_config
- set PermitRootLogin to no in /etc/ssh/sshd_config
- configure firewall to disable all incoming and allow all outgoing
  - and enable ports 2200, 80, and 123
- create .ssh folder for grader and apply proper permissions
- create ssh key pair for grader using key-gen
- set timezone to UTC
- configure Postgresql and install my database and load my data
- create and enable plays.conf file for apache
- create virtual environment and install below listed software



## The software I installed on this server was:
- Apache2
- Postgresql
- Postgresql-contrib
- Git
- Python-psycopg2
- Python-Flask
- Python-PIP
- Python-dev
- sqlalchemy
- Flask-SQLAlchemy
- oauth2client
- requests
- httplib2
- flask-seasurf
- render_template
- virtualenv
- finger
- ntp
- libapache2-mod-wsgi

## These were installed in the virtual env:
- Flask
- httplib2
- requests
- oauth2client
- sqlalchemy
- Flask-SQLAlchemy
- python-psycopg2

## I made use of MANY FSND Forum posts and some google searches.
Primarily focused on https://github.com/petergns/linux_server_catalog/blob/master/README.md#login-authorization-configuration 
as my primary source and googled anything I didn't understand or that didn't work (I didn't keep a list of those).
