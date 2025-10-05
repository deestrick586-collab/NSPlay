# Electric Secure Suite (8-Layer Starter Monorepo)

A practical starter kit to secure **every electric device** (edge/IoT, gateways, cloud) using an **8-layer defense**:
1) Auth & Identity, 2) Encryption, 3) Access Control, 4) Monitoring/Auditing,
5) Threat Detection, 6) Backup/Recovery hooks, 7) Policy Enforcement, 8) User Awareness (UI).

## Components
- `device_agent/` (Python): Lightweight edge agent for Linux-capable devices (e.g., Pi/routers).
- `gateway/` (Go): Proxies device traffic, caches/enforces policy, forwards telemetry.
- `control_plane/` (TypeScript/Node): Issues identities, stores policies, exposes APIs.
- `shared/` : Policy schema and helper assets.
- `docker-compose.yml`: Local dev wiring.

> This is a scaffold meant to run locally for demos. Harden, test, and adapt before production.
