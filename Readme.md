# UNIX/Linux operating systems (Basic)

Linux system installation and updates. Administration basics.

## Part 1. Installation of the OS

##### Install Ubuntu 20.04 Server LTS

cat /etc/issue

![cat_etc_issue](img/cat_etc_issue.jpg)

## Part 2. Creating a user

##### Create a user other than the one created during installation. The user must be added to adm group.

Creating a new user

![creating_a_user](img/sudo_useradd_usermod.JPG)

cat /etc/passwd

![cat_etc_passwd](/img/cat_etc_passwd.JPG)

## Part 3. Setting up OS network

##### Set the machine name as user-1

![set-hostname](/img/set-hostname.jpg)

##### Set the time zone corresponding to your current location.

![timedatectl](/img/timedatectl.JPG)

##### Output the names of the network interfaces using a console command.

![ip-a](img/ip-a.JPG)

Interface lo can be used by network client software to communicate with a server application located on the same computer. That is, if you specify the URL http://127.0.0.1/ or http://localhost/ in the web browser on the computer where the web server is running, it takes you to that computer's web site. This mechanism works without any active connection, so it is useful for testing services without compromising their security as with remote network access.

##### Use the console command to get the ip address of the device you are working on from the DHCP server.

![wget](img/wget.JPG)
