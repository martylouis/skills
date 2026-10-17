# Marty Thierry's Agent Skills

## Skills

| Name | Use | Source | Added |
| --- | --- | --- | --- |
| [`create-verification-skill`](skills/create-verification-skill/SKILL.md) | Generate a project-local skill that drives an app the way a user does and captures proof. | Adapted from [pstack](https://github.com/cursor/plugins/tree/main/pstack/skills/create-verification-skill) by Lauren Tan (poteto), v0.15.25 @ `09d06eb`. MIT, see [LICENSE](skills/create-verification-skill/LICENSE). | 2026-10-16 |
| [`write-ux-invoice-line`](skills/write-ux-invoice-line/SKILL.md) | Write a timesheet description line for the UX work done in this session. | Original | |

Third-party skills installed unmodified into `.agents/skills/` are tracked in `skills-lock.json`.

## Development

To install dependencies:

```bash
bun install
```

To run:

```bash
bun run index.ts
```

This project was created using `bun init` in bun v1.3.14. [Bun](https://bun.com) is a fast all-in-one JavaScript runtime.
