# Citation and Teaching Standard

Mortartium is a public teaching repository. Every document should help readers learn how a claim was built, what evidence supports it, and where the boundary between material evidence and symbolic interpretation sits.

This standard governs citations, source notes, quotations, artifact cards, dossiers, and teaching-oriented explanations.

## Core rule

No substantive factual claim should stand without a source path.

A source path may be:

- A footnote citation in the document.
- A link to an internal source card.
- A link to an artifact card that contains the supporting evidence.
- A claim-ledger entry that points to sources.
- A non-claim entry that explains why the claim is not being made.

## Citation style

Use Markdown footnotes for public prose:

```markdown
Historic lime mortar is typically composed of lime, aggregate, and water.[^lime-mortar]

[^lime-mortar]: Author or institution, "Title," publication or repository, date if known, URL or archive reference, accessed YYYY-MM-DD.
```

For object files and artifact cards, include a `sources` section:

```yaml
sources:
  - id: source-short-id
    type: conservation-report
    citation: "Author, Title, Publisher, Year."
    url:
    accessed:
    supports:
      - material_substrate
      - destructive_process
      - claim_grade
```

## Source hierarchy

Prefer sources in this order:

1. Object-specific conservation reports, lab reports, excavation reports, museum catalogs, cathedral/church records, archival inventories.
2. Primary historical sources: recipes, workshop manuals, inscriptions, liturgical records, building accounts, ritual documents, correspondence.
3. Scholarly secondary sources: peer-reviewed articles, academic books, museum essays, conservation handbooks, university publications.
4. Institutional public sources: official site histories, national park/heritage records, government or museum pages.
5. General reference sources: encyclopedias and broad summaries, used only for orientation or low-risk background.
6. Esoteric, symbolic, or interpretive sources: Hall, Steiner, Theosophy, Rosicrucian, Masonic, alchemical, or occult texts. These support symbolic grammar or reception history, not material composition by themselves.

## Evidence labels

When writing public-facing text, label the evidence mode where useful:

- **Material evidence:** chemistry, microscopy, petrography, source-controlled conservation data, object analysis.
- **Textual evidence:** recipe, inscription, inventory, archive, historical record.
- **Institutional evidence:** church, guild, state, lodge, museum, or restoration authority.
- **Symbolic evidence:** iconographic, ritual, esoteric, mythic, or comparative reading.
- **Comparative evidence:** parallels across object classes or traditions.
- **Speculative hypothesis:** research-generating but not established.

## Teaching standard

Each major dossier should include:

1. **What the object is** — plain-language description.
2. **What it is made of** — material substrate.
3. **What was transformed** — destructive process.
4. **What it became** — artifact form.
5. **What it did socially or ritually** — institutional function.
6. **What it may symbolize** — symbolic reading, clearly marked.
7. **What we know** — established claims.
8. **What we do not claim** — explicit non-claims.
9. **What would prove more** — open tests.
10. **Where to read next** — source trail.

## Quotation policy

Use short quotations only where the wording matters.

Prefer paraphrase with citation for general facts.

Long quoted passages should be avoided unless the source is public domain and the quotation is necessary for teaching or analysis.

## Artifact-card citation requirements

Each artifact card should have at least one source before it is treated as more than a stub.

A complete artifact card should cite sources for:

- Material substrate.
- Destructive process.
- Historical context.
- Institutional authority.
- Symbolic interpretation, if asserted.
- Claim grade.
- Non-claim boundary, if relevant.

## Hard-claim citation requirements

Hard claims require object-specific sources. General symbolic sources are insufficient.

Examples:

- A claim about human remains in mortar requires object-specific material analysis or archival record.
- A claim about organ-derived stained-glass colorants requires object-specific conservation chemistry, recipe evidence, or workshop record.
- A claim about esoteric intentionality in a column or building requires object-specific iconography, inscription, patronage record, lodge record, or documented reception chain.

## Source-card template

Use source cards under `docs/sources/` when a source supports multiple claims.

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

## Public posture

Mortartium should teach readers how to read layered artifacts without forcing one layer to do the work of another.

The repo may say:

- "This artifact materially demonstrates destructive transformation."
- "This artifact can be read symbolically as death-bind, light-body, relic-core, or threshold."
- "This object raises a hard question that requires further evidence."

The repo should not say:

- "The symbol proves the material recipe."
- "All such artifacts share one hidden lineage."
- "Human remains are present unless object-specific evidence proves it."
- "Restoration evidence is neutral or self-interpreting."
