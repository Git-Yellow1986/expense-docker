FROM nginx
RUN rm -rf /usr/share/nginx/html/*
COPY code /usr/share/nginx/html
COPY expense.conf /etc/nginx/default.d/expense.conf
# EXPOSE 80
# CMD ["nginx", "-g", "daemon off;"]


