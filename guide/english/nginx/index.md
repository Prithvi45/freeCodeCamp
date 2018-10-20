---
title: Installation of Nginx in Ubuntu and RHEL
---

## 1. Installation of Nginx in Ubuntu

Step 1: Update Apt-Get

As always, we update and upgrade our package manager.

`apt-get update && apt-get upgrade`

Step 2: Install Nginx

One simple command to install Nginx is all that is needed:

`apt-get -y install nginx`


## 2. Installation of Nginx in RHEL

Step 1: Install the EPEL repository

`sudo yum install epel-release`

Step 2: Update the repository
`sudo yum update`

Step 3: Install NGINX Open Source
`sudo yum install nginx`

Step 4: Verify the installation
`sudo nginx -v`
