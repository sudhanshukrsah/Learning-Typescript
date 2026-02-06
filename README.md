# My TypeScript Journey

Welcome! This repository captures my learning path with TypeScript — practical experiments, small projects, notes, and patterns I discover along the way. It’s a living log of progress, mistakes, and wins.

## About

TypeScript brings type safety and better tooling to JavaScript. In this repo I explore core TypeScript concepts, integrate it with build tools, and apply it to real problems to improve code quality and developer experience.

## What’s Inside

- Notes and mini-projects demonstrating TypeScript features (types, interfaces, generics, utility types).
- Example setups for bundlers and runtimes (ts-node, tsc, bundlers like esbuild/webpack/vite).
- Small libraries or utilities I build to practice typing and design.

## Learning Goals

- Understand static types and how they prevent common bugs.
- Learn advanced typing: mapped types, conditional types, and generics.
- Integrate TypeScript into modern toolchains and CI.
- Improve API design with clear, maintainable type definitions.

## Project Structure (example)

- `src/` — source TypeScript files
- `dist/` — compiled JavaScript output (gitignored)
- `package.json` — project metadata and scripts

Adjust paths if your setup differs.

## Getting Started

Prerequisites:
- Node.js (LTS)
- npm or yarn

Install dependencies:

```bash
npm install
# or
# yarn install
```

Build (if `tsc` is configured):

```bash
npm run build
# or
# npx tsc
```

Run in development (example using ts-node):

```bash
npm run dev
# or
# npx ts-node src/index.ts
```

Note: replace scripts with the actual ones in `package.json` for this project.

## What I Learned

- How type narrowing improves function correctness.
- How to design expressive, minimal public types for libraries.
- When to prefer `unknown` vs `any` and how to incrementally type legacy code.

## Roadmap

- Add typed examples for common design patterns.
- Add tests (Jest + ts-jest or vitest).
- CI integration to run type checks and tests on push.

## Resources

- TypeScript Handbook: https://www.typescriptlang.org/docs/
- Effective TypeScript (book)
- Community articles and blog posts I find useful.

## Contributing

This is a personal learning repo. Feel free to open issues or suggest improvements — I appreciate tips and corrections.

## License

This repository is for learning. Use examples for personal learning; include attribution if you reuse larger parts.

---

If you want this README tailored with a personalized intro, project-specific scripts, or translations, tell me what to include and I’ll update it.