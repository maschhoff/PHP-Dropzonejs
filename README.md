# PHP-Dropzonejs
a simple dropzonejs implementation - Create your own dropbox site

Installation

1. Put all files into a folder
2. create a folder inside this folder called uploads (files will go there)
3. Make shure you got permissions to write into this folder
4. Have a look at you php.ini set upload_max_filesize, post_max_size and memory_limit as you prefer
5. Create a .htaccess file into the uploads folder containing: (this will disable php inside this folder - important for security)

'''
RemoveHandler .php .phtml .php3
RemoveType .php .phtml .php3
php_flag engine off
'''

Credits to http://www.dropzonejs.com/

I´ve installed it on my homeserver in case someone want to send me bigger files
