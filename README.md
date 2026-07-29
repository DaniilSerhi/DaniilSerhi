<h1 align="center">Daniil Serhieiev</h1>

<p align="center">
  <b>I design systems and direct AI agents to build them.</b><br>
  Founder of a shipped, revenue-capable product · preparing for a B.Sc. in Business Informatics
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Next.js-16-000000?style=flat-square&logo=nextdotjs&logoColor=white">
  <img src="https://img.shields.io/badge/TypeScript-5-3178C6?style=flat-square&logo=typescript&logoColor=white">
  <img src="https://img.shields.io/badge/React-18-61DAFB?style=flat-square&logo=react&logoColor=black">
  <img src="https://img.shields.io/badge/Stripe-20-635BFF?style=flat-square&logo=stripe&logoColor=white">
  <img src="https://img.shields.io/badge/Tailwind-3-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white">
  <img src="https://img.shields.io/badge/Python-3.11-3776AB?style=flat-square&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/Azure-Linux-0078D4?style=flat-square&logo=microsoftazure&logoColor=white">
  <img src="https://img.shields.io/badge/Claude_Code-agentic-D97757?style=flat-square&logo=anthropic&logoColor=white">
</p>

---

Not "I use ChatGPT sometimes." I write the specifications, the state models and the constraints — then direct agents through the implementation. The generated code is the cheap part. The engineering is deciding what the system must never be allowed to do.

Two systems below are the proof: one is in production with paying infrastructure behind it, the other is currently forcing me through university-level mathematics.

---

## 🚀 MoveNLearn — [movenlearn.academy](https://movenlearn.academy)

**A commercial education platform. Live, registered business, built end-to-end by directing AI agents.**

<table>
<tr>
<td><b>51,000</b><br>lines TS/TSX</td>
<td><b>41</b><br>pages</td>
<td><b>29</b><br>API routes</td>
<td><b>81</b><br>components</td>
<td><b>5</b><br>locales</td>
</tr>
</table>

Next.js 16 · TypeScript · React · Stripe payments · i18n (DE/EN/RU/UA/KK) · transactional email · deployed on Vercel

Alongside it: a registered German sole proprietorship, its own bookkeeping (EÜR, expense tracking), a B2B outreach pipeline, and full legal/GDPR documentation. Not a side project — an operating business.

---

## 🎓 [self-driving-tutor](https://github.com/DaniilSerhi/self-driving-tutor)

**A study system that decides what you learn next — and refuses to let you skip ahead.**

Four agent specifications over two JSON state files. You type `weiter`. It reads its own memory, picks the next step, generates the lesson, grades the answer, updates the spaced-repetition model, and enforces a weekly quota.

The design problem wasn't teaching. It was **stopping the learner from escaping into the subject they're already good at**:

| Mechanism | What it prevents |
|---|---|
| **Protected quota** | The weak subjects have a weekly minimum the strong one can never displace |
| **Mastery gate** | A topic isn't left until you pass on a *later day* — anything else measures short-term memory |
| **Self-downgrade** | Report that you needed AI help and the concept is demoted, not passed |
| **Pause rule** | Come back after a break and you get a comeback drill, not your old bookmark |

It once annulled its own grade because the *system* had generated an invalid task. That's in the log.

**One month in:** school algebra → sequences and limits · 22 graded checks · every failure recorded.

---

## ⚙️ Also running

**A Telegram coaching agent in 24/7 production** — Python on an Azure VM, systemd, persistent memory and journaling, wearable-data integration, LLM routing with fallback. Migrated across cloud providers without downtime.

**Bookkeeping and property accounting** at a real-estate firm — operating-cost statements, payroll reconciliation against bank records.

---

## 🌍

🇺🇦 → 🇩🇪 · **Ukrainian · Russian · German · English**

Ukrainian-born. Learned German from zero, now study and work in it, and am preparing to take a technical degree in it.

---

<p align="center">
  <a href="mailto:sergeevdaniil008@gmail.com">
    <img src="https://img.shields.io/badge/Email-sergeevdaniil008@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white">
  </a>
  <a href="https://movenlearn.academy">
    <img src="https://img.shields.io/badge/Website-movenlearn.academy-4285F4?style=flat-square&logo=googlechrome&logoColor=white">
  </a>
</p>
