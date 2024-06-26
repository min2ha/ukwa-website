# UKWA WEBSITE (STATIC)

## Building and running static UKWA WEBSITE

To build docker image

```
docker build -t <TAG-NAME> .
```

To run docker image (for this specific NGINX configuration)

```
docker run -p 80:80 -d <TAG-NAME>
```

