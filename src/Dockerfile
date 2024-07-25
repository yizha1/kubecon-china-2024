ARG BASE_IMAGE

FROM ${BASE_IMAGE}

# Copy custom HTML file to the Nginx default directory
COPY index.html /usr/share/nginx/html/

# Expose port 80
EXPOSE 80

# Start Nginx server
CMD ["nginx", "-g", "daemon off;"]
