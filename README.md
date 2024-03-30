# php_5.4-installtion-on-plesk
```
sudo apt-get install software-properties-common
```
```
sudo add-apt-repository -y ppa:ondrej/php
```
```
sudo apt-get update
```
```
sudo apt-get install php5.6
```
```
sudo apt-get install php5.6-gd php5.6-mysql php5.6-dom php5.6-cli php5.6-json php5.6-common php5.6-mbstring php5.6-opcache php5.6-readline php5.6-xsl php5.6-bcmath php5.6-mbstring php5.6-soap php5.6-xml php5.6-zip
```
```
sudo apt-get install php5.6-cgi
```
```
sudo -i
```
```
/usr/local/psa/bin/php_handler --add  -displayname php5.6-os    -path /usr/bin/php-cgi5.6   -phpini /etc/php/5.6/apache2/php.ini     -clipath /usr/bin/php5.6 -type fastcgi     -id php5.6-so
```

# for get php gui 
```
sudo plesk login
```
## paste link on browser

## if you want to change your plesk admin password 
```
plesk bin admin --set-admin-password -passwd "MyPassword"
```
## and if you want to login without password 
```
sudo /usr/local/psa/bin/admin --get-login-link
```
