# Usage

```
docker run -it -p 8080:8080 titogarrido/composer-playground-s390x
```

or daemon mode:

```
docker run -dit -p 8080:8080 titogarrido/composer-playground-s390x
```

This port is based on:

https://github.com/mhart/alpine-node/blob/f4ce91eb2e624c34e25e5aa437f0d8c0c3caef2b/Dockerfile
and
https://github.com/hyperledger/composer/blob/master/packages/composer-playground/docker/Dockerfile
