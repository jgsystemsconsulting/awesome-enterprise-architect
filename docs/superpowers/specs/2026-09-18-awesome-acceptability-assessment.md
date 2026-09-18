# Awesome list acceptability assessment: awesome-enterprise-architect

Date: 2026-09-18 (updated after sindresorhus-awesome-ready audit + fixes)
Tool: `python ~/.zcode/skills/sindresorhus-awesome-ready/tools/audit.py --repo . --gh --lint`

## Auditor decision

**WAIT** (calendar age only). Zero FAIL after fixes. SA-AGE needs >=30 days from first public commit (2026-09-18).

## FAIL / WAIT / WARN ledger

| ID | Status | Action taken |
|---|---|---|
| SA-PUBLIC | PASS | Repo set public |
| SA-TOPICS | PASS | Topics: awesome, awesome-list, enterprise-architect, sparx, mbse, sysml, uml |
| SA-LICENCE-SIDEBAR | PASS | LICENSE replaced with family CC0 text GitHub detects as CC0-1.0 |
| SA-LICENCE-PROSE | PASS | Removed licence-enquiry bullet that tripped WARN |
| SA-LOGO | PASS | Added media/logo.svg + README img |
| SA-AGE | WAIT | age_days from first commit 2026-09-18; need 30 more days. Do not fake age. |
| SA-LINT | PASS | awesome-lint@2.3.0 on README.md |
| Manual IDs | open | SA-REVIEW-FOUR, SA-UNICORN, SA-HUMAN-PR, SA-RE-READ, SA-NOT-DUPLICATE, SA-QUALITY, SA-NOT-AI-LIST, SA-NO-DRAFT, SA-LINKS |

## Prerequisites before sindresorhus/awesome PR

1. SA-AGE PASS (real calendar >=30 days). Optional: note on sindresorhus/awesome#2242 while waiting.
2. Re-run auditor on submit week: zero FAIL, SA-AGE PASS.
3. Clean lychee on README.md + docs/index.html.
4. Human completes manual checklist (review four open awesome PRs, unicorn comment, human PR body, re-read live template, not duplicate, quality).
5. Do **not** open the meta-list PR until 1-4 clear. Do not fake commit dates.

## Suggested PR package (when GO)

- Title: `Add Enterprise Architect`
- Entry: `- [Enterprise Architect](https://github.com/jgsystemsconsulting/awesome-enterprise-architect#readme) - Curated resources for Sparx Systems Enterprise Architect (the modeling product): add-ins, MDG, scripting, tutorials, and sample models.`

## Decision

**WAIT / no PR now.** All code/docs WARNs and FAILs that are fixable are fixed. Age gate remains.

## Non-goals

- Opening sindresorhus/awesome PR this session
- Backdating commits
