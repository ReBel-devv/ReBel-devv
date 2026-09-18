# Réda Belghiti

Full-stack TypeScript engineer, Paris. Engineering degree, ESIEE Paris (2025).

I build products end to end and I put LLMs in production: multi-provider
pipelines, agents with guardrails, and the verification that stops a fluent
answer from being a wrong one.

**Portfolio:** [rebel-dev.me](https://rebel-dev.me) ·

---

### What I am working on

**[career-ops-web](https://github.com/ReBel-devv/career-ops-web)** —
[live demo](https://career-ops-web-plum.vercel.app/) · Next.js 16, React 19,
TypeScript strict, Tailwind v4

A web dashboard for the [career-ops](https://github.com/santifer/career-ops)
CLI: Kanban board, report viewer, analytics, and an embedded conversational
agent built on the Claude Agent SDK. The interesting part is not the UI, it is
the safety model. Every mutation is a single locked, backed-up, atomically
renamed, verify-gated write, with golden-file tests asserting the data file is
byte-identical except the one changed cell. The agent refuses `git push`,
`rm -rf`, `sudo` and out-of-repo writes even in autonomous mode. A build-time
gate makes it impossible to deploy real data, and the public demo runs the
actual production parser over fictional fixtures, so it cannot drift from the
real app. 223 unit tests, 47 end-to-end tests, WCAG AA in both themes,
axe-core on every screen.

---

### Work that is not on GitHub

Most of what I ship is client or product code in private repositories. The
short version:

- **Gamified Habit-tracking mobile app**, live on the stores, around 100 users. React
  Native and Expo in a TypeScript monorepo, with Payload CMS 3, Next.js and
  SQLite on the back end.
- **Royal Canin global platform** at Ekino (Havas Group). Angular and
  TypeScript web components, configuration-driven forms, REST integrations,
  Core Web Vitals work, Jest on every component. 
- **ANSM**, the French medicines safety agency. React and TypeScript
  interfaces on the public medicines data platform, and Medistock, a prototype
  I took from a one-sentence ministry request to a demo in front of a state
  start-up investment committee.

---

### Stack

TypeScript · React · Next.js · React Native · Angular · Node.js · Python ·
PostgreSQL · SQLite/Drizzle · Redis · Docker · Playwright · Jest

Anthropic's official Claude Code course (2026). I work with coding agents
daily.

The older repositories below are learning projects from 2024 and 2025.
