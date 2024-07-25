# Use the official Nginx image as the base image
FROM nginx:1.21.6

# Copy custom HTML file to the Nginx default directory
COPY index.html /usr/share/nginx/html/

# Expose port 80
EXPOSE 80

# Start Nginx server
CMD ["nginx", "-g", "daemon off;"]
