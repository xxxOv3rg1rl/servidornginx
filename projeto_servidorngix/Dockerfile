
FROM nginx:latest

COPY ./nginx/nginx.conf /etc/nginx/nginx.conf

COPY ./site /usr/share/nginx/html

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]
