# TeeChat golden digests (public)

**Public trust root** for Golden Image TEE / image digests (OpenAPI, Gateway, Engine).

- Design: see TeeChat `docs/design/golden-digests-publish.md`
- **No image blobs** — digests JSON only
- App binary hashes stay on component GitHub Releases (`teechat-openapi`, InferenceEngine, …)

## Assets

| File | Meaning |
|------|---------|
| `golden-digests.json` | Multi-role allowlist (`teechat-golden-digests-manifest/v1`) |
| `SHA256SUMS` | Digest of the JSON asset(s) |

Cadence: publish a Release **only when promoting a new golden image**, not on every app tag.
