stack: node
port: 3000

setup:
npm install

start:
node server.js

healthcheck:
http://localhost:3000