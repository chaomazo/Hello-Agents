# Hello Agents

> A free, build-first course for people who want to understand and ship AI agents.

Hello Agents is a hands-on learning experience for building AI-native agents from first principles. It moves from the mechanics of a single tool-using loop to memory, retrieval, multi-agent systems, evaluation, and real-world capstone projects.

The project includes a bilingual English / 中文 web experience, a living curriculum, practical builder notes, community context, and a clear path from first prompt to production-minded agent systems.

## Why this exists

AI agent content is everywhere, but a clear path from curiosity to working software is still hard to find. Hello Agents focuses on the parts that compound:

- **Build over talk** — every idea should become code you can run, break, and repair.
- **Explain the why** — understand the mechanics underneath frameworks and patterns.
- **Measure honestly** — use logs, benchmarks, and evaluation instead of demos alone.
- **Open and free** — learn in public and make the work easier for the next builder.

## What you can explore

- Agent foundations, tool use, loops, and orchestration
- Context engineering, memory, retrieval, and RAG
- Multi-agent communication and emerging agent protocols
- Evaluation, metrics, benchmarks, and agentic reinforcement learning
- A practical roadmap that ends with projects you can run and share
- Responsive pages for the home, about, roadmap, legal, and login experiences

## Tech stack

- React 19 + TypeScript
- Vite
- Tailwind CSS 4
- Framer Motion
- Responsive, client-side routing
- English / 中文 content support

## Getting started

### Prerequisites

- Node.js 20+
- npm 10+ (or another compatible package manager)

### Install and run

```bash
npm install
npm run dev
```

Then open the local URL printed by Vite.

### Production build

```bash
npm run build
npm run preview
```

## Project structure

```text
src/
├── components/   Reusable page and interaction components
├── pages/        Route-level screens
├── content.ts    Curriculum and editorial content
├── data.ts       Shared content types and data
├── i18n.tsx       Language provider and translation helpers
├── router.tsx     Lightweight client-side routing
└── index.css      Global styles and design tokens
public/            Favicon, manifest, and social preview assets
```

## Contributing

Contributions that make the learning path clearer, more practical, or more welcoming are encouraged. Before opening a pull request:

1. Keep examples runnable and explain the reasoning behind meaningful changes.
2. Preserve the English / 中文 experience when editing user-facing content.
3. Run `npm run build` locally.
4. Describe what a learner can now understand or build after the change.

For substantial changes, open an issue first so the direction can be discussed openly.

## Roadmap

The curriculum is intentionally iterative. Future improvements may include more runnable examples, deeper evaluation walkthroughs, community-submitted projects, and additional translations.

## License

The project is shared for learning and community use. A formal license will be added when the project maintainer selects the appropriate terms.

---

Built for curious people who learn by making.
