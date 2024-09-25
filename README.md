# User Signup API

This project is a simple API built with Node.js and Express for handling user signups and fetching user data. User information is stored in a JSON file (`users.json`), and the API supports basic CORS functionality.

## Features

- **User Signup**: Accepts user details and stores them in a local JSON file.
- **Fetch Users**: Retrieves all registered users from the JSON file.
- **CORS Enabled**: Allows cross-origin requests from any domain.
- **JSON Data Storage**: Simple user data persistence using a local file.

## Endpoints

### `GET /`

Returns a welcome message.

### `POST /api/signup`

Accepts user details (`name`, `username`, `email`, `password`) and stores them in the JSON file.

### `GET /api/users`

Returns a list of all registered users from the JSON file.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/user-signup-api.git

   ```

2. Navigate into the project directory:

   ```bash
    cd user-signup-api

   ```

3. Install the dependencies:

```bash
    npm install
```

4. Create a db directory and a users.json file for storing user data:
```bash
    mkdir db
```
```bash
    echo "[]" > db/users.json
```
    Running the Server
    To start the server, run:


```bash
    npm start
```
    The server will be available at http://localhost:3000.

## Dependencies
1. Express
2. fs (File System)
3. path
4. cors

