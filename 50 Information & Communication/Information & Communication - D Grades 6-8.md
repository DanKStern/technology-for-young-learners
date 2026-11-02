---
status: draft
kind: technical
created: "2026-10-22"
tags: [youth-curriculum]
---

# Information & Communication — Band D (Grades 6–8, ages 11–13)

**Core idea:** a wire or channel has limited "bandwidth," and a computer appears to do many things at once by context-switching very fast between them — the same cost from Band C, just measured in milliseconds. A markup language (HTML, LaTeX) is a formal, agreed-upon code for the display layer Band C introduced informally, with its own exact rules for how instructions have to be written and nested.

**Spiral note:** builds on [[Information & Communication - C Grades 3-5]] — context-switching and message size are already familiar; this band formalizes bandwidth and encoding, and connects directly to [[Computing & Logic - D Grades 6-8]]'s time/frequency-division multiplexing as the engineering answer to "how do we share one wire?" It also formalizes Band C's hand-markup-to-Markdown lesson into two real markup languages — HTML, whose tags must nest correctly inside each other just like [[Systems, Hierarchy & Nesting - D Grades 6-8]]'s module/package/function boxes, and LaTeX, used when plain text genuinely can't carry a kind of information (a fraction, an exponent) without a markup layer to show it properly.

## Hands-on activities
- Compare sending a photo vs. a text message over the same internet connection and discuss why one takes longer — different amounts of information, same "wire."
- Demonstrate simple encoding: convert a short message to Morse code or binary by hand and back.
- Revisit the Band C task-switching cost and reframe it precisely: a computer's CPU does the same thing, pausing one task's state to load another's, many times per second.
- Explicitly preview the Band D multiplexing idea in [[Computing & Logic - D Grades 6-8]]: old telephone systems sent many calls over one wire by taking turns in time or splitting by frequency — the engineering version of "sharing a channel."
- Write a tiny HTML page by hand (a heading, a paragraph, one bold word) and open it in a browser to see the tags "disappear" into formatting — the same hidden layer idea from Band C, now with a strict code the writer and the browser both have to agree on.
- Typeset a math formula the child already knows (area of a circle, the Pythagorean theorem) in LaTeX and compare it to the same formula typed in plain text, noticing what plain text can't show properly (true fractions, stacked exponents).
- Line Markdown, HTML, and LaTeX up side by side for the same short piece of content and ask what each is good for and why none of them replaces the other two.
- Use [[Voice Scope]] to build a "telephone voice" by switching on only the middle bands, and find out how much of a voice can be thrown away while still being understood — the bandwidth a phone call actually needs.

## Draft

### Why the Photo Takes Longer

Send a photo and a short text message over the same connection (or just compare file sizes) and ask the child to predict which will take longer to send and why. The answer: a photo simply carries more information than a short text, and more information takes more time (or more "wire") to move, even over the exact same connection — a concrete, measurable version of the "how much does this message carry" idea from Band C.

### Turning Words Into Code

Pick a short message and convert it to Morse code by hand, or to binary (a simple letter-to-number-to-binary lookup works fine), then have the child decode it back without seeing the original. Ask: "could I have picked a completely different code and had it work just as well, as long as we both agreed on it?" (Yes — the same sender/receiver-needs-the-same-code idea from [[Information & Communication - B Grades 1-2]]'s secret-code lesson, just with a real, standardized code instead of an invented one.)

### The Computer's Version of Switching Tasks

Revisit the Band C task-switching cost and reframe it precisely: a computer's processor does the exact same thing a brain does when juggling math and reading — it pauses one task, saves exactly where it left off, loads a different task's state, works on that for a moment, then switches back. It feels like "doing many things at once" only because the switching happens many thousands of times per second, far too fast to notice — the same way a movie's still frames feel like smooth motion once they flip by fast enough.

### How Many Calls, One Wire?

Preview the question this whole strand has been building toward: old telephone systems had to carry many different people's calls over a single shared wire. Ask the child, before any answer: "if only one call can really travel on a wire at once, how do you think the phone company fit hundreds of calls onto it?" Don't answer it here — that's exactly the engineering problem [[Computing & Logic - D Grades 6-8]] solves next, with two real strategies.

### Tags That Wrap Their Meaning

Write a tiny HTML page by hand together — a heading tag, a paragraph tag, one word wrapped in bold tags — then open the file in a browser and watch the tags vanish into actual formatting. Ask: "where did the tags go?" They didn't go anywhere — the browser read them and used them as instructions, the same way the child's eye used to read a boxed word in Band C's hand-markup lesson. Point out that every opening tag needs a matching closing tag, and tags have to nest cleanly inside each other, never crossing — the exact same box-inside-a-box rule as [[Systems, Hierarchy & Nesting - D Grades 6-8]]'s module/package/function hierarchy, just written as `<tags>` instead of folders.

### When Plain Text Isn't Enough

Pick a formula the child already knows — the area of a circle, or the Pythagorean theorem — and type it two ways: once in plain text (`a^2 + b^2 = c^2`) and once typeset properly in LaTeX, with a real stacked exponent and clean spacing. Ask which one is easier to read at a glance, and why. The idea underneath: some information — a true fraction, a stacked exponent, a square-root sign — genuinely can't be shown in plain text no matter how it's arranged; LaTeX exists because math needed its own exact markup language, the same way [[Information & Communication - B Grades 1-2]]'s secret code needed sender and receiver to agree on a system before it could carry anything.

### Three Dialects, One Idea

Lay Markdown, HTML, and LaTeX side by side for the same short piece of content — a heading and a sentence, say — and ask the child what each one is actually for: Markdown for quick, readable notes; HTML for pages a browser displays; LaTeX for math and print that has to be exact. None of the three replaces the others, the same way Morse code and binary from earlier in this band aren't competing, just suited to different jobs. Close by asking: "if you were writing a note to yourself, a web page, and a math proof, which of the three would you reach for each time?"

### How Much Voice Does a Telephone Need?

Start with a question: "a voice reaches from deep rumbles to high hisses — how much of that do you think a phone call actually sends?" Then test it. Record a sentence into [[Voice Scope]] and switch on only Person and Bird (roughly 300 to 3000 Hz). It instantly sounds like someone on an old phone line — because that's almost exactly the slice traditional telephone lines carried, about 300 to 3400 Hz, throwing the rest away. Ask whether it's still understandable (it is) and still recognizable as *their* voice (mostly).

That slice is the call's bandwidth: the range of frequencies it uses. Engineers kept it narrow on purpose — the less of the frequency range each call takes up, the more calls can be packed side by side on one wire, which is exactly the setup for [[Information & Communication - D Grades 6-8#How Many Calls, One Wire?|How Many Calls, One Wire?]] and the frequency-splitting answer in [[Computing & Logic - D Grades 6-8#Two Tones, One Air|Two Tones, One Air]]. One more thing worth noticing: with Bear switched off, a deep voice still *sounds* deep. The lowest note of a voice is barely there in a phone call, and the listener's brain rebuilds it from the pattern of the higher bands — a reminder that the receiver is doing real work too, not just the wire. Connect it to [[Information & Communication - D Grades 6-8#Why the Photo Takes Longer|Why the Photo Takes Longer]]: a phone call is the opposite trade — instead of sending more information slowly, it sends less, chosen carefully, so more of it fits.

