FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/hmtl/index.hmtl
COPY index.hmtl /usr/share/nginx/hmtl/index.hmtl
CMD ["nginx","-g","daemon off;"]