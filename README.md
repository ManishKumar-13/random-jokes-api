# Random Jokes and Images API

## Overview

This API serves random jokes and images. It includes three endpoints:
- `/api/jokes/random`: Returns a random joke.
- `/api/images/random`: Returns a URL to a random image.
- `/api/random`: Returns both a random joke and an image URL.

## Setup

1. Clone the repository.
2. Run `npm install` to install dependencies.
3. Run `node index.js` to start the server.

## Endpoints

- **GET /api/jokes/random**: Returns a random joke.
- **GET /api/images/random**: Returns a URL to a random image.
- **GET /api/random**: Returns both a random joke and an image URL.

## Challenges

- **Challenge**: Fetching random images from a third-party API.
- **Solution**: Used `axios` to make HTTP requests and handle responses.
