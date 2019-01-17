# musichubapi

Install the necessary packages with
```npm install```

Start the server
```npm start```

## Architecture

routes/index.js : The sign in/sign up with Google.
routes/playlists : RESTful services on playlists.
routes/songs : RESTful services on songs.

## Swagger Documentation

[Can be found in the /doc directory.](https://github.com/kfontain/musichubapi/blob/master/doc/swagger.yml)

## Requirements

npm==6.4.0
node==10.13.0
mongoDB (adress to the database needs to be specified in app.js)
