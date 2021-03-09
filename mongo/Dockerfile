FROM mongo:4.0

EXPOSE 27017

ENV SERVICE_TAGS webapp

CMD ["mongod", "--smallfiles", "--oplogSize", "128", "--replSet", "rs0", "--storageEngine=mmapv1"]
