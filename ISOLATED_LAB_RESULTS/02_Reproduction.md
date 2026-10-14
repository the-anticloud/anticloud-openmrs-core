# Reproduction — OPENMRS_CORE

1. Environment: Windows, Python 3.12.10, runner version 1.0.0
2. `cd anticloud/`
3. `python tools\run_bench.py --quiet`  (exit 0 = all 16 PASS)
4. Compare `anticloud/BENCH.json` SHA3-256: `902341818c8a9bc4ed20bb1b2e81a325305126c28a41675bd60baf64ae1e82d2`

The `anticloud/` overlay is a standalone copy of the anticloud_reference tree; the 16 checks run against it via `tools/run_bench.py`.
