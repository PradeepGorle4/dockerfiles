FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
# ONBUILD executes when other user uses our image
ONBUILD COPY index.html /usr/share/nginx/html/index.html
CMD ["nginx", "-g" " daemon off;"]

