# Contributing

Thanks for helping keep this the best-curated Sparx Systems Enterprise Architect
product index in the awesome-mbse family. Read this before opening a PR: the CI
gates enforce most of it.

The fastest path: open an issue describing the resource, or open a pull request
that edits `README.md` directly.

## 1. How to suggest a resource

- **Issue:** describe the resource and why it belongs. Good for "I found this, you decide."
- **PR:** edit `README.md`, follow the entry format below, tick the PR checklist. CI
  link-checks your entry and lints the list.

## 2. Inclusion bar

An entry is accepted only if **all** hold:

1. **On-topic** — genuinely about Sparx Systems Enterprise Architect product use
   (modeling with EA, automation, MDG, add-ins, Sparx-hosted frameworks). Not
   general "enterprise architecture" without Sparx product substance. Not
   ArchiMate-only material that belongs on awesome-archimate.
2. **Substantive** — it teaches, demonstrates, specifies, or provides something
   usable. Not a stub. Not pure vendor marketing splash pages.
3. **Live** — the link resolves right now.
4. **Not duplicative** — not already listed (see the canonical-URL rule, §6).
   Not a copy of an ArchiMate spoke entry.
5. **Legally linkable** — publicly accessible. We **link**, we never re-host
   model files, PDFs, or proprietary content.

Tie-breakers (nice-to-have, not gates): has a real openable model (`has-model`),
recently updated, from a recognized source (Sparx Systems, established add-in
authors, a university, an established practitioner).

## 3. Entry format

One line per entry, **hyphen separator** (` - `, never an en/em dash: awesome-lint
rejects those), tags as **inline code spans inside the sentence before the terminal
period**, year parenthesized as the last token:

```text
- [Resource Name](https://example.com) - One-line factual description `SysML-general` `Sparx-EA` `plugin` (2024).
```

- **Description:** factual, one line, **≤ 140 characters** (measured from the first
  character after ` - ` to the last character before the first tag, excluding the link
  markup and tags). No hype.
- **`has-model`** means: a **directly downloadable, non-paywalled** file in a
  recognized Sparx EA model format (`.eap`, `.eapx`, `.qea`) that opens in licensed
  Sparx EA (or a stated compatible tool). Screenshots, papers *describing* a model,
  and access-gated / "contact sales for model" files **do not** qualify.

## 4. Tag vocabulary, cardinality & order

Tags appear in this fixed order, drawn **only** from this vocabulary:

`language → method → tool → has-model → type → spec/standard → paid → year`

| Axis | Cardinality | Values |
| --- | --- | --- |
| language | exactly 1 | `SysML-general` (SysML via Sparx) · `UML` (UML-centric EA resources) · `BPMN` (BPMN in EA) · `other-lang` (graduate at 3+) · `EA-general` (product-wide or multi-notation resources; pick the dominant notation otherwise) |
| method | 0 or 1 | Omit until a named method has 3+ entries; then graduate a named tag. Do not invent method tags early |
| tool | 1 or more | Always include `Sparx-EA`. Add named add-in tags after graduating from `other-tool` at 3+ shared entries |
| has-model | 0 or 1 | `has-model` |
| type | exactly 1 (dominant form) | `tutorial` · `course` · `book` · `paper` · `blog` · `video` · `tool` · `plugin` · `docs` · `case-study` · `script` |
| spec/standard | 0 or 1 | `standard` (resource is primarily a standards mapping hosted for EA) |
| paid | 0 or 1 | `paid` |
| year | exactly 1 | `(YYYY)` (see §5) |

- `other-tool` graduates to its own tag only once ≥ 3 entries share it; update this
  table in the same change.
- For a normative standard document use `standard` and omit `paper`.

## 5. The year rule (`YYYY`)

`(YYYY)` = the year of the resource's **most recent author-published version**:

- a paper → its publication year;
- a repo → its latest tagged release, or the latest default-branch commit if untagged;
- a course → its current cohort year.

**Trivial edits (typo fixes) don't count.** Examples:

- A 2019 paper with a 2024 typo-fix commit → `(2019)`.
- A repo whose latest release tag is `v2.1` from 2023 → `(2023)`.

## 6. Canonical-URL rule (dedupe)

Before deciding "is this a duplicate", canonicalize both URLs: force `https`, lowercase
the host, strip a trailing slash, drop the query string and fragment unless they're
semantically required. If the canonical forms match, it's a duplicate.

Also check the public awesome-archimate README when that spoke is reachable: Sparx
product entries must not appear as full duplicates there and here. Cross-link only.

## 7. Editorial neutrality

This list is maintained by JG Systems Consulting Ltd., which sells commercial MBSE
consulting services. To keep it trustworthy:

- JGS-adjacent entries are listed by the **same inclusion bar** as everything else.
- Every JGS-adjacent entry sits next to **≥ 1 genuine competing/alternative entry**.
- **A superior competing resource is listed above a JGS-adjacent one.** Neutrality is
  enforced by this rule, not by tone.

> **Table of Contents:** the `## Contents` ToC is hand-maintained and lists only the
> top-level sections (a flat ToC keeps awesome-lint happy). If you add or rename a
> **top-level** section, update the ToC by hand; sub-sections are not listed. CI
> validates every ToC anchor resolves (lychee `--include-fragments anchor-only`).

## 8. Local link-check

No install needed. Check your changed links with Docker:

```sh
docker run --rm -v "$PWD:/d" -w /d lycheeverse/lychee --include-fragments anchor-only README.md
```

Or open a **draft PR** and let CI check it for you.

## 9. Maintenance cadence

The maintainers run a **quarterly sweep** (add new resources, prune rot), logged in
`CHANGELOG.md` with the date, and update the *Last full sweep* badge at the top of the
README each time. If it's been **> 6 months** since the last sweep, the badge flips to
"maintenance lapsed"; call it out in an issue.
