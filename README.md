# musichubapi

Install the necessary packages with
```npm install```

Start the server
```npm start```

## Architecture

routes/index.js : The sign in/sign up with Google.

routes/playlists : RESTful services for playlist ressources.

routes/songs : RESTful services for song ressources.

## Swagger Documentation

[Can be found in the /doc directory.](https://github.com/kfontain/musichubapi/blob/master/doc/swagger.yml)

## Requirements

npm==6.4.0

node==10.13.0

mongoDB (adress to the database needs to be specified in app.js)
