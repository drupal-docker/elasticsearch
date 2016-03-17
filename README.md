Elasticsearch for Drupal
=====================
[![Build Status](https://travis-ci.org/drupal-docker/elasticsearch.svg?branch=master)](https://travis-ci.org/drupal-docker/elasticsearch)

Version | Tags | Dockerfile
--- | --- | ---
1.5 | `1.5` | [Dockerfile](https://github.com/drupal-docker/elasticsearch/blob/master/5.4/Dockerfile)
1.6 | `1.6` | [Dockerfile](https://github.com/drupal-docker/elasticsearch/blob/master/5.4/apache/Dockerfile)
1.7 | `1.7`, `1` | [Dockerfile](https://github.com/drupal-docker/elasticsearch/blob/master/5.4/fpm/Dockerfile)
2.0 | `2.0` | [Dockerfile](https://github.com/drupal-docker/elasticsearch/blob/master/5.5/Dockerfile)
2.1 | `2.1` | [Dockerfile](https://github.com/drupal-docker/elasticsearch/blob/master/5.5/apache/Dockerfile)
2.2 | `2.2`, `2`, `latest` | [Dockerfile](https://github.com/drupal-docker/elasticsearch/blob/master/5.5/fpm/Dockerfile)
[![drupaldocker/elasticsearch](https://badge.imagelayers.io/drupaldocker/elasticsearch:latest.svg)](https://imagelayers.io/?images=drupaldocker/elasticsearch:1.5,drupaldocker/elasticsearch:1.6,drupaldocker/elasticsearch:1.7,drupaldocker/elasticsearch:2.0,drupaldocker/elasticsearch:2.1,drupaldocker/elasticsearch:2.2)

# Quickstart:

```bash
docker run -d drupaldocker/elasticsearch
```

# Environmental variables

No variables

# Description

Right now there is no difference if you use official `elasticsearch` docker images or `drupal-docker/elasticsearch`.

@todo

# Status

Proof of concept

# Credits
`drupaldocker/elasticsearch` images were built on the top of official [Elasticsearch images](https://hub.docker.com/r/_/elasticsearch/).
