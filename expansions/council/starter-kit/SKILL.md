---
name: council
description: >
  Use when I want my council's judgment on an idea I'm deciding on. Full
  council: "run this through my council," "full council read," "what does
  everyone think." One voice: "run this past my critic," "what would my
  beneficiary say," "council: long view," or any request that names one
  of my voices (Advocate, Critic, Beneficiary, Executor, Long View, or
  any voice I've added in voices/). Do NOT use for ordinary questions
  that aren't an idea I'm weighing.
---

# The Council

<!--
  START HERE. This folder is your whole council: one skill, with your
  voices as files inside it. Copy the whole starter-kit folder to
  .claude/skills/council/ in your project (the folder must be named
  council). You only do that once.

  Then fill in ONE line below, "My material lives in," and build your
  voices one at a time in voices/. Each voice works the moment you save
  it: "council: advocate" runs just that voice, before the Weaver or any
  other voice exists. Unbuilt templates are skipped automatically.

  Everything else is pre-wired for the full five. If you've built fewer,
  leave the Sequence line alone: three voices + the Weaver is a complete
  council.

  Worked example: ../worked-examples/worked-example-council.md
  Delete these comments when done.
-->

One skill, a few files. The voices live in `voices/`, the synthesis
lives in `weaver.md`, and this file decides which of them to run.

**Sequence:** Advocate → Critic → Beneficiary → Executor → Long View →
Weaver

**My material lives in:** [where your stories, pattern hunch, and open
questions are kept: file names or a folder, e.g. "story-cards.md,
hunch.md, open-questions.md"]

## How to run it

**1. Pick the mode from the request.**
- *Full council* ("run this through my council"): every built voice in
  Sequence order, then the Weaver.
- *One voice* ("run this past my critic," "council: critic"): only that
  voice. No Weaver unless I ask for it.
- *A few voices* ("council: critic and executor"): only those, in
  Sequence order. No Weaver unless I ask.

**2. Load only what the mode needs.** Read `voices/<name>.md` for each
voice that will speak. Read `weaver.md` only when the Weaver will run. A
voice whose **Grounded in** line still contains `[bracketed]`
placeholders is an unbuilt template: skip it and tell me it was skipped.

**3. Re-ground each voice before it speaks.** Open the stories, hunch,
and questions its **Grounded in** line names, from **My material lives
in** above, and read the current text. Argue from what is written there
now, not from memory and not only from the summary in the voice file.
If you can't find something a voice cites, say which one and run that
voice from its file alone, marked as ungrounded. Never invent a story.

**4. Each voice speaks in turn.** One model, taking one grounded lens at
a time. Write each read from that voice's lens only, in its own voice
and using its **Always asks** question, without reacting to what an
earlier voice said. Hold every read.

**5. Return the result.**
- *Full council:* the Weaver's synthesis first, as the primary answer,
  with each voice's read below it so I can see the raw disagreement.
- *One or a few voices:* just those reads.

## Never does

- Skip a built voice in a full-council run, collapse two voices into one
  pass, or let the Weaver run before every voice has spoken.
- Convene the whole council when I asked about one angle.
- Write or alter my stories, patterns, or voice files while running. A
  run reads my material; it doesn't edit it.

## Changing the council

This is meant to be edited, and Claude can do it with me.
- *Sharpen or re-ground a voice:* edit `voices/<name>.md`. Re-grounding
  after new stories land is the point of keeping them in your repo.
- *Add a voice:* copy `voices/_TEMPLATE-voice.md` to
  `voices/<new-name>.md`, fill it in, add it to **Sequence**, and add
  its name to the `description` above so it triggers by name.
- *Retire a voice that never surprises me:* take it out of **Sequence**
  and the `description`, and move its file out of `voices/`.

<!--
  Manual fallback: if this skill ever drifts, run each voice by hand in
  a separate conversation (voices that can see each other start
  agreeing), then paste the reads plus weaver.md into a fresh one.
-->
