FROM almalinux:9
RUN dnf install -y nginx
CMD ["nginx", "-g", "daemon off;"]
LABEL maintainer="balaji@example.com" \
      build-date="2026-08-09" 
EXPOSE 80/tcp
RUN rm -rf /usr/share/nginx/html/index.html
COPY index.html /usr/share/nginx/html/index.html