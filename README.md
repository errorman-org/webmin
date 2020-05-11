# webmin

#Installing on Debian

$ sudo su

$ wget http://prdownloads.sourceforge.net/webadmin/webmin_1.941_all.deb

$ dpkg --install webmin_1.941_all.deb

$ apt install perl libnet-ssleay-perl openssl libauthen-pam-perl libpam-runtime libio-pty-perl apt-show-versions python

$ nano /etc/apt/sources  
     , paste deb https://download.webmin.com/download/repository sarge contrib 

$ cd /root

$ wget https://download.webmin.com/jcameron-key.asc

$ apt-key add jcameron-key.asc
     
$ apt install apt-transport-https

$ apt update

$ apt install webmin 

open https://localhost:10000 user=root password=? yours root password
