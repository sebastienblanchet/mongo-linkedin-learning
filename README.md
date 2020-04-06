# MongoDB LinkedIn Learning

Tracking previous works for LinkedIn Learning course.

## Installing

```bash
brew tap mongodb/brew
brew install mongodb-community
brew services start mongodb-community
```

## Import

Starting mongod on macOS Catalina:
```bash
# start server in one terminal
mongod --dbpath=/Users/{userName}/data/db
# in another
cd src
npm start
```

## Resources

* [see here](https://stackoverflow.com/questions/58034955/read-only-file-system-when-attempting-mkdir-data-db-on-mac)
* [shell](https://docs.mongodb.com/manual/reference/mongo-shell/)