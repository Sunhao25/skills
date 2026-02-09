# Skills (AI Agent Skills Library)

This repository is a **skills library** for AI agents: a structured collection of reusable “Skill packs” that help an agent follow consistent workflows and produce stable, high-quality outputs.

A **Skill** is typically a folder that contains:
- `SKILL.md` — the entrypoint instructions (what the skill is for, how to use it, what to output)
- `references/` — optional long-form guides, checklists, examples (loaded only when needed)
- `templates/` or `assets/` — optional reusable templates, snippets, or resources

> This repo stores **skills only**. Code assets (Python/SQL/etc.) live in separate repositories.

---

## What is a “Skill” (and why use it)?

A skill is a **repeatable playbook** for an AI agent. Instead of writing the same prompts and rules again and again, you package them into a folder so the agent can:
- follow a standardized process
- reuse proven templates
- stay consistent across sessions
- scale to new tasks by adding new skill folders

---

## Compatibility (where these skills can be used)

These skills are designed for **AI agents that support “skill folders” / SKILL.md style workflows**, such as:
- agent environments that can load `SKILL.md` as instruction packs
- editors/agents that support skills or similar modular instruction systems
- the skills.sh ecosystem (when used as individual skills or via manual folder selection)

> Note: Not every tool supports “installing a subfolder as a skill” automatically.  
> If your agent can’t install from a subfolder, you can still copy the skill folder (the one containing `SKILL.md`) into your agent’s skills directory and use it the same way.

---

## Repository structure

This repo is organized by **high-level modules**.  
Each top-level folder represents a major use case category (a “big skill domain”).

Current modules:
- `writing/` — writing skills (novels, fanfic, erotica, etc.)

Planned modules (coming soon):
- `learning/` — study skills, tutoring workflows, exam prep, note-to-knowledge systems
- `coding/` — programming skills, code review, debugging playbooks, repo onboarding
- `data/` — data analysis skills, metric definitions, reporting workflows
- `hr/` — hiring, interviewing, performance review, HR comms playbooks
- `ops/` — operations, customer support playbooks, SOPs, incident response
- `product/` — PM workflows, PRDs, UX writing, launch checklists

---

## How to browse skills

1. Start from a module folder (e.g. `writing/`)
2. Choose a specific skill folder (e.g. `writing/novel-master/`)
3. Open `SKILL.md` to see:
   - what the skill does
   - required inputs
   - step-by-step workflow
   - output formats / templates

---

## Writing module: how it’s subdivided

Inside `writing/`, skills can be grouped by sub-types such as:
- `general/` — general fiction / web novel writing
- `fanfic/` — fan fiction specific workflows (canon handling, character voice, tags)
- `erotica/` — adult/erotica writing workflows (consent boundaries, tone control, pacing)

Example shape:
- `writing/general/<skill-name>/SKILL.md`
- `writing/fanfic/<skill-name>/SKILL.md`
- `writing/erotica/<skill-name>/SKILL.md`

> Any adult writing skills here are intended for **consenting adults and legal content only**.

---

## Contributing / adding a new skill

When adding a new skill, follow this minimum standard:
1. Create a folder for the skill
2. Add `SKILL.md` (required)
3. Add optional `references/` for long guides and examples
4. Keep folder names short and category-based (avoid overly detailed file-like names)

Recommended minimal layout:
