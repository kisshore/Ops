
# Soma
## Rajahmundry
- abc
- edf
1.Chapter - 3 Time & Date

timedatectl			displaying current and global time zone with NTP configuration status.
timedatectl set-time HH:MM:SS	command updates the system time.
timedatectl set-time YYYY-MM-DD	changing the date without specifying the current time results in setting the time to 00:00:00
date				current date and time
date +"format"			displayed word format
date +"%Y-%m-%d %H:%M"		displaying year-month-date hours:minutes(2018-07-16 10:34)

2. Chapter - 4 Managing user groups

cat /etc/group		list of groups stored.
cat /etc/passwd		passwords saved in encrypted format
cat /etc/shadow		password aging information stored in it.
useradd			To add new user
usermod			to add an already existing user to an already existing group
userdel			To delete the existing user
umask			displaying the current umask

3. Chapter 5 - ACL

getfacl /var/log/messages	//To determine the existing ACLs for a file or directory
setfacl -m rules files		//The setfacl utility sets ACLs for files and directories. Use the -m option to add or modify the ACL of a file or directory


4. CHAPTER 6. GAINING PRIVILEGES

# usermod -a -G wheel username	//adding username to the special administrative group called wheel.
#cat /etc/sudoers		//users listed in the /etc/sudoers configuration file are allowed to use the sudo command


5. CHAPTER 9. YUM

yum check-update	//it looks for the available updates for the packages
yum update rpm		//to update a single package, multiple packages, or all packages at once
yum search vim		//it is useful for searching for packages, list all packages that match “vim”


6. CHAPTER 10. MANAGING SERVICES WITH SYSTEMD

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

7. CHAPTER 12. OPENSSH

systemctl start sshd.service
cat /etc/ssh/sshd_config

8. CHAPTER 23. AUTOMATING SYSTEM TASKS

cat /etc/crontab
crontab -l
crontab -e
