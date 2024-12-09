
# Ionic Express App Backend

This is the backend for the Ionic Express App. It is built using Express.js and MongoDB.

## How to run

1. Clone the repository
2. Run `npm install`
3. Run `npm start`

The server will start on `http://localhost:3000`.

## API Endpoints

- GET `/api/posts`: Get all posts
- POST `/api/posts`: Create a new post
- GET `/api/posts/:id`: Get a post by ID
- PUT `/api/posts/:id`: Update a post by ID
- DELETE `/api/posts/:id`: Delete a post by ID

## Environment Variables

Create a `.env` file in the root directory and add the following environment variables:

```

PORT=3000
MONGO_URI=mongodb://localhost:27017/ionic-express-app

```
