[Русский](README.md) | **English**

# Hi! I'm Misha

**Frontend engineer (and a bit of a backend dev).** I build with React, Next.js and Expo.

I make web, mobile and desktop apps (Tauri 2 / Rust). I like making a project easier to work on: automating routine tasks, fixing builds and releases, deleting dead code.

Get in touch: [Telegram](https://t.me/hromas)

---

### Daily stack

* **Frontend:** Next.js (App Router, RSC), React, TypeScript, Tailwind CSS, Vite (Rollup/Rolldown)
* **Mobile and Desktop:** React Native, Expo, Reanimated; Tauri 2, Rust
* **State and data:** Zustand, TanStack Query, WebSockets
* **Architecture and quality:** Feature-Sliced Design, Vitest, Oxlint, Prettier, Fallow, Lefthook
* **AI and workflow:** Claude Code, Git, GitLab CI, GitHub Actions

<details>
<summary><b>Also worked with</b></summary>

* **Web and Desktop:** Astro, TanStack Router, React Router, CSS Modules, Turbopack, WebGL, React Flow, dnd-kit
* **Mobile:** MMKV, Firebase, Gesture Handler, Bottom Sheet
* **State and data:** Redux Toolkit, Immer, REST, JSON-RPC
* **Tooling and DevOps:** Docker, Nginx, Jest, Knip, Fastlane, Semantic Release, npm, pnpm, Yarn, Bun
* **Backend:** Node.js, NestJS, Express, FastAPI, PostgreSQL, MongoDB, Laravel

</details>

---

### Principles I build on

#### 1. A codebase that is easy to understand

The amount anyone can hold in their head is limited (people and AI alike). Code should be readable in parts:

* Structure and naming show where things live without reading half the project.
* Clear module boundaries: a narrow entry and exit, dependencies pointing one way.
* Documentation explains *why* (reasons for decisions, rules), not *what*: the code already shows that.

#### 2. Checks on top of tests and linters

Results are predictable when an independent automated system verifies them, not trust in the author:

* Project invariants are checked mechanically: layer boundaries, forbidden dependencies.
* Fast feedback: errors are caught right away (pre-commit, CI), not in review.
* Behavior and end-to-end scenarios are tested, and the verifier is independent of what it verifies.

#### 3. Measurable review quality

What isn't measured can't be improved. Review can be evaluated against a set of real defects: how many problems it found (recall) and how many of its comments were correct (precision).

* Review scales worse than writing code, so it has to be made cheaper: small changes with a clear goal and automated checks before it.
* Changes to the review process are checked for regressions against the same set.
