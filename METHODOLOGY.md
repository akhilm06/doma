# Methodology

> Early concept, and a deliverable of month one. Expect substantial change.

Milestone one is mostly technical, providing a foundation for scholars to build upon. Profiles will round out through contribution.

## Principles
- Every granular aspect of a claim or decision must be rigorously cited with evidence. Do not rely on model data for context.
- Conservative disposition: err towards less, always. Allow thinness.
- Embrace ambiguity and fuzziness. Uncertainty is shown, no speculation dressed up as confident fact.
- Write plainly and encyclopedically: no flourish or rhetoric.
- Prioritize ultra simplicity and robustness. No clever implementations.
- Human in the loop: doma believes humans and artificial intelligences serve unique complementary functions, and harnesses the ability of both. Specialist humans have authority over AI.

## Risks/Failure Modes
- Fragment epistemology and ambiguity: humans curate and enter all evidence. AI synthesizes evidence into profiles through informed decisions. Both parties are capable of error.
- Evidence sourcing: handling copyright, translation without losing nuance, building infrastructure to allow for outside contribution.
- Uncaught error/drift: evidence that contains inaccuracy will enable degradation of profile quality. So will AI overstating or misstating evidence.

## Milestone One Tech Stack
- Data: one JSON file per record, in git.
- Schema: Pydantic.
- Pipeline: Python + Claude API. Managed with uv, linted with ruff, tested with pytest.
- Site: Python + Jinja2 (static).
- Graph: NetworkX + SVG.
- Hosting: static, host-independent.

## Built On
- Public-domain editions of quoting authors (Stobaeus, Athenaeus, et cetera).
- Public-domain fragment editions (Nauck, Pearson, Smyth).
- Perseus Digital Library and First1KGreek.
- papyri.info.
<!-- - CLTK (Classical Language Toolkit). -->

## Sourcing and Copyright
- Evidence is curated by human hand.
- Evidence is sourced solely from public-domain and openly licensed material.
<!-- - Modern editions, such as Radt, TrGF are used as an index, not reproduced. -->

## Evidence

### Content
- Evidence is recorded in the original language, with both public domain and machine assisted translations (only the latter if necessary).

### Taxonomy (what kind of thing is this?)
- Evidence type: fragment or testimonium; verbatim quotation, paraphrase, et cetera.

### Provenance (where it came from, and how?)
- Source and locus.
- Translator or model.
- Who entered this evidence and when.
- License.

## Lost Work Node and Profile Synthesis

### Profile form
- Profiles include introduction, concepts, contested, et cetera, with a strict form and uncertainty system.
- Profile length scales with evidence. Thin profiles are celebrated.
- Informed choices are logged in the decision log.

### Profile synthesis workflow
- Will delve further in month two.

### Decision log
- Decision logs record written justifications of any informed choice with links to relevant evidence.
- Decisions can be flagged for human review.
- Humans can use decision log, but are subject to the same rigor and level of transparency.

### Verification loop
- Profile generation and decisions require strict citations with a goal of no hallucinated information.
- A verification loop checks that every claim is supported by its cited evidence.
- The loop runs for a maximum number of rounds. Claims still unsupported are flagged for human review.
- Verification status is recorded per claim, with the model and date that ran it.

## Lost Work Types

| Lost work type | Title   | Author  |
|----------------|---------|---------|
| Attested       | known   | known   |
| Orphaned       | known   | unknown |
| Strayed        | unknown | known   |

<!-- | Adespota       | unknown | unknown | -->
