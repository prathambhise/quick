RED HAT

### Basic commands

`pwd` print working directory
`ls -R` recurssive
`cd`
`mkdir`
`rmdir`
`rm -fR`

### Matching expressions
`ls a*`
`ls *a`
`ls [ac]*`
`ls ???` '.'is counted as charactor
`echo {sunday, monday, tuesday}.log`
`echo file_{1..3}.py`
file_1.py file_2.py file_3.py
`echo file_{a,b}{1..3}.txt`
file_a1.txt file_a2.txt file_a3.txt file_b1.txt file_b2.txt file_b3.txt
`echo file{a{1,2}b,c}`
filea1, filea2, fileb, filec

### directory
`/etc/passwd`
`/etc/group`
`/ect/shadow`

### help
`man ls`
`man 3 ls` help in 3rd section

### user, groups

`uid`
`gid`

`useradd ram`
`passwd ram`
`userdel -rf ram`
`groupadd network`
`groupdel network`
`gpasswd network`

`usermod -u 2001 ram` = change user id
`groupmod -g 5001 network` =change group id
`usermod -g network ram` change peimary group
`usermod -G network ram` change secondary group
`usermod -G sham ram` override secondary group
`usermod -aG network ram` append secondary group
`gpasswd -d ram network` remove user from group
`usermod -s /usr/sbin/nologin ram` restrict usr login
`usermod -s /usr/bin/bash ram`
`usermod -aG wheel ram` add usr to root privilage

### access
r w x all

4 2 1 7

`chmod 264 file`
`chown alice file`
`chown :network file`
`chown alice:network file`
`umask 007` remove all permission of others
`umask 027` remove 2, 7 permission


### process
`ps aux`
`ping 8.8.8.8`
`jobs`
`fg %1 %id`
`kill -l`







