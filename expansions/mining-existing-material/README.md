# Mining Existing Material — When You Didn't Start From Zero

*Expansion pack · self-paced · no stage prerequisite — this is a faster
on-ramp to Stage 1, not a later-stage production tool*

> The worked example behind this whole path didn't start with a blank
> page either. A systematic pass over years of old session material is
> what produced Foundry's first patterns and questions — before Foundry
> had a name.

------------------------------------------------------------------------

# When You're Ready (the gate)

Every other pack in this folder asks you to wait for a later stage.
This one runs backwards: it's most useful **before or right at Stage 1**,
and only for one specific situation — you have a backlog of documents
or slides written before you had any system for capturing your own
expertise. Old talks. Session decks. Coaching notes. A wiki you kept for
years and never mined for yourself.

If that's not you — if you're starting genuinely fresh, with no old
material to draw from — skip this pack entirely and go write your first
story card this week. There's nothing here for you yet, and that's not
a gap. Stage 1 exists for exactly that case.

------------------------------------------------------------------------

# The Problem This Solves

`stage-1-feed-the-system.md` asks for one story a week, written from
scratch. That's the right rhythm for someone starting from nothing. But
if you've been doing the work for years — leading, coaching, teaching,
building — you're probably not starting from nothing. You're starting
from a hard drive full of old decks and docs that already contain your
stories, just not in a shape anyone can use yet.

Re-living all of that from memory, one week at a time, throws away
evidence you already wrote down once. This pack is the alternative:
point an AI agent at your old material and let it do a first pass,
surfacing candidate story cards, pattern hunches, and recurring
questions — from what the documents actually say, not from a
retelling.

------------------------------------------------------------------------

# The One Rule This Pack Cannot Break

**Never invent what the source doesn't say.** An old slide deck's
bullet points are usually the *conclusion* of a story, not the story
itself — "share failures, not just wins" is a lesson, not the moment
that taught it. If the underlying moment isn't written down anywhere in
your source material, an extraction pass has two honest choices: leave
that field blank, or flag it as something only you can supply. Making
up a plausible-sounding moment to fill the gap is the one failure mode
this pack exists to prevent — and it is *not* a hypothetical: the
original Foundry has at least one story it knows it lost this way, a
personal story its own facilitation notes reference by name but never
actually wrote down, and its Open Questions record says plainly that it
"should not be reconstructed from the session description alone."

This is the same hard rule this whole repo already runs on — **never
write the person's stories for them** — applied to a document instead
of a conversation. The AI's job is to find what you already wrote and
put it in a shape you can use. It is not the AI's job to guess what you
meant.

------------------------------------------------------------------------

# What It Produces

Point the agent at a folder or a handful of files (`.pptx`, `.docx`,
`.pdf`, `.md`, `.txt` all work) and it drafts, into **one new file you
name yourself** — never into `templates.md` or any path file:

- **Story Card candidates**, in the exact shape from `templates.md`,
  using the source's own words for "What happened" and leaving "What it
  revealed" honestly blank if the source never states it
- **Pattern Hunch candidates**, only where the same lesson shows up in
  at least two sources from genuinely different contexts — one strong
  appearance is a story, not a pattern yet
- **Question candidates**, where a question recurs across sources
- **A "Needs You Directly" list** — the moments a source references but
  doesn't actually capture, named honestly instead of filled in

Every candidate carries a source citation (file name, slide or page
number) so you can check it against the original before you trust it.

None of it is a finished story yet. All of it is a draft, in your
words, waiting for the same read-through and honest judgment every
story in Stage 1 gets — just starting from a document instead of a
blank page.

------------------------------------------------------------------------

# Installing It (any tool — capability travels)

**Fastest path — Claude users:** download
**[mining-existing-material.skill](mining-existing-material.skill)**
from this folder and drop it into Claude — in a chat, in Cowork, or
into `.claude/skills/` in Claude Code. It's already packaged and ready
to run: attach your old material and it starts the process on its own,
no prompting required.

**Any other AI assistant with standing/custom instructions** (ChatGPT
custom instructions, a Claude Project, a Gemini Gem): paste the body of
`SKILL.md` in as the instructions, then attach or paste in your source
material.

**Anything else:** paste `SKILL.md`'s body at the top of a fresh
conversation, then paste in your source material. One extra step, same
result.

------------------------------------------------------------------------

# The Guardrails (same family as `ai-thinking-partner.md`)

1.  **Drafts, never promotions.** The output is candidates in a new
    file, not additions to your Story Library. You still do the
    reading, the judging, and the moving-into-place by hand.
2.  **Cited, always.** Every candidate names the exact source it came
    from. If you can't tell where a candidate came from, don't trust
    it.
3.  **Silence is an honest answer.** A source with no real specifics
    behind its conclusions should produce fewer candidates, not
    stretched ones. A short output from a thin source is the pack
    working correctly, not underperforming.
4.  **A pattern needs two contexts, not two mentions.** The same deck
    reused for three audiences is one context, said three times — not
    three pieces of evidence.

------------------------------------------------------------------------

# One Meaningful Next Step

Don't run this on your whole archive today. Pick the single oldest
thing you can find — one old deck, one set of session notes — and run
it on that alone. Read what comes back against the source with your own
eyes before you trust the shape of the output on anything bigger.
