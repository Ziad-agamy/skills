# Agent Skills Collection

A repository of specialized agent skills — modular instruction packages that teach AI coding agents how to perform specific tasks. Each skill lives in its own directory and is independently installable via `npx skills add`.

---

## Available Skills

### Landing Page Architect

Design high-conversion landing pages using psychology-driven section architecture.

| | |
|---|---|
| **Install** | `npx skills add Ziad-agamy/landing-page-architect` |
| **Location** | `skills/landing-page-architect/` |
| **Trigger** | Any landing page, sales page, or conversion page request |

The skill interviews you about your product, audience, and offer, then produces a complete section-by-section blueprint with copywriting angles and psychological triggers. Covers the full sequence from hero to FAQ using the PAS and Transformation frameworks.

**Key features:**
- 9-section architecture (Hero → Social Proof → Problem → Solution → Demo → Deep Social Proof → Differentiation → CTA → FAQ)
- Discovery-driven intake interview (never assumes)
- Each section includes its psychological trigger and a design note
- Outputs an architecture document ready for designer/copywriter execution

**Includes:** `references/copywriting-frameworks.md` — PAS, Transformation, and Scanning Architecture frameworks.

---

### Freelance Proposal Writer

Write professional freelance project proposals in Arabic and English that win clients.

| | |
|---|---|
| **Install** | `npx skills add Ziad-agamy/freelance-proposal-writer` |
| **Location** | `skills/freelance-proposal-writer/` |
| **Trigger** | Writing a proposal/cover letter/bid for Mostaqel, Upwork, Freelancer, Khamsat, etc. |

On first use, the skill builds a persistent profile of your experience, past projects, and skills. On subsequent uses, it reuses that profile and crafts tailored proposals for each client project description you provide.

**Key features:**
- 4-part proposal architecture (Hook → Core → Commitment → PS)
- Quality gates checklist before delivering any proposal
- 6 ground rules (250-character window, personalization, no AI fluff, etc.)
- Supports Arabic or English based on the client's project language
- Refinement loop: adjust tone, length, or formality after the first draft

**Includes:** `references/framework.md` (full architecture), `references/templates.md` (structural patterns for different project types).

---

## Installation

Install any skill with a single command:

```bash
npx skills add Ziad-agamy/<skill-name>
```

For example:

```bash
npx skills add Ziad-agamy/landing-page-architect
npx skills add Ziad-agamy/freelance-proposal-writer
```

The CLI resolves `Ziad-agamy/<skill-name>` by looking for the matching directory inside the `Ziad-agamy/skills` repository.

See the [skills CLI documentation](https://skills.sh) for more options (`--global`, `--agent`, `--list`, etc.).

---

## Repository Structure

```
skills/
├── landing-page-architect/
│   ├── SKILL.md
│   └── references/
│       └── copywriting-frameworks.md
└── freelance-proposal-writer/
    ├── SKILL.md
    ├── references/
    │   ├── framework.md
    │   └── templates.md
    └── user-profile/
        └── profile.md          # Created on first use (user-specific data)
```

Each skill must have a `SKILL.md` file with YAML frontmatter (`name`, `description`). The `description` field is what agents match against to trigger the skill automatically.

---

## Adding a New Skill

1. Create `skills/<name>/SKILL.md` with frontmatter (`name` + `description`). Keep the description precise — it determines when the skill activates.
2. Add supporting files (references, scripts, templates) under `skills/<name>/`.
3. Update this `README.md` with the new skill name, description, and install command.
4. Push to GitHub and test with `npx skills add Ziad-agamy/<name>`.

---

## License

MIT
