# Mortartium Work Plan

Mortartium is organized as a claim-disciplined research atlas. The work proceeds from stable material evidence toward symbolic interpretation, then toward object-specific hard tests.

## Controlling aim

Build a public research repository that can support a serious investigation into destructive transformation across sacred art, masonry, material culture, relic systems, restoration science, and the royal arts.

The project should make layered artifacts legible without collapsing them into one interpretation.

## Operating principles

1. **Material evidence first** — conservation science, craft history, object analysis, and material process are the foundation.
2. **Layered reading** — artifacts may simultaneously be chemical objects, craft products, symbolic diagrams, ritual instruments, institutional claims, and historical remainders.
3. **Claim grading** — every significant claim must be marked as established, strongly supported, plausible, speculative, open test, or rejected.
4. **No broad extraordinary claims** — claims about human remains, organs, relic dust, blood, bone ash, or other charged substances must be object-specific.
5. **Restoration discipline** — distinguish original fabric, later repair, contamination, environmental decay, and interpretive overlay.
6. **Public defensibility** — the repo should be readable by historians, conservators, artists, material scientists, esoteric scholars, and general readers.

## Phase 0 — Repository bootstrap

Goal: create the research frame.

Deliverables:

- `README.md`
- `docs/work-plan.md`
- `docs/claim-ledger.md`
- `docs/evidence-matrix.md`
- `docs/glossary.md`
- `docs/archetypes/README.md`
- `schemas/artifact-card.schema.json`

Acceptance criteria:

- The project has a clear thesis and claim boundary.
- The archetype model is explicit.
- There is a reusable artifact-card format.
- The repo does not present speculative claims as established fact.

## Phase 1 — Archetype taxonomy

Goal: define the reusable interpretive architecture.

Initial archetypes:

1. Death-Bind
2. Weeping Wall
3. Light-Body
4. Relic-Core
5. Inscribed Skin
6. Bone-to-Color
7. Royal Furnace
8. Threshold / Initiation
9. Ruin-as-Body
10. Sounding Remains

Deliverables:

- One markdown file per archetype under `docs/archetypes/`.
- Each archetype file should include material signatures, destructive processes, symbolic operations, evidence types, target artifacts, and claim hazards.

Acceptance criteria:

- Every archetype can be used to classify real artifacts.
- Archetypes are allowed to overlap.
- Each archetype includes at least one established material example and one symbolic interpretive lane.

## Phase 2 — Source intake

Goal: build the first controlled source base.

Initial source lanes:

- Masonry and restoration science: lime mortar, repointing, carbonation, sulfate attack, efflorescence, spalling, calthemites, concrete degradation.
- Sacred architecture and relics: altars, crypts, ossuaries, reliquaries, saint bodies, catacombs, bone chapels.
- Art material transformation: parchment, vellum, hide glue, gelatin, casein, egg, bone black, bone ash, ivory, shell, horn, pigment, glass, enamel, glaze.
- Symbolic corpora: Manly P. Hall, Rudolf Steiner, alchemy, Rosicrucianism, Theosophy, Masonic death-rebirth symbolism, royal art.
- Target sites: Chartres, Sainte-Chapelle, Notre-Dame, Rosslyn, Hagia Sophia, Assisi, Sedlec Ossuary, Capuchin Crypt, Westminster, Canterbury, York.

Deliverables:

- `docs/sources/source-register.md`
- Source notes grouped by lane under `docs/sources/`
- Citation/provenance notes for every source

Acceptance criteria:

- Each source is tagged by lane, artifact relevance, and evidence type.
- Sources are not used beyond what they actually support.
- Sources that are symbolic or speculative are marked as such.

## Phase 3 — Evidence matrix

Goal: make the layered model operational.

Each artifact or object class should be mapped across:

- Object / site
- Material substrate
- Destructive process
- Binding or fixation process
- Visible artifact
- Hidden layer
- Symbolic operation
- Institutional authority
- Evidence available
- Claim grade
- Open tests
- Sources

Deliverables:

- `docs/evidence-matrix.md`
- `artifacts/<lane>/<artifact>.md` cards
- Optional machine-readable artifact cards once schema is stable

Acceptance criteria:

- Matrix separates material facts from symbolic interpretations.
- Every artifact has a claim grade.
- Hard claims are converted into open tests rather than asserted.

## Phase 4 — First proof campaign

Goal: prove the broad thesis with noncontroversial cases before touching the hardest claims.

Proof targets:

1. Lime mortar: calcination, slaking, carbonation, sacrificial joint, restoration ethics.
2. Brick: fired earth, manufactured body-unit, weathering and spalling.
3. Parchment: prepared animal skin as writing substrate.
4. Bone black / bone ash: remains converted into pigment, ceramic, or memorial medium.
5. Relic architecture: bodies and body-fragments anchoring sacred space.
6. Stained glass: mineral transformation and light-body symbolism, without assuming organ-derived colorants.

Deliverables:

- `docs/dossiers/first-proof-campaign.md`
- Artifact cards for at least one object in each proof target
- Claim ledger entries for each major claim

Acceptance criteria:

- The broad thesis is supported without reliance on speculative claims.
- Each proof target includes material process, artifact form, and symbolic interpretation.
- Stained-glass claims remain bounded.

## Phase 5 — Hard-claim tests

Goal: isolate and test extraordinary or difficult claims.

Candidate questions:

- Were human or animal remains incorporated into specific sacred architectural media?
- Do conservation reports identify bone ash, phosphate, apatite, blood, collagen, animal glue, casein, egg, or other organic residues in particular objects?
- Are there medieval, early modern, or ritual recipes linking organ matter, humors, colors, glass, pigment, plaster, mortar, or relic dust?
- Where does symbolic organ-color correspondence exist without material use?
- Where does material use exist without symbolic doctrine?

Deliverables:

- `docs/hard-claims.md`
- One card per hard claim
- Required evidence checklist per claim

Acceptance criteria:

- No hard claim is asserted unless evidence satisfies its checklist.
- Unsupported claims are preserved only as open tests.
- Rejected claims are documented rather than silently dropped.

## Phase 6 — Public synthesis

Goal: turn the atlas into readable public scholarship.

Deliverables:

- `docs/dossiers/death-bind.md`
- `docs/dossiers/weeping-wall.md`
- `docs/dossiers/light-body.md`
- `docs/dossiers/relic-core.md`
- `docs/dossiers/royal-arts.md`

Acceptance criteria:

- Dossiers cite the evidence matrix and claim ledger.
- Public prose remains readable without sacrificing claim discipline.
- Symbolic interpretation is clearly distinguished from material proof.

## Immediate next backlog

1. Add claim ledger skeleton.
2. Add evidence matrix skeleton.
3. Add artifact-card schema.
4. Add archetype overview.
5. Add first source register seeded from known source lanes.
6. Add first artifact card: lime mortar joint.
7. Add first artifact card: cathedral rose window.
8. Add first artifact card: parchment manuscript.
9. Add first artifact card: relic altar.
10. Add hard-claims skeleton.
