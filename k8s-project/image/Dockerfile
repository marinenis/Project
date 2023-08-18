# Use the official Nginx image as the base image
FROM nginx:alpine

# Copy the HTML files into the default Nginx document root
COPY page1.html page2.html index.html /usr/share/nginx/html/
COPY nginx.conf /etc/nginx/nginx.conf
# Expose port 80 for Nginx
EXPOSE 80

# Start Nginx when the container starts
CMD ["nginx", "-g", "daemon off;"]
