# XSS-Vulnerable-Code
XSS Vulnerable code examples for you to practice locally. 

### Introduction
Welcome to my XSS vulnerable code sample bank, I created these challenges and advise you to run these locally to practice exploiting XSS vulnerablities. Hopefully this repo provides a range of challenges to help you understand why the code is vulnerable and how to avoid making the same mistakes. 

##*Feeling Lost?*
Use my suggestions below to get your battlestation up and running, you'll be exploiting in no time! 
#####Prerequisites
This tutorial uses Linux, it's just easier and things *work*. If you aren't already using Linux, go and install it.

### Install XAMPP
Go and download [XAMPP for Linux](https://www.apachefriends.org/download.html).
Change the Permissions to an executable. 

chmod 755 xampp-linux-*-installer.run

Run the installer

sudo ./xampp-linux-*-installer.run

XAMPP is now installed and is located in the /opt/lampp directory.

### Battlestation Setup
Change directory

cd /opt/lampp/htdocs

Make a new directory for your battlestation

mkdir battlestation

Clone this git repo to the directory or move the files in the directory depending on which you would like to try, they will all be located at localhost/battlestation/

### Start XAMPP
When you load up your browser and navigate to localhost/battlestation it won't work unless you start XAMPP, so start it!

sudo /opt/lampp/lampp start

### Fin
You should be good to go now, go to your browser and check out the challenges. 
