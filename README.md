# sericea

My (very experimental) OCI image derived from [Fedora Sericea 38](https://docs.fedoraproject.org/en-US/fedora-sericea/)

## Changes from stock Sericea

* Ships with `podman-compose`
* Removes native Firefox from the base image
* Sets automatic weekly system upgrades
* Automatic weekly updates for user-installed flatpaks (disabled by default)