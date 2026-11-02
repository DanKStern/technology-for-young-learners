---
status: draft
kind: technical
created: "2026-10-22"
tags: [youth-curriculum]
---

# Best Practices — Working With Claude on This Curriculum

Two audiences for this note: how Dan gets the best results asking Claude to keep fleshing out the curriculum, and how Dan gets the best results actually running a lesson with Becca or Mila. Both grew out of how the first batch of lessons (the radiometer, the Band B drafts across all six strands) actually came together — this isn't theoretical advice, it's what already worked.

## Working with Claude on this curriculum

- **Name the real object, not just the topic.** "Draft the radiometer lesson" produced a much better lesson than "draft a Forces & Motion lesson" would have — a real prop in hand gives Claude something concrete to build the whole demo sequence around, instead of inventing a generic activity. When you've bought or found something for an upcoming visit, say so and name it.
- **Name the child and her age when the ask is delivery-oriented.** "For Becca, she's 6" is enough for Claude to land on the right band without you having to look up which one that is. If Becca and Mila are different ages, say which child a given request is for — don't assume Claude will guess.
- **Let clippings do the research, then just point at them.** Drop source material (articles, videos, AI research chats) into `Clippings/` as usual. You don't need to paste research into the chat — either run `classify-inbox` and let its `[Curriculum: ...]` tagging find the right strand/band automatically, or just tell Claude directly which notes should link where, the way you did with the radiometer and powers-of-ten clippings. Your judgment on which band a source fits is generally better than a guess, since you know Becca and Mila specifically.
- **Ask strand-by-strand, band-by-band, not "draft the whole thing."** Every lesson drafted so far was requested as its own ask. That kept each one intentional and left room to redirect mid-stream (e.g. asking for just a short pointer instead of a full lesson when one strand's angle on a topic was minor). A single "flesh out the whole curriculum" request would produce a lot of generated-but-unreviewed prose with no chance to correct course partway through.
- **Use the Scope and Sequence grid as the map.** `00 General/Scope and Sequence.md` names every strand/band cell — pointing at a specific cell ("the Band C Systems, Hierarchy & Nesting one") is faster and more precise than describing the topic from scratch.
- **Say so explicitly for anything structural** — a new strand, renumbering, folder moves. Per the vault's standing rule, Claude won't do this unprompted, but it also won't guess whether a given ask is structural or just content — when in doubt, say what you want listed out before it happens.

## Delivering material to Becca and Mila

- **Lead with the object or demo, never the word.** This is the curriculum's own governing mantra — "learn the tool when you need to use the tool" — and the drafted lessons are written around it: show the radiometer spinning before saying "force"; watch the bean sprout before saying "life cycle." If a lesson draft seems to jump to vocabulary too early for how a session is actually going, slow down, not the other way around.
- **Ask before you explain.** Every drafted lesson has an embedded question ("what do you think is pushing it?", "how do you know which one I mean?") placed *before* the answer. Actually pause there — the question is doing real work, not just decorating the script.
- **"Scientists still argue about this" is a complete, satisfying answer at Band A/B.** The lessons deliberately withhold the real mechanism until Band D (the radiometer's actual physics, DNA's actual chemistry). If a question runs ahead of the band you're in, naming the uncertainty honestly is better than either dodging it or over-explaining.
- **Follow a tangent when one comes up.** If a question veers off the planned concept, that's often the richest moment in the room — the band file is a starting point, not a script to force through to the end.
- **Band boundaries are a guide, not a fence.** Becca and Mila may be different ages or just different on a given day — flex a Band B lesson down toward Band A phrasing, or up toward Band C, based on how the child is actually responding, rather than sticking rigidly to the file you opened.
- **Call back to the spiral out loud.** When a prop or idea returns at a later band (the radiometer again, the nesting-dolls idea reappearing as file paths), say the callback explicitly — "remember when we watched this spin before?" — rather than just quietly running a deeper version of the same activity. The callback is what makes the repetition feel like progress instead of déjà vu.
- **Stop while interest is still high**, especially at Band A/B — ending a beat early leaves her wanting the next one; running a demo past its natural end teaches that the moment of discovery runs out.
