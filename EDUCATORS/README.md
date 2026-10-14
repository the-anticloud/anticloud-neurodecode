# Educators — NEURODECODE

**Project:** NEURODECODE  
**Category:** BRAIN_COMPUTER_INTERFACE  
**Upstream:** see BENCH.json  
**Pinned commit:** `4e3be772f557b07ea8d4e220b1e3fe5e60d883cb`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `3c463961e5480b3a3956a4d4127e7da45189541765e33a5c6ce31101abc213ff`  
**Date:** October 2026

## Teaching with NEURODECODE

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `3c463961e5480b3a3956a4d4127e7da45189541765e33a5c6ce31101abc213ff` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
