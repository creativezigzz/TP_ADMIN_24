FROM nginx:latest
RUN apt update
RUN apt install -y nano net-tools
RUN apt install -y certbot python3-certbot-nginx

# Copier la configuration personnalisée de Nginx dans l'image
COPY config/nginx.conf /etc/nginx/nginx.conf
