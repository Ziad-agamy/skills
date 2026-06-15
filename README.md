# Landing Page Architect

A Claude skill that turns you into a high-conversion landing page strategist — without writing a single line of final copy until the architecture is right.

Most people jump straight to writing headlines and picking templates. This skill does the opposite: it interviews you about your product, your audience, and your offer, then builds a complete **section-by-section blueprint** — what goes in each section, why it's there, and what psychological job it's doing. The output is a spec a designer or copywriter can pick up and execute immediately.

## What this is (and isn't)

- ✅ Builds the **architecture**: section order, content guidance, copywriting angles, psychological triggers, and design notes for every section
- ✅ Asks before it assumes — no generic "we help businesses grow" filler
- ❌ Does not write final polished marketing copy
- ❌ Does not generate the actual page, HTML, or design files

Think of it as the strategy brief that comes *before* the build.

## The framework

The skill is built around a single idea: a high-conversion landing page guides a visitor along one path — **emotional hook → logical rationalization → action**. Every section has one job, and nothing is filler.

It walks through 9 sections in order:

1. **Hero** — captures attention in 5 seconds, gives a reason to scroll
2. **Primary Social Proof** — instant credibility at a glance (logos, ratings, numbers)
3. **Problem / Agitation** — the emotional hook, built using the PAS framework (Problem → Agitate → Solve)
4. **Solution / Benefits** — turns features into outcomes using the "So What?" method
5. **Product Demo / Showcase** — the "wow, I need this" moment
6. **Deep Social Proof** — testimonials, reviews, and case studies, shown in full (never hidden in carousels)
7. **Why Us** — the differentiation section, ideally a comparison table
8. **Final CTA** — one offer, one button, the buy-or-leave moment
9. **FAQ** — objection-reframed questions that act as the last safety net before someone leaves

It also leans on two supporting frameworks: the **Transformation Framework** (Big Idea → End Result → Transformation) for the Hero headline, and the **Scanning Architecture Framework**, which assumes visitors only read ~20% of your page and structures every section so the headlines alone tell the full story.

## How it works

1. **Intake interview** — asked in small batches, never a giant form dump:
   - Your offer (what it is, the page's single goal, pricing)
   - Your buyer (who they are, their pain, their dream outcome, their #1 objection)
   - Your positioning (competitors, your edge, existing proof, existing assets)
2. **Section-by-section build** — for each of the 9 sections, the skill asks any remaining specific questions, then writes out the headline direction, CTA copy, visuals, and the psychological trigger at play
3. **Final architecture document** — everything compiled into one structured blueprint, ready to hand to a designer, copywriter, or no-code page builder

The skill will push back on vague answers. If you say "our product saves time," it'll ask *how much time, for whom, doing what* — because specificity is what makes a landing page convert.

## Example prompts that trigger this skill

- "Help me build a landing page for my freelance video editing service"
- "I need to structure a sales page for my SaaS product"
- "What sections should my landing page have and what should go in each one?"
- "Can you help me plan out a high-conversion page for my coaching offer?"

## Installation

1. Download `landing-page-architect.skill`
2. In Claude, go to **Settings → Skills → Install from file**
3. Upload the `.skill` file
4. Start a conversation describing your product — the skill activates automatically

## What's inside

```
landing-page-architect/
├── SKILL.md                                # Core workflow, interview questions, and section-by-section guidance
└── references/
    └── copywriting-frameworks.md           # Deep dive on PAS, Transformation, and Scanning Architecture frameworks
```

## Best for

- Founders and freelancers building their first landing page
- Marketers who want a structured brief before opening a page builder
- Anyone who keeps staring at a blank page wondering "what even goes in a landing page?"

## License

MIT