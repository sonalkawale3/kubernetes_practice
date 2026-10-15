# Base image: Lightweight Nginx Alpine
FROM nginx:alpine

# Copy the custom index.html into Nginx default web directory
COPY index.html /usr/share/nginx/html/index.html

# Expose standard HTTP port
EXPOSE 80

# Start Nginx in the foreground
CMD ["nginx", "-g", "daemon off;"]
