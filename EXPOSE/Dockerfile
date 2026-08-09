FROM almalinux:9
RUN dnf install -y nginx
CMD ["nginx", "-g", "daemon off;"]
LABEL maintainer="balaji@example.com" \
      build-date="2026-08-09" 
EXPOSE 80/tcp