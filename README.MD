# Odoo 13 Fluffy

## Requirements

- [Docker](https://www.docker.com/get-started)

## Usage

Start the container:

```sh
docker-compose up
```

Then open `localhost:8069` to access Odoo 13.0. If you want to start the server with a different port, change [`YOUR_PORT`](docker-compose.yml#L18) to expected value:

```
    ports:
      - "YOUR_PORT:8069"
```

To run in detached mode, execute this command:

```sh
docker-compose up -d
```
