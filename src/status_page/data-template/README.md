# Local DB info

1. Create a new directory named `data` in the `src/status_page` directory

1. From the root of this repo, run the following command:

```bash
cp -r src/status_page/data-template/. src/status_page/data/
```

These files are just used for local testing to have a persistent dev env. These files contain the persistent configuration for uptime-kuma. They include the credentials for login, healthcheck endpoints, healthcheck history, etc..

Test credentials:

- username: `test`
- password: `testpw1`
