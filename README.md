# otp-verification
OTP verification App using Node JS and Mongo DB

## Technologies and Packages used
1. express: For creating the web server.
2. mongoose: For interacting with MongoDB.
3. twilio: To send OTP via SMS.
4. dotenv: For managing environment variables.
5. body-parser: Middleware for parsing incoming request bodies.

## References
[MongoDB](https://www.prisma.io/dataguide/mongodb/setting-up-a-local-mongodb-database#setting-up-mongodb-on-macos)


## To start the mongodb server

```
sudo cp bin/* /usr/local/bin

sudo mkdir -p /usr/local/var/mongodb

sudo mkdir -p /usr/local/var/log/mongodb

sudo chown $USER /usr/local/var/mongodb
sudo chown $USER /usr/local/var/log/mongodb

mongod --dbpath /usr/local/var/mongodb --logpath /usr/local/var/log/mongodb/mongo.log --fork
```