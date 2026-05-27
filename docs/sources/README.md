# Sources

This directory contains source cards for Mortartium.

A source card records what a source is, what kind of evidence it can support, what it cannot support, and which claims or artifacts it touches.

## Source-card template

```yaml
id:
title:
author_or_institution:
year:
source_type:
url:
archive_url:
accessed:
reliability:
used_for:
  - material evidence
  - process evidence
  - symbolic interpretation
  - institutional context
summary:
key_limits:
related_claims:
related_non_claims:
related_artifacts:
```

## Source type vocabulary

Use one or more of the following:

- conservation-report
- lab-analysis
- excavation-report
- museum-catalog
- institutional-history
- archival-record
- primary-text
- recipe-or-workshop-manual
- scholarly-article
- scholarly-book
- public-reference
- esoteric-text
- symbolic-interpretation
- field-note
- image-or-photograph
- restoration-record

## Reliability labels

| Label | Meaning |
|---|---|
| high-object-specific | Directly tied to a specific object or site. |
| high-institutional | Official institution, museum, archive, conservation body, or site authority. |
| scholarly | Academic or peer-reviewed source. |
| orienting | Useful for background, not final proof. |
| interpretive | Useful for symbolic grammar or reception history. |
| speculative | Preserved for hypothesis generation only. |

## Use rule

A source may support one layer without supporting another.

Example: an esoteric text may support symbolic interpretation but not material composition.

Example: a conservation report may support material composition but not intended ritual meaning.

Example: an institutional site history may support provenance but not hidden contents.
