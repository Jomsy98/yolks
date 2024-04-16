# Images

This repository contains a bunch of images designed for use with Pterodactyl's egg system.  Each image is rebuilt
periodically to ensure dependencies are always up-to-date.

Images are hosted on `ghcr.io`.

To use any of these images, use `ghcr.io/jomsy98/images:<IMAGE>`.

Any images ending with `-install` should only be used as a install image for running an install script, these images
will not work to run the actual server and are only designed to reduce installation time and network usage by
pre-installing common installation dependencies such as `curl` and `wget`.

This repo is cloned off of [matthewpi](https://github.com/matthewpi/images) and modified for my own hosting purposes.

## Available Images

### Games

- [`source`](https://github.com/jomsy98/images/tree/master/games/source)
  - Image specifically designed for running Source Engine servers.
  - Tags
    - `ghcr.io/jomsy98/images:source`
  - Supported Architectures
    - `linux/amd64`
