phpMyAdmin for OpenShift
========================

[![dockeri.co](http://dockeri.co/image/vshn/phpmyadmin)](https://hub.docker.com/r/vshn/phpmyadmin/)

[![MIT License](https://img.shields.io/github/license/vshn/docker-phpmyadmin.svg)](https://github.com/vshn/docker-phpmyadmin/blob/master/LICENSE
) [![GitHub issues](https://img.shields.io/github/issues-raw/vshn/docker-phpmyadmin.svg)](https://github.com/vshn/docker-phpmyadmin/issues
) [![GitHub PRs](https://img.shields.io/github/issues-pr-raw/vshn/docker-phpmyadmin.svg)](https://github.com/vshn/docker-phpmyadmin/pulls)

Dockerized MariaDB/MySQL Administration
---------------------------------------

[phpMyAdmin](https://www.phpmyadmin.net/) is a free Web-based administration tool
for MariaDB and MySQL written in PHP. We provide this Docker image on popular demand
for the [OpenShift container platform](https://www.openshift.com/). Unfortunately,
the official [phpmyadmin/phpmyadmin](https://hub.docker.com/r/phpmyadmin/phpmyadmin/)
image is unsuitable for running on OpenShift.

This image derives from [nazarpc/phpmyadmin](https://hub.docker.com/r/nazarpc/phpmyadmin/),
which is a friendly-looking, refreshingly simple, well-supported and popular
Apache-based setup of phpMyAdmin. 

Supported Tags
--------------

- [`latest`](https://github.com/vshn/docker-phpmyadmin/blob/master/Dockerfile) [![Image Layers](
  https://img.shields.io/imagelayers/layers/vshn/phpmyadmin/latest.svg)](https://imagelayers.io/?images=vshn/phpmyadmin:latest
  ) (functionally equivalent with `nazarpc/phpmyadmin:latest`)

Usage
-----

phpMyAdmin is accessible by default from ports 8080 and 4443.

See the [base image readme](https://github.com/nazar-pc/docker-phpmyadmin/blob/master/readme.md)
for extensive runtime customization options.

Development
-----------

- [Issue tracker](https://github.com/vshn/docker-phpmyadmin/issues) (GitHub)

Automatic builds are configured on Docker Hub and should trigger automatically
whenever the base image is updated.
