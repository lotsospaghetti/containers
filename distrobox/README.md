# distroboxes

All my `distrobox-assemble` files are in this directory.

More info about distrobox: https://distrobox.it/

## non-rootful containers

- [libreboot-build.ini](libreboot-build.ini): `debian:stable` with dependencies and configuration for building [Libreboot](https://libreboot.org/) from source
- [website.ini](website.ini): Two [Wolfi OS](https://github.com/wolfi-dev) (`cgr.dev/chainguard/wolfi-base:latest`) containers; one with `npm` and `neocities` binaries for deploying [my website](https://lotsaspaghetti.com) and another with `lighttpd` as an extremely basic way to serve my site to other local devices for testing

## rootful containers

- [rootful-kali.ini](rootful-kali.ini): Just `kali-rolling` with headless packages auto-installed
