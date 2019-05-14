# PostgreSQL Extensions Image

This image includes common extensions used by Out There Labs.

## Usage

See [sclorg/postgresql-container](https://github.com/sclorg/postgresql-container/tree/generated/10) for environment
variables and volume information.

```shell
$ docker run -d --name postgresql_database \
    -e POSTGRESQL_USER=user \
    -e POSTGRESQL_PASSWORD=pass \
    -e POSTGRESQL_DATABASE=db \
    -p 5432:5432 \
    outtherelabs/postgresql-10-centos7-extensions
```
