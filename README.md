# Mehmet Bozkurt

**Software Architect · Technical Lead · Full-Stack Developer**

I design software systems, build developer tools, and explore practical ways to use AI in engineering.

My background spans backend development, software architecture, technical leadership, and end-to-end web applications. PHP and Laravel are at the core of my work, alongside modern JavaScript tools for the frontend.

Today, I’m bringing that experience into AI-assisted development: comparing coding models on real tasks, building verification workflows, and exploring the hardware and cost tradeoffs of local language models.

## Featured work

### [BenchForge](https://github.com/mehmet-bozkurt/BenchForge)

**Compare coding models. Inspect the results.**

A local evaluation environment that runs AI coding models against the same task and starting project through OpenCode. It brings automated checks, execution time, token usage, cost, and human evaluation into one comparison workflow.

- Validates outputs through lint, production build, static export, route checks, and browser smoke tests.
- Keeps separate workspaces for model runs and supports side-by-side output previews.
- Preserves first-attempt results while allowing failed runs to be retried and inspected.

`Laravel` · `SQLite` · `Node.js` · `OpenCode` · `Playwright`

*Early-stage, single-user tool for local use. Results are specific to the tasks and conditions tested.*

### [Local AI Feasibility Dashboard](https://github.com/mehmet-bozkurt/turkiye-local-llm-rehberi)

**Explore what it takes to run AI locally.**

An interactive research tool for comparing model requirements, hardware capacity, inference runtimes, and local-versus-cloud costs. Built from my research into the practical tradeoffs of running language models on personal hardware.

- Explores memory requirements and hardware options across different use cases.
- Compares inference runtimes and model deployment considerations.
- Includes interactive cost estimates, feasibility views, and a decision guide.

`React` · `TypeScript` · `Vite` · `Tailwind CSS` · `Recharts`

*Research tool with Turkish content. Data and estimates are approximate, not official benchmarks.*

## Engineering focus

- **Architecture & backend:** application boundaries, relational data models, APIs, authorization, and maintainable business systems.
- **Full-stack delivery:** connecting backend services, frontend interfaces, and operational requirements.
- **Developer tooling:** automating repetitive work and making development results easier to inspect.
- **AI-assisted engineering:** agent context, repeatable workflows, output verification, and model evaluation.

## Tools I work with

| Area | Technologies |
| --- | --- |
| Backend & data | PHP, Laravel, CodeIgniter, MySQL, MariaDB, Redis |
| Frontend | JavaScript, TypeScript, Vue.js, React, Next.js, Tailwind CSS |
| Infrastructure | Linux, Nginx, Docker, Cloudflare, Git, CI/CD |
| AI workflows & experimentation | OpenCode, Claude Code, Cursor, OpenRouter, MCP, Playwright |

## How I approach the work

I start with the problem, the data relationships, and the constraints. I care about how a system will be tested, maintained, and operated as much as how it is built.

When working with AI, I focus on preserving useful context and checking the resulting software. Tests, working outputs, execution time, and cost help me decide which approaches are useful in practice.

Outside web development, I’m interested in game development, 3D printing, and robotics prototyping.
