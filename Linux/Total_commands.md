## Execute following commands and write observations in a notebook.

#### 1.Chapter - 3 Time & Date
```
timedatectl
timedatectl set-time HH:MM:SS
timedatectl set-time YYYY-MM-DD
date
date +"format"
date +"%Y-%m-%d %H:%M"
```
#### 2. Chapter - 4 Managing user groups
```
cat /etc/group
cat /etc/passwd  
cat /etc/shadow
useradd
usermod
userdel
umask
```
#### 3. Chapter 5 - ACL
```
getfacl /var/log/messages
setfacl -m rules files
```
### CHAPTER 6. GAINING PRIVILEGES
```
# usermod -a -G wheel username
#cat /etc/sudoers
```
