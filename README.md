# How to use this image

## start profanity

```
docker run --name profanity -i -t cremuzzi/profanity
```

## where to store configurations

1. Create a data directory on a suitable volume on your host system, e.g. `/my/own/datadir`

2. Start your `profanity` container like this:

```
docker run --name profanity -i -t -v /my/own/datadir:/home/profanity cremuzzi/profanity
```
