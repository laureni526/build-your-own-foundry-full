# Foundry Council — Starter Kit

Everything you need to build your council today, so nobody starts from a
blank page. Copy these, fill the blanks, and you have a working council.

## What's in here

- **`_TEMPLATE-voice.md`** — the blank voice skill. Copy it once per voice
  and fill it in. Start with your Core Three: an **Advocate**, a
  **Critic**, and a **Beneficiary**.
- **`weaver.md`** — the synthesis skill. Mostly done already — the
  synthesis logic is generic. You just tell it which voices it reads.
- **`council.md`** — the one-command runner (the reach goal). Pre-wired;
  you fill in the sequence of your own voices.

For a full worked example — five real voices, a Weaver, and a runner, all
grounded in one person's actual material — see the
`../worked-examples/` folder. Read the Advocate there before you write
yours; it shows what "grounded, not generic" looks like.

## How to install a skill (Claude Code)

Each file here is the *body* of a Claude Code skill. To make it real in
your own project:

1. In your project folder, create `.claude/skills/<voice-name>/`.
2. Save the filled-in file inside it as `SKILL.md`.
3. Make sure the `name:` in the frontmatter matches the folder name.

Now you can invoke a single voice ("run this past my critic") or, once
you've built the runner, the whole council ("run this through my
council").

## The one rule that matters

Fill in **"Grounded in"** before you write anything else in a voice. A
voice grounded in a real story, your pattern hunch, or a real open
question gives sharp feedback. A voice grounded in "be skeptical" gives
you a fortune cookie. The grounding *is* the skill.
