# Cloud Native PHP

Educational projet for cloud native transformation of a codebase

Adapted from https://github.com/ywxbear/PHP-Bookstore-Website-Example


## Requirements

- A working installation of docker (cf. https://docs.docker.com/get-started/get-docker/)
- A working installation of docker compose (cf. https://docs.docker.com/compose/install/)

## Usage

- Clone this repo
- Create a .env file based on [.env.sample](./.env.sample)
- Fill relevant variables (hint: you can generate passwords with `pwgen` on Linux/Mac or use online services like https://passwordsgenerator.net/)
- Start the stack 
```bash
docker compose up -d
```
- Check that all 3 services (app, db, phpmyadmin) are started successfully
```bash
docker compose ps -a
```
- Your app should now be available at `http://localhost:8086`