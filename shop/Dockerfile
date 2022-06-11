FROM nginx:stable-alpine as production-stage
COPY ./nginx.conf /etc/nginx/conf.d/default.conf
COPY ./index.html /usr/share/nginx/html
EXPOSE 82
CMD ["nginx", "-g", "daemon off;"]
