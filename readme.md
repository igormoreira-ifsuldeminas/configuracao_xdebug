 apt install -y php5.6-xdebug

nano /etc/php/5.6/apache2/conf.d/20-xdebug.ini 

service apache2 restart

php --info | grep xdebug

```php
if (!function_exists('xdebug_break')) {
  function xdebug_break() {}
}
        
xdebug_break(); 
```
