# Personal Context Portfolio

Every AI you work with starts from zero. It doesn't know your story, your values, what you're afraid of, how your mind works, or what you sound like. You re-explain yourself every time — or more likely, you don't, and the AI fills in the gaps with generic assumptions about a generic person.

The personal context portfolio fixes this. It's a structured set of markdown files that together represent you as a whole person — not your work history or your professional profile, but who you actually are. Your origin story, your inner life, your relationships, your taste, the questions you're carrying. Something any AI system can read and immediately understand the human it's working with.

It's not a resume. It's not a personality quiz. It's the context that makes AI feel like it knows you.

## What's In It

Ten files, each covering a different dimension of who you are:

| File | What It Captures |
|------|-----------------|
| `origin-story.md` | Where you come from — the narrative, the turning points, the through-line |
| `values-and-beliefs.md` | What you actually orient around — visible in choices, not just words |
| `inner-life.md` | Practices, recovery, philosophy, what you're working on in yourself |
| `relationships.md` | The people who matter and your patterns in how you connect |
| `how-i-think.md` | Your cognitive shape — how you process, what grabs you, where you get stuck |
| `aesthetics-and-taste.md` | What you're drawn to across everything — the things that reveal you sideways |
| `body-and-health.md` | Physical reality, what you're managing, hard boundaries |
| `communication-and-voice.md` | How you actually talk and write — your voice, not a style guide |
| `unresolved-questions.md` | What you're sitting with — the open loops, the things you haven't figured out |
| `aspirations-and-fears.md` | Where you're pointed and what scares you — in life terms, not career terms |

## Design Principles

**Markdown-first.** Every AI system on earth can read markdown. It's the universal interchange format for context. Not JSON, not PDFs, not databases. Markdown files that are human-readable AND machine-readable.

**Modular, not monolithic.** Not one giant "about me" file. Separate files for separate domains. An AI helping you think through a relationship doesn't need your cognitive patterns — it needs your relationships file and maybe your values. Modularity lets systems grab what's relevant.

**Living, not static.** This isn't a thing you write once. You'll change your mind, resolve questions, find new ones, become a different version of yourself. The portfolio evolves with you.

**Portable across everything.** Works with Claude, works with ChatGPT, works with custom agents, works with whatever comes next. No vendor lock-in. It's just files.

**Honest, not aspirational.** These files describe who you actually are, not who you wish you were. An AI working from an aspirational profile will give you confident but wrong responses. Ground truth beats flattery.

## Two Ways to Build Yours

**Use the interview app.** A purpose-built interviewer agent walks you through the whole process. Calm, unhurried, one question at a time. You talk, it drafts, you correct what it gets wrong, and you walk away with your complete portfolio.

**Do it yourself.** Fork this repo and use the templates in `/templates`. Each template includes the interview questions and the output structure. Hand any template to your AI of choice and say "let's do this one."

## After You Build It

The portfolio is raw material. What makes it powerful is wiring it into the systems you actually use. The `/wiring` directory has guides for exposing your portfolio as an MCP resource, using it in Claude Projects, connecting it to agent systems, and more.

## Repo Structure

```
personal-context-portfolio/
├── README.md                    <- you are here
├── GETTING-STARTED.md           <- step-by-step for both paths
├── templates/                   <- empty templates with interview protocols
├── examples/                    <- filled-out examples (coming soon)
├── wiring/                      <- guides for connecting your portfolio to AI tools
└── interview-protocol/
    └── agent-system-prompt.md   <- the full system prompt for the interview experience
```

## License

MIT. Fork it, customize it, use it however you want.
