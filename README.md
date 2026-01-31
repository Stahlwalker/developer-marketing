# Developer Marketing

A Claude Code skill based on [Luke Stahl's Developer Marketing Handbook](https://lukestahl.io/handbook/) that helps create authentic, technical content and strategies for reaching developer audiences.

## Installation

### Recommended (clone directly into Claude Code skills directory)

```bash
mkdir -p ~/.claude/skills
git clone https://github.com/yourusername/developer-marketing.git ~/.claude/skills/developer-marketing
```

### Manual install/update (only the skill file)

If you already have this repo cloned (or you downloaded `SKILL.md`), copy the skill file into Claude Code's skills directory:

```bash
mkdir -p ~/.claude/skills/developer-marketing
cp SKILL.md ~/.claude/skills/developer-marketing/
```

## Usage

In Claude Code, invoke the skill:

```
/developer-marketing

[describe your task]
```

Or ask Claude directly:

```
Help me write a technical blog post about our new API
Create a developer advocacy strategy for our open source project
Review this documentation for developer audience fit
```

## Overview

Based on the [Developer Marketing Handbook](https://lukestahl.io/handbook/) by [Luke Stahl](https://lukestahl.io/).

Developer marketing builds trust first, pipeline second. The work connects your product to how developers actually build and helps that credibility translate into adoption and revenue.

### Key Principle

> "Developer marketing builds trust first, pipeline second."

## Core Framework

### Goals
Developer marketing builds trust first, pipeline second. Success isn't clicks or vanity metrics—it's measurable engagement that creates product-qualified leads, builds influence across teams, and contributes to both product-led and sales-led growth.

A great developer experience is the foundation. It starts with discoverability, continues through docs, and carries into the product itself.

### Strategy
Start with reality, not aspiration. Map where your product fits in the developer workflow, then help them do that job faster or with less friction.

**Lead with clarity.** Explain what it is, what it does, and why it matters.

Show the system behind the product. Architecture, examples, and tradeoffs explain more than positioning ever will.

### Developer Journey

**Awareness → Evaluation → Adoption → Advocacy**

| Stage | Where It Happens | What Matters |
|-------|-----------------|--------------|
| **Awareness** | GitHub, Reddit, newsletters, blogs | Be present where developers already spend time |
| **Evaluation** | Docs, demos, sandboxes | The docs are the real homepage—accuracy and structure matter more than polish |
| **Adoption** | First success experience | How fast they reach first success determines adoption |
| **Advocacy** | Community, word-of-mouth | When they start teaching others what they learned from you |

### Messaging Pillars

Be clear first. Be clever only if it helps. Build around three pillars:

| Pillar | What It Means |
|--------|---------------|
| **Speed** | Faster builds, fewer tickets |
| **Efficiency** | Consolidated stack, lower maintenance |
| **Control** | Safe scale, long-term confidence |

If you can back it with code, data, or proof, keep it. If it only sounds good, cut it.

## Personas

Create personas based on who buys the product and who actually uses it.

| Persona | Cares About | Content They Need |
|---------|-------------|-------------------|
| **CTO / Engineering Leader** | Governance, ROI | Architecture docs, security, scale proof |
| **Senior Engineer** | Performance, flexibility, code quality | Deep technical content, benchmarks, integration guides |
| **Implementation Architect** | Integration, scale | System design, API references, migration paths |
| **Frontend Developer** | UI/UX integration, performance | Component docs, examples, playground |
| **Full-stack Developer** | End-to-end workflow | Complete tutorials, stack integration |
| **App Developer** | Speed to market, reliability | Quick starts, SDKs, common patterns |
| **Ops/DevOps** | Deployment, monitoring, reliability | Infrastructure guides, observability, security |

Write for what each person owns, not what you wish they cared about.

## Content Strategy

Write with clarity and intention. Every piece should help developers build faster, learn something new, or solve a real problem.

Strong content earns attention because it's useful. Lead with the outcome or insight, then show how to get there. Make it skim from top to bottom.

### Core Content Types

| Type | Purpose | Best Practices |
|------|---------|----------------|
| **Blog posts** | Tutorials, technical breakdowns, opinionated takes | Ground in experience, show working examples |
| **Guides and tutorials** | Step-by-step instructions | Lead to a working result |
| **Integration/workflow content** | Explain how tools connect | Show where they fit in developer's process |
| **Technical guides & code examples** | Deep implementation detail | For experienced readers |
| **Explainer/glossary content** | Answer specific questions | Clear, factual definitions |
| **Video/live sessions** | Demos, interviews, walkthroughs | Show real workflows |
| **Research and surveys** | Industry insights | Help developers understand their field |

### Content Strategy Buckets

| Bucket | Purpose | Content Types |
|--------|---------|---------------|
| **Awareness** | Generate buzz | Hot takes, thought leadership, conversation starters |
| **Acquisition** | Bring new developers in | Problem-solving tutorials, guides, explainers |
| **Enablement** | Help existing users succeed | Deep tutorials, documentation extensions, how-tos |
| **Convert Paid** | Drive upgrades or signups | Feature-specific walkthroughs, advanced use cases |

Each piece should fit into one of these buckets and serve a clear purpose. Clarity is the standard. Use it to earn credibility.

## Campaigns

Treat campaigns like product launches. Plan, ship, measure, repeat.

### Every campaign should answer three questions:

1. **What developer problem are we solving?**
2. **What proof are we showing?**
3. **What happens next?**

Treat developer feedback like bug reports and close the loop quickly when something needs to be corrected or clarified.

Make it easy for developers to try, test, or share. Run retros on every launch and capture what worked, what didn't, and what to change next time. Always learn from what you launch.

## Community

Reddit. GitHub. Discord. Slack. YouTube and other social platforms.

**Join conversations, don't start pitches.**

Be helpful. Add context. Share working examples. When your content becomes the answer people link to, you've earned credibility.

## Metrics

Mean and revenue, not reach. Awareness is useful, but only if it drives activation or expansion.

### Focus on signals that show impact:

- Product or API usage
- Time to first success
- Product-qualified leads
- Developer-influenced revenue
- Retention and repeat engagement

The goal is to prove that trust earned from developers shows up later in product usage and revenue.

## References

- [Luke Stahl's Developer Marketing Handbook](https://lukestahl.io/handbook/) - Primary source for this skill
- [Luke Stahl](https://lukestahl.io/) - Developer marketing consultant

## Version History

- **1.0.0** - Initial release

## License

MIT
