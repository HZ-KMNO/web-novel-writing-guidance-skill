# Web Novel Writing Guidance Skill

<p align="center">
  <img src="assets/logo.png" alt="Web Novel Writing Guidance Skill Logo" width="200">
</p>

> A portable Chinese web-novel guidance skill for planning, drafting, revising, de-AI polishing, and managing long-form serialized fiction.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Skill Type](https://img.shields.io/badge/Type-AI%20Agent%20Skill-green.svg)](https://github.com/HZ-KMNO/web-novel-writing-guidance-skill)

[English](README.md) | [简体中文](README.zh-CN.md)

---

## Overview

This skill is designed for AI agents that need to act as a long-term fiction-writing coordinator rather than a one-shot text generator. It captures a complete workflow for idea intake, story-engine design, chapter blueprints, chapter task cards, Draft A/B/C production, user-feedback revision, quality supervision, continuity records, and final handoff.

## Latest Enhancements

- Chapter blueprints and key-information files before drafting
- Independent character goals, information boundaries, mistaken beliefs, speech limits, and life traces
- Revision gates for tool-like characters, impossible knowledge, weak scene causality, and odd details
- Method-only summary of 20 excellent novel cases
- Extraction and statistics inventory for epub case files
- 13-part protocol for turning literary cases into practical fiction-writing methods
- Male-frequency suspense, puzzle, and reasoning execution rules with real evidence, fair clues, information gaps, and credible institutions

## Why This Skill Exists

AI can write fluent prose quickly, but long-form fiction needs more than fluency.

A useful novel-writing agent must:

- Understand the user's creative intent
- Organize scattered ideas into a working story engine
- Preserve canon across chapters
- Separate drafting, revision, and final polish
- Accept user feedback without rewriting everything unnecessarily
- Remove AI-like prose only after content is approved
- Track foreshadowing, timeline, character changes, and unresolved hooks
- Check quality from structure to prose, not the other way around

This skill provides that operating system.

## Core Workflow

```text
User ideas / suggestions / context
  → AI selects relevant skills and references
  → Chapter blueprint and key-information file
  → Chapter task card
  → Draft A: Complete initial draft
  → User feedback
  → Draft B: Content revision
  → User approval
  → Draft C: De-AI final pass
  → Continuity record and next-chapter handoff
```

**Core Principle:**

```text
Draft A writes it complete.
Draft B makes it correct.
Draft C makes it human.
```

## What The Skill Covers

- Idea expansion
- Story engine design
- Protagonist goal, wound, obstacle, and stakes
- Genre promise and reader pleasure
- Long-form outline thinking
- Chapter task cards
- Scene beats
- Draft A initial chapter writing
- Draft B user-directed revision
- Draft C de-AI prose polishing
- Dialogue humanization
- Continuity records
- Foreshadowing tracking
- Timeline management
- Quality gates
- Tutorial and source orchestration
- Long-running project handoff

## Repository Structure

```text
.
├── SKILL.md
├── agents/
│   └── openai.yaml
├── references/
│   ├── web-novel-craft.md
│   ├── excellent-novel-case-methods.md
│   ├── excellent-novel-case-inventory.json
│   └── writer-oriented-literary-analysis-protocol.md
├── README.md
├── README.zh-CN.md
├── LICENSE
└── assets/
    └── logo.png
```

The repository root is the actual skill package.

## Installation

Copy the skill folder into your AI agent's skill directory:

```bash
cp -r web-novel-writing-guidance-skill/ ~/.your-agent/skills/
```

For OpenAI or Codex-style skills, the trigger metadata is in `SKILL.md`.

## Example Prompts

**Generate Draft A:**

```text
Use web-novel-writing-guidance-skill. I will give you a premise and previous chapter summary. First create a chapter blueprint and key-information file, then write Draft A.
```

**Revise to Draft B:**

```text
Use web-novel-writing-guidance-skill to revise this chapter according to my feedback. Classify my feedback first, preserve the parts I liked, then produce Draft B.
```

**Polish to Draft C:**

```text
The content direction is approved. Use web-novel-writing-guidance-skill to perform Draft C de-AI polishing without changing canon, then write the continuity record.
```

## Quality Philosophy

The skill reviews fiction from large to small:

1. Reader promise
2. Chapter purpose
3. Protagonist goal and pressure
4. Conflict and situation change
5. Continuity and canon
6. Character motivation
7. Pacing and scene structure
8. Hook and payoff
9. Dialogue
10. Prose naturalness
11. De-AI residue

It explicitly avoids starting with sentence polish when the story structure is broken.

## License

MIT License. See [LICENSE](LICENSE) for details.
