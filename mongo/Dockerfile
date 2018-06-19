FROM mongo:3.6.5

LABEL hapi-app.version="0.0.1"

ENV MONGO_PASSWORD=mongo
ENV APP_DB_NAME=app
ENV APP_USERNAME=username
ENV APP_PASSWORD=password

COPY init.sh /docker-entrypoint-initdb.d/init.sh

EXPOSE 27017
