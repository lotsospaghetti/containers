# distroboxes

All my `distrobox-assemble` files are in this directory.

More info about distrobox: https://distrobox.it/

## non-rootful containers

- [libreboot-build.ini](libreboot-build.ini): `debian:stable` with dependencies and configuration for building [Libreboot](https://libreboot.org/) from source
- [website-tools.ini](website-tools.ini): [Wolfi OS](https://github.com/wolfi-dev) (`cgr.dev/chainguard/wolfi-base:latest`, specifically) with `npm`, `neocities` and `darkhttpd` binaries for testing and deploying [my website](https://lotsaspaghetti.com)

## rootful containers

- [rootful-kali.ini](rootful-kali.ini): Just `kali-rolling` with headless packages auto-installed
