# docker-compose-slim

A simple docker compose workflow that sets up a LEMP network of containers for local Slim development.

## Usage

- Clone the repo
- cd into the directory
- Run `docker-compose up -d --build`
- Navigate to `http://localhost:8080`
- See the Hello World example from the SlimFramework website.

## Containers created and their ports

- *nginx* `:8080`
- *mysql* `:3306`
- *php* `:9000`
- *composer*

