FROM nginx

COPY code /usr/share/nginx/html
#RUN rm -rf /usr/share/nginx/nginx.conf
RUN rm -rf /etc/nginx/conf.d/default.conf
#COPY nginx.conf /etc/nginx/nginx.conf
COPY default.conf /etc/nginx/conf.d/default.conf

CMD ["nginx", "-g", "daemon off;"]
