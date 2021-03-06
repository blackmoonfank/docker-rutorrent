# docker-rutorrent

![Docker Pulls](https://img.shields.io/docker/pulls/furqon/mediawiki)
![Docker Stars](https://img.shields.io/docker/stars/furqon/mediawiki)
![GitHub Repo stars](https://img.shields.io/github/stars/blackmoonfank/docker-mediawiki?label=github%20star)
![GitHub forks](https://img.shields.io/github/forks/blackmoonfank/docker-mediawiki?label=github%20forks&style=plastic)
![GitHub](https://img.shields.io/github/license/blackmoonfank/docker-mediawiki)

Docker container for [Rutorrent](https://www.mediawiki.org) running under [Nginx](https://www.nginx.com) and [PHP-FPM](https://php-fpm.org/). Based on the official PHP7 [images](https://hub.docker.com/_/php/).

For a basic understanding of docker please refer to the official [documentation](https://docs.docker.com/).

   * [Supported Tags](#supported-tags)
   * [Features](#features)
   * [Changelog](#changelog)
   * [Usage](#usage)
      * [With MySQL](#with-mysql)
      * [With SQLite](#with-sqlite)
   * [Configuration](#configuration)
      * [General](#general)
      * [Uploads](#uploads)
      * [E-Mail](#e-mail)
      * [Logo](#logo)
      * [Skins](#skins)
      * [Extensions](#extensions)
      * [HTTPS](#https)
      * [Additional configuration](#additional-configuration)
      * [Configuration file](#configuration-file)
      * [Performance](#performance)
   * [Configuration reference](#configuration-reference)
   * [Extending this image](#extending-this-image)
   * [Security](#security)
   * [Contributing](#contributing)
   * [License](#license)

## Supported Tags


## Features


## Changelog

See [CHANGELOG.md](https://github.com/kristophjunge/docker-mediawiki/blob/master/docs/CHANGELOG.md) for information about the latest changes.

## Security

* Nginx and PHP-FPM worker processes run under the `www-data` user with UID 999 and GID 999.

## Contributing

See [CONTRIBUTING.md](https://github.com/kristophjunge/docker-mediawiki/blob/master/docs/CONTRIBUTING.md) for information on how to contribute to the project.

See [CONTRIBUTORS.md](https://github.com/kristophjunge/docker-mediawiki/blob/master/docs/CONTRIBUTORS.md) for the list of contributors.


## License

This project is licensed under the MIT license by Nurul Furqon R.