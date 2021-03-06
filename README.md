# RESTful API

This RESTful API has been written for an Android application "FindMe" (in development right now).

## Стек технологий:

1. **NodeJS**;
2. **ExpressJS**;
3. **PassportJS**;
4. **MongoDB**;
5. **node-gcm** для *PUSH-уведомлений*.

## Установка и запуск базы:

`dnf install -y mongodb-server mongodb`

`mkdir /data`

`mkdir /data/db`

`mongod --fork --logpath /var/log/mongodb.log`

## Development mode (using nodemon):

`cd src`

`npm install`

`npm run start-dev`

## Deploy the application:

`docker-compose up`

## Credits

Has been written by ***[Anton Babinin](mailto:wkyborgw@gmail.com)***.
