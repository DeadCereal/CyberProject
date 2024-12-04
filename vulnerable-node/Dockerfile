# Node.js (outdated version) # Node.js 10.x is outdated
FROM node:10  
WORKDIR /var/www/html

# Add app file
COPY package*.json ./
COPY app.js ./

# Install a vulnerable package
RUN npm install express@4.16.0  # Known vulnerabilities in this version
  
EXPOSE 3000
# Add app file
CMD ["node", "app.js"]
