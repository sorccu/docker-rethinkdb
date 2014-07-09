# docker-rethinkdb

This repository contains a [Dockerfile](https://www.docker.io/) for [RethinkDB](http://www.rethinkdb.com/).

## Why create yet another one?

This image was created mainly for two reasons. First, to be able to use the default ubuntu base image, saving time and space. But even more importantly, for tags. Currently most other Dockerfiles just install the latest version (or worse, haven't been updated for months and are horribly out of date), potentially leading to surprise updates or inability to upgrade.

This repository aims to provide a tag for each minor version (e.g. 1.x) as they are released, with the tag pointing to the latest patch version (i.e. tag 1.13 points to 1.13.1 or newer).

## License

See [LICENSE](LICENSE).
