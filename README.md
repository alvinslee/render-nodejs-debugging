# Nodejs Postgresql Server

## Usage

- `yarn install`
- `yarn build`
- `yarn start:prod`

## DB Migrations

Run

```bash
env DATABASE_URL=<external-db-url-from-render> yarn migrate up --no-reject-unauthorized
```

### Special Thanks

Special thanks to [Nathan Gilbert](https://gitlab.com/nathan_gilbert) for his help on this demo project setup.
