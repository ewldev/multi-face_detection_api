# Multi-face detection api
Back end of multiple faces recognition app.

Created with Express.js and integrated with Clarifai's face recognition api.

Connected to a Postgres database which allows user registration and log in.

It will also keep counts and show the number of times a user has logged in.

1. Clone this repo
2. Run `npm install`
3. Run `npm start`
4. You must add your own API key in the `controllers/image.js` file to connect to Clarifai API
5. Add your own database credentials to `server.js` line 17

You can grab Clarifai API key [here](https://www.clarifai.com/)

** Make sure you use postgreSQL instead of mySQL for this code base.
