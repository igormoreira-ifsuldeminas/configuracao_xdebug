nano /etc/php/5.6/apache2/conf.d/20-xdebug.ini 

service apache2 restart

php --info | grep xdebug

