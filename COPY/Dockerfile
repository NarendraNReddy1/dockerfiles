FROM almalinux:9 
RUN dnf install nginx -y
RUN rm -rf /usr/share/nging/html/index.html
COPY index.html /usr/share/nging/html/index.html 
CMD ["nginx","-g","daemonoff;"]


