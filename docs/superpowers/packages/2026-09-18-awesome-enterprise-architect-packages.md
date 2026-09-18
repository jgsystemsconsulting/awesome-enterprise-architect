---
date: 2026-09-18
project: awesome-enterprise-architect
mode: light
rounds: 1
open_objections: []
---

# Work packages: awesome-enterprise-architect (2026-09-18)

Path S Pages landing and release gate, matching awesome-archimate. Packages implemented in one drain on branch feat/pages-landing-and-packages.

## P2: landing-truth-gate

| Field | Value |
|---|---|
| id | P2 |
| name | landing-truth-gate |
| size | M |
| deps | none |
| status | done |
| first_prompt | landing truth gate |

**Problem.** Version, sweep, and entry chips and section-index anchors must match RELEASE-INFO and README or Pages desyncs silently.

**In scope.** scripts/check_release.py landing assertions; validate.yml runs the gate.

**Status.** done: check_release.py PASS with 7 curated sections and chips 0.1.0 / 2026-09 / 61.

## P1: landing-visitor-copy

| Field | Value |
|---|---|
| id | P1 |
| name | landing-visitor-copy |
| size | S |
| deps | P2 |
| status | done |

**Problem.** Visitor-facing landing copy and chrome (favicon E, woff2 preload, sticky nav, one primary CTA).

**Status.** done: docs/index.html Path S shell from ArchiMate contract, Sparx product claim, no maintainer jargon.

## P3: org-catalogue-entry

| Field | Value |
|---|---|
| id | P3 |
| name | org-catalogue-entry |
| size | S |
| deps | P1 |
| status | ready |

**Problem.** Labs products.yml entry when policy allows private or public list.

**Status.** ready: DISTRIBUTION planned; implement when website branch cut (may be same session if website clone present).

## P4: awesome-acceptability-assessment

| Field | Value |
|---|---|
| id | P4 |
| name | awesome-acceptability-assessment |
| size | S |
| deps | P1 |
| status | done |

**Problem.** sindresorhus/awesome go/no-go assessment only.

**Status.** done: assessment doc; no PR opened (private + prerequisites).

## P5: link-check-product-surface

| Field | Value |
|---|---|
| id | P5 |
| name | link-check-product-surface |
| size | S |
| deps | P2 |
| status | done |

**Problem.** lychee must cover README.md and docs/index.html; PR fails on broken product-surface links; action SHA pins.

**Status.** done: links.yml + validate.yml SHA-pinned from ArchiMate gold.

## P6: pin-validate-setup-python

| Field | Value |
|---|---|
| id | P6 |
| name | pin-validate-setup-python |
| size | S |
| deps | none |
| status | done |

**Status.** done: setup-python full SHA in validate.yml (copied from ArchiMate).
