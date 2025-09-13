# `@recaptime-dev/dotenvx-secretstore` - centralized secret store

This is the centralized project for managing secrets encrypted by `dotenvx` with Git levels of audit trail for changes.

## Usage

**GitHub Actions**: Use [`dotenvx-action/remote-loader`](https://github.com/andreijiroh-dev/dotenvx-action/tree/main/remote-loader) action to load secrets from this repository.

**GitLab CI and others**: Simply `wget` the file's raw URL somewhere and run with `dotenvx run` command.

## Open-in-CDE links

You can use these buttons to setup a cloud environment for development if you don't want to declutter things locally.

| Platform / App | Button | Limits/Pricing |
| --- | --- | --- |
| Codespaces | [![Open in Codespaces](https://github.com/codespaces/badge.svg)][ghcs-new] | [See Codespaces pricing][ghcs-pricing] |
| Firebase Studio (previously Project IDX) | [![Open in Firebase Studio](https://cdn.firebasestudio.dev/btn/open_blue_32.svg)][fbs-open] | Up to 2 free workspaces, 10 for regular Google Dev Program members, 30 on Premium ([docs][fbs-quota])|

[ghcs-new]: https://codespaces.new/recaptime-dev/dotenvx-secretstore
[ghcs-pricing]: https://docs.github.com/en/billing/managing-billing-for-your-products/managing-billing-for-github-codespaces/about-billing-for-github-codespaces
[fbs-open]: https://studio.firebase.google.com/import?url=https%3A%2F%2Fgithub.com%2Frecaptime-dev%2Fdotenvx-secretstore
[fbs-quota]: https://firebase.google.com/docs/studio#pricing

## License

MPL-2.0
