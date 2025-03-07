# wordpress
Wordpress + Nginx on docker compose

In docker-compose.yml and nginx.conf raplace MY_DOMAIN with domain name example.com and MY_EMAIL with email address

In .env replace HASLO with password and UZYTKOWNIK with username

crontab for ssl_renew.sh:

0 12 * * * /home/sammy/wordpress/ssl_renew.sh >> /var/log/cron.log 2>&1
