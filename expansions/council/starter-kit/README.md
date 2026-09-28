# Foundry Council — Starter Kit

Everything you need to build a full council today, so nobody starts
from a blank page. There's one template per voice, already shaped, with
its grounding question built in. You bring the evidence.

## What's in here

| File | What it is | When you build it |
|---|---|---|
| `advocate.md` | Voice 1: the strongest case *for* | Core Three |
| `critic.md` | Voice 2: the stress test, aimed at your real blind spot | Core Three |
| `beneficiary.md` | Voice 3: the one real person it's for | Core Three |
| `weaver.md` | Synthesis into one decision | Right after the Core Three. **This is the floor.** |
| `executor.md` | Voice 4: the smallest real first move | Complete your council |
| `long-view.md` | Voice 5: what this sets in motion in two years | Complete your council |
| `council.md` | The one-command runner, pre-wired for all five | Complete your council |
| `_TEMPLATE-voice.md` | Blank voice, for a voice of your own (First Principles, the Compass, a mentor, your future self) | Swap in or add on |

Each voice template has a worked example in `../worked-examples/`: a
real, finished council grounded in one person's actual stories. Read
the matching example before you fill a template. Copy its shape, never
its content.

## The order

1. **Advocate, Critic, Beneficiary.** Build and test each one alone.
2. **Weaver.** Now you have a Minimum Viable Council: three voices and a
   Weaver, running. That's the floor. Everyone gets here.
3. **Executor and Long View.** Voices four and five.
4. **Council runner.** One command convenes all five, then the Weaver.
5. **Run the same idea through the full council** and compare it to your
   three-voice read. What did the extra voices catch?

Aim for all five, the Weaver, and the runner. The templates are built so
that's reachable in one sitting. If you stop at step 2, you still have a
council that works.

## How to fill a template

1. Answer the grounding question in the comment at the top first, in
   writing, from your own story cards, hunch, or open questions.
2. Fill **Grounded in** next. A voice grounded in a real story gives
   sharp feedback. A voice grounded in "be skeptical" gives you a
   fortune cookie. The grounding *is* the skill.
3. Then **Always asks**, then the **Sample output**.
4. **Never does** is pre-filled with a default. It's a dial, not a law.
   Turn it up or down until the voice sounds like you.
5. Delete the comments.

## How to install a skill (Claude Code)

Each file here is the body of a Claude Code skill. In your own project:

1. Create `.claude/skills/<voice-name>/` (for example
   `.claude/skills/critic/`).
2. Save the filled-in file inside it as `SKILL.md`.
3. Make sure the `name:` in the frontmatter matches the folder name.

Then "run this past my critic" fires one voice, and, once you've built
the runner, "run this through my council" fires all of them.

## No Claude Code?

Every file is plain markdown. In any AI assistant, paste one filled-in
voice plus your idea into its own conversation, repeat for each voice,
then paste all the outputs plus `weaver.md` into a fresh conversation.
Same council, done by hand.
