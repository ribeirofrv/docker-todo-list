
FROM node:14-alpine
WORKDIR /app
EXPOSE 3000
ADD ./node_modules.tar.gz /usr/local/bin
COPY . /usr/local/bin
CMD [ "npm", "start" ]