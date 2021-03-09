FROM rocketchat/rocket.chat:latest

ENV MONGO_URL=mongodb://mongo:27017/rocketchat
ENV MONGO_OPLOG_URL=mongodb://mongo:27017/local


EXPOSE 3000
ENV SERVICE_TAGS webapp

ENV ROOT_URL http://localhost:3000/rocketchat

CMD ["node", "main.js"]




