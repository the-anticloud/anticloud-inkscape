# Educators — INKSCAPE

**Project:** INKSCAPE  
**Category:** DESIGN_TOOLS  
**Upstream:** see BENCH.json  
**Pinned commit:** `1232eac68aff12978b208ff3ebfbbcc3ecbd7022`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `85d473decb1dfd39f1a31333497d052a60433ab98b436753b1bc200fe06a9838`  
**Date:** October 2026

## Teaching with INKSCAPE

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `85d473decb1dfd39f1a31333497d052a60433ab98b436753b1bc200fe06a9838` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
