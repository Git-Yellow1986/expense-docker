FROM nginx
RUN rm -rf /usr/share/nginx/html/*
COPY code /usr/share/nginx/html
EXPOSE 80
COPY expense.conf /etc/nginx/conf.d/default.conf
RUN  restart nginx
CMD ["nginx", "-g", "daemon off;"]
