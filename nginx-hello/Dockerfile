FROM akkerman/rpi-nginx
RUN rm /etc/nginx/conf.d/* & true
ADD hello.conf /etc/nginx/sites-enabled/default
ADD hello.conf /etc/nginx/sites-available/default
ADD index.html /usr/share/nginx/html/
