here is the code what you have to paste in your .htaccess file and then refresh your wordpress dashboard.
99% times it will work,but sometime in live server it may not work then you have to install plugin to resolve this issue.

code is here:

php_value upload_max_filesize 512M
php_value post_max_size 512M
php_value memory_limit 300M
php_value max_execution_time 180
php_value max_input_time 180
