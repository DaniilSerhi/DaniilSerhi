## Daniil Serhieiev

I design systems and have AI agents build them.

Not "I use ChatGPT sometimes" — I write the specifications, the state models and the constraints, then direct agents through the implementation. The interesting part isn't the generated code. It's deciding what the system must never be allowed to do.

---

### 🎯 Currently

Preparing for a **B.Sc. Wirtschaftsinformatik** in Germany — closing the two gaps that actually decide it: **mathematics** and **programming**.

So I built the thing that's making me do it.

---

### 📌 [self-driving-tutor](https://github.com/DaniilSerhi/self-driving-tutor)

**A study system that decides what you learn next — and refuses to let you skip ahead.**

Four agent specifications over two JSON state files. You type `weiter`. It reads its own memory, picks the next step, generates the lesson, grades the answer, and updates the spaced-repetition model.

The design problem wasn't teaching. It was **stopping the learner from escaping into the subject they're already good at**:

- **Protected quota** — the weak subjects have a weekly minimum that the strong one can never displace
- **Mastery gate** — a topic isn't left until you pass on a *later day*. Anything else measures short-term memory
- **Self-downgrade** — report that you needed AI help and the concept is demoted, not passed
- **Pause rule** — come back after a break and you get a comeback drill, not your old bookmark

It once annulled its own grade because the *system* had generated an invalid task. That's in the log.

One month in: school algebra → sequences and limits, 22 graded checks, every failure recorded.

---

### 🛠️ What I actually do

| | |
|---|---|
| **Agentic systems** | Specification-driven development with Claude Code / Gemini CLI · state design · governance layers · prompt architecture |
| **Production** | A full commercial web platform — Next.js, TypeScript, Stripe, i18n — spec'd and shipped without writing the code by hand |
| **Infrastructure** | Linux, Azure, systemd, Python · a Telegram coaching agent running 24/7 in production |
| **Business** | Own registered business · bookkeeping and property accounting at a real-estate firm |

---

### 🌍

🇺🇦 → 🇩🇪 · Ukrainian · Russian · German · English
Ukrainian-born, learned German from zero, now studying in it.

---

### 📫

[sergeevdaniil008@gmail.com](mailto:sergeevdaniil008@gmail.com)
