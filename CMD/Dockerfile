FROM almalinux:9

RUN dnf install nginx -y
# Exec form — daemon off keeps nginx in the foreground so the container stays alive
CMD ["nginx", "-g", "daemon off;"]