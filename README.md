# Riemann 0.2.5

This Dockerfile runs Riemann from Ubuntu Trusty.

## Starting the Server

```
docker run -p 5555:5555 -p 5555:5555/udp -p 5556:5556 davidkelley/riemann
```

## Accessing the Dashboard

Use this Docker Repository: https://index.docker.io/davidkelley/riemann-dash