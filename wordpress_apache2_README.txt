To start the test site with wordpress 4.5 you have to change the 
"000-default.conf" in "etc/apache2/sites-available".
The File has following content:

ServerAdmin webmaster@localhost
DocumentRoot /var/www/html
#DocumentRoot /var/www/html/wordpress

Just remove the hashtag in front of the 3rd line and put it infront of the second line to change
commentet text to one line above