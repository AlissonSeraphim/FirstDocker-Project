FROM node:16

EXPOSE 3001

WORKDIR /app/back-end

ADD node_modules.tar.gz .

COPY . .

ENTRYPOINT [ "npm install" ]

CMD ["npm start"]