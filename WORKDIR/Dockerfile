FROM almalinux:9
RUN dnf install -y nginx
RUN useradd ec2-user
CMD ["nginx", "-g", "daemon off;"]
USER ec2-user
WORKDIR /var/temp