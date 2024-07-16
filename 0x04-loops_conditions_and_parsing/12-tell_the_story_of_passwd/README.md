Read:
-	[IFS(internal field separator)](https://tldp.org/LDP/abs/html/internalvariables.html)
-	[Understanding /etc/passwd](https://www.cyberciti.biz/faq/understanding-etcpasswd-file-format/)

The file ```/etc/passwd``` has already been covered in a previous project and you should be familiar with it. Today we will make up a story based on it.

Write a Bash script that displays the content of the file ```/etc/passwd```, using the ```while``` loop + IFS.

Format: ```The user USERNAME is part of the GROUP_ID gang, lives in HOME_DIRECTORY and rides COMMAND/SHELL. USER ID's place is protected by the passcode PASSWORD, more info about the user here: USER ID INFO```

Requirements:

- You must use the ```while``` loop (```for``` and ```until``` are forbidden)
```
sylvain@ubuntu$ ./101-tell_the_story_of_passwd
The user root is part of the 0 gang, lives in /root and rides /bin/bash. 0's place is protected by the passcode x, more info about the user here: root
The user daemon is part of the 1 gang, lives in /usr/sbin and rides /usr/sbin/nologin. 1's place is protected by the passcode x, more info about the user here: daemon
The user bin is part of the 2 gang, lives in /bin and rides /usr/sbin/nologin. 2's place is protected by the passcode x, more info about the user here: bin
The user sys is part of the 3 gang, lives in /dev and rides /usr/sbin/nologin. 3's place is protected by the passcode x, more info about the user here: sys
The user sync is part of the 65534 gang, lives in /bin and rides /bin/sync. 4's place is protected by the passcode x, more info about the user here: sync
The user games is part of the 60 gang, lives in /usr/games and rides /usr/sbin/nologin. 5's place is protected by the passcode x, more info about the user here: games
The user man is part of the 12 gang, lives in /var/cache/man and rides /usr/sbin/nologin. 6's place is protected by the passcode x, more info about the user here: man
The user lp is part of the 7 gang, lives in /var/spool/lpd and rides /usr/sbin/nologin. 7's place is protected by the passcode x, more info about the user here: lp
The user mail is part of the 8 gang, lives in /var/mail and rides /usr/sbin/nologin. 8's place is protected by the passcode x, more info about the user here: mail
The user news is part of the 9 gang, lives in /var/spool/news and rides /usr/sbin/nologin. 9's place is protected by the passcode x, more info about the user here: news
The user uucp is part of the 10 gang, lives in /var/spool/uucp and rides /usr/sbin/nologin. 10's place is protected by the passcode x, more info about the user here: uucp
The user proxy is part of the 13 gang, lives in /bin and rides /usr/sbin/nologin. 13's place is protected by the passcode x, more info about the user here: proxy
The user www-data is part of the 33 gang, lives in /var/www and rides /usr/sbin/nologin. 33's place is protected by the passcode x, more info about the user here: www-data
The user backup is part of the 34 gang, lives in /var/backups and rides /usr/sbin/nologin. 34's place is protected by the passcode x, more info about the user here: backup
The user list is part of the 38 gang, lives in /var/list and rides /usr/sbin/nologin. 38's place is protected by the passcode x, more info about the user here: Mailing List Manager
The user irc is part of the 39 gang, lives in /var/run/ircd and rides /usr/sbin/nologin. 39's place is protected by the passcode x, more info about the user here: ircd
The user gnats is part of the 41 gang, lives in /var/lib/gnats and rides /usr/sbin/nologin. 41's place is protected by the passcode x, more info about the user here: Gnats Bug-Reporting System (admin)
The user nobody is part of the 65534 gang, lives in /nonexistent and rides /usr/sbin/nologin. 65534's place is protected by the passcode x, more info about the user here: nobody
The user libuuid is part of the 101 gang, lives in /var/lib/libuuid and rides . 100's place is protected by the passcode x, more info about the user here: 
The user syslog is part of the 104 gang, lives in /home/syslog and rides /bin/false. 101's place is protected by the passcode x, more info about the user here: 
The user messagebus is part of the 106 gang, lives in /var/run/dbus and rides /bin/false. 102's place is protected by the passcode x, more info about the user here: 
The user landscape is part of the 109 gang, lives in /var/lib/landscape and rides /bin/false. 103's place is protected by the passcode x, more info about the user here: 
The user sshd is part of the 65534 gang, lives in /var/run/sshd and rides /usr/sbin/nologin. 104's place is protected by the passcode x, more info about the user here: 
The user pollinate is part of the 1 gang, lives in /var/cache/pollinate and rides /bin/false. 105's place is protected by the passcode x, more info about the user here: 
The user vagrant is part of the 1000 gang, lives in /home/vagrant and rides /bin/bash. 1000's place is protected by the passcode x, more info about the user here: 
The user colord is part of the 112 gang, lives in /var/lib/colord and rides /bin/false. 106's place is protected by the passcode x, more info about the user here: colord colour management daemon,,,
The user statd is part of the 65534 gang, lives in /var/lib/nfs and rides /bin/false. 107's place is protected by the passcode x, more info about the user here: 
The user puppet is part of the 114 gang, lives in /var/lib/puppet and rides /bin/false. 108's place is protected by the passcode x, more info about the user here: Puppet configuration management daemon,,,
The user ubuntu is part of the 1001 gang, lives in /home/ubuntu and rides /bin/bash. 1001's place is protected by the passcode x, more info about the user here: Ubuntu
sylvain@ubuntu$
```
