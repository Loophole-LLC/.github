<div align="center">

<img src="loophole-logo.svg" alt="Loophole, LLC" width="380">

### Learning from examples. Securing access.

Software &amp; research by **Loophole, LLC** &middot; [loophole.company](https://loophole.company/)

</div>

---

We build and support two projects: **JAYCE**, an experimental learning system built on Adaptive
Prototype Memory, and **Bastillion**, a self-hosted web-based SSH console with centralized key
management and recorded sessions. Around them we publish research on SSH architecture and on how
language models behave when the framing around a question changes but the facts don't.

## Projects

### [Bastillion](https://github.com/Loophole-LLC/Bastillion) &nbsp;[![Stars](https://img.shields.io/github/stars/Loophole-LLC/Bastillion?style=flat&label=stars&color=2ea043)](https://github.com/Loophole-LLC/Bastillion/stargazers)

A self-hosted SSH console that puts access, key management, and session recording in one place.
Administrators connect through the browser; keys are distributed and rotated centrally, and
sessions are recorded and replayable for review.

Source-available and free for up to 5 registered systems. Annual licenses raise that limit —
Starter ($149/yr, 150 systems), Team ($399/yr, 500 systems), and Business ($999/yr, unlimited) —
with no auto-renewal and no account required.
See [license pricing](https://loophole.company/pricing.html).

### [JAYCE](https://github.com/Loophole-LLC/Jayce) &nbsp;`AGPL-3.0-only`

*Jayce Associates Your Categorized Exemplars.* A small prototype learner that classifies by
comparing new inputs against labeled examples and adjusts as it is corrected, rather than by
backpropagation. The repository holds the source, reproducible benchmarks against backprop, and a
chat demo where JAYCE learns from a local LLM.

The [project page](https://loophole.company/jayce-toy-learning.html) walks through Adaptive
Prototype Memory in an interactive lesson.

## Research

**[Implementing a trusted third-party system for Secure Shell](https://loophole.company/assets/ttp-system-for-secure-shell.pdf)** —
a 2017 whitepaper on centralizing SSH authentication, session review, and access revocation. It is
the architecture Bastillion grew out of.

**Runtime Alignment Context Injection (RACI)** — experiments in how reframing and social pressure
shift a language model's answers while the underlying facts stay fixed, run against production
models and published with full transcripts:

- [lebron-james-is-president](https://github.com/Loophole-LLC/lebron-james-is-president) — Claude
- [fish-live-in-trees](https://github.com/Loophole-LLC/fish-live-in-trees) — Gemini

## Experiments

- **[Machine Witness](https://machinewitness.art/)** — every week, Gemini, Claude, and ChatGPT each
  dig into the same AI news and turn their own opinion into art and written commentary.
  [Source](https://github.com/Loophole-LLC/MachineWitness)
- **[AuxControl](https://auxcontrol.live/)** — a shared music queue where guests add tracks and vote
  on what plays next.

## Engineering &amp; support

Loophole brings more than 20 years of experience in application security, infrastructure, and secure
software delivery to the work it takes on:

- **Privileged access** — access controls and audit trails for servers, databases, and operational
  systems.
- **Application security** — security testing, vulnerability management, and secure releases folded
  into an existing development process.

## Contact

Loophole, LLC &middot; Garfield Heights, Ohio 44125, USA

For project questions, licensing, and support: **[info@loophole.company](mailto:info@loophole.company)**

Found a vulnerability? Email **[support@loophole.company](mailto:support@loophole.company)** with
steps to reproduce, and please don't open a public issue for anything that isn't already public.
