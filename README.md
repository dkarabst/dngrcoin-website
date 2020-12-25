# dngrcoin-website
simple website http://3.128.107.229

Easy installation on VPS:

sudo apt-get install apache2

copy dngrcoin.cf.conf to /etc/apache2/conf-available

copy dngrcoin.cf to /var/www/

sudo chmod -R 755 /var/www/dngrcoin.cf

sudo systemctl enable apache2

sudo a2enconf dngrcoin.cf.conf

service apache2 reload

sudo ufw allow 80

