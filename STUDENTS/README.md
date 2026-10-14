# Students — INKSCAPE

**Project:** INKSCAPE  
**Category:** DESIGN_TOOLS  
**Upstream:** see BENCH.json  
**Pinned commit:** `1232eac68aff12978b208ff3ebfbbcc3ecbd7022`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `85d473decb1dfd39f1a31333497d052a60433ab98b436753b1bc200fe06a9838`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `1232eac68aff12978b208ff3ebfbbcc3ecbd7022`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `85d473decb1dfd39f1a31333497d052a60433ab98b436753b1bc200fe06a9838`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
