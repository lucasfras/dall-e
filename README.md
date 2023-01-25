# DALL-E Clone Application

## Description
This is a fullstack MERN application which uses OpenAI API DALL-E for generating images based on text, it uses cloudinary to store the generated images and MongoDB to store the posts created by uses, such as name, prompt and image url. All the backend is express.js and frontend react.js

## Usage for server
For usage use the following commands in the server folder
```
npm install
npm start
```

## Usage for client
For usage use the following commands in the server folder
```
npm install
npm start
```

## Usage NOTE
If you want this project to run in a production way you should build the client

## Don't forget to set the environment variables 
Don't forget to set the following environment variables to your project run :grinning:

### Server side environment variables
```
MONGODB_URL
OPENAI_API_KEY
CLOUDINARY_CLOUD_NAME
CLOUDINARY_CLOUD_API_KEY
CLOUDINARY_CLOUD_API_SECRET
```

### Client side environment variables

```
VITE_BACKEND_URL
```