# My first Flask project - Flaskr

Project to learn the basics of working with Flask.

## API

Current startup routine:

1. `$ poetry install` - App built using poetry. Installs dependecies.
2. `$ poetry shell` - starts venv.
3. `$ export FLASK_APP=flaskr` - sets FLASK_APP env variable
4. `$ export FLASK_ENV=development` - sets FLASK_ENV env variable
5. `$ flask init-db` - initializes db instance
6. `$ flask run` - runs app.

Current Endpoints:

* `/hello` - Used for proof of life. Outputs "Hello world!"
