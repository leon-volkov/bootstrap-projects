# PostgreSQL in Docker

Bootstrap template for a configured PostgreSQL in Docker database

## Running it

Copy the file `/env/.tpl.env` into `/env/.dev.env`

Run the command
`docker-compose -f docker-compose.dev.yml up -d database`

## Setting it up for your project

Find for the string `myproject` and replace it with whatever you want in the whole project

Open `/env/.dev.env` and fill it with your settings

## TODO

- [ ] Maybe we can move all scripts into a folder and load all of them instead of one by one
