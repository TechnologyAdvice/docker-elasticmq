# ElasticMQ Docker Image

Provides [ElasticMQ](https://github.com/adamw/elasticmq).

## Supported tags and respective `Dockerfile` links
 * [`latest`, `0.8` (Dockerfile)](https://github.com/technologyadvice/docker-elasticmq/blob/master/Dockerfile)

## technologyadvice/elasticmq:latest

Installs the latest version of ElasticMQ and exposes port 9324.

Running should be as simple as:

    docker run -p 80:9324 -d technologyadvice/elasticmq

If you wish to custimise the settings, mount your config at `/elasticmq/custom.conf`.

## Credits

Adapted from the (Expert360 repository)[https://github.com/expert360/docker-elasticmq].

