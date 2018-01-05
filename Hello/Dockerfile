FROM readytalk/nodejs
RUN mkdir /app
WORKDIR /app
ADD package.json /app/
RUN npm install
ADD . /app
CMD []
ENTRYPOINT ["/nodejs/bin/npm", "start"]
