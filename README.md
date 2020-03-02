# Docker & Symfony

[![Docker Stars](https://img.shields.io/docker/stars/solune/symfony-yarn.svg?style=flat)](https://hub.docker.com/r/solune/symfony-yarn/)
[![Docker Pulls](https://img.shields.io/docker/pulls/solune/symfony-yarn.svg?style=flat)](https://hub.docker.com/r/solune/symfony-yarn/)

PHP CLI based Docker image with all the minimum requirements for a Symfony project with Webpack Encore.

*Warning: You must mount a directory to `/srv` to make the entrypoint work (it use the host user to match www-data user).*
