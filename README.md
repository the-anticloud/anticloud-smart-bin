# SMART_BIN

> This directory contains the full 30-folder standard documentation set for `SMART_BIN`:

**Category:** WASTE_MANAGEMENT · **Ecosystem:** unknown · **Vendored upstream:** https://github.com/tlkh/SmartBin · **Pinned commit:** `134eee02795dd9bd5936846c261283070c7b062e` · **Vendor:** Anticloud FZ LLE

> **Note:** this package vendors `https://github.com/tlkh/SmartBin` as the implementation for the `SMART_BIN` slot. The vendored repository name differs from the package name; the pin above is the exact commit vendored here.

## What This Project Is

This directory contains the full 30-folder standard documentation set for `SMART_BIN`:

This is the upstream project, vendored at the pinned commit above and packaged offline-first. The 12 improvements Anticloud adds live in `anticloud/` and are described under *Anticloud Overlay* below. Every fact in this file traces to a file in this directory.

## Installation

```
# See the upstream README (linked above) for build steps.
```

## Usage

See the upstream README (linked above) for usage. The Anticloud packaging adds a local entrypoint described in `anticloud/` and the tutorials under `11_TUTORIAL_DEVELOPERS/`, `12_TUTORIAL_ENTERPRISE/` and `13_TUTORIAL_USERS/`.

## Anticloud Overlay

The 12 improvements live under `anticloud/`. Run the check suite from this directory:

```
python anticloud/bench/runner.py --cwd anticloud
```

## Benchmark Results

The suite is recorded in `BENCH.json`; no benchmark rows were found in this package.

## Licence

The upstream licence is preserved in `LICENSE` and `THIRD_PARTY_LICENSES/`. The Anticloud overlay is licensed under Anticommons 0.1.0 (`ANTICOMMONS_LICENSE.md`).

## Verification

SHA3-256 of `BENCH.json`:

```
f887566a6b19f7ad32a4efdf7995fe363fa1698b3df0a55c07ce685f5f9f3b06
```

Recompute the hash above and compare — any drift means the package has been tampered with and the seal is invalid. This is a self-assessment; no external audit has been performed and a SOC 2 / NIST independent audit is committed post-funding.
