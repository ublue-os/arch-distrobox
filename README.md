# arch-distrobox

[![build-arch-distrobox](https://github.com/ublue-os/arch-distrobox/actions/workflows/build.yml/badge.svg)](https://github.com/ublue-os/arch-distrobox/actions/workflows/build.yml) 

Arch image designed for use in distrobox. This image includes all of the packages normally installed by distrobox on first start, [paru](https://github.com/Morganamilo/paru) pre-installed, and a modified [xdg-utils](https://github.com/KyleGospo/xdg-utils-distrobox-arch) that allows the container to open your host operating system's web browsers and file explorer.

## Verification

These images are signed with sisgstore's [cosign](https://docs.sigstore.dev/cosign/overview/). You can verify the signature by downloading the `cosign.pub` key from this repo and running the following command:

    cosign verify --key cosign.pub ghcr.io/ublue-os/arch-distrobox
