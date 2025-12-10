# Use the official nginx image as base
FROM nginx:latest

# Copy all website content to nginx default serving location
COPY . /usr/share/nginx/html/

# Expose port 80
EXPOSE 80

