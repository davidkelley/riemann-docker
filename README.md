# Riemann 0.2.5

This Dockerfile runs [Riemann](https://riemann.io) from Ubuntu Trusty.

## Starting the Server

```
docker run -p 5555:5555 -p 5555:5555/udp -p 5556:5556 davidkelley/riemann
```

## Accessing the Dashboard

Use this Docker Repository: [https://index.docker.io/u/davidkelley/riemann-dash](https://index.docker.io/u/davidkelley/riemann-dash)