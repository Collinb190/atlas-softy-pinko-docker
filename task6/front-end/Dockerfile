# Use the latest ubuntu image.
FROM nginx:latest

# Copy the softy-pinko-front-end files to the nginx html directory
COPY softy-pinko-front-end /var/www/html/softy-pinko-front-end

# Copy the Nginx config file to the appropriate location
COPY softy-pinko-front-end.conf /etc/nginx/conf.d/default.conf
