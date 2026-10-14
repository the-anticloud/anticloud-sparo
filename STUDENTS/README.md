# Students — SPARO

**Project:** SPARO  
**Category:** SOCIAL_MEDIA  
**Upstream:** https://github.com/TikTok/sparo  
**Pinned commit:** `ca06251a491699b020e0529903ba8a726ff135e2`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `3ea2a65e0dc7407a073d6c60d3edbe439b044ad6b2b978411f6e8fb8e193a2ce`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `ca06251a491699b020e0529903ba8a726ff135e2`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `3ea2a65e0dc7407a073d6c60d3edbe439b044ad6b2b978411f6e8fb8e193a2ce`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
