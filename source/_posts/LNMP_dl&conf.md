---
title:The download and configuration of LNMP
---

## Pre-words
Hey, it's 1:38 A.M. in Nanjing now.
I've just bought a cloud server from tencent and decided to download some softwares and configure them.
Alors, to build my blog website from the server end, i need to download several things:
*Nginx* for communication, *Mysql* for storage, *php* for programming ...

It's very easy to download with the help of **apt**, like: (sudo means superuser do)
```bash
sudo apt-get install nginx -y 
sudo service nginx start
```
```bash
sudo apt-get install mysql-server -y 
mysql -uroot -p
```
```bash
sudo apt-add-repository ppa:ondrej/php 
sudo apt-get install php7.4 php7.4-fpm  
```
(also you can find the latest version by: sudo apt-cache search php)
then deal with the relation between mysql and php using
```bash
sudo apt-get install php7.4-mysql
```



## loading...
Actually I am not familiar with the usage of **ubuntu**, I just played it on virtualBox for a small period of time.
So I have to find some tutorials.

First, I'm able to use **vim**, a good text editor, in Linux.
then I use the command
```bash
sudo vim test.php
```
if you want to write down something then press **I**, use **ESC** to quit to normal mode(read only)
If you want to quit then type **:** avec **q** or **wq** or **q!**(not save) then press **Enter**

then we can better configure our softwares.

## Problems occurred
Unfortunately we tend to run into many bugs. Not to say today.
The first problem is when I try to access the test.php that I've created in /var/www/html
I can only download it's text file rather than view its contents.



# NOT FINISHED, I NEED TO SLEEP. IT'S 2:30 A.M. NOW!!! GOOD NIGHT! WILL BE FINISHED TOMORROW!!



