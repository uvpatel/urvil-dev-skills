# urvil-dev-skills

[![skills.sh](https://img.shields.io/badge/skills.sh-discoverable-blue?style=flat-square)](https://skills.sh)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg?style=flat-square)](https://opensource.org/licenses/MIT)

A curated collection of production-grade developer skills and architectural guidelines for modern fullstack Next.js applications, AI integrations, database systems, UI engineering, code reviews, and debugging.

Discoverable and installable on [skills.sh](https://skills.sh) for AI coding assistants (Antigravity, Claude Code, Cursor, GitHub Copilot, etc.).

---

## ⚡ Quick Install via `skills.sh`

Install all skills into your current project:
```bash
npx skills add uvpatel/urvil-dev-skills
```

Install globally (available across all projects):
```bash
npx skills add uvpatel/urvil-dev-skills -g
```

Install a specific skill:
```bash
npx skills add uvpatel/urvil-dev-skills --skill nextjs-production
npx skills add uvpatel/urvil-dev-skills --skill nextjs-ai
npx skills add uvpatel/urvil-dev-skills --skill nextjs-auth
```

List available skills without installing:
```bash
npx skills add uvpatel/urvil-dev-skills -l
```

---

## 🚀 Skills Catalog

| Skill Name | Description | Key Focus Areas |
| :--- | :--- | :--- |
| [`nextjs-production`](./skills/nextjs-production/SKILL.md) | Production architecture, routing, RSC boundaries, and optimizations | App Router, Server Actions, Caching, Bundle Optimization |
| [`nextjs-auth`](./skills/nextjs-auth/SKILL.md) | Complete authentication and authorization workflows | Better Auth, GitHub OAuth, RBAC, Session Security |
| [`nextjs-database`](./skills/nextjs-database/SKILL.md) | Database connections, ORM modeling, and migrations | Drizzle ORM, Neon Postgres, Mongoose, MongoDB, Migrations |
| [`nextjs-ui`](./skills/nextjs-ui/SKILL.md) | Modern UI components, styling, and design system engineering | shadcn/ui, Tailwind CSS, Radix UI, WCAG Accessibility |
| [`nextjs-ai`](./skills/nextjs-ai/SKILL.md) | Generative AI integration, streaming, and tool calling | Vercel AI SDK, Google Gemini, Multi-modal, Function Calling |
| [`nextjs-code-review`](./skills/nextjs-code-review/SKILL.md) | Systematic code review and quality audits for Next.js | Security Audits, Memory Leaks, Anti-pattern Detection |
| [`nextjs-debugging`](./skills/nextjs-debugging/SKILL.md) | Diagnostic workflows for Next.js runtime and build issues | Hydration Mismatch, Server Action Failures, Route Handlers |
| [`fullstack-architect`](./skills/fullstack-architect/SKILL.md) | System design, technical specifications, and infrastructure | Scalability, Database Schemas, API Design, System Architecture |

---

## 📁 Repository Structure

```
urvil-dev-skills/
├── README.md
├── LICENSE
└── skills/
    ├── nextjs-production/
    │   ├── SKILL.md
    │   └── references/
    │       ├── architecture.md
    │       ├── routing.md
    │       ├── server-client.md
    │       ├── performance.md
    │       └── debugging.md
    │
    ├── nextjs-auth/
    │   ├── SKILL.md
    │   └── references/
    │       ├── better-auth.md
    │       ├── github-oauth.md
    │       └── rbac.md
    │
    ├── nextjs-database/
    │   ├── SKILL.md
    │   └── references/
    │       ├── drizzle-neon.md
    │       ├── mongoose.md
    │       └── migrations.md
    │
    ├── nextjs-ui/
    │   ├── SKILL.md
    │   └── references/
    │       ├── shadcn.md
    │       ├── tailwind.md
    │       └── accessibility.md
    │
    ├── nextjs-ai/
    │   ├── SKILL.md
    │   └── references/
    │       ├── vercel-ai-sdk.md
    │       ├── gemini.md
    │       ├── streaming.md
    │       └── tool-calling.md
    │
    ├── nextjs-code-review/
    │   └── SKILL.md
    │
    ├── nextjs-debugging/
    │   └── SKILL.md
    │
    └── fullstack-architect/
        └── SKILL.md
```

---

## 🤖 Supported Agents

These skills comply with the Open Agent Skills specification and can be consumed by:
- **Google Antigravity** (`.agents/skills/` or `~/.gemini/config/skills/`)
- **Claude Code** (`.claude/skills/`)
- **Cursor** (`.cursor/skills/` or rules)
- **GitHub Copilot**
- Any agent supporting standard `SKILL.md` workflows.

---

## 📄 License

MIT License. See [LICENSE](./LICENSE) for details.
