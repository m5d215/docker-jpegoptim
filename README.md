# docker-jpegoptim

![size and layers](https://images.microbadger.com/badges/image/m5d215/jpegoptim.svg)

Minimal [Jpegoptim](https://github.com/tjko/jpegoptim) Docker image.

## Usage

```sh
docker container run --rm -v "$PWD/large.jpeg:/image.jpeg" m5d215/jpegoptim:latest /image.jpeg
```
