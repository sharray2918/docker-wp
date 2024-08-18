# docker-wp

Simple wordpress app with docker compose

## Requirements

[Install Docker Desktop application](https://docs.docker.com/engine/install/)

## Dev

### Build and start the app

```.shell
docker-compose up -d
```

Open `localhost:8000` from there you can access your app and Install wordpress in the (local) server. Once installed, you can develop.
When you need to access admin page, access `localhost:8000/wp-login.php`

### Delete and rebuild the app

Delete `Images` and `Volumes` in Docker Desktop, and then restart from **Build and start the app** in this document.

## Versioning

Versioning WordPress theme and plugins are more tricky than ordinary web app development. See `.gitignore`.
