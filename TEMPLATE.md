# [VULN CLASS] — [one-line what breaks]

- **Lab/Target:** `APPRENTICE|PRACTITIONER|CTF|TARGET:<program>` — <name + link if public>
- **Date:** YYYY-MM-DD
- **Difficulty reset test:** re-solved from memory on YYYY-MM-DD? (Y/n)

## Summary

One paragraph: what the bug is, where, and what an attacker gains.

## Root cause

Why the code/config allows this. Where applicable, the *class* of mistake — this is the transferable part.

## PoC

Minimal reproduction. Requests as raw HTTP, payloads typed not pasted.

```http
GET /example?param=<payload> HTTP/1.1
Host: ...
```

## Impact

What an attacker achieves, constrained and realistic (not "full server takeover" for a reflected XSS on a 404 page).

## Remediation

How to fix, in the language/framework of the target where possible.

## Web3 mirror (optional)

The equivalent bug class I already know from smart-contract auditing — e.g. *IDOR ≈ missing `require(msg.sender == owner)`*, *race condition ≈ reentrancy without checks-effects-interactions*.

## References

- Lab/tutorial/docs links
