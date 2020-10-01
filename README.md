# express-server


## Basic Setup

1. Create a server.js
2. Run `npm init -y`
3. Run `npm install express`

## Build Our Express Server

1. Require Express
2. Create an instance of Express
3. Add a port to listen on (allow for Heroku deployment)
4. Listen on the port. 
5. Add middleware

## BONUS: 

### Install Nodemon
``` bash
npm install nodemon -g
```

``` javascript
"dev": "nodemon server.js"
```

## Setup Routes

### GET Routes

1. Use `app.get`
2. Specify the route path (should include the resource type)
3. Retrieve the data
4. Send response to the user. 

### POST Routes
1. Use `app.post`
2. Specify the route path (should include resource type)
3. Handle the incoming POST body
4. Save the data
5. Send response to the user. 

6. Error handling

#### To Test POST Routes
1. Go to Postman
2. Select POST request from the dropdown
3. Select Body from the menu
4. Select `raw`
5. Select JSON
