# MySQL Docker Pattern (With phpMyAdmin)
## What's this?
This is a pattern for easily launching MySQL (for local development environment). It is easier than using SQLite.

## Usage
1. `cp .env_sample .env` and edit `.env`  
1. `docker-compose up`
1. If you want to create a table or insert initial data, put `*.sql` or `*.sh` in `./initdb`.
1. In your apps, connect to `localhost:3333`
1. PhpMyAdmin http://localhost:8080