# coffee_shop-Full-stack
New digitally enabled coffee shop where students can order drinks, socialize, and study.
  1. Display graphics representing the ratios of ingredients in each drink.
  2. Allow public users to view drink names and graphics.
  3. Allow the shop baristas to see the recipe information.
  4. Allow the shop managers to create new drinks and edit existing drinks.
## Getting started
### Pre-requisites and local development

Developers using this project should already have python3,pip and node installed in thier local machines

#### Backend
The ./backend directory contains a partially completed Flask and SQLAlchemy server.
From the backend folder run pip install `requirements.txt`. All required package included in requirements file.

To run the server, execute:

`export FLASK_APP=api.py

 export FLASK_ENV=development
 
 flask run`
 
 The application is run on  `http://127.0.0.1:5000/`by default that is the localhost
#### Frontend
The ./frontend directory contains a complete ionic angular frontend to consume the data from the Flask server. 

From the frontend folder run the following commands to start the client:

  `npm install //only once to install dependencies

   ionic serve`

By default, the frontend run on localhost `http://localhost:8100`
Note:if the frontend doesn't work after command `ionic serve` try to download node-sass (version 4)
