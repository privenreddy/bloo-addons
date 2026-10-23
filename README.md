# bloo add-ons

Optional add-on packs for bloo. Downloaded by the app only when you ask.

Each pack is a GitHub release here with a `manifest.json` and its Ed25519 signature
(`manifest.json.sig`). The app checks the signature with the key built into it, then checks each
download's size and SHA-256 against the signed manifest before using it.

| Pack | What it is | Licence |
| --- | --- | --- |
| `formats` | [Filee](https://github.com/KnifeLemon/Filee)'s own release files, unchanged | MIT (see THIRD_PARTY_NOTICES.md) |
