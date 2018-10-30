## Please take the following into account
IP:
54.186.190.133
URL
http://ec2-54-186-190-133.us-west-2.compute.amazonaws.com/

Only allowed connections are:
ssh (port 2200), 
HTTP (port 80), 
and NTP (port 123)

## config changes:
Updated all currently installed packages.
Changed the SSH port from 22 to 2200. 
added ufw rules to allow it
updated time to UTC
configured libapache2-mod-wsgi-py3

## Users:
  grader
  ubuntu
  student

## installed software:
  git
  sqlalchemy
  python3
  apache2
  postgre
  sqlite

## 3rd part resources used
libapache2-mod-wsgi-py3
ssh-keygen
project catalog was cloned
