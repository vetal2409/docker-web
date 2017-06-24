FROM vetal2409/nginx-php:latest

COPY scripts/before/20_test.sh /var/scripts/before/
COPY scripts/after/20_test.sh /var/scripts/after/
RUN echo "* * * * * php -v >> /var/log/cron/default.log 2>&1" >> /etc/cron.d/default
