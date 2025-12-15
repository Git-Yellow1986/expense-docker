FROM nginx
RUN rm -rf /usr/share/nginx/html/*
COPY code /usr/share/nginx/html
EXPOSE 80
COPY expense.conf /etc/nginx/conf.d/expense.conf
RUN start nginx
CMD ["nginx", "-g", "daemon off;"]
