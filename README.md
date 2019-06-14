# Python Dev Environment

I've developed this docker-compose file to make it easy to spin up a Dev Environment with different Python versions and to experiment between versions 2 and 3.

I've used:

* macOS Mojave 10.14.4
* Docker Desktop 2.0.4.1

## Pre-reqs

* Docker installed <https://www.docker.com>
* it's interesting to have completed the Get Started at the Docker website
* choose your Python version in <https://hub.docker.com/_/python> and change this line in `docker-compose.yml`:

    `image: python:3.7.2-slim`

## Spinning up the Dev Environment

```bash
docker-compose run python-dev-environment
```

## Using it

After spinning up the environment, `/root/src/` inside the container will be linked to `./src/` on the host OS.

Have fun with Python!

<a rel="edwaldoalmeida.com" href="https://www.edwaldoalmeida.com">**Edwaldo Almeida**</a> @ 2019
