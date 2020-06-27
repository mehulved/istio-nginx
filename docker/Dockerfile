FROM nginx:1.19.0

COPY config/default.conf /etc/nginx/conf.d/custom.conf

EXPOSE 80

STOPSIGNAL SIGTERM

CMD ["nginx", "-g", "daemon off;"]
