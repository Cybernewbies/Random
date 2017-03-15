## File Systems
### /
* Root, disk based
* /etc
* /root
* /media
* /mnt
### /boot
### /usr
### /opt
### /home
### /dev
### /proc
### /sys
### /tmp

## Absolute & Relative Paths

## File Types
file
file .bash_profile
file /root

## File and Directory Operations

## File and Directory Control Attributes

## Finding FIles

## Linking Files and Directories

## File and Directory Permissions

### Exercise 3-1
### Exercise 3-2

## File Ownership and Group Membership

### Exercise 3-3
useradd user100
useradd user200

cd /home/user1
chown user100 file10
ll file10

chgrp user100 file10 -v
ll file10

chown user200:user:200 file10 -v
ll file10

chown -R user200:user200 dir10
ll -d dir10

## Special Permissions
* 3 Types of permissions:

  1.) setuid

  2.) setgid

  3.) sticky

### Exercise 3-4
