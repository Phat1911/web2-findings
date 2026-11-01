# web2-findings

Developing web2 offensive-security skills: reproducing vulnerabilities with minimal PoCs, and documenting **root cause / impact / remediation** — same discipline as [Codehawk-findings](https://github.com/Phat1911/Codehawk-findings), new attack surface.

> Context: I spent ~10 months auditing smart contracts (build → audit → repeat). This repo is the web2 chapter of the same journey. Labs are mostly [PortSwigger Web Security Academy](https://portswigger.net/web-security); anything marked `TARGET` is from an authorized program's scope.

## Structure

```
findings/     one markdown file per vulnerability class or notable lab chain
journal/      daily log: labs solved, stuck log, weird behaviors worth revisiting
resources.md  curated links I actually use
TEMPLATE.md   finding template
```

## Progress

| Phase | Window | Focus | Status |
|---|---|---|---|
| 1 — Foundations | 15 Nov – 5 Dec 2026 | PortSwigger Apprentice: server-side, client-side, access control, auth, APIs | ☐ |
| 2 — Depth | 6 Dec 2026 – 2 Jan 2027 | Practitioner tracks, tools, HTB University CTF, first recon | ☐ |
| 3 — Hunt & apply | 3 – 31 Jan 2027 | Bug bounty, writeups, applications | ☐ |

## Vulnerability classes covered

<!-- update as findings land -->
| Class | Finding count | Notes |
|---|---|---|
| SQL injection | 0 | |
| XSS (reflected/stored/DOM) | 0 | |
| Access control / IDOR | 0 | |
| SSRF | 0 | |
| Auth (JWT/OAuth/session) | 0 | |
| Race conditions | 0 | |
| Prototype pollution | 0 | |

## Rules I hold myself to

1. Everything learned → one public artifact.
2. Root cause / impact / remediation, in English, every time.
3. Never test outside authorized scope.
