# Obsidian (obsidian)

Obsidian is a local-first knowledge base and note-taking app built on plain Markdown files. Obsidian Inc. does not publish a hosted SaaS API; programmatic access is provided through the in-app Plugin API (TypeScript) and the community-built Local REST API plugin that exposes vault operations over localhost HTTPS.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/obsidian/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=obsidian-api-evangelist&utm_content=repo)

## Type

- **x-type:** company

## Tags:

 - Productivity, Knowledge Management, Markdown, Notes, Local-First

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## Notes on API Surface

Obsidian is local-first software. There is **no public hosted REST API** from Obsidian Inc. The "API" surface consists of:

1. **Obsidian Plugin API** — an in-process TypeScript SDK used by community plugins.
2. **Obsidian Local REST API** — a community plugin (`coddingtonbear/obsidian-local-rest-api`) that exposes vault operations on `https://127.0.0.1:27124` for use by browser extensions, scripts, and AI agents.
3. **Obsidian Sync / Obsidian Publish** — paid managed add-ons accessed only through the Obsidian client; no public API.

## APIs

| API | Description |
|---|---|
| Obsidian Plugin API | In-process TypeScript SDK for building Obsidian plugins. |
| Obsidian Local REST API | Localhost HTTPS API (port 27124) for vault, active file, periodic notes, search, commands, tags, and file opening (community plugin). |
| Obsidian Sync | Managed cross-device sync with E2E encryption (paid add-on; no public API). |
| Obsidian Publish | Managed website publishing (paid add-on; no public API). |

## Common Properties

- [Website](https://obsidian.md/)
- [Documentation](https://docs.obsidian.md/Home)
- [Pricing](https://obsidian.md/pricing)
- [GitHub](https://github.com/obsidianmd)
- [Plans](plans/obsidian-plans-pricing.yml) — API Commons Plans 0.1
- [RateLimits](rate-limits/obsidian-rate-limits.yml) — API Commons Rate Limits 0.1
- [FinOps](finops/obsidian-finops.yml) — FOCUS-aligned FinOps Framework 1.0

## Artifacts

| Artifact | Path | Notes |
|---|---|---|
| Plans | `plans/obsidian-plans-pricing.yml` | Personal (free) / Commercial $50/yr / Catalyst $25 / Sync $4-5/user/mo / Publish $8-10/site/mo |
| Rate Limits | `rate-limits/obsidian-rate-limits.yml` | No remote API rate limits — local-first; bounded by device |
| FinOps | `finops/obsidian-finops.yml` | Subscription (add-ons) + one-time license model |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
