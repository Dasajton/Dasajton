# GitHub profile redesign

Date: 2026-08-22
Status: approved design, pending final spec review by David

## Goal

Replace the outdated profile README with a compact, professional English profile that positions David Sajitz as a product-focused Full-Stack Developer with practical experience in modern web development, self-hosted infrastructure, automation and AI-assisted engineering.

The profile should support future freelance and business opportunities without claiming customers, seniority, public projects or business results that cannot currently be demonstrated.

## Audience

- Potential freelance clients and collaboration partners
- Developers and technical project partners
- Recruiters looking for modern full-stack and product-oriented experience

## Positioning

Primary label:

> Product-focused Full-Stack Developer

Supporting themes:

- Modern web applications based on real business requirements
- Headless CMS integrations with Directus
- Practical automation workflows
- Secure multi-tenant and data-driven software
- Reliable deployments on self-managed Linux infrastructure
- Structured use of AI coding agents with review, testing and verification

Location: Dortmund, Germany.

Availability statement:

> Open to selected freelance projects and technical collaborations.

## Tone

The README will be written in professional, natural English. It should be confident without implying unsupported seniority or commercial success.

Avoid:

- Generic phrases such as "passionate developer" or "innovative solutions"
- Titles such as expert, senior, founder or entrepreneur
- Claims about customers, production scale or measurable business outcomes
- Excessive emojis, slogans and marketing language
- Skill percentages, visitor counters, quote widgets and generated GitHub statistics

## Visible README structure

1. Introduction
2. What I'm working on
3. Core development
4. Infrastructure & delivery
5. AI-assisted workflow
6. How I work
7. Let's connect

A `Selected projects` section will be added later, between `What I'm working on` and the stack, once suitable public work exists. The current README will not display an empty placeholder.

## Approved content direction

### Introduction

```md
# Hi, I'm David

Product-focused Full-Stack Developer based in Dortmund, Germany.

I build modern web applications, practical automation workflows and reliable self-hosted systems. My current focus is on turning real business requirements into maintainable products with TypeScript, modern web frameworks and AI-assisted development workflows.

I care about clear architecture, secure data boundaries and software that remains understandable after the first release.

Open to selected freelance projects and technical collaborations.
```

The existing image header will be removed. The text introduction is more adaptable, readable on mobile and less likely to become visually outdated.

### What I'm working on

```md
## What I'm working on

- Product-oriented web applications built around real business requirements
- Headless CMS integrations and content platforms with Directus
- Automation workflows that reduce repetitive operational work
- Secure multi-tenant architectures and data-driven business software
- Reproducible deployments on self-managed Linux infrastructure
```

This section describes current areas of work without naming private repositories or presenting them as public case studies.

### Stack groups

Use compact Shields.io badges with `style=flat-square`. Badges within each group should use consistent naming, official logos where available and readable logo contrast.

#### Core development

- TypeScript
- JavaScript
- React
- Next.js
- Vue.js
- Nuxt
- Node.js
- Tailwind CSS
- Directus

HTML and CSS remain implied foundations rather than prominent positioning badges. Sass, Bootstrap, Figma and VS Code will be removed from the visible stack because they are not central to the intended profile positioning.

#### Infrastructure & delivery

- Linux
- Docker
- PostgreSQL
- Traefik
- Git
- GitHub Actions

Ubuntu will not receive a separate badge because Linux already communicates the broader capability and avoids redundant platform badges.

#### AI-assisted workflow

- Hermes Agent
- Claude Code
- OpenAI Codex

Supporting explanation:

```md
I use AI coding agents as part of a structured engineering workflow, with clear task ownership, independent review and verified delivery.
```

The explanation prevents the tools from appearing as unsupported AI name-dropping.

### How I work

```md
## How I work

I like building systems from the product idea down to deployment. That means understanding the requirement, choosing a maintainable architecture, implementing the application and operating it reliably.

AI tools are part of that process, but they do not replace engineering judgment. I use them with defined responsibilities, code review, focused tests and explicit verification.
```

### Contact

```md
## Let's connect

I'm open to selected freelance projects and technical collaborations, especially around modern web applications, headless CMS integrations and practical automation.
```

The existing LinkedIn profile remains the primary public contact method and will use a compact matching badge.

## Repository metadata

Replace the repository description:

> Config files for my GitHub profile.

with:

> GitHub profile of David Sajitz — product-focused full-stack development, automation and self-hosted systems.

Replace the current `config` and `github-config` topics with:

- profile-readme
- full-stack-development
- web-development
- automation
- self-hosting

## Scope boundaries

Included:

- Rewrite `README.md`
- Remove the old header image reference from the README
- Keep the image file only if deletion would add no practical value; otherwise delete it as unused
- Update repository description and topics
- Verify README rendering and all external links after publishing

Not included:

- Changing David's GitHub account bio or profile metadata outside this repository
- Publishing private project names or links
- Creating a new visual banner
- Adding dynamic statistics or third-party activity widgets
- Claiming customer work or commercial outcomes

## Acceptance criteria

- The README is fully written in English.
- The opening identifies David as a product-focused Full-Stack Developer based in Dortmund.
- Directus and headless CMS work are visible in both focus and stack sections.
- The stack is divided into Core development, Infrastructure & delivery and AI-assisted workflow.
- All badges use a consistent compact style and render successfully.
- AI tooling is described as a reviewed engineering workflow rather than autonomous authority.
- The profile contains no unsupported customer, seniority or performance claims.
- The old image header is no longer rendered.
- LinkedIn points to `https://www.linkedin.com/in/david-sajitz-748b831a4`.
- Repository description and topics match the new positioning.
- The published README and metadata are read back from GitHub before completion is reported.
