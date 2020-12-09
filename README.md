# Install Wp cli

* #### Install cli phar file. (The phar extension provides a way to put entire PHP applications into a single file called a "phar" )<br>
```
curl -O https://raw.githubusercontent.com/wp-cli/builds/gh-pages/phar/wp-cli.phar
```
* ####  Next, check the Phar file to verify that it’s working.
```
php wp-cli.phar --info
```
* #### To use WP-CLI from the command line by typing wp, make the file executable and move it to somewhere in your PATH. For example:<br>
```
chmod +x wp-cli.phar
sudo mv wp-cli.phar /usr/local/bin/wp
```
* #### If WP-CLI was installed successfully, you should see something like this when you run wp --info:<br>
```
OS:	Darwin 16.7.0 Darwin Kernel Version 16.7.0: Thu Jan 11 22:59:40 PST 2018; root:xnu-3789.73.8~1/RELEASE_X86_64 x86_64
Shell:	/bin/zsh
PHP binary:    /usr/local/bin/php
PHP version:    7.0.22
php.ini used:   /etc/local/etc/php/7.0/php.ini
WP-CLI root dir:        /home/wp-cli/.wp-cli/vendor/wp-cli/wp-cli
WP-CLI vendor dir:	    /home/wp-cli/.wp-cli/vendor
WP-CLI packages dir:    /home/wp-cli/.wp-cli/packages/
WP-CLI global config:   /home/wp-cli/.wp-cli/config.yml
WP-CLI project config:
WP-CLI version: 2.4.0
```
* #### Next Update your cli<br>
```
wp cli update
```

* #### Next locate your server directory by terminal and create new directory:<br>
```
mkdir wordpress
```
* #### Next enter the directory and use wp core download:<br>
```
wp core download
```
* #### Next Create your wp-config file:<br>
```
wp config create --dbname=dbname --dbuser=username --dbpass=password

```
* #### Next Create your database:<br>
```
wp db create

```
 
># Thank you :smile:

  

   




