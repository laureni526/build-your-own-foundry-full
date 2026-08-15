---
name: mining-existing-material
description: Extracts story, pattern, and question candidates from documents and slide decks written before this person had a Foundry-style system — old talks, session decks, coaching notes, a wiki export, a folder of past docs or PDFs. Drafts them into the Story Card / Pattern Hunch / Question shapes from templates.md and stages them in one new file, using the source's own words and never inventing narrative the source doesn't contain. Use whenever the person mentions an old deck, a past talk, an existing wiki, or a folder of old material, and wants to seed their Story Library from it instead of starting from a blank page. Requires `expansions/mining-existing-material/README.md`'s gate to already apply — a real backlog of pre-Foundry material, not aspiration. Not for capturing a brand-new story from a live conversation — that's the ordinary Stage 1 interview in `stage-1-feed-the-system.md`.
---

# Mining Existing Material

Read `expansions/mining-existing-material/README.md` first if you haven't
— it has the full reasoning. This file is the operating instructions.

## The one rule this skill cannot break

**Never invent what the source doesn't say.** This repo's `AGENTS.md`
already states the hard rule this extends: *do not write the person's
stories for them.* Applied to a document instead of a live conversation,
that means: use the source's own words for concrete details, and when a
field a template asks for isn't actually stated in the source, leave it
honestly unfilled rather than writing something plausible. A source that
references a moment without capturing it ("tell the bathroom door
story") is not the same as a source that contains the moment — treat
the first as a gap to flag, never as raw material to reconstruct from.

## Process

1.  **Get the source material.** Ask which files or folder to work from.
    Read `.pptx`, `.docx`, `.pdf`, `.md`, `.txt` in full — slide text
    *and* speaker notes, document body *and* headers. Speaker notes
    often hold the actual story a slide only gestures at.

2.  **Read for concrete units, not conclusions.** A deck's bullet points
    are usually the lesson, not the moment that taught it. Look for: a
    specific named event, a decision, an exchange with a real person, a
    mistake, a turning point, advice repeated more than once, a question
    asked repeatedly, an exercise taught more than once. A slide that
    only states a conclusion, with no specifics anywhere in the source,
    isn't a story candidate — it may be a question or pattern candidate
    instead, or nothing yet.

3.  **Draft each candidate in the exact shape `templates.md` defines** —
    match its structure, don't invent your own. Use the source's own
    language for "What happened." If "What it revealed" isn't stated
    anywhere in the source, write `Not stated in source — needs your
    read` instead of inferring a lesson that sounds right.

4.  **Watch for repetition across sources, not within one file.** A
    framework taught in three different decks, or a question that opens
    five different sessions, is stronger evidence than anything seen
    once. Note the count and the actual contexts — don't round up to
    "always," and don't count the same deck reused for different
    audiences as more than one context.

5.  **Flag what needs them directly.** Anything a source references
    without capturing goes on a "Needs You Directly" list, not into a
    Story Card. This is the highest-leverage rule in this whole skill:
    getting this wrong produces a confident-sounding fake story instead
    of an honest gap.

6.  **Write everything to one new file, named by the person** (e.g.
    `mined-stories-{source-name}.md`) — never into `templates.md`,
    `stage-1-feed-the-system.md`, or any other path file. If they don't
    have a place for it yet, ask where they keep their working notes and
    put it there.

7.  **Close with a plain summary and stop — don't advance them.** How
    many candidates of each type, how many sources, how many flagged as
    needing them directly, and where the file landed. Then the same
    pacing rule as the rest of this repo applies: this is not permission
    to walk them into Stage 1's pattern check or anything else. Wait for
    them to say they want to keep going.

## Output shapes

Use `templates.md`'s Story Card, Pattern Entry, and Question Library
Entry shapes exactly. Two additions specific to extraction:

**On every Story Card**, add a source line right under the title:
```
Source: {file}, {slide/page/section}
Status: unreviewed candidate
```

**A Needs You Directly list**, appended once at the end of the output
file:
```markdown
## Needs You Directly

- **{Topic}** — {what the source references without capturing}. Not
  reconstructed — this needs you.
```

Only draft a Pattern Entry when the same lesson appears in **at least
two sources from genuinely different contexts.** One strong appearance,
however compelling, is a Story candidate — not a pattern yet. That
threshold is `templates.md`'s own rule for pattern hunches, applied
here without a discount for how much material a single extraction pass
turned up.

## What this skill is not for

- It doesn't write a story from something the person tells you live —
  that's the ordinary Stage 1 interview.
- It doesn't decide what's ready to promote from hunch to pattern to
  principle — that call belongs to the human, same as everywhere else
  in this repo.
- It doesn't touch `templates.md`, any `stage-*.md` file, or
  `participant-worksheet.md`. It only ever creates one new file the
  person can find again.

## When you're done

Tell them plainly what you drafted, from which sources, what got
flagged as needing them directly, and where the file is — the same
transparency `AGENTS.md` asks for everywhere else in this repo. This
system depends on them understanding their own material, not on files
appearing.
