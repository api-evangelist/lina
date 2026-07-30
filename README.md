# Lina

Lina is a medical coworking company providing space, community, and support for independent healthcare practitioners in private practice. Founded by Vicrum Puri and Rachel Puri, Lina offers turnkey private office suites alongside on-demand medical, therapy, and bodywork spaces that are HIPAA and OSHA compliant and bookable by the hour or by the day.

Locations operate in NoMad and Grand Central in New York City and Aventura, Florida, with expansion announced for Washington DC, West Palm Beach, the Upper West Side, and Brooklyn.

Backed by: bloomberg-beta — https://lina.co/

## API surface

As of the 2026-07-19 enrichment pass, Lina publishes **no public API**, developer portal, OpenAPI definition, SDK, CLI, webhook surface, or `/.well-known/` discovery documents. The site is a Webflow marketing property. Artifacts in this repo are limited to identity, a generated `llms.txt`, and live probe results.

## Artifacts

- `apis.yml` — APIs.json 0.20 profile
- `llms/lina-llms.txt` — generated llms.txt
- `security/lina-domain-security.yml` — probed TLS/HSTS/DNS posture
- `well-known/lina-well-known.yml` — probed `/.well-known/` surface (all 404)
