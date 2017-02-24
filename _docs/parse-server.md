---
title: Parse Server
---

# Parse server

## Install

### Windows

```
npm install -g parse-server mongodb-runner
```

If MongoDb fails, [download MongoDb](https://www.mongodb.com/download-center#production).

## MongoDb

* Create the folder: C:\data\db\ where MongoDB will store database files
* Add to path: `set PATH=%PATH%;C:/Program Files/MongoDB/Server/3.2/bin/`

### Start database

    "C:\Program Files\MongoDB\Server\3.4\bin\mongod.exe" --dbpath "d:\test\mongo db data"

### Connect to MongoDb

    "C:\Program Files\MongoDB\Server\3.4\bin\mongo.exe

## Resources

* [Installing your own parse-server on Windows](https://medium.com/@cristi_ursachi/installing-your-own-parse-server-on-windows-b2c7a2498d19#.1qmcj7xkn)
* [Install MongoDB Community Edition on Windows — MongoDB Manual 3.4](https://docs.mongodb.com/manual/tutorial/install-mongodb-on-windows/)