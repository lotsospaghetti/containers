# distroboxes

All my `distrobox-assemble` files are in this directory.

More info about distrobox: https://distrobox.it/

## non-rootful containers

- [libreboot-build.ini](libreboot-build.ini): `debian:stable` with dependencies and configuration for building [Libreboot](https://libreboot.org/) from source
- [website-tools.ini](website-tools.ini): [Wolfi OS](https://github.com/wolfi-dev) (`cgr.dev/chainguard/wolfi-base:latest`, specifically) with `npm`, `neocities` and `darkhttpd` binaries for testing and deploying [my website](https://lotsaspaghetti.com)
- [renoise-amd64.ini](renoise-amd64.ini): `debian-toolbox:stable` which installs [Renoise](https://www.renoise.com/) from a provided gzip archive. See assemble file for important details!
- [renoise-arm64.ini](renoise-arm64.ini): Just a copy of the other Renoise assemble file with several things renamed to make the ARM version (hopefully) work.

## rootful containers

- [rootful-kali.ini](rootful-kali.ini): Just `kali-rolling` with headless packages auto-installed
- [rootful-nmap.ini](rootful-nmap.ini): `wolfi-base:latest` with `nmap` and `nmap-doc`, the former is an exported binary and the latter is accessible via `distrobox enter --root kali -- man nmap`
