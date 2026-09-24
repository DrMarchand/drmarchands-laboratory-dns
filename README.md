# DrMarchand’s Laboratory - DNS Reference

> A minimal public repository coordinate for Laboratory and Design Orchard DNS-related documentation.

**Repository coordinate:** `DrMarchand/drmarchands-laboratory-dns`

This repository must remain intentionally small. Public DNS documentation may describe release-safe domain purpose and routing relationships, but it must not contain credentials, origin secrets, private host inventories, authentication material, internal-only records, or unpublished infrastructure topology.

## Boundary

- **Legal and operating company:** Design Orchard LLC
- **Operating DBA:** DrMarchand’s Laboratory
- **Protected environment:** 🔬 DrMarchand’s Lab⚛︎ratory™

## Design Orchard Atlas domain roles

- `atlas.designorchard.net` — canonical identity for 🌎 Design Orchard Atlas™.
- `server.designorchard.net` — state source read by the Atlas instruction layer.
- Relationship: `atlas.designorchard.net --reads_state_from--> server.designorchard.net`.

These declarations identify purpose and relationship; they are not proof that DNS, TLS, hosting, or runtime state is currently active. Atlas instructions remain ⬛ BLACK until verified server binding is active, and the server state remains □👁️‍🗨️ UNKNOWN until it is read and validated.

Operational DNS changes are validated outside this README. Repository text is documentation, not proof of current DNS state.

See [`RIGHTS.md`](RIGHTS.md) for repository rights information.
