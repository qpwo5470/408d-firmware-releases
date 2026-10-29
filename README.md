# 408D firmware releases

Public distribution assets and installation index. Original source repository visibility is unchanged. CUP and syrup packages intentionally contain approved Python/HTML runtime source.

Index: [firmware-index.json](firmware-index.json). Schema version 1. Each release entry binds an HTTPS manifest URL, size and SHA256 to an artifact URL. Original source repository and commit describe provenance, not the public download location. Ice-control manifests include `control_metadata` with the exact variant and original published binary hash.

Development prereleases; installation and hardware validation are separate. CUP 2MB blank-board runtime UF2 is not supplied. Gateway is pending a public-safe provisioning build; no fallback to previous private gateway binaries is provided.

Ice-control 1.4.8 files preserve original binaries whose build provenance is `81cb1a3-dirty`; the publication tag commit is not proof of a reproduced build. Its bootloader UF2 is a separate factory provisioning asset, not an application OTA payload.
