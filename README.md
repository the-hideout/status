# status 🚦

The-Hideout's official status page

**[status.tarkov.dev](https://status.tarkov.dev)** 🔗

## Running locally 🔨

When running locally you have two options:

1. Completely from scratch
2. With a template

## Completely from Scratch 📰

This will start the Docker stack locally, with no DB template files. This means that it will be a fresh slate for the status page:

```bash
make run
```

Navigate to [https://localhost/dashboard](https://localhost/dashboard) 🎉

## With a Template 📄

This will start the Docker statck locally with a DB template so it contains some monitors for you:

1. First, run the following command to copy your template files into your `data` directory:

    ```bash
    cp -r src/status_page/data-template/. src/status_page/data/
    ```

1. Start your Docker stack

    ```bash
    make run
    ```

Navigate to [https://localhost/dashboard](https://localhost/dashboard) 🎉

- Local Username: `test`
- Local Password: `testpw1`

> Note: You will notice pre-configured monitors now as well
