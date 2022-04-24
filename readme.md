# Countries API

This is a sample API built using a tutorial from realpython.com:

https://realpython.com/api-integration-in-python/

It contains a list of countries with some data about each one, and will respond to HTTP requests in a few ways.

To run this API while in the `~/countries_api` folder:
1. `export FLASK_APP=app.py` # sets the server code file
2. `export FLASK_ENV=development` # useful debugging messages and reloads on every change to the file
3. `flask run`

Running the app will show the IP address FLask is watching. This will allow you to use `curl` to send HTTP requests at it.
