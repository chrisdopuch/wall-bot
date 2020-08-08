# wall-bot

This is a Discord bot for my friends and I to keep track of who has won in the games we're playing.

I'm following this tutorial to get started: https://realpython.com/how-to-make-a-discord-bot-python/

## Dependencies

- [Python](https://www.python.org/downloads/) 3.7 or greater
- [pipenv](https://pypi.org/project/pipenv/)
- [heroku CLI](https://devcenter.heroku.com/articles/heroku-cli)
- [Postgres DB](https://devcenter.heroku.com/articles/heroku-postgresql#local-setup)

## Setup

Create an environment with pipenv and install the dependencies:
```
$ pipenv --python 3.7
$ pipenv install
```

Then create a `.env` file at the root with these contents:
```
# Get the token from the Discord developer portal for this Application
DISCORD_TOKEN=<the token goes here>
```

Then to run, do this:
```
$ pyenv shell
$ python bot.py
```