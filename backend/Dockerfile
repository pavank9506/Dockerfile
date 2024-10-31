FROM node:20
EXPOSE 8080
RUN mkdir /opt/server
ENV DB_HOST="mysql"
WORKDIR /opt/server
ADD package.json .
ADD *.js .
RUN npm install
CMD ["node","index.js;"]
