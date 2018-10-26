FROM nginx

RUN rm -v /usr/share/nginx/html/index.html
ADD index.html /usr/share/nginx/html/index.html

CMD [ "nginx", "-g", "daemon off;" ]

