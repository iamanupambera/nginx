FROM nginx:latest

# Copy SSL certificates
COPY ssl.crt /etc/nginx/ssl/ssl.crt
COPY ssl.key /etc/nginx/ssl/ssl.key

# Copy Nginx configuration
RUN rm /etc/nginx/nginx.conf

COPY nginx.conf /etc/nginx/nginx.conf