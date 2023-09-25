# arch-distrobox

[![build-arch-distrobox](https://github.com/ublue-os/arch-distrobox/actions/workflows/build.yml/badge.svg)](https://github.com/ublue-os/arch-distrobox/actions/workflows/build.yml) 

Arch images designed for use in distrobox. These come with the bare minimum, but are pre-configured to use the host's xdg-open and come with paru preinstalled.

## Verification

These images are signed with sisgstore's [cosign](https://docs.sigstore.dev/cosign/overview/). You can verify the signature by downloading the `cosign.pub` key from this repo and running the following command:

    cosign verify --key cosign.pub ghcr.io/ublue-os/arch-distrobox
