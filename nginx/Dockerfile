FROM nginx:latest

COPY ./nginx/conf.d/default.conf /etc/nginx/conf.d/default.conf

# No need to copy the php files to the /var/www/html folder.
# All the php proccessing occurs in the app container.
# Copy the public folder and all the CSS, images, HTML
COPY ./app/public /var/www/html/public