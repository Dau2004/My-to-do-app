# Use a lightweight Nginx image as base
FROM nginx:alpine

# Copy the static files into the nginx directory
COPY . /usr/share/nginx/html

# Expose port 80
EXPOSE 80

# Command to start Nginx (it runs automatically)
CMD ["nginx", "-g", "daemon off;"]


