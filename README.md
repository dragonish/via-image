# via-image

[VIA Web Application](https://usevia.app/) - Your keyboards best friend.

## Usage

```bash
# pull
docker pull giterhub/via:nightly

# run
docker run -d \
    --name via \
    --restart unless-stopped \
    -p 80:80 \
    giterhub/via:nightly
```

## Extended Usage

```bash
docker run -d \
    --name via \
    --restart unless-stopped \
    -p 80:80 \
    -v "$(pwd)"/data:/www/data \
    giterhub/via:nightly
```

This places the required JSON files in the `/data` directory on disk and retrieves them by accessing `/data/`.

## Docker Hub Image

- [giterhub/via](https://hub.docker.com/r/giterhub/via)

## Credits

- [emikulic/darkhttpd](https://github.com/emikulic/darkhttpd)
- [the-via/app](https://github.com/the-via/app)
