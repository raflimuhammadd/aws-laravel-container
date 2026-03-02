FROM nginx:1.25-alpine

# Copy nginx config dari host ke container (Path dari root project)
COPY ./docker/nginx/default.conf /etc/nginx/conf.d/default.conf

# Copy Laravel public assets (Agar Nginx bisa baca index.php dsb)
COPY ./laravel/public /var/www/html/public