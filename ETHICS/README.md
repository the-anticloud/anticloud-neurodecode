# Ethics — NEURODECODE

**Project:** NEURODECODE  
**Category:** BRAIN_COMPUTER_INTERFACE  
**Upstream:** see BENCH.json  
**Pinned commit:** `4e3be772f557b07ea8d4e220b1e3fe5e60d883cb`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `3c463961e5480b3a3956a4d4127e7da45189541765e33a5c6ce31101abc213ff`  
**Date:** October 2026

## Position

NEURODECODE is packaged for offline deployment with a verifiable audit trail. The
ethical questions this raises are answered by making the system's behaviour
checkable rather than by policy statements.

## The four commitments

1. **No hidden egress.** The deployment has no external API dependency; this is
   testable by running it with the network disconnected.
2. **Attributable output.** Every artifact is recorded in a hash chain, so what
   the system produced can be reconstructed.
3. **Operator control.** The institution owns the hardware and the keys.
4. **Refusal to overclaim.** Where a certification is not held, the project says
   so rather than implying it.

## Dual use

This project is packaged for civilian and public-sector deployment. Where an
upstream has dual-use characteristics, the licence gate and the reference-only
marking in `BENCH.json` record that.
