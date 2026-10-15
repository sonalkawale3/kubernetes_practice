# Base image: Lightweight Nginx Alpine
FROM nginx:alpine

# Copy custom Nginx configuration for routing /payment and /
COPY default.conf /etc/nginx/conf.d/default.conf

# Copy the payment web index.html
COPY index.html /usr/share/nginx/html/index.html

# Expose standard HTTP port
EXPOSE 80

# Start Nginx in the foreground
CMD ["nginx", "-g", "daemon off;"]
