# Students — NEURODECODE

**Project:** NEURODECODE  
**Category:** BRAIN_COMPUTER_INTERFACE  
**Upstream:** see BENCH.json  
**Pinned commit:** `4e3be772f557b07ea8d4e220b1e3fe5e60d883cb`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `3c463961e5480b3a3956a4d4127e7da45189541765e33a5c6ce31101abc213ff`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `4e3be772f557b07ea8d4e220b1e3fe5e60d883cb`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `3c463961e5480b3a3956a4d4127e7da45189541765e33a5c6ce31101abc213ff`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
