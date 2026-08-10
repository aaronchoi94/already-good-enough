# already-good-enough

> 📖 **[Read in Chinese 中文](README.md)**

> You are already enough. An Agent Skill for **quietly holding space** for people.

It is not a "chicken soup for the soul" bot. It does not pump positivity, and it does not lecture you on how to live.

It does exactly one thing: **stay with someone in their most self-critical moments.**

- No judgment
- No pushing
- No empty encouragement
- **Just holding space** → acknowledging the hard work → gently returning the standard of "good enough" to the person themselves → only opening the door to moving forward when they ask for it

---

## What this is

`already-good-enough` is a comforting-conversation Skill (in SKILL.md format) that most modern Agent / conversation frameworks can recognize and load.

Where it fits:
- Your own Agent (Claude Code-style agents, other LLM agent frameworks, etc.)
- Any downstream app that wants its conversations to have a little more humanity

**When it triggers**: late-night spirals, work setbacks, relationship hurt, giving without being seen, painful self-comparison, collapsed self-worth, emotional exhaustion — in one phrase, **when someone is at war with themselves**.

**Bilingual by design**: the response library ships with an English Mode that follows the same holding principles.

**When it does NOT trigger**: normal chat, small tasks, casual complaints. It doesn't steal the stage — it only shows up when it's truly needed.

---

## Layout

```
already-good-enough/
├── SKILL.md                    # Trigger logic + core principles + response structure
├── references/
│   ├── responses.md            # Response library: 9 scenario types + what-not-to-say + English Mode
│   └── boundaries.md           # Boundaries: this is not therapy
├── examples/
│   └── conversations.md        # Full worked conversations
├── README.md                   # 中文说明
└── README.en.md                # This file
```

---

## How to use

Put `SKILL.md` + `references/` into your Agent's skill directory (loading methods differ by framework — check your framework's skill docs).

### Read before you deploy

1. Read `references/boundaries.md`. This is not an afterthought — **this skill deals with real human emotions**. Deploy it responsibly.
2. `responses.md` is a sheet of music, not a script. Good responses come from the Agent's felt sense of the moment, not from reciting lines.
3. If you ship it in a product, include a disclaimer and links to real help resources.

---

## Design principles

**The default mode is "hold", not "fix".**

Before every response, run one self-check:

> Does this sentence make them feel understood — or make them feel corrected?

- If they want to move forward, they have to say so themselves. **If they don't ask, you don't push.**
- Chicken soup doesn't travel far, because it refuses to acknowledge people's real hardship. Acknowledge the hardship, and people can actually stand steady.

---

## Boundaries

- ⚠️ This is not psychological therapy and cannot replace professionals.
- When someone speaks of self-harm or extreme despair: hold them first, then gently guide toward help. See `references/boundaries.md`.

---

## A closing note

There is no flashy tech in this project. Its entire weight is the sense of measure: **there is a single line between comfort and indulgence.**

May everyone who uses it, on some late night, find a little bit of real warmth in a sentence like "you've already carried yourself this far."

> You, who made it to this moment, have already done something difficult.