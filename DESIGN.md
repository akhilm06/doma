# Design

> Early concept. Expect this to change substantially, and get gradually more fleshed out, as I progress up the stack.

## Analogies
- doma is an observatory: discovery, melancholy, beauty. 
- doma is a spaceship: play, data, wonder. 
- doma is an atlas: perspective, precision, trust.

Borrow the feeling, never the imagery. No space visuals. 
*Never kitsch.*

## Principles

- Apple-like design philosophy and human interface guidelines:
  - Design with intentionality, simplicity, accessibility.
  - Remember the goal is craft and delight. 
- Omarchy's feel: 
  - Hard corners, thin borders, technical feel, disciplined aesthetic. 
    - doma is a scholarship tool from the future. Inspire awe.
- Sophistication:
  - doma is high-brow. Design with restraint. No gimmicks. Embrace dead space. 

## Rules 
- Monospace for technical aspects, serif for within profiles. 
- Color is supplemental cue only, always add visual distinction. 
- Hard edges, fixed position, never touch edges (ING exception).
- doma is lowercase.

## UI Concept 

See the concept sketch at the top of [README](README.md).

- General:
  - Thin top bar that contains logo top left, then pages. Right side has binary toggles or dropdowns.
  - Canvas beneath.
  - doma is a reddish color. Panel background is black tinted blue. 
- Library
  - The data set backbone, now as an instrument.
  - Feels like Omarchy's activity monitor: dense and granular and valuable. 
- Interactive Node Graph (ING) Page
  - ING represents lost works in a pale blue color with dashed border.
  - ING represents known works in an olive green color with solid border.
  - ING displays known and lost works together, enabling spatial navigation. Click to enter.
  - ING contains four types of lost works (each will be made visually distinct; see table below).
  - ING visually displays edges to represent relation (direct quote, commentary, et cetera).
  - ING visually displays how much of a lost work is known through node opacity and size.
  - ING creates a visceral display of how much of a corpus has been lost, making the gaps, the lacunae, the focal point.

  | Lost work type | Title   | Author  |
  |----------------|---------|---------|
  | Attested       | known   | known   |
  | Orphaned       | known   | unknown |
  | Strayed        | unknown | known   |
  | Adespota       | unknown | unknown |
