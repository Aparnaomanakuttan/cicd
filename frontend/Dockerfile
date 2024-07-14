# Use an official Nginx image as a parent image
#FROM nginx:alpine

# Copy the frontend files into the container
#COPY index.html /usr/share/nginx/html/
FROM nginx:latest
COPY nginx.conf /etc/nginx/nginx.conf
COPY index.html /usr/share/nginx/html