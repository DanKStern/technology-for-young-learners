---
status: draft
kind: technical
created: "2026-10-22"
tags: [youth-curriculum]
---

# Curriculum Outline — Technology for Young Learners

A STEM curriculum for Mila, Becca, and anyone else pre-K through grade 8 (roughly ages 3–13). Originated from two early seed notes (since deleted) that this note formalized into a full organizing structure.

## Organizing structure

**Six strands** — topic threads that run through the whole curriculum rather than one-off lessons:

- [[Forces & Motion]] — gravity, friction, energy, machines
- [[Matter & Energy]] — states of matter, atoms, chemical change
- [[Life & Living Systems]] — living vs. non-living, cells, ecosystems, genetics
- [[Systems, Hierarchy & Nesting]] — boxes-in-boxes, file systems, classification, class hierarchies
- [[Information & Communication]] — context, signals, codes, bandwidth, markup (Markdown/HTML/LaTeX)
- [[Computing & Logic]] — instructions, algorithms, multitasking, multiplexing

**Four age bands** — following the NGSS/CSTA convention of grade bands rather than grade-by-grade standards, with Pre-K split from K-2 to honor the developmental gap NAEYC/NSTA flag between preschool and early elementary:

| Band | Ages / Grades | Learning mode |
|---|---|---|
| A | Pre-K–K (3–5) | Sensory, play-based exploration; no abstraction |
| B | Grades 1–2 (6–7) | Concrete cause/effect, simple named concepts |
| C | Grades 3–5 (8–10) | Systems thinking, first real models, measurement |
| D | Grades 6–8 (11–13) | Abstraction, mechanism-level explanation |

Each strand has one file per band (24 files total, inside the six strand folders). A band file is **not** a one-time lesson — it's a spiral pass. Each band explicitly builds on what the child already has from the band before it (Bruner's spiral curriculum principle) rather than treating a topic as "done" after one pass.

## Pedagogical guideline: "learn the tool when you need to use the tool"

Every lesson should be driven by hands-on, experiential need — a concrete problem, question, or object in front of the child — not an abstract concept introduced because it's next in a sequence. Teach gravity because a ball just fell. Teach multiplexing because a toy needs to do two things over one wire. The vocabulary and formalism arrive *after* the hands-on experience generates the need for them, never before.

In practice:
- Every band file names at least one concrete hands-on activity before introducing any vocabulary.
- If a band file can't point to a real object, demo, or experience that motivates the concept, the concept doesn't belong at that band yet — push it to the next one.
- Formal names and definitions arrive once the child has already noticed the phenomenon and can be prompted to ask "why does that happen?"

## Research grounding

- NGSS's grade-band (not grade-by-grade) progression of disciplinary core ideas — [NGSS Topic Arrangements](https://www.nextgenscience.org/overview-topics)
- NAEYC/NSTA's joint position that young children are capable STEM learners through exploration and discovery — [More Than a Foundation](https://www.naeyc.org/resources/pubs/yc/nov2017/STEM-learners)
- Bruner's spiral curriculum — revisit, don't retire, each topic — [Spiral Curriculum overview](https://www.structural-learning.com/post/the-spiral-curriculum-a-teachers-guide)
- CSTA's 2026 PK-12 CS standards, for grain-size precedent in the early grades — [2026 CSTA Standards](https://csteachers.org/wp-content/uploads/2026/07/2026-CSTA-PK%E2%80%9312-Computer-Science-Standards.pdf)

## Map

See [[Scope and Sequence]] for the full strand × band grid with links to every lesson file.

See [[Drafted Lessons]] for a running index of every individual lesson drafted so far.

See [[Voice Scope]] for the one software tool the curriculum uses so far — what it is, how to set it up, and which lessons use it. Public since 2026-11-01, no install needed: [dankstern.github.io/voice-scope](https://dankstern.github.io/voice-scope/).

See [[Best Practices - Working With Claude on This Curriculum]] for how to get the best results asking Claude to keep developing lessons, and for running them with Becca and Mila.

## Supplementary (outside the formal lesson sequence)

[Becca's Arcade](https://dankstern.github.io/becca-arcade/) — a separate set of browser games built for Becca to play for fun, not drafted as formal lessons, but several riff on concepts from this curriculum and work fine as optional reinforcement: Mix-It Lab (color mixing, same idea as [[Matter & Energy - A PreK-K#Mixing Colors|Mixing Colors]]) and Sound Match (matches Voice Scope's wiggle-pictures-to-sounds idea, gamified). Public personal project, no formal license — no curriculum tie-in beyond the overlap in concept.
