FROM node:24-slim
WORKDIR /uploader-app
COPY app/ .
RUN npm install
EXPOSE 3000
CMD ["node", "server.js"]