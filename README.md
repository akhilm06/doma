# doma

*An open-source atlas of synthesized lost work profiles from classical antiquity.*

δῶμα -- Ancient Greek for house.

> pre-alpha: seeking funding.

```
┌──────────────────────────────────────────────────────────────────────────────┐
│ doma   graph   library   method                                     settings │
├──────────────────────────────────────────────────────────────────────────────┤
│ Aeschylus:                                    ┌────────────────────────────┐ │
│ 70-90 plays written. 7 survive.               │ search works…              │ │
│                                               └────────────┬─────────┬─────┘ │
│            ●                                               │ filters │       │
│             ╲            ●                                 └─────────┘       │
│              ╲          ╱                                                    │
│       ● ─ ─ ─ ○────────○                      ┌────────────────────────────┐ │
│               │         ╲                     │ Myrmidons                  │ │
│               │          ● ─ ─ ●              │ attested · Aeschylus       │ │
│          ●    │                               │ ────────────────────────── │ │
│           ╲   ○                  ●            │                            │ │
│            ╲ ╱ ╲                ╱             │                            │ │
│             ●   ○─ ─ ─ ─ ─ ─ ─ ○              │                            │ │
│                                 ╲             │                            │ │
│                 ●                ●            │                            │ │
│                                               │       Content here.        │ │
│ ┌────────────────────┐                        │                            │ │
│ │                    │                        │                            │ │
│ │     Key here.      │                        │                            │ │
│ │                    │                        │                            │ │
│ │                    │                        │                            │ │
│ └────────────────────┘                        └────────────────────────────┘ │
│                                                                              │
└──────────────────────────────────────────────────────────────────────────────┘
```

Concept art.

## Documentation
- Methodology: [METHODOLOGY.md](METHODOLOGY.md)
- Design: [DESIGN.md](DESIGN.md)
- Choices: [CHOICES.md](CHOICES.md)
- Contributing: [CONTRIBUTING.md](CONTRIBUTING.md)
- License: code [MIT](LICENSE), data [CC BY-SA 4.0](LICENSE-DATA)

## What is doma?
Most of ancient literature has been lost to history. For example, Aristotle wrote an estimated 200 works. We only have access to 31. The existence of these lost works is known to us through fragments, quotations, references, et cetera. 

Specialists devote their careers to collecting and annotating this evidence, but what they provide is often dense, paywalled, and generally inaccessible to nonacademics (for example: TrGF). A useful analogy is the difference between a book on the industrial revolution and a Wikipedia article on it -- both serve useful functions, and are in fact complementary.

doma aims to serve the latter functionality, harnessing modern software and AI-assisted workflows to transform fragments and scattered references of lost works into living profiles, all displayed alongside known works on an interactive node graph.

## What doma Isn't
doma is primarily a conceptual innovation enabled by technological innovation. It is not:
- Reconstructions in the voice of authors.
- Speculation presented as fact.
- Replacement for specialist scholarship.
- A traditional startup. 

## Related Work
- Specialist fragment editions: Tragicorum Graecorum Fragmenta (TrGF), Brill's New Jacoby.
  - Dense, narrow, often paywalled or difficult to access, built on years of expert labor.
- Leipzig Open Fragmentary Texts Series (LOFTS), Digital Fragmenta Historicorum Graecorum (DFHG).
  - Open digital editions that link fragments to their source texts. 
- FragTrag (Greek Fragmentary Tragedians Online).
  - Open edition of 45 minor tragedians. 
- papyri.info, Digital Corpus of Literary Papyri (DCLP).
  - Open papyrus transcriptions. Raw evidence.
- Ithaca, Aeneas, Vesuvius Challenge.
  - AI that restores lost text. 
- Lost Plays Database.
  - doma’s closest analog. doma applies its model to antiquity.
- Wikipedia.
  - Strong for famous lost works, otherwise sparse or nonexistent.
    
None I found turns evidence for antiquity's lost works into cited, living profiles.

doma does, built on top of a novel open data layer and concordance table that supports independent research and future digital humanities projects, while also keeping the knowledge work accessible to non-scholars: autodidacts, students, and curious people.

## Roadmap
- Milestone one (minimum lovable product):
  - Month one (data foundations):
    - Deliverable: working data set and public methodology document.
    - Scope: sections Sourcing and Copyright through Initial Ingestion, within [methodology](METHODOLOGY.md).
  - Month two (profile synthesis):
    - Deliverable: Aeschylus's profiles and published evaluation results.
    - Scope: section Lost Work Node and Profile Synthesis, within [methodology](METHODOLOGY.md).
  - Month three (ING and launch):
    - Deliverable: public alpha covering Aeschylus.
    - Scope: implement the design, within [design](DESIGN.md).
  - Concurrently:
    - Research and develop domain knowledge.
    - Run outreach on classicists for advisor role and join community.
    - Continue to iterate on and refine features and concepts.
    - Learn Ancient Greek.
- Milestone two:
  - Deliverable: public alpha covering all three tragedians.
- Future deliverables:
  - Timeline and shelf format.
  - Frames: preset filters of ING users can explore.
  - Community can submit evidence and receive recognition for contribution.
- Long term goals:
  - Hand doma off to an institution that can sustain it.
  - Be used by real people: autodidacts, students, and professors.
  - Enable new insights and novel digital humanities research.

## About

I came up with the concept for doma about six months ago. I was listening to some podcast, and offhand, the host or guest mentioned how the majority of ancient literature has been lost to history. This induced a deep level of sadness within me, and, as I continued to dwell on that feeling, it bloomed into the concept for doma. 

Now, half a year later still, I just can't seem to get doma out of my head, and I'd like to dedicate a portion of my youth working on a project that contributes something of real intellectual value.  

### Prior Prototype

doma began as Lacuna, a basic prototype ([repo](https://github.com/akhilm06/Lacuna), [demo](https://lacuna-two.vercel.app/)). A full rebuild is in progress. Assume this repo as the source of truth.

<details>
<summary>Screenshot</summary>

<img width="1920" height="991" alt="Lacuna prototype" src="https://github.com/user-attachments/assets/acb04bc1-e203-4ced-8868-c12032e0584f" />

</details>

### About Me

I'm 20, and attended WashU for a couple semesters, and then worked on Gr0ve: a startup that transformed open-text feedback into context-aware and actionable business intelligence. Funding makes doma my full-time work. 

My living costs are minimal, so funds go directly into the work. I plan to learn Ancient Greek as well, and I'm looking for classicists willing to advise. 

For more context, please visit other md files in repository. 

Email Me: akhil.muthyala@outlook.com

### Right Now

- Applying for grants (main focus).
- Learning about contemporary tools and approaches. 
- Brushing up on specific technical skills. 
- Iterating on doma concept.  
