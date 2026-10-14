# SPARO

![license](https://img.shields.io/badge/license-MIT-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![category](https://img.shields.io/badge/category-social_media-lightgrey)

> Anticloud-hardened packaging of the upstream project `SPARO` in category **SOCIAL MEDIA**. Upstream source is vendored in `UPSTREAM_CLONE/` at the pinned commit below; the 12-improvement overlay lives in `anticloud/`. Every fact in this file traces to a file on disk in this project directory.

**Category:** SOCIAL MEDIA · **Upstream:** https://github.com/TikTok/sparo · **Upstream pin:** `ca06251a491699b020e0529903ba8a726ff135e2` · **Vendor:** Anticloud FZ LLE

---

## What This Project Does

<img width="380" src="./common/assets/sparo-380.png" alt="Sparo" />

## Monorepo for Sparo toolkit

<!-- Text below this line should stay in sync with the website index.md -->
<!-- ------------------------------------------------------------------ -->

**Sparo** optimizes performance of Git operations for your large frontend monorepo.

## Key features

- **Familiar interface:** The `sparo` command-line interface (CLI) wrapper offers **better defaults** and **performance suggestions** without altering the familiar `git` syntax. (The native `git` CLI is also supported.)
- **A proven solution:** Git provides [quite a lot of ingredients](./pages/guide/git_features.md) for optimizing very large projects; Sparo is your recipe for combining these features intelligently.
- **Simplified sparse checkout:** Work with sparse checkout [profiles](./pages/guide/sparo_profiles.md) instead of confusing "cones" and globs
- **Frontend integration:** Sparo leverages [Rush](https://rushjs.io/) and [PNPM](https://pnpm.io/) workspace configurations, including the ability to automatically checkout project dependencies
- **Dual workflows:** The `sparo-ci` tool implements a specialized checkout model optimized for continuous integration (CI) pipelines
- **Extra safeguards**: Avoid common Git mistakes such as checkouts with staged files outside the active view
- **Go beyond Git hooks:** Optionally collect anonymized Git timing metrics in your monorepo, enabling your build team to set data-driven goals for _local_ developer experience (not just CI!)

  _(Metrics are transmitted to your own service and are not accessible by any other party.)_

<!-- ------------------------------------------------------------------ -->
<!-- Text above this line should stay in sync with the website index.md -->

For details, consult the [Sparo documentation](./apps/sparo/README.md).

<!-- GENERATED PROJECT SUMMARY START -->

## Published Packages

<!-- the table below was generated using the ./project-scripts/project-toolbox script -->

| Folder | Version | Changelog | Package |
| ------ | ------- | --------- | ------- |
| [/apps/sparo](./apps/sparo/) | [![npm version](https://badge.fury.io/js/sparo.svg)](https://badge.fury.io/js/sparo) | [changelog](./apps/sparo/CHANGELOG.md) | [sparo](https://www.npmjs.com/package/sparo) |
| [/apps/sparo-lib](./apps/sparo-lib/) | [![npm version](https://badge.fury.io/js/sparo-lib.svg)](https://badge.fury.io/js/sparo-lib) | | [sparo-lib](https://www.npmjs.com/package/sparo-lib) |

## Unpublished Local Projects

<!-- the table below was generated using the ./project-scripts/project-toolbox script -->

| Folder | Description |
| ------ | -----------|
| [/apps/website](./apps/website/) | The Sparo documentation website |
| [/build-tests/sparo-output-test](./build-tests/sparo-output-test/) | Building this project tests Sparo command-line outputs |
| [/build-tests/sparo-real-project-test](./build-tests/sparo-real-project-test/) | Building this project tests Sparo by cloning a real project |
| [/build-tests/test-utilities](./build-tests/test-utilities/) | Code shared between the build test projects in this project |
<!-- GENERATED PROJECT SUMMARY END -->

## Contributing

Building the projects in this monorepo:

1. Install the [RushJS](https://rushjs.io/) tool:

   ```shell
   npm install -g @microsoft/rush
   ```

2. source the project:

   ```shell
   git source https://github.com/tiktok/sparo.git
   ```

3. Install the dependencies

   ```shell
   cd sparo
   rush install
   ```

4. Build all projects

   ```shell
   rush build
   ```

How to invoke your locally built `sparo` command:

```shell
cd apps/sparo
node lib/start.js
```

*Quoted from the upstream `README.md` file in `UPSTREAM_CLONE/`.*
Project-specific facts detected in this directory:

- Ecosystem: **Unknown (no standard manifest detected)** (manifests: none detected; scanned in UPSTREAM_CLONE)
- Top-level source layout: `apps/`, `build-tests/`, `common/`, `zsh-plugin/`
- Snapshot size: **234 files**, **7539 lines of code** (measured; see Benchmarks)
- Primary languages: `.txt` (66), `.ts` (49), `.json` (48), `(none)` (18), `.js` (17), `.md` (12)
- Upstream commit pinned for this packaging: `ca06251a491699b020e0529903ba8a726ff135e2`

---

## Installation

_(Metrics are transmitted to your own service and are not accessible by any other party.)_

<!-- ------------------------------------------------------------------ -->
<!-- Text above this line should stay in sync with the website index.md -->

For details, consult the [Sparo documentation](./apps/sparo/README.md).

<!-- GENERATED PROJECT SUMMARY START -->

*Section quoted from the upstream readme.*
Overlay install (this project):

```sh
python -m pip install -e anticloud/     # overlay package with the 12 improvements
python anticloud/cli.py --help          # 13 subcommands, JSON stdout
```

---

## Usage

No usage section was found in the upstream readme. Entry points detected in this project directory:

Browse the snapshot layout listed under What This Project Does and follow the upstream run instructions for the detected ecosystem (Unknown (no standard manifest detected)).

Anticloud overlay CLI (available in every project):

```sh
python anticloud/cli.py --help     # 13 subcommands, JSON stdout
python anticloud/cli.py checks     # run the 16-check suite
```

---

## API

- **A proven solution:** Git provides [quite a lot of ingredients](./pages/guide/git_features.md) for optimizing very large projects; Sparo is your recipe for combining these features intelligently.
- **Simplified sparse checkout:** Work with sparse checkout [profiles](./pages/guide/sparo_profiles.md) instead of confusing "cones" and globs
- **Frontend integration:** Sparo leverages [Rush](https://rushjs.io/) and [PNPM](https://pnpm.io/) workspace configurations, including the ability to automatically checkout project dependencies
- **Dual workflows:** The `sparo-ci` tool implements a specialized checkout model optimized for continuous integration (CI) pipelines
- **Extra safeguards**: Avoid common Git mistakes such as checkouts with staged files outside the active view
- **Go beyond Git hooks:** Optionally collect anonymized Git timing metrics in your monorepo, enabling your build team to set data-driven goals for _local_ developer experience (not just CI!)

  _(Metrics are transmitted to your own service and are not accessible by any other party.)_

<!-- ------------------------------------------------------------------ -->
<!-- Text above this line should stay in sync with the website index.md -->

For details, consult the [Sparo documentation](./apps/sparo/README.md).

<!-- GENERATED PROJECT SUMMARY START -->

*Section quoted from the upstream readme.*
---

## Dependencies

| Metric | Value |
|--------|-------|
| Ecosystem | Unknown (no standard manifest detected) |
| Manifests detected | none |
| Files in snapshot | 234 |
| Lines of code | 7539 |
| Dependency references | 86 |
| Dependencies by ecosystem | npm: 86 |
| Upstream license | MIT |
| Overlay license | Anticommons 0.1.0 |

Top dependency references recorded in the benchmark snapshot:

| Ecosystem | Name | Version | Source file |
|-----------|------|---------|-------------|
| npm | @rushstack/node-core-library | ~3.64.2 | apps/sparo/package.json |
| npm | sparo-lib | workspace:* | apps/sparo/package.json |
| npm | @rushstack/heft | 0.64.3 | apps/sparo/package.json |
| npm | @rushstack/heft-node-rig | 2.4.5 | apps/sparo/package.json |
| npm | @types/heft-jest | 1.0.6 | apps/sparo/package.json |
| npm | @types/node | 20.11.16 | apps/sparo/package.json |
| npm | eslint | 8.56.0 | apps/sparo/package.json |
| npm | typescript | ~5.3.3 | apps/sparo/package.json |
| npm | @rushstack/node-core-library | ~3.64.2 | apps/sparo-lib/package.json |
| npm | @rushstack/terminal | ~0.8.1 | apps/sparo-lib/package.json |
| npm | git-project-info | ~2.1.1 | apps/sparo-lib/package.json |
| npm | inversify | ~6.0.2 | apps/sparo-lib/package.json |
| npm | npm-package-arg | ~6.1.0 | apps/sparo-lib/package.json |
| npm | reflect-metadata | ~0.2.1 | apps/sparo-lib/package.json |
| npm | semver | ~7.6.0 | apps/sparo-lib/package.json |
| ... | (71 more) | | |

Pinned lockfile: `anticloud/requirements.lock` (hash-pinned, PEP 508). SBOM: `sbom.cdx.json` (CycloneDX 1.5, pinned to the upstream SHA).

---

## Configuration

- **Dual workflows:** The `sparo-ci` tool implements a specialized checkout model optimized for continuous integration (CI) pipelines
- **Extra safeguards**: Avoid common Git mistakes such as checkouts with staged files outside the active view
- **Go beyond Git hooks:** Optionally collect anonymized Git timing metrics in your monorepo, enabling your build team to set data-driven goals for _local_ developer experience (not just CI!)

  _(Metrics are transmitted to your own service and are not accessible by any other party.)_

<!-- ------------------------------------------------------------------ -->
<!-- Text above this line should stay in sync with the website index.md -->

For details, consult the [Sparo documentation](./apps/sparo/README.md).

<!-- GENERATED PROJECT SUMMARY START -->

*Section quoted from the upstream readme.*
Overlay configuration (Anticloud):

- `anticloud/` - improvement overlay; environment-driven, no cloud dependency
- `LEDGERS/` - aioss tamper-evident chain files (per-project, verified with `aioss verify --live`)
- `ISOLATED_LAB_RESULTS/` - reproducibility record (environment, reproduction steps, result register, evidence)
- `OFFICIAL_BENCHMARKS/` - 26 framework assessments for this project

---

## Contributing

Upstream contributions: fork the `SPARO` project, create a feature branch, and open a pull request against upstream. Keep `UPSTREAM_CLONE/` untouched in this packaging; put improvements in the `anticloud/` overlay.

Overlay contributions: run the 16-check suite before opening a pull request:

```sh
python anticloud/bench/runner.py --cwd anticloud
```

---

## License

**Upstream license: MIT** (evidence: `LICENSE` in the upstream snapshot).

License file excerpt:

```text
MIT License

Copyright (c) TikTok Pte. Ltd.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
```

### Anticommons 0.1.0 overlay

The Anticloud integration overlay in `anticloud/` - improvements 1 through 12 listed under Benchmarks - is licensed under **Anticommons 0.1.0**. Upstream code remains under its original MIT terms. See `ANTICOMMONS_LICENSE.md` in this directory for the overlay terms and contact.

SPDX: `MIT` (upstream) + Anticommons 0.1.0 (overlay, dual).

---

## Upstream

- **Project:** `SPARO` (category: SOCIAL MEDIA)
- **Upstream URL:** https://github.com/TikTok/sparo
- **Pinned commit (SHA):** `ca06251a491699b020e0529903ba8a726ff135e2`
- **Branch:** main
- **Pin provenance:** resolved during the second documentation pass. The parent-project stamp is explicitly rejected for this project.
- **Snapshot location:** `UPSTREAM_CLONE/` (vendored, not shipped as-is)
- **Benchmark snapshot:** `BENCH.json`

---

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`90c23f58c88b0d36de0ea96ece3f0149d4c64ca5936f47dd030a1273701702be`.

| Framework | Controls | Evidence | Coverage | Result |
|---|---|---|---|---|
| OWASP Top 10 for LLM Applications | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| OWASP Top 10 (2021) | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| SOC 2 Type II readiness | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| NIST AI Risk Management Framework | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| NIST SP 800-53 Rev. 5 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| NIST Cybersecurity Framework 2.0 | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| FedRAMP Rev. 5 | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| PCI DSS v4.0.1 | 11 controls mapped | 11 with evidence | 100.0% | PASS |
| ISO/IEC 27001:2022 | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| MITRE ATT&CK v16 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| ML Technology Readiness Level | TRL 8 | 8/8 criteria | | PASS |

**Overall: 16/16 checks passing.**

See `ISOLATED_LAB_RESULTS/03_Result_Register.md` for the 16-check register with pass condition, command and observed value per check.

Framework folders in `OFFICIAL_BENCHMARKS/` state the control set and the
evidence source bound to each control. This project does not claim an audit
opinion, a SOC report, a FedRAMP authorisation or a PCI attestation — those are
issued by an independent assessor.



## Archives and Permanent Records

| Platform | Identifier | Volume |
|---|---|---|
| Harvard Dataverse | DOI 10.7910/DVN/YMJKOG | 145 citable datasets |
| AIOSS verification kit | DOI 10.7910/DVN/OORKNJ | Offline hash verification |
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe and Mail, Business Insider, National Post, Financial Post, StreetInsider, Digital Journal, Barchart, International Business Times, and fox47 · National Law Review.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.

