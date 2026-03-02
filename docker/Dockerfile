# from which image
FROM node:20-alpine

# label
LABEL MAINTAINER="mlewis@spartaglobal.com"

# set the default working directory to /usr/src/app
WORKDIR /usr/src/app

# copy app folder (to same place as Dockerfile, then copy to default location in container)
COPY app /usr/src/app

# install dependencies with npm
RUN npm install

# expose port
EXPOSE 3000

# CMD [node app.js or npm start]
CMD [ "npm", "start" ]