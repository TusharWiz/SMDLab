FROM ubuntu/apache2
WROKDIR /var/www/html
RUN rm index.html
RUN touch index.html
RUN echo "Yogesh Pawar">index.html
EXPOSE 80
CMD ["apache2ctl","-D","FOREGROUND"]