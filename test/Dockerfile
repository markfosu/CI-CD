# Step 1: Use an official lightweight Nginx image
FROM nginx:alpine

# Step 2: Copy Mario game files into Nginx’s default web directory
COPY . /usr/share/nginx/html

# Step 3: Expose port 80 so it can be accessed externally
EXPOSE 80

# Step 4: Start Nginx (default command already runs Nginx)
CMD ["nginx", "-g", "daemon off;"]
