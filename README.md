# Nebula Photos — signed update manifests

`manifest.json` pins the exact Immich image digests Nebula Photos appliances
are allowed to update to. It is signed with the vendor's minisign key
(`manifest.json.minisig`); appliances verify the signature against their
baked-in public key and refuse anything else. Published only after the
release has been tested on reference hardware.
