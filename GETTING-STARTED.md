# Getting Started

Two paths to building your personal context portfolio. Pick whichever fits.

---

## Path 1: Use the Interview App

The most natural way. A purpose-built interviewer handles the whole process — calm, unhurried, one question at a time.

1. Go to [app URL].
2. The interviewer introduces the process and starts with your origin story.
3. It works through all ten files in sequence — asking questions, drafting each file, and asking you to tell it what it got wrong.
4. You can stop after any file and come back later. It picks up where you left off.
5. When you're done, download your complete portfolio.

The whole thing takes 30-60 minutes if you do it in one sitting. Some files are heavier than others — you might want to spread it out.

---

## Path 2: Do It Yourself

Fork this repo and work through the templates with your own AI (Claude, ChatGPT, or whatever you use).

1. Fork or clone this repo.
2. Open any template file from `/templates`.
3. Copy the entire file and paste it to your AI.
4. Say "let's do this one."
5. Your AI will read the interview protocol embedded in the template and start asking you questions.
6. When it has enough, it'll draft the file. Read the draft and tell it what's wrong.
7. Save the final version. Move to the next template.

**Recommended order:** Start with `origin-story.md` — everything builds from there. After that, `values-and-beliefs.md` and `inner-life.md` give the deepest foundation. The rest can go in any order, though the sequence below is designed so each file builds on what came before.

**Full sequence:**

1. `origin-story.md`
2. `values-and-beliefs.md`
3. `inner-life.md`
4. `relationships.md`
5. `how-i-think.md`
6. `aesthetics-and-taste.md`
7. `body-and-health.md`
8. `communication-and-voice.md`
9. `unresolved-questions.md`
10. `aspirations-and-fears.md`

---

## After You Build It

Your portfolio is a set of markdown files. That's the point — they're portable. But they don't do anything until you wire them into the tools you actually use.

The `/wiring` directory has guides for:

- Copy-paste patterns for system prompts (works with anything)
- Using it in Claude Projects
- Exposing your portfolio as an MCP resource
- Connecting it to custom agent systems
- Building an API layer

Start with whatever tool you use most.

---

## Tips

- **Be honest, not aspirational.** The portfolio should describe who you actually are, not who you wish you were. Your AI needs ground truth, not a flattering profile.
- **Don't skip the reaction pass.** When your interviewer drafts a file, read it and find what's wrong. The corrections are where the real signal is. A rubber-stamped draft is a mediocre file.
- **Short is better than long.** A good context file is one page, not five. AI systems perform better with dense, high-signal context than with sprawling documents.
- **Some files will be harder than others.** The inner life, fears, and unresolved questions files ask you to be more vulnerable than a typical AI interaction. Take your time. A short honest file beats a long performative one.
- **Update when you change.** Not on a schedule — when something real shifts. You resolve a question, a relationship changes, you learn something about yourself. That's when you update.
- **You can skip files.** If a file doesn't feel relevant or you're not ready for it, skip it. A portfolio with seven real files beats ten forced ones.
