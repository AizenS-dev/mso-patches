# Mystic Sea Online Patches

This repository hosts launcher patch manifests and patch payloads.

The launcher reads `manifest/current.xml`, compares its version to the local
`Client/local_version.txt`, then downloads and verifies each file listed in the
manifest.

Do not use GitHub `blob` page URLs in manifests. Use raw GitHub URLs, Vercel
redirect URLs, or GitHub release asset download URLs.
