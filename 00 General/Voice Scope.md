---
status: draft
kind: technical
created: "2026-10-31"
tags: [youth-curriculum]
---

# Voice Scope

A kid-friendly oscilloscope for the voice: a single web page that shows a child's voice from the computer's microphone as a picture, records four seconds of it, and plays the recording back split into four frequency bands she can switch on and off. Unlike the other props in this curriculum it's software, but it plays the same role — the real object in front of the child that the lesson is built around.

Built 2026-10-30 for Becca's visit. The lessons below were drafted 2026-10-31 assuming that first session went well. First real session was 2026-11-01: starting cold from a voice-shaped line graph read too abstract for Band A, so the Band A lesson and the lesson list below were revised to lead with a simpler loudness display and a prediction game instead — see the revision note on [[Matter & Energy - A PreK-K#Seeing Your Voice|Seeing Your Voice]]. The new Band A and Band B activities below (Guess the Sound, Piano Pictures, Step by Step, Then Smooth) assume Voice Scope features that don't exist yet — a light-bar loudness display, a canned sound library, a piano/tone input with a frequency readout, and an adjustable tone generator — noted inline where each one applies. No rebuild planned yet; these are drafted ahead of the tool, same as the rest of this file was.

## What's on the screen

- **Top screen — "your voice over time."** A scrolling loudness line while live; after recording, the whole four seconds frozen in place. Tap it to pick a moment to zoom in on.
- **Bottom screen — "the wiggles."** The actual waveform, zoomed in to about a fiftieth of a second, held still the way a real oscilloscope does.
- **Dashed lines** on both screens marked *whisper*, *talking*, *shouting*.
- **🔴 Record** — 3-2-1 countdown, then four seconds.
- **▶ Play, 🔁 Loop, 🎤 Live** — hear the recording, repeat it, or go back to the live picture.
- **The four animals** — each one a slice of the voice by pitch. Switching them changes both the sound and the pictures; the full original voice stays as a faint ghost behind the trace.
  - 🐻 **Bear** — low, under 300 Hz (the deep hum of a voice)
  - 🙂 **Person** — middle, 300–1000 Hz
  - 🐦 **Bird** — upper, 1000–3000 Hz
  - 🐍 **Snake** — hiss, over 3000 Hz (the "s," "t," "f" sounds)

## Getting it running

- **Anyone — parents, teachers, Becca herself:** [dankstern.github.io/voice-scope](https://dankstern.github.io/voice-scope/) — just open the link, nothing to install, no Claude or Dan involved. Public since 2026-11-01's "first revision" pass (prominent privacy statement, one-line intro, MIT-licensed, GitHub Pages hosting — see the repo's commit history for the teacher-facing rewrite).
- **Dan's machines (for editing):** `C:\Users\danks\dev\projects\voice-scope\index.html`. Source is the public GitHub repo `DanKStern/voice-scope`; on another machine, `gh repo clone DanKStern/voice-scope` into `C:\Users\danks\dev\projects`.
- Needs a laptop or desktop with a microphone and Chrome (or another modern browser). No headphones needed — the microphone is never sent to the speakers, so it can't squeal.
- Add `?test` to the end of the address to use a built-in test sound instead of the microphone — handy for checking everything works before the child arrives.

## Before a session

- Open **Grown-up settings** and slide **Mic boost** until talking normally reaches the "talking" line. Every laptop's mic is different; the page remembers the setting.
- Set **Playback volume** in the room you'll actually use.
- For clean, readable wiggles on the bottom screen, **hum or sing a steady "oooo"** — ordinary talking makes a messy wave that's harder to see.
- Nothing is uploaded or saved — the recording only lives on the page until the next one replaces it. Worth saying out loud to any parent who asks.

## Lessons that use it

- [[Matter & Energy - A PreK-K#Seeing Your Voice|Seeing Your Voice]] — Band A
- [[Matter & Energy - A PreK-K#Guess the Sound|Guess the Sound]] — Band A
- [[Matter & Energy - B Grades 1-2#Fast Wiggles, Slow Wiggles|Fast Wiggles, Slow Wiggles]] — Band B
- [[Matter & Energy - B Grades 1-2#Which Animal Lives in Your Voice?|Which Animal Lives in Your Voice?]] — Band B
- [[Matter & Energy - B Grades 1-2#Piano Pictures|Piano Pictures]] — Band B
- [[Matter & Energy - B Grades 1-2#Step by Step, Then Smooth|Step by Step, Then Smooth]] — Band B
- [[Information & Communication - C Grades 3-5#Which Part Carries the Words?|Which Part Carries the Words?]] — Band C
- [[Information & Communication - D Grades 6-8#How Much Voice Does a Telephone Need?|How Much Voice Does a Telephone Need?]] — Band D
- [[Computing & Logic - D Grades 6-8#Two Tones, One Air|Two Tones, One Air]] — Band D (Voice Scope as the filter)
