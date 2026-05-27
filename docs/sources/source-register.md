# Source Register

This register tracks sources before they are expanded into full source cards.

The register is intentionally conservative. A source is listed with what it can support and what it cannot support.

## Source hierarchy reminder

1. Object-specific conservation reports, lab reports, excavation reports, museum catalogs, cathedral/church records, archival inventories.
2. Primary historical sources: recipes, workshop manuals, inscriptions, liturgical records, building accounts, ritual documents, correspondence.
3. Scholarly secondary sources: peer-reviewed articles, academic books, museum essays, conservation handbooks, university publications.
4. Institutional public sources: official site histories, national park/heritage records, government or museum pages.
5. General reference sources: encyclopedias and broad summaries.
6. Esoteric, symbolic, or interpretive sources.

## Initial register

| ID | Source / target | Type | Reliability | Supports | Does not support yet | Status |
|---|---|---|---|---|---|---|
| SRC-CAPITOL-COLUMNS-001 | National Capitol Columns / U.S. National Arboretum official or institutional history | institutional-history | high-institutional | Provenance of removed Capitol portico columns; relocation and public reinstallation | Any claim that columns contain remains | Needed |
| SRC-CAPITOL-CRYPT-001 | U.S. Capitol Crypt official or institutional history | institutional-history | high-institutional | Capitol Crypt, Rotunda support, Washington tomb design context | Any claim that Washington was buried there; remains inside columns | Needed |
| SRC-TRAJAN-001 | Trajan's Column object/site source | museum-catalog or scholarly-source | pending | Column as victory monument; ash/interment tradition in base | Full-body entombment inside shaft; general rule for Roman columns | Needed |
| SRC-ROMAN-FUNERARY-001 | Roman funerary altars, cippi, and ash containers | scholarly-source | pending | Roman cinerary/funerary container forms; altar/cippus cavities | Body-sized column claim unless object-specific | Needed |
| SRC-LIME-MORTAR-001 | Historic lime mortar and repointing source | conservation-handbook | pending | Mortar composition, sacrificial joint, restoration practice | Esoteric intent or human remains | Needed |
| SRC-CARBONATION-001 | Mortar carbonation / hydraulic mortar source | scholarly-article | pending | Calcination/slaking/carbonation and mortar chemistry | Symbolic claim unless separately interpreted | Needed |
| SRC-SULFATE-001 | Sulfate attack in concrete and mortar source | technical-reference | orienting | Sulfate migration, brick/mortar decay, pyrite/sulfate pathway | Intentional symbolic weeping | Needed |
| SRC-CALTHEMITE-001 | Calthemite / concrete leaching source | technical-reference | orienting | Concrete leaching, mineral growth, surface exudation | Ritual or symbolic intent | Needed |
| SRC-HALL-NIMBUS-001 | Manly P. Hall, nimbus/aureole/cathedral window passage | esoteric-text | interpretive | Light-body, halo, aureole, cathedral-window symbolic reading | Material composition of stained glass | Needed |
| SRC-STEINER-SALT-001 | Rudolf Steiner, Salt/Mercury/Sulphur lecture | esoteric-text | interpretive | Salt-process symbolic grammar; dissolution/re-formation | Material evidence for masonry or art composition | Needed |
| SRC-PARCHMENT-001 | Manuscript conservation / parchment material source | conservation-source | pending | Animal skin to writing substrate; liming, scraping, stretching | Human remains or esoteric intent | Needed |
| SRC-BONE-BLACK-001 | Pigment source on bone black | pigment-reference | pending | Bone-to-color material class | Human remains unless specified | Needed |
| SRC-OSSUARY-001 | Sedlec Ossuary / Capuchin Crypt / bone chapel source | institutional-history or conservation-source | pending | Human bone architecture at specific sites | Remains in mortar/glass/pigment | Needed |

## Source-card workflow

1. Add source to register.
2. Create source card under `docs/sources/` when used in an artifact or dossier.
3. Link source card to claim ledger, non-claim ledger, evidence matrix, and artifact card.
4. Do not use a source to support a layer it does not actually support.
