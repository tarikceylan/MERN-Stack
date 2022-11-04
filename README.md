# **MERN-Stack**

This repository is for MERN Stack training prepared by Dave Gray on Youtube which can be found on [MERN Stack Full Tutorial & Project](https://www.youtube.com/watch?v=CvCiNeLnZ00)

## **What is MERN Stack?**

**MERN** is an acaronym for **M**ongoDB, **E**xpressJS, **R**eactJS, **N**odeJS which is a stack of technologies to build a full-stack web app.

> A **Full-Stack** web app is built with two parts. **Back-End** and **Front-End**

## **1. Back-End**

**Back-End** of a full-stack web application handles communication with internal and external resources. (e.g. application endpoints, database, etc.)

> In this project a 404 page and other views which could be considered as **front-end** are included for testing purposes.

### **1. 1. Back-End Structure**

- [**Express**](https://expressjs.com/) framework is used to setup [**RESTful API**](https://restfulapi.net/).
- [**cors**](https://www.npmjs.com/package/cors) package used as a middleware to configure [**Cross-Origin Resource Sharing**](https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS).
- [**date-fns**](https://www.npmjs.com/package/date-fns) package is used for **timestamps in logs.**
- [**cookie-parser**](https://www.npmjs.com/package/cookie-parser) package is used for **parsing information from cookies.**
- [**uuid**](https://www.npmjs.com/package/uuid) package is used for assigning **unique identifiers** for log items.
- [**dotenv**](https://www.npmjs.com/package/dotenv) package is used for storing environment variables.
- [**mongoose-sequence**](https://www.npmjs.com/package/mongoose-sequence) package is used to assign custom IDs to collection entries.
- [**express-async-handler**]() package is used for **simplfying async calls** in express
- [**bcrypt**]() package is used for **encrypting sensitive information** when storing in the database

### **1. 2. Database**

- [**MongoDB**](https://www.mongodb.com/) is a **document database** which consists of [**collections**](https://www.mongodb.com/docs/manual/core/databases-and-collections/#collections)
- [**Mongoose**](https://mongoosejs.com/) is an ODM which helps interactions with MongoDB easier through code.
