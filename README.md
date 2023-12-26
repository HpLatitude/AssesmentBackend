# Movie Catalog Backend

## Introduction

This repository contains the backend API for the Movie Catalog web app. The API is responsible for handling movie data, including creating, reading, updating, and deleting movie records. Each movie entity consists of a title, publishing year, and an image for the poster.

## Getting Started
- npm init -y

### Prerequisites

Before you begin, ensure you have met the following requirements:
- Node.js (version 16 or higher)
- npm or yarn
- MongoDB (for database)

### Installation

To install the project dependencies, run the following command:

```bash
npm install
# or
yarn install

**Dependencies**

   bcryptjs
    cloudinary
    cors
    dotenv
    express
    jsonwebtoken
    moment
    mongoose
    multer
    validator

Configuration
Create a .env file in the project root and add the necessary environment variables:

dbconfig file

MONGODB_URI=<your_mongodb_uri>
PORT=<desired_port_number>
Running the App
To start the server, run:

bash

npm start
# or
yarn start
API Documentation
Endpoints
POST /movies/api/create Create a new movie
GET /movies/api/listing?page=1 Get a list of movies
GET /movies/api/details/658a799aff8e649aa7fc0d39 Get a single movie by ID
PATCH /movies/api/update/658a799aff8e649aa7fc0d39 Update a movie by ID
DELETE /movies/api/delete/658a799aff8e649aa7fc0d39 Delete a movie by ID

## Request and Response Examples
POST /movies/api/create

## Request body:

dummy json

{
  "moviename": "Movie Title",
  "publishyear": 2021,
  "image": "image_url"
}

## Response:

dummy json

{
  "success": true,
  "data": {
    "_id": "movie_id",
    "userid":"userid",
    "moviename": "Movie Title",
    "publishyear": 2021,
    "image": "image_url"
  }
}

Deployment
This API is deployable on cloud platforms like AWS. 

Contributing
Contributions to this project are welcome. Please follow the standard fork-and-pull request workflow.

License
MIT License

![pathaan](https://github.com/HpLatitude/AssesmentBackend/assets/148424369/e113eebf-ab9e-493f-be20-38c3368c866f)

<img width="1440"  src="https://github.com/HpLatitude/AssesmentBackend/assets/148424369/e113eebf-ab9e-493f-be20-38c3368c866f">

