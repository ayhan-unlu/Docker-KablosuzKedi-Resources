 FROM node:24-slim
 WORKDIR /opt/n ode-todo-app
 COPY . .
 ENV PORT=4000
 EXPOSE 4000
 RUN npm install
 
 CMD ["node","app.js"]

 # ENTRYPOINT ["node"]
 # CMD ["app.js"]
 # this way app.js file is default and user can enter a different file name to start running with node 
 