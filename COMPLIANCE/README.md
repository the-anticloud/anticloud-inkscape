# Compliance — INKSCAPE

**Project:** INKSCAPE  
**Category:** DESIGN_TOOLS  
**Upstream:** see BENCH.json  
**Pinned commit:** `1232eac68aff12978b208ff3ebfbbcc3ecbd7022`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `85d473decb1dfd39f1a31333497d052a60433ab98b436753b1bc200fe06a9838`  
**Date:** October 2026

## Position

INKSCAPE is mapped against eleven frameworks in `BENCH.json`:
OWASP LLM Top 10, OWASP Top 10 (2021), SOC 2 Type II readiness, NIST AI RMF,
NIST SP 800-53 Rev. 5, NIST CSF 2.0, FedRAMP Rev. 5, PCI DSS v4.0.1,
ISO/IEC 27001:2022, MITRE ATT&CK v16, and ML TRL.

**Current result: 16/16 checks passing.**

## What the mapping asserts

For each framework, every in-scope control is bound to a named evidence source
in this project, and that source exists and is re-runnable. The control counts
and evidence counts are recorded per framework in `BENCH.json`.

## What is not claimed

No audit opinion, SOC report, FedRAMP authorisation, PCI attestation or ISO
certificate is held. Those are issued by an independent assessor against a
defined period of operation; no project can self-issue one. See
`OFFICIAL_BENCHMARKS/` for the per-framework scope statement.

## Verification

Open `ISOLATED_LAB_RESULTS/03_Result_Register.md`, read a row, recompute the
SHA3-256 of its evidence file in `04_Evidence/`, compare.
