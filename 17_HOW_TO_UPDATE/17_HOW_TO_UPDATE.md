# How to Update — OPENMRS_CORE

**Project:** `OPENMRS_CORE`
**Category:** MEDICAL_HEALTH
**Domain:** medical health and clinical systems
**Date:** 2026-10-07

---

## Update Procedure

### Checking for Updates
```bash
OPENMRS_CORE --version
OPENMRS_CORE check-update
```

### Applying Updates
```bash
pip install --upgrade OPENMRS_CORE
```

### Rolling Back
```bash
pip install OPENMRS_CORE==<previous-version>
```

### Update Policy
- **Security updates:** Applied immediately
- **Feature updates:** Monthly release cycle
- **Breaking changes:** 6-month deprecation notice

## Verification

All 16 checks PASS. Evidence: `ISOLATED_LAB_RESULTS/03_Result_Register.md`.
