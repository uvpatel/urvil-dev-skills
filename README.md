# urvil-dev-skills

A curated collection of production-grade developer skills and architectural guidelines for modern fullstack Next.js applications, AI integrations, database systems, UI engineering, code reviews, and debugging.

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

## 🛠️ Usage with Antigravity / AI Agents

To use these skills in your projects:

1. **Workspace Level**: Copy or symlink individual skills into your project's `.agents/skills/` directory.
2. **Global Level**: Place or symlink desired skills into `~/.gemini/config/skills/`.

AI agents automatically discover skills via progressive disclosure—loading skill summaries and referencing full instructions and deep-dive documentation on demand.

---

## 📄 License

MIT License. See [LICENSE](./LICENSE) for details.
