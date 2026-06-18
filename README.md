# Mystic Sea Online Patches

This repository hosts launcher patch manifests and patch payloads.

The launcher reads `manifest/current.xml`, compares its version to the local
`Client/local_version.txt`, then downloads and verifies each file listed in the
manifest.

The production baseline is `1.0.0` with no payload files. The first real
production patch should use `1.0.1`.

Do not use GitHub `blob` page URLs in manifests. Use raw GitHub URLs, Vercel
redirect URLs, or GitHub release asset download URLs.
