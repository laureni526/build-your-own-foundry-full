# Foundry Council — Starter Kit

Everything you need to build a full council today, so nobody starts
from a blank page. This folder **is** your council: one skill, with a
template for each voice already inside it. You bring the evidence.

## Install it once

Copy this whole folder into your project as `.claude/skills/council/`.
The folder must be named `council`. That's the only install step. After
that, every voice you build is just a file you save inside it.

Open `SKILL.md` and fill in one line, **My material lives in**: where
your story cards, pattern hunch, and open questions are kept. Your
stories stay in your repo, not inside the skill. Every run re-reads
them, so a story you add next month sharpens the council next month.

## What's in here

| File | What it is | When you build it |
|---|---|---|
| `SKILL.md` | The runner. Already wired for all five voices. Fill in "My material lives in." | First, once |
| `voices/advocate.md` | Voice 1: the strongest case *for* | Core Three |
| `voices/critic.md` | Voice 2: the stress test, aimed at your real blind spot | Core Three |
| `voices/beneficiary.md` | Voice 3: the one real person it's for | Core Three |
| `weaver.md` | Synthesis into one decision | Right after the Core Three. **This is the floor.** |
| `voices/executor.md` | Voice 4: the smallest real first move | Complete your council |
| `voices/long-view.md` | Voice 5: what this sets in motion in two years | Complete your council |
| `voices/_TEMPLATE-voice.md` | Blank voice, for a voice of your own (First Principles, the Compass, a mentor, your future self) | Swap in or add on |

Each voice template has a worked example in `../worked-examples/`: a
real, finished council grounded in one person's actual stories. Read
the matching example before you fill a template. Copy its shape, never
its content.

## The order

1. **Advocate, Critic, Beneficiary.** Build one voice at a time. After
   you save each, run it alone: `council: advocate`. You can test it
   before any other voice exists.
2. **Weaver.** Now you have a Minimum Viable Council: three voices and a
   Weaver, running. That's the floor. Everyone gets here.
3. **Executor and Long View.** Voices four and five.
4. **Run the full council** on one real idea: "run this through my
   council." Compare it to your three-voice read. What did the extra
   voices catch?

Aim for all five and the Weaver. The runner is already built, so the
rest is filling in voices. If you stop at step 2, you still have a
council that works. Any voice you haven't filled in is skipped, not an
error.

## Running it

- **Everyone:** "run this through my council"
- **One voice:** "run this past my critic," or "council: critic"
- **A few voices:** "council: critic and executor"

A single voice never runs the Weaver unless you ask for it.

## How to fill a template

1. Answer the grounding question in the comment at the top first, in
   writing, from your own story cards, hunch, or open questions.
2. Fill **Grounded in** next. Name the story or hunch by the title it
   has in your repo, so the council can find and re-read it. A voice
   grounded in a real story gives sharp feedback. A voice grounded in
   "be skeptical" gives you a fortune cookie. The grounding *is* the
   skill.
3. Then **Always asks**, then the **Sample output**.
4. **Never does** is pre-filled with a default. It's a dial, not a law.
   Turn it up or down until the voice sounds like you.
5. Delete the comments.

## Changing it later

Nothing here is final. To sharpen a voice, re-ground it on a newer story,
add a voice, or retire one that never surprises you, ask Claude: "make my
Critic sharper," "re-ground my Advocate on the story I wrote Tuesday,"
"add a voice called Mentor." Each is an edit to one file, and `SKILL.md`
tells Claude how to keep the Sequence line and trigger description in
sync. A council that never changes has stopped learning.

## No Claude Code?

- **Claude.ai chat:** zip the `council/` folder and upload it as one
  skill. Claude.ai can't read your repo, so paste or attach the stories
  your voices cite.
- **Any other assistant:** every file is plain markdown. Paste one
  filled-in voice plus your idea into its own conversation, repeat for
  each voice, then paste all the outputs plus `weaver.md` into a fresh
  conversation. Same council, done by hand.
