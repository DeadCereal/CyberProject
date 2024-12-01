# Node.js (outdated version) # Node.js 10.x is outdated
FROM node:10  

# Install a vulnerable package
RUN npm install express@4.16.0  # Known vulnerabilities in this version

# Add app file
COPY app.js /app.js
CMD ["node", "app.js"]
