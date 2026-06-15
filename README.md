# Agent Skills Collection

A professional repository of specialized agent skills designed to enhance productivity and expertise across various domains. Each skill is independently installable and can be integrated into your agent workflow.

## Overview

This repository contains a curated collection of agent skills—extensible tools that augment your agent's capabilities across specific domains. New skills are continuously added to support evolving use cases.

## Available Skills

### Landing Page Architect

A strategic framework for designing high-conversion landing pages through structured architecture and psychology-driven section design.

**Description:** Guides you through building the architecture of your landing page blueprint using proven frameworks for emotional engagement, logical persuasion, and conversion optimization. Outputs a detailed specification ready for designer or copywriter execution.

**Key Features:**
- Section-by-section architecture with psychological triggers
- Discovery-driven approach (interviews your product, audience, and offer)
- Frameworks: Transformation Framework, Scanning Architecture, PAS copywriting
- 9-section structure: Hero → Social Proof → Problem/Agitation → Solution → Demo → Deep Social Proof → Differentiation → CTA → FAQ

**Location:** `skills/landing-page-architect/`

---

## Installation Instructions

### Installing Skills

Skills can be installed using the `npx skills` command.

```bash
npx skills add Ziad-agamy/landing-page-architect
```

This will pull the skill from the GitHub repository and integrate it into your agent.

---

### Skill Repository Structure

Each skill folder contains:
- `SKILL.md` — Skill definition file (required for installation)
- Documentation and guidance files
- Reference materials and frameworks

---

## Using Skills

Once integrated, skills are triggered automatically by your writer agent based on task context and content requirements. The agent evaluates the writing request and engages the most relevant skill.

Example:
- "Help me build a landing page architecture for my SaaS product" → Activates Landing Page Architect skill

---

## File Structure

```
skills/
└── landing-page-architect/
    ├── SKILL.md
    └── references/
        └── copywriting-frameworks.md
```

---

## License

MIT