FROM node:latest

WORKDIR /cloud-developer-my-instagram-aws
COPY . /cloud-developer-my-instagram-aws
RUN cd /cloud-developer-my-instagram-aws && npm install
EXPOSE 3000

# CMD ["node", "/cloud-developer-my-instagram-aws/server.js"]
CMD [ "npm", "run", "dev" ]
