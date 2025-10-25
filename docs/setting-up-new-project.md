# Setting up a new project

## Important: Branch off your work to avoid conflicts

To avoid merge conflicts, please branch off any proposed changed and use the
GitHub/GitLab flow unless in case of emergency (like API key or
`DOTENV_PUBLIC_KEY`/`DOTENV_PRIVATE_KEY` rotation).

## Using the `new-project` script

Run the `new-project`, replacing `name-here` with your desired project name.

```bash
# with direnv loaded
new-project name-here

# w/o direnv, at root directory
./scripts/new-project name-here
```

After that, `cd` into the newly created directory and set up secrets via
`dotenvx` CLI yourself or [import existing ones](./importing-secrets.md).
Don't forget to update the `README.md` file to reflect your project's usage and
`git commit` the changes.
