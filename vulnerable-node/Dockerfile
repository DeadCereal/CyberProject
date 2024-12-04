# Node.js (outdated version) # Node.js 10.x is outdated
FROM node:23-slim  

WORKDIR /var/www/html

# Add app file
COPY package*.json ./
COPY app.js ./

RUN npm install
EXPOSE 3000
CMD ["node", "app.js"]
