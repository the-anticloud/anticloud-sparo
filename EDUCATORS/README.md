# Educators — SPARO

**Project:** SPARO  
**Category:** SOCIAL_MEDIA  
**Upstream:** https://github.com/TikTok/sparo  
**Pinned commit:** `ca06251a491699b020e0529903ba8a726ff135e2`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `3ea2a65e0dc7407a073d6c60d3edbe439b044ad6b2b978411f6e8fb8e193a2ce`  
**Date:** October 2026

## Teaching with SPARO

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `3ea2a65e0dc7407a073d6c60d3edbe439b044ad6b2b978411f6e8fb8e193a2ce` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
