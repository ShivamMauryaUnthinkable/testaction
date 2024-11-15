# Use the official Nginx image from the Docker Hub
FROM nginx:alpine

# Copy the index.html from the current directory to the Nginx's HTML directory
COPY index.html /usr/share/nginx/html/index.html

# Expose port 80 to access the web server
EXPOSE 80

# Nginx runs by default on port 80, so no need for an explicit command
# The default entrypoint for the Nginx image will automatically run Nginx