FROM nginx:alpine
RUN mkdir /root/ca
ADD conf.d /etc/nginx/conf.d
ADD ca /root/ca
ADD nginx.conf /etc/nginx/
RUN ln -sf /dev/null /var/log/nginx/access.log 
RUN ln -sf /dev/null /var/log/nginx/error.log
