# doma

*an open-source atlas of synthesized lost work profiles from classical antiquity.*

δῶμα -- ancient Greek for house.

> pre-alpha.

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
<!-- - Live site: [https://akhilm06.github.io/doma/](https://akhilm06.github.io/doma/). -->
- Methodology: [METHODOLOGY.md](METHODOLOGY.md).
- Design: [DESIGN.md](DESIGN.md).
- Choices: [CHOICES.md](CHOICES.md).
- Contributing: [CONTRIBUTING.md](CONTRIBUTING.md).
- License: code [MIT](LICENSE), data [CC BY-SA 4.0](LICENSE-DATA).

## What is doma?
Much of ancient literature has been lost to history. For example, around 70-90 plays are attributed to Aeschylus. We only have access to seven of them, with the authorship of one, Prometheus Bound, being disputed. The existence of these lost works is known solely through fragments, quotations, references, et cetera. 

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
  - Open digital editions that link fragments to their source texts. DFHG covers historians, not tragedy.
- FragTrag (Greek Fragmentary Tragedians Online).
  - Open edition of 45 minor tragedians. 
  - Licensed CC BY-NC-ND. doma only links, does not reuse.
- papyri.info, Digital Corpus of Literary Papyri (DCLP).
  - Open papyrus transcriptions. Raw evidence.
- Ithaca, Aeneas, Vesuvius Challenge.
  - AI that restores or reads damaged ancient text. Adjacent to doma, not the same problem.
- Lost Plays Database.
  - doma's closest analog, though not in subject (English drama). doma applies its model to antiquity.
- Matthew Wright, The Lost Plays of Greek Tragedy (Bloomsbury, two volumes).
  - doma's closest analog in terms of subject, but in print form. doma provides a robust open data layer and novel form factor.
- Wikipedia.
  - Strong for famous lost works, otherwise sparse or nonexistent.
    
None I found turns evidence for antiquity's lost works into cited, living profiles.

doma does, built on top of a novel open data layer and concordance table that supports independent research and future digital humanities projects, while also keeping the knowledge work accessible to non-scholars: autodidacts, students, and curious people.

## Roadmap
- Milestone one (minimum lovable product, technical foundation):
  - Month one (data foundations):
    - Deliverable: working data set and public methodology document.
    - Scope: sections Sourcing and Copyright through Evidence, within [methodology](METHODOLOGY.md).
  - Month two (profile synthesis):
    - Deliverable: profiles for a seed set of Aeschylus's lost plays, and published evaluation results against Wright's book.
    - Scope: section Lost Work Node and Profile Synthesis, within [methodology](METHODOLOGY.md).
  - Month three (interactive node graph and launch):
    - Deliverable: public alpha with all of Aeschylus's titles on the graph, seed plays fully profiled.
    - Scope: implement the design, within [design](DESIGN.md). Expert review by classicist.
  - Concurrently:
    - Research and develop domain knowledge.
    - Run outreach on classicists for advisor role and join community.
    - Continue to iterate on and refine features and concepts.
    - Learn Ancient Greek.
- After:
  - Hand doma off to an institution that can sustain it.
    - Allow scholars to contribute by submitting evidence, in a model akin to Wikipedia.
  - Be used by real people: autodidacts, students, and professors.
  - Enable new insights and novel digital humanities research.
- Additional Functionality:
  - Interpretation sections once scholars are able to contribute it.
  - Timeline and shelf format.
  - Frames: preset filters of the interactive node graph that users can explore.

## About

### About Me

I came up with the concept for doma about six months ago. I was listening to some podcast, and offhand, the host or guest mentioned how the majority of ancient literature has been lost to history. This induced a deep level of sadness within me, and, as I continued to dwell on that feeling, it bloomed into the concept for doma. 

Now, half a year later still, I just can't seem to get doma out of my head, and I'd like to dedicate a portion of my youth working on a project that contributes something of real intellectual value.  

I plan to learn Ancient Greek as well, and I'm looking for classicists willing to advise. 

For more context on doma, please visit other md files in repository. 

Email Me: akhil.muthyala@outlook.com.

### Prior Prototype

doma began as Lacuna, a basic prototype ([repo](https://github.com/akhilm06/Lacuna), [demo](https://lacuna-two.vercel.app/)). A full rebuild is in progress. Assume this repo as the source of truth.

<details>
<summary>Screenshot</summary>

<img width="1920" height="991" alt="Lacuna prototype" src="https://github.com/user-attachments/assets/acb04bc1-e203-4ced-8868-c12032e0584f" />

</details>

### Things I've Learned
- The significance of doma having a human in the loop. At first, I figured human involvement would end after providing the data, but now, humans are involved in practically every step. 
- How incredibly difficult sourcing evidence is. I thought because the texts were millennia old, copyright wouldn't be a factor! But the modern editions and translations usually are. I've scoped down considerably, and now rely on domain experts to aid in fully fleshing out the data set. If one thing provides lasting value, it'll be the open data layer.
- After fleshing out the concept so thoroughly, I've become aware that past concept and technical implementation, the lasting success of doma relies on the successful handoff to scholars who hold decades of deep domain knowledge, with an interest in nurturing this project long term.

### Right Now

- Applying for grants (main focus).
- Learning and iterating on methodology and month one's data foundations.
- Learning about contemporary tools and approaches. 
- Brushing up on specific technical skills. 
- Iterating on doma concept.

