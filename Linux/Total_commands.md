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
#### 4. CHAPTER 6. GAINING PRIVILEGES
```
# usermod -a -G wheel username
#cat /etc/sudoers
```
#### 5. CHAPTER 9. YUM
```
yum check-update
yum update rpm
yum search vim
```
#### 6. CHAPTER 10. MANAGING SERVICES WITH SYSTEMD
```
service name start
service name stop
service name restart
service name reload
service name status
service --status-all
chkconfig name on
chkconfig --list
systemctl is-active name.service
systemctl is-enabled name.service
```
#### 7. CHAPTER 12. OPENSSH
```
systemctl start sshd.service
cat /etc/ssh/sshd_config
```

#### 8. CHAPTER 23. AUTOMATING SYSTEM TASKS
```
cat /etc/crontab
crontab -l
crontab -e
```
