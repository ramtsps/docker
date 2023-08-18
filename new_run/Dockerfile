# Use the official Nginx base image
FROM nginx

# Copy your HTML file to the appropriate directory
COPY index.html /usr/share/nginx/html

# Expose the port that Nginx will listen on
EXPOSE 80

# Start the Nginx server
CMD ["nginx", "-g", "daemon off;"]
