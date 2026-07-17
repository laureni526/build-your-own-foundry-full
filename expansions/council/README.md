# The Foundry Council — Build a Thinking Partner From Your Own Evidence

*Expansion pack · self-paced · works alongside any stage of the Solo Path
from Stage 1 onward*

> Not five generic AI personas. A council of voices that argue from
> your own stories — and disagree with each other in front of you.
>
> A generic Critic prompted with "be skeptical" pokes at surface-level
> risk. A Critic grounded in *your actual pattern hunch and your open
> questions* pokes at the blind spot you've already half-admitted to
> having. Same role. Entirely different value.

This pack exists as a live buildathon session too. If you're planning
to attend that session, you can stop reading — building it twice makes
the second build worse, because the surprise is part of the learning.
This self-paced version is for everyone else: you're not attending,
you attended and want to rebuild it properly, or you're working the
Solo Path on your own and your evidence is ready to be *used*.

------------------------------------------------------------------------

# What You Need Before Starting

The Council isn't a separate exercise. It's the first real use of your
Foundry's raw material. You need:

-   A few **story cards** (2–3 minimum; Stage 1 depth makes every
    voice sharper)
-   One **pattern hunch**, honestly stated
-   Your **Open Questions page** with at least one question that
    actually worries you

If you don't have these yet, the answer is the one you already know:
not yet. Go write two story cards and come back. Five fresh personas
bolted onto a philosophy that doesn't exist yet is just generic AI
roleplay with better branding.

**Tools:** the files in this folder are written as [Claude Code](https://claude.com/claude-code)
skill files, and that's the smoothest path. But every voice file also
works as a plain copy-paste prompt in any capable AI assistant —
capability travels, tools don't. A "how to run it anywhere" note is at
the end.

------------------------------------------------------------------------

# The Finish Line (deliberately small)

> **The Minimum Viable Council = 3 voices + the Weaver, actually
> running on one real idea.**

That's a complete, useful thinking partner. Everything past it — more
voices, custom voices, the one-command runner — is enrichment layered
on a thing that already works. Build in an order where you *always*
have something that runs:

1.  **Core Three voices** — build and test each one alone.
2.  **The Weaver** — synthesis. Reaching here = Minimum Viable
    Council. If you stop here, you still won.
3.  **The runner** — one command convenes everyone. A reach goal, not
    a requirement.
4.  **Then customize** — add, swap, or invent voices. This is where it
    becomes yours.

A council is only as good as the **disagreement** it produces. Its
value isn't five nice opinions — it's the friction between them, which
the Weaver turns into one real decision.

------------------------------------------------------------------------

# The Core Three

They form the tightest universal tension triangle: *is it great / will
it break / does anyone it's for actually care.*

Every voice is calibrated **before** a line of prompt is written, by
answering one grounding question from your own material. That
calibration step is the whole game — skip it and all your voices sound
the same.

## The Advocate — the strongest case *for*

A lawyer for the idea's best version, not a cheerleader.

> **Grounding question:** Look at your pattern hunch. What's the
> version of this idea that fully honors it — what would it look like
> if this pattern got to be completely true here?

## The Critic — the stress test

Names the blind spot, the assumption, the thing that breaks.

> **Grounding question:** Open your Open Questions page. Which
> unresolved question, if ignored, would sink this idea? Aim the
> Critic at *that* — not at generic risk.
>
> *(No Open Questions page yet? What's the thing about your work
> you're quietly hoping nobody asks about? That's your open question.
> Have the Critic ask it out loud.)*

## The Beneficiary — the person it's for

Not a customer persona — one real human on the other end.

> **Grounding question:** Who is this actually for? Picture one of
> them. What do they need, what do they feel, and — honestly — would
> they even care about this?

------------------------------------------------------------------------

# Building a Voice

Copy `_TEMPLATE-voice.md` once per voice. Fill in **"Grounded in"
first** — a voice grounded in a real story gives sharp feedback; a
voice grounded in "be skeptical" gives you a fortune cookie. The
grounding *is* the skill.

Before you write your first voice, read
[`worked-example-advocate.md`](worked-example-advocate.md) — one real,
finished voice from the original Foundry, grounded in an actual
pattern hunch and named stories. Notice that every line points at
specific evidence. That's the standard. (The complete worked council —
five voices, Weaver, and runner — lives in the
[original Foundry repository](https://github.com/laureni526/foundry/tree/main/public/workshops/build-your-own-foundry/council-buildathon/lauren-council-example).)

**Installing in Claude Code:** each file here is the *body* of a
skill. In your project folder create `.claude/skills/<voice-name>/`,
save the filled-in file inside as `SKILL.md`, and make sure the
`name:` in the frontmatter matches the folder name. Now "run this past
my critic" fires just that voice.

Then build the **Weaver** (`weaver.md` — mostly done, you list your
voices) and, if you want the reach goal, the **runner** (`council.md`
— pre-wired, you fill in your sequence).

------------------------------------------------------------------------

# The Test Round (do not skip this)

A council you never ran is a folder of untested prompts.

-   Bring **one real idea you're actually deciding on** — not a
    hypothetical.
-   Run it through the council. Read the outputs cold, without
    explaining or defending the idea first.
-   **The diagnostic question:** did any voice tell you something you
    didn't already know — or did they all just agree with you in
    different tones?

If every voice agrees, the calibration isn't done. Go back to the
grounding questions — not the prompt wording.

Stuck for a test idea? A side project you've mentioned but never
started. A decision you're avoiding at work. "Should I start posting
publicly about my expertise?" Or the council itself: "Should I keep
using this, and how?"

------------------------------------------------------------------------

# When It Goes Wrong (it will — this is the fix table)

| Symptom | Likely cause | Fix |
|---|---|---|
| Voices all sound the same | Calibration skipped or answered generically | Go back to a specific story card, not a vibe |
| Critic is just mean | Grounded in "be skeptical," not a real open question | Re-anchor to one named question |
| Advocate is just cheerleading | No pattern-hunch reference | Anchor to what the hunch *predicts*, not enthusiasm |
| Two voices blur together | Both grounded as "the skeptical one" | Give each its own lane: Critic → execution risk; Beneficiary → does it help the real person; a First-Principles voice → the premise itself |
| Beneficiary sounds like a market-research slide | No specific person pictured | Picture one real face and write from their situation |
| Weaver just lists what each voice said | No real friction to synthesize | Rebuild it after a test round that produced actual disagreement |
| Stuck at zero | Perfectionism on voice #1 | Clone the worked example, then edit until it's yours |

------------------------------------------------------------------------

# Growing the Council (the menu)

Once the Minimum Viable Council runs, add voices that would genuinely
change your thinking — and only those:

-   **The Executor** — the how. Ground it in the story where you
    actually shipped something under real constraints.
-   **First Principles** — should this exist at all? Ground it in your
    North Star question specifically.
-   **The Long View** — what does this set in motion, for you and for
    others, over the next two years? The voice most people are missing
    and don't realize it.
-   **The Compass** — does this fit who I am and what I'm building
    toward? Maps to whatever your Stage 5 foundations become.
-   **Your own.** A specific mentor's voice. Your future self. The
    skeptic who always finds the flaw. If a voice would genuinely
    change your thinking, build it.

And retire voices that never surprise you. A voice that always agrees
is dead weight.

As your Foundry grows, **re-ground the voices.** New stories and new
open questions should flow back into the council — a council that
never changes is a council that's stopped learning.

------------------------------------------------------------------------

# Running It Without Claude Code

Every file here is plain markdown. In any AI assistant:

1.  Paste a filled-in voice file and your idea → that voice's read.
2.  Repeat per voice, in separate conversations (separate matters —
    voices that can see each other's answers start agreeing).
3.  Paste all the outputs plus `weaver.md` into a fresh conversation →
    the synthesis.

That's the whole orchestration, done by hand. One more step, same
council.

------------------------------------------------------------------------

# One Meaningful Next Step

Don't build the council today. Answer **one grounding question** — the
Advocate's — in writing, from your actual pattern hunch. If the answer
points at real evidence, you're ready to build. If it comes out
generic, that's not a failure; it's your Foundry telling you which
stories it still needs.

> The council doesn't replace your judgment. It creates the conditions
> where your judgment has something real to push against.
