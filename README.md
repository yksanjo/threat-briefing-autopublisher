# Threat Briefing Autopublisher

Publish daily threat briefs from trusted intel and internal telemetry.

## Priority Metadata

- ID: 114
- Domain: security-agent
- TTE (days): 2
- Exposure score: 9/10
- Wave: 1
- Priority score: 8.60

## Phase-1 Build

1. Risk/exposure assessment API.
2. Deterministic launch planning endpoint.
3. Domain-tailored threat and rollout docs.
4. CI test gate and local runnable service.
5. Spatial 3D starter (for spatial projects).

## Run

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -e .[dev]
make test
make run
```
