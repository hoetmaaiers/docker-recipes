FROM node:6

# use nodemon for development
RUN npm install --global nodemon

# use cached layer for node modules
ADD package.json /tmp/package.json
RUN cd /tmp && npm install
RUN mkdir -p /app && cp -a /tmp/node_modules /app

EXPOSE 1337
EXPOSE 5858

COPY . /app
WORKDIR /app

CMD ["npm", "start"]
