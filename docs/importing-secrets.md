# Importing secrets from other secret stores

## Importing existing `.env` files

If you are currently using `dotenvx` on your project and you want to move them
here, simply `mkdir projects/<your-project>` and copy your existing
dotenvx-encrypted `.env` files.

## Migrating from Doppler

For project-specific secrets, you can export them from Doppler as a `.env` file
via the Dashboard or CLI and then encrypt them using `dotenvx` CLI.

```bash
doppler secrets download --format env --no-file > .env.ci
dotenvx encrypt -f .env.ci
```

If you have seperate environments, you can export them one by one and encrypt
them into separate files like `.env.ci`, `.env.staging`, `.env.prod`, etc., to
keep them organized and neat.
