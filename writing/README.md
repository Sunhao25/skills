# Writing Skills (AI Agent Skills)

This folder contains **writing-related AI agent skills** — reusable playbooks that help an agent write, revise, and package text consistently.

Each **skill** is a standalone folder that includes:
- `SKILL.md` — the entrypoint instructions (inputs, workflow, output formats)
- `references/` — optional guides, examples, checklists (used on demand)

---

## What belongs here?

Use `writing/` for skills that primarily produce or improve written content, such as:
- web novels / serialized fiction
- short stories
- fan fiction
- erotica (adult-only, legal content)
- blurbs, hooks, titles, tags, marketing copy for written works
- editing, revision, style transformation, and consistency management (story bible)

> Non-writing skills (coding, data analysis, HR, study workflows, etc.) should live in their own top-level modules.

---

## Subcategories (how this folder is organized)

This module is organized into **subcategories** so you can find the right writing skill quickly:

### 1) `general/` — General fiction / web novel writing
Use this when you want:
- story ideas, worldbuilding, character setup
- outlines and chapter plans
- chapter drafting and serialized pacing
- revision and improvement for mainstream fiction/web novels

### 2) `fanfic/` — Fan fiction workflows
Use this when you want:
- canon alignment / divergence control
- character voice matching
- relationship-focused structure and tag planning
- fandom-friendly summaries and tagging

### 3) `erotica/` — Adult writing workflows (18+ only)
Use this when you want:
- adult/erotic fiction writing support
- pacing, consent boundaries, tone control, intimacy scene structure

Only create and use erotica skills for **consenting adults** and **legal content**.  
No underage content, no coercion, no illegal content.

---

## Current skills in this module

### ✅ Available
- `novel-master/`  
  A full-stack web novel writing skill: positioning → outline → chapter drafting → revision → story consistency → marketing copy.

> If you add more skills, list them here with one line per skill and keep names short and memorable.

---

## How to use a writing skill

1. Enter a specific skill folder (e.g. `writing/novel-master/`)
2. Open `SKILL.md`
3. Follow the “Inputs” section and provide what the skill asks for
4. Use the requested output format (outline, chapter, story bible snapshot, etc.)

**Tip:** If your agent/tool does not support installing skills from a subfolder automatically, you can still use the skill by copying the skill folder (the one containing `SKILL.md`) into your agent’s skill directory.

---

## Naming & structure rules (keep this repo clean)

### Folder naming
- Use short, capability-based names: `novel-master`, `plot-doctor`, `blurb-maker`
- Avoid overly detailed names that look like file titles
- Prefer hyphen-case for consistency

### Recommended structure
writing/<subcategory>/<skill-name>/
SKILL.md
references/
.gitkeep


### Minimum requirement for a new skill
- Must include `SKILL.md`
- Should include `references/` if the skill needs long-form supporting docs

---

## Add a new writing skill (quick checklist)

1. Pick a subcategory: `general/` / `fanfic/` / `erotica/`
2. Create the skill folder: `writing/<subcategory>/<skill-name>/`
3. Add `SKILL.md` with:
   - purpose + triggers (what this skill is for)
   - required inputs
   - workflow steps
   - output templates (formats)
4. Add optional references in `references/`
5. Update this `writing/README.md` to list the new skill

---

## Roadmap ideas (optional)

Possible future writing skills:
- `plot-doctor/` — diagnose pacing/conflict/motivation issues and rewrite
- `hook-lab/` — generate strong openings and chapter-end cliffhangers
- `title-tag-studio/` — titles, tags, blurbs optimized per platform
- `character-bible/` — character consistency management across long serialization
- `fanfic-canon-keeper/` — canon constraints + voice matching + tag planning
- `erotica-scene-architect/` — scene beats, consent framing, tone control
