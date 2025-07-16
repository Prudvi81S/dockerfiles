FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://raw.githubusercontent.com/Prudvi81S/expense-terraform-dev/refs/heads/main/readme.MD /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]