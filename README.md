# wait-http

An http service that just waits the requested number of seconds


## Run

    docker run --publish 80:80 --detach iperdomo/wait-http:1583315712

    # http://localhost/wait/<seconds> e.g.

	curl --verbose http://localhost/wait/10


Latest version of the image is published in Docker Hub

https://hub.docker.com/r/iperdomo/wait-http/tags

## Build

    docker build iperdomo/wait-http .
