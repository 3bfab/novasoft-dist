# novasoft-dist

NovaSoft update channel. Machines read `latest.json` from a branch; the binary is a release asset of this repo.

| Branch | Channel |
|---|---|
| `main` | customer releases (machines on api.3bfab.com) |
| `beta` | pre-releases (machines on apidev / a local dev API) |

Every `latest.json` is signed (Ed25519); machines refuse unsigned manifests. Published only by NovaSoft's `scripts/publish_update.py` / Release workflow - do not edit by hand.
