# domaindex.io — Bulk Domain Availability Checker

**[domaindex.io](https://domaindex.io)** — type a keyword, instantly check its availability across hundreds of TLDs in parallel. Powered by RDAP. No account. No tracking.

---

## What It Does

Enter any keyword (letters, digits, hyphens). domaindex fires up to **30 parallel RDAP queries** across your selected TLD list and streams results back as they resolve — you see available domains appear in real time, not after the slowest registry responds.

```
keyword: claude

claude.com   → taken    (registered 1998-09-15)
claude.io    → available ✓
claude.ai    → taken    (registered 2021-03-10)
claude.dev   → available ✓
claude.app   → taken
...
```

## Features

### Parallel RDAP Queries
Up to 30 RDAP requests run concurrently. Results appear as they land — gTLDs and ccTLDs resolve at their own pace, you are never waiting on the slowest registry.

### Broad TLD Coverage
Check availability across **gTLDs** (`.com`, `.net`, `.org`, `.io`, `.ai`, `.app`, `.dev`…), **ccTLDs** (`.co`, `.me`, `.so`…), and **IDN suffixes**. The TLD list is sourced from the IANA RDAP bootstrap registry.

### Shareable Queries
Your keyword and selected TLDs are encoded in the URL. Paste the link anywhere — the recipient lands directly on the same search, no setup needed.

### Custom TLD Selection
Build your own suffix set from the full TLD list. Your selection is saved locally in the browser — no account required.

### One-Click Registrar Handoff
Available domains link directly to **Namecheap**, **Porkbun**, and **GoDaddy**. No copy-paste detour between tools.

### Domain Detail Panel
Click any result to see registrar, registration date, expiration date, and direct purchase links — all pulled from live RDAP data.

### No Account Required
Zero sign-up. Zero telemetry. Zero dark patterns. Every query is stateless and runs directly against public RDAP endpoints.

## Use Cases

- **Founders** searching for a brand name across `.com`, `.io`, `.ai` simultaneously
- **Developers** checking if a project name is available before committing to it
- **Domain investors** scanning a keyword across dozens of TLDs at once
- **Agencies** doing quick availability checks during naming sprints

## How It Works

1. Enter a keyword and select your TLDs
2. The browser fires parallel requests to the domaindex API
3. Each query is proxied server-side to the correct RDAP endpoint (looked up from the IANA bootstrap registry — clients never supply URLs directly)
4. Results stream back and render as they resolve

RDAP (Registration Data Access Protocol) is the modern, structured replacement for WHOIS — machine-readable JSON, no scraping, no rate-limit guessing.

## Privacy

- No user accounts, no cookies, no analytics
- Queries are not logged or stored
- TLD preferences are saved in `localStorage` only — never sent to any server

---

> domaindex.io is a hosted web service. The source code is not publicly available.

**Try it:** [domaindex.io](https://domaindex.io)
