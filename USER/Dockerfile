FROM almalinux:9
RUN dnf install nginx -y
# root access required to create user or install packages
RUN useradd roboshop
CMD ["nginx", "-g", "daemon off;"]

USER roboshop