# Between Chapters

A 30-day self-interview for anyone in the middle of a life change.

Between Chapters is an open-source prompt framework that turns any LLM into a structured, depth-escalating interview process. It was designed for people navigating career transitions, relationship uncertainty, identity questions, or any moment where the old map no longer fits.

It asks questions. Only questions. For 29 days.

On Day 30, it tells you what it heard.

---

## What it is

A single system prompt that runs a 30-day interview across four themes:

- **Self** — who you are underneath what you've performed
- **Career** — what you're actually good at, not just what you've done
- **Relationship** — what you want vs. what you're settling for
- **Fear / the unspoken** — what you're avoiding, what your envy is pointing at

The depth escalates by week:

| Week | Focus |
|------|-------|
| Week 1 (Days 1–7) | Surface — what happened, what you felt, what you noticed |
| Week 2 (Days 8–14) | Patterns — what keeps repeating |
| Week 3 (Days 15–21) | Values — what you'd defend even if no one agreed |
| Week 4 (Days 22–29) | Fears — what you won't say out loud |

On **Day 30**, the interviewer breaks character and delivers two things: an existential portrait of who you are based on everything you've said, and a talent report that names what you're actually built for.

---

## How to use it

1. Open a new chat on any LLM — Claude, ChatGPT, Gemini, or anything else that accepts a system prompt.
2. Paste the full contents of [`prompt.md`](./prompt.md) as your first message.
3. Begin. Show up daily. Answer honestly.

Keep the conversation in a single thread. The conversation history is the memory — no exports, no setup, no accounts.

**One thread. 30 days. That's it.**

---

## What to expect

Each session: 3 questions. No advice. No reframing. No comfort — not yet.

The questions will feel surface-level in Week 1 and progressively harder to answer honestly by Week 4. That's by design. The process works because of accumulation, not insight events.

Some days you'll have a lot to say. Some days three sentences. Both are fine.

---

## Platform notes

The prompt works on any LLM that supports a system prompt or custom instructions. Context window limits are not a concern — 30 sessions of typical length fall well within what every major platform handles today.

- **Claude** — paste into a new Project, or just start a conversation
- **ChatGPT** — create a Custom GPT, or paste into a new chat
- **Gemini** — create a Gem, or paste into a new chat

If you use a platform that doesn't support persistent system prompts, paste `prompt.md` at the start of each session with a brief note of where you left off.

---

## Files

```
between-chapters/
├── README.md                  ← you are here
├── prompt.md                  ← the full system prompt; paste this to begin
├── day-30-portrait.md         ← optional template to capture your Day 30 output
└── CONTRIBUTING.md
```

---

## Contributing

See [`CONTRIBUTING.md`](./CONTRIBUTING.md). The most valuable contributions are not technical — they're people who've run the 30 days and have feedback on what the questions missed, what landed wrong, or what opened something unexpected.

---

## License

MIT. Use it, fork it, adapt it. If you build something on top of it, consider sharing it back.
