# Web Novel Writing Mainbrain Skill

![Web Novel Writing Mainbrain logo](assets/logo.png)

A portable AI-agent skill for planning, drafting, revising, de-AI polishing, and managing long-form web novels or serialized genre fiction.

This skill is designed for AI agents that need to act as a long-term fiction-writing "mainbrain" rather than a one-shot text generator. It captures a complete workflow for idea intake, story-engine design, chapter task cards, Draft A/B/C production, user-feedback revision, quality supervision, continuity records, and final handoff.

## Why This Skill Exists

AI can write fluent prose quickly, but long-form fiction needs more than fluency.

A useful novel-writing agent must:

- understand the user's creative intent;
- organize scattered ideas into a working story engine;
- preserve canon across chapters;
- separate drafting, revision, and final polish;
- accept user feedback without rewriting everything unnecessarily;
- remove AI-like prose only after content is approved;
- track foreshadowing, timeline, character changes, and unresolved hooks;
- check quality from structure to prose, not the other way around.

This skill provides that operating system.

## Core Workflow

```text
User ideas / suggestions / context
-> AI selects relevant skills and references
-> chapter task card
-> Draft A: complete initial draft
-> user feedback
-> Draft B: content revision
-> user approval
-> Draft C: de-AI final pass
-> continuity record and next-chapter handoff
```

Core principle:

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
- Tutorial/source orchestration
- Long-running project handoff

## Repository Structure

```text
.
├─ README.md
├─ README.zh-CN.md
├─ LICENSE
├─ assets/
│  └─ logo.png
└─ web-novel-writing-mainbrain/
   ├─ SKILL.md
   ├─ agents/
   │  └─ openai.yaml
   └─ references/
      ├─ chapter-workflow.md
      ├─ quality-supervision.md
      ├─ de-ai-polishing.md
      ├─ continuity-records.md
      └─ source-and-skill-orchestration.md
```

The actual skill package is the `web-novel-writing-mainbrain/` folder.

## Installation

Copy the skill folder into your AI agent's skill directory:

```text
web-novel-writing-mainbrain/
```

For OpenAI/Codex-style skills, the trigger metadata is in:

```text
web-novel-writing-mainbrain/SKILL.md
```

## Example Prompts

```text
Use $web-novel-writing-mainbrain. I will give you a premise and previous chapter summary. First create a chapter task card, then write Draft A.
```

```text
Use $web-novel-writing-mainbrain to revise this chapter according to my feedback. Classify my feedback first, preserve the parts I liked, then produce Draft B.
```

```text
The content direction is approved. Use $web-novel-writing-mainbrain to perform Draft C de-AI polishing without changing canon, then write the continuity record.
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

## Chinese README

中文版说明见 [README.zh-CN.md](README.zh-CN.md).

## License

MIT License.
