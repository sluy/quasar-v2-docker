# Quasar App (app)

## Docker build & run
```bash
cd quasar-v2-docker
docker build -t quasar-v2-docker
docker run -it -p 8000:80 --rm dockerize-quasar
```

## docker-compose
```bash
cd quasar-v2-docker
docker-compose up --build
```

A Quasar Framework app

## Install the dependencies
```bash
yarn
```

### Start the app in development mode (hot-code reloading, error reporting, etc.)
```bash
quasar dev
```

### Lint the files
```bash
yarn run lint
```

### Build the app for production
```bash
quasar build
```

### Customize the configuration
See [Configuring quasar.conf.js](https://v2.quasar.dev/quasar-cli/quasar-conf-js).
