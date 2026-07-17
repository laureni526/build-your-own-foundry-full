# Practice Documents — When Your Foundry Starts Producing Work

*Expansion pack · self-paced · most useful at Stage 4 and beyond*

> Rules in files, not requests in prompts.
>
> That's the whole insight. Everything below is how to earn it.

------------------------------------------------------------------------

# The Problem This Solves

Somewhere around Stage 4, your Foundry stops being only a system of
reflection and starts being a system of *production*. You have moves
you use more than once. You have a language page. And you have
deliverables that keep recurring — a monthly session you design, a
deck you build, a report you write, a coaching engagement you
structure.

Then you notice something frustrating: **every time you produce one,
you re-explain yourself.** To a collaborator. To an AI assistant. To
yourself, six weeks later. The quality swings with the quality of the
re-explaining. Some days the output sounds like you; some days it's
generic — and you can't say why, because the rules that make it yours
live in your head and leave no trail.

A **practice document** is the fix: one versioned file that captures
how you produce a recurring deliverable — completely enough that a
collaborator, an AI, or future-you can follow it and get *your*
quality, not a generic approximation of it.

This is not a new idea bolted onto the path. It's the same rule your
whole Foundry runs on, pointed at production: don't re-derive what
you've already earned. Write it down, version it, and make the next
one compound on the last one.

------------------------------------------------------------------------

# When You've Earned One (and when you haven't)

Write a practice document when **all three** are true:

1.  **The deliverable recurs.** You've produced it at least twice, and
    you expect to produce it again.
2.  **You've caught yourself re-explaining.** The same instructions,
    preferences, or corrections keep coming out of your mouth or
    keyboard.
3.  **You can name at least one thing that went wrong** — a failure
    you'd recognize if it happened again. (If nothing has gone wrong
    yet, you don't know the rules well enough to write them.)

One-off deliverable? Don't. Rules you *think* you'd want but haven't
tested? Not yet — that's writing "My 10 Principles" all over again,
just for production. The default answer is the one you know: keep
observing.

------------------------------------------------------------------------

# The Shape

A practice document has five parts. The order matters less than their
separation — especially the first split.

## 1. Method vs. style — keep them separate

The **method** is what stays true about producing this deliverable no
matter how your taste evolves: the invariants, the process, the
quality bar. The **style** is your current voice, palette, format,
tone — expected to change, and versioned so it *can* change without
touching the method.

This split is what makes the document survive. When your style
evolves (it will), you update one section and the method stands. When
you learn a new failure mode, the anti-pattern list grows and your
style is untouched.

## 2. Invariants — the non-negotiables, stated as non-negotiables

The small set of rules that apply to every instance, every time, no
exceptions. Write them like you mean them ("one idea per slide";
"never invent a statistic"; "every session ends with one meaningful
next step, not a list"). If a rule has exceptions, it isn't an
invariant — it's guidance, and it goes elsewhere.

## 3. The anti-pattern list — name the exact failure

This is the highest-leverage part, and the least intuitive: a list of
the *specific* failures you've observed, stated concretely enough to
recognize on sight. Not "avoid being generic" — that's a wish. Instead:
"no decorative shapes that carry no meaning," "no opening with the
framework before the question," "no bullet lists longer than the
thinking behind them."

Vague rules produce vague compliance. Named failures get caught.
Every time an instance goes wrong in a new way, the list grows by one
line — and that failure never needs to be re-litigated.

## 4. The evidence log — why each rule exists

A short table: date, what happened, what it taught. This is what
separates a practice document from a style guide someone handed you.
Every rule traces to a moment. When you (or an AI, or a collaborator)
wonders "does this rule really matter?", the log answers with a story
instead of an assertion.

## 5. Version and promotion path

Date it. Number it (v0.1, v0.2 …). And write down what would promote
it from draft to trusted — the same discipline as the rest of your
Foundry. A reasonable bar: **it survives three real instances without
major revision.** Until then it's a hypothesis about how you work,
and hypotheses are allowed to be wrong.

------------------------------------------------------------------------

# Why This Changes Your AI Work Specifically

If you use an AI assistant to help produce the deliverable, the
practice document quietly becomes the most valuable file you own.

Describing your standards conversationally — "make it warm but
professional, not too wordy, you know, like last time" — produces
different results every time, because every conversation starts from
zero. Pointing the AI at a practice document produces *convergent*
results, because the rules are identical on every run. The
anti-pattern list matters double here: AI systems drift toward the
same generic failures over and over, and naming the exact failure is
what suppresses it. "Don't be generic" does nothing. "No decorative
corner arcs" works.

This is also the honest division of labor. The AI brings speed and
range. The document brings *you* — your evidence, your taste, your
hard-won rules. Capability travels; tools don't. The practice document
is how your capability travels into whatever tool you're using this
year, and the next one.

*(This pairs with `ai-thinking-partner.md`'s guardrails: the AI
follows your practice document; it doesn't write it. A rule the AI
proposed but you never saw fail is not a rule — it's a suggestion
awaiting evidence.)*

------------------------------------------------------------------------

# A Real Trace (how one of these actually gets earned)

From the original Foundry, condensed — the pattern, not the specifics:

1.  A deliverable recurred (professional-development sessions for a
    community; separately, slide decks).
2.  The re-explaining tax showed up: each new session or deck meant
    re-stating the same standards, and quality swung.
3.  A failure got named: an AI-generated deck came back with
    decorative shapes that carried no meaning. Instead of just fixing
    the deck, the failure went into an anti-pattern list — one line,
    permanent.
4.  The rules moved into versioned files: method separated from
    style, invariants stated as invariants, an evidence log recording
    where each rule came from, a promotion path requiring three real
    instances.
5.  The next instance started from the document instead of from a
    blank conversation — and the document caught a rule violation *its
    own author* made while building the very first test. That's the
    sign a practice document has teeth: it corrects you, too.

Two practice documents, different domains, same shape. That's what
earned this expansion pack a place here — the same bar your patterns
have to clear.

------------------------------------------------------------------------

# The Template

``` markdown
# [Deliverable] Practice v0.1 (Draft)

*Practice document · started [date]*

**Status:** Draft — becomes trusted after three real instances
without major revision.

## Purpose
[What this deliverable is, who it's for, and what "good" looks like
in two sentences.]

## Method (stable)
**Invariants — every instance, no exceptions:**
- [rule]
- [rule]

**Anti-patterns — named failures, observed, never repeated:**
- ✗ [specific failure] *(seen [date/instance])*
- ✗ [specific failure]

**Process:** [the steps that reliably produce it, only as much
detail as you actually follow]

## Style (current — versioned, expected to change)
[Voice, format, structure, palette — whatever "sounds/looks like me"
means for this deliverable, concretely. When this changes, bump the
version and note why in the log.]

## Evidence log
| Date | What happened | What it taught |
|---|---|---|
| | | |

## Promotion path
Draft → trusted after [your bar — e.g., three real instances].
Version on every style change: v0.2, v0.3 …
```

------------------------------------------------------------------------

# One Meaningful Next Step

Name the one deliverable you've re-explained most often — the one
where you can already hear yourself saying the same three corrections
again. Don't write the whole document. Write only the anti-pattern
list, from memory, tonight: every failure you've actually seen, one
line each.

If you get three or more lines, you've earned the rest of the
document. If you can't get three, that's not a failure either — it's
evidence the deliverable hasn't taught you its rules yet. Keep
producing. Keep observing.
