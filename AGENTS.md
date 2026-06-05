# Agent Instructions

This repo is a hands-on learning timeline for the JavaScript ecosystem. Follow the roadmap in `README.md` and preserve the historical progression from browser-only JavaScript to modern full-stack tooling.

## Core Principles

- Keep each phase folder independently runnable.
- Add a short `README.md` inside each phase folder.
- Explain what problem each phase solves compared with the previous phase.
- Keep examples small, focused, and educational.
- Prefer clarity over production polish.
- Do not introduce tools, frameworks, or abstractions before the phase where they belong.

## Phase Boundaries

- Early browser phases should use plain HTML, CSS, and JavaScript.
- Do not use npm before the Node/npm phase.
- Do not use bundlers before the build tooling phase.
- Do not use React before the React phases.
- Do not use TypeScript before the TypeScript phase.
- Do not use Next.js before the final modern full-stack phase.

## Folder Expectations

Each phase folder should include:

- runnable source files
- a phase-level `README.md`
- a clear learning goal
- a short explanation of the pain point that motivated the next ecosystem step

When useful, include a minimal `package.json` with scripts such as `dev`, `start`, or `test`, but only after the roadmap has introduced Node/npm.

## Commit Style

Prefer small commits that correspond to one learning phase or one focused documentation update.

