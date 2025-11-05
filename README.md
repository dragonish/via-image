# via-image

[VIA Web Application](https://usevia.app/) - Your keyboards best friend.

## Usage

```sh
# pull
docker pull giterhub/via:latest

# run
docker run -d \
    --name via \
    --restart unless-stopped \
    -p 80:80 \
    giterhub/via:latest
```

## Docker Hub Image

- [giterhub/via](https://hub.docker.com/r/giterhub/via)

## Credits

- [emikulic/darkhttpd](https://github.com/emikulic/darkhttpd)
- [the-via/app](https://github.com/the-via/app)
