# Asynchronous-Tic-Tac-Toe

An asynchronous version of multi player tic-tac-toe, a playable web frontend using ReactJS and NodeJS.
Here Asynchronous means that both players take turns to play the game at their own convenience of time once started. Both players do not need to be online at the same time to play this game

## Local Setup

Clone the repository, cd into them individually, and then follow the below mentioned steps for setting up backend and frontend separately.

Frontend:

    - Fork the repository.
    - Clone the repository (git clone https://github.com/Rajaneesh12345/AsynchronousTTT).
    - Open the folder in which you cloned the repository.
    - Run npm install.
    - Run *npm run build* to build the frontend
    - Then run *npm start* to start the frontend locally.
    - Setup your backend using the below mentioned steps.

Backend:

    - Clone the repository (git clone https://github.com/Rajaneesh12345/AsynchronousTTT_Backend).
    - Open the folder in which you cloned the repository.
    - Run *npm install*.
    - Create a .env file in the root directory and add the following variables:
        - PORT = 5000
        - MONGO_URI = <Your MongoDB URI>
        - JWT_SECRET = <Your JWT Secret>
    - Now you can run 'npm start' and start working locally.

## Packages Used

    - Node Js
    - Express
    - JWT
    - Bcrypt Js
    - Mongoose
    - Dotnev
    - React

## Features Implemented

### Frontend

1. Login/Register pages:

   -  Registeration for new users.
   -  Login for register user.

2. Dashboard Page:

   -  View all games that the user has played.
   -  Navigate to the play screen for a game.

3. New Game Page :

   -  Create new game by entering the email id of any existing user.

4. Play Page :
   -  Make moves on this page.

<br>

### Backend

1. Auth Route(auth/)

   -  register -> Registeration of user.
   -  login -> Authentication of user.

2. Game Route(game/)
   -  getAllGame -> Fetch all games of a user by their email id.
   -  startNewGame -> Start a new game between two user.
   -  updateGame -> Update a games current state.
