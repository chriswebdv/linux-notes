# linux-notes

### [[sudo]]
- sensitive file is the etc/shadow file
	- sudo etc/shadow
		- related to the etc/passwd file
- use sudo if necessary only
- permission are granted because user is part of a sudoers file
- How to switch to root?
	- command sudo su -

###  [[linux file system]]
- files are case sensitive
- kali@kali
	- first part: user
	- second part: host name (workstation)
- pwd = command tells your where you are in the file system

### cd = change directory
	- cd .. = go backwards all the way to root
	- How to get to another folder not in your directory?
		- Example: cd /etc 
		- Example: ls /etc
- ctrl - l = clear screen or command clear

### ls = list files
	- command ls  -la = long all
		- hidden files start with a dot .
		- website: exaplainshell.com
		- or you can use man pages
			- example: command man ls (good for no internet access)
		- or use command ls  --help (not all the details)

  
