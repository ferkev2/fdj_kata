# FDJ kata

## Installing server app

```shell

  cd sport-app-server

  yarn install
  yarn run dev
```

```shell
  cd sport-app-front
  yarn install
  yarn start
```

## For the database

You need to have mongodb installed.
The string url of database is ```mongodb://127.0.0.1:27017/sports```. If you use and other string url or database name, you would change the string url in the ```app.ts``` file in server folder in order to connect your databse.

## Build the app and stating

Execute these commmands

```shell
  yarn run build
  yarn start
```
