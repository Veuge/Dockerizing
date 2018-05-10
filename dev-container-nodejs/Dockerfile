FROM node:carbon

RUN mkdir -p /home/node/node-app
COPY package.json /home/node/node-app/package.json
RUN chown -R node:node /home/node/*

USER node
WORKDIR /home/node/node-app
RUN yarn

CMD ["yarn", "start"]