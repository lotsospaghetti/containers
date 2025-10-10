# quadlets

My `podman-systemd` service units are in this directory. These need to be placed in `$HOME/.config/containers/systemd/` to work.

More info about Podman Quadlets: https://docs.podman.io/en/stable/markdown/podman-systemd.unit.5.html

## non-rootful containers

- [jellyfin.container](jellyfin.container): `jellyfin:latest` with `/dev/dri` passed through for hardware acceleration
