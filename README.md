# Community Learning Hub

> Learning platform built with the MERN stack & Redux.

<img src="./server/public/assets/Screenshot 2025-05-03 141356.png">


## Usage

- Create a MongoDB database and obtain your `MongoDB URI` - [MongoDB Atlas](https://www.mongodb.com/cloud/atlas/register)


### Env Variables

Create the  `.env` inside server directory and add the following

```
PORT = 3001
MONGO_URI = your mongodb uri
JWT_SECRET = 'abc123'
```

Change the JWT_SECRET to what you want

### Install Dependencies (frontend & backend)

```
cd client
npm install
cd server
npm install
```

### Run

```

# Run client (:3000) & server (:3001)
cd client
npm run start
cd server
npm run start

# Run server
npm run start
```
