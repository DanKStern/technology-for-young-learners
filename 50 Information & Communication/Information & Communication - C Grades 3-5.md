---
status: draft
kind: technical
created: "2026-10-22"
tags: [youth-curriculum]
---

# Information & Communication — Band C (Grades 3–5, ages 8–10)

**Core idea:** switching your attention between two things has a cost (context-switching), messages can be compared by how much they carry — a long story carries more than a one-word answer — and a message can carry a second, separate layer on top of the words: instructions for how to display them, called markup, which changes how something looks without changing what it says.

**Spiral note:** builds on [[Information & Communication - B Grades 1-2]] — sender/receiver and context are familiar; this band names context-switching directly and starts treating "how much information" as something comparable, setting up [[Computing & Logic - C Grades 3-5]]'s multitasking lesson from the other side of the same idea. This band also introduces markup as a separate layer on top of content — hand-drawn underlines and boxes first, then the same marks typed as Markdown symbols — setting up [[Information & Communication - D Grades 6-8]]'s real markup languages (HTML, LaTeX) and echoing [[Computing & Logic - C Grades 3-5]]'s algorithm lesson, since a numbered list of steps is itself a tiny markup language for sequence.

## Hands-on activities
- Try doing two tasks at once that both need focus (reading aloud while doing math) and notice how much slower/harder it is than doing either alone — that slowdown is the cost of context-switching.
- Compare two messages about the same event — a one-word text vs. a full paragraph — and discuss what's lost in the short one.
- Play a rapid-switch game (answer a math question, then a word question, then back) and time how performance changes with faster switching.
- Revisit Band B's context examples and explicitly connect: switching contexts (bat-the-animal to bat-the-toy) takes a moment of mental "reloading," same shape as task-switching.
- Mark up a plain paragraph by hand first (underline the title, box key words, draw bullet dots), then "translate" the same marks into typed Markdown symbols (`#`, `**`, `-`) and compare — the content is identical, only the display layer changed.
- Turn a recipe card into a Markdown document — headings for sections, a numbered list for steps, bullets for ingredients — and connect the numbered steps back to the "how much does this message carry" idea.
- Record a sentence in [[Voice Scope]] and play each frequency band alone, ranking which one carries the most of the actual words — the sound version of "what's lost in the short version."

## Vocabulary

Words this band uses, defined the way we'd describe them to someone who'd never seen them — what happens, not how it feels:

- **Context-switching** — the cost, in time or focus, of moving attention from one task to a different one and back.
- **Markup** — a separate layer of instructions describing how to display content, which doesn't change the content itself.

Held back for later: *bandwidth* (the range of a signal a channel can carry) and *encoding* (converting a message into a standardized code two sides agree on ahead of time) — both arrive by name in [[Information & Communication - D Grades 6-8]].

## Draft

### Reading Aloud and Doing Math at Once

Have the child try reading a paragraph aloud while simultaneously solving simple math problems called out one at a time — both tasks they can do easily alone. Time how much slower or more error-prone either task gets done together versus separately. Ask: "why would doing two easy things together be harder than doing either one alone?" The answer worth landing on: switching attention back and forth costs something, even if neither task is hard by itself — call this cost context-switching directly, now that they've felt it.

### What's Lost in the Short Version

Compare two messages about the same event — a one-word text ("fine") versus a full paragraph describing how the day actually went. Ask the child to list everything the short version leaves out. Then flip it: ask when the short version is actually better (urgent, simple situations) and when the long one is worth the extra length. The idea underneath: messages can be compared by how much they carry, and shorter isn't always worse, just different.

### The Switching Game

Play a rapid-switch game — alternate quickly between a math question, then a word question, then back, speeding up each round — and time how accuracy or speed changes as the switching gets faster. Ask the child to connect this back to the reading-and-math activity: same cost, just made more extreme by speeding it up.

### Bat, Context, and Switching

Pull the "bat the animal vs. bat the toy" example back out from [[Information & Communication - B Grades 1-2]] and ask: "did figuring out which 'bat' I meant take you any time at all, even a tiny bit?" It did, even if it felt instant — that small moment of mental reloading when a word's meaning shifts is the same shape as the bigger, more obvious cost of switching between the math and reading tasks, just too fast to notice without looking for it.

### Dressing Up Plain Text

Give the child a plain paragraph with no formatting and ask them to mark it up by hand with a pencil — underline a title, box a few important words, draw dots next to a list buried in the sentence. Then show the same paragraph retyped with Markdown symbols instead: `# ` before the title, `**asterisks**` around the important words, `- ` before each list item — and open it in Obsidian or any Markdown viewer to see it render. Ask: "did the words change at all?" They didn't — only the separate layer of instructions about how to show them did. That separate layer is markup.

### A Recipe Card vs. a Recipe in Markdown

Take a recipe card with an ingredients section and a numbered steps section, and have the child retype it as a Markdown document — a heading for each section, bullets for ingredients, a numbered list for the steps. Ask: "does turning this into a numbered list change what you have to do, or just how clearly it's written down?" Connect it back to the earlier "what's lost in the short version" lesson — the numbering itself carries information (this step comes before that one), the same way a long message carries more than a short one. The numbered list is also the same idea [[Computing & Logic - C Grades 3-5]] calls an algorithm — a recipe already was one; Markdown just makes the sequence visible on the page.

### Which Part Carries the Words?

Have the child record a sentence they've never said before into [[Voice Scope]] — something a listener couldn't guess, like "the purple giraffe sat on my sandwich." Play it back four times, each time with only one animal band switched on, and have someone who didn't hear the original try to write down what was said. Before each playback, ask: "which band do you predict will be easiest to understand?" Most people guess Bear, because it's the loudest — and it turns out to be close to useless for words, while Bird and Snake, which look tiny on the screen, carry most of the consonants that tell "sat" from "fat" from "hat."

Connect it back to [[Information & Communication - C Grades 3-5#What's Lost in the Short Version|What's Lost in the Short Version]]: each band alone is a short version of the full message, and each one leaves out something different. The loudest part of a signal isn't necessarily the part carrying the most information. A real-world check: music through a wall from the neighbors' house is all thump and no words, because walls block the high bands and let the low ones through. Revisited at [[Information & Communication - D Grades 6-8#How Much Voice Does a Telephone Need?|Band D]], where the question becomes how much of a voice can be thrown away on purpose.

