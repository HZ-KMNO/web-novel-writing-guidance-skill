# ✍️ Web Novel Writing Guidance Skill

![Web Novel Writing Guidance Skill logo](assets/logo.png)

💡 A portable Chinese web-novel guidance skill for planning, drafting, revising, de-AI polishing, and managing long-form serialized fiction.

💡 This skill is designed for AI agents that need to act as a long-term fiction-writing coordinator rather than a one-shot text generator. It captures a complete workflow for idea intake, story-engine design, chapter blueprints, chapter task cards, Draft A/B/C production, user-feedback revision, quality supervision, continuity records, and final handoff.

## ✨ Latest Enhancements

- ✅ Chapter blueprints and key-information files before drafting.
- ✅ Independent character goals, information boundaries, mistaken beliefs, speech limits, and life traces.
- ✅ Revision gates for tool-like characters, impossible knowledge, weak scene causality, and odd details.
- ✅ `excellent-novel-case-methods.md`, a method-only summary of 20 excellent novel cases.
- ✅ `excellent-novel-case-inventory.json`, an extraction/statistics inventory for those epub case files.
- ✅ `writer-oriented-literary-analysis-protocol.md`, a 13-part protocol for turning literary cases into practical fiction-writing methods. Every section answers: "What can this do for my own novel writing?"
- ✅ `literary-deep-reading-workflow.md`, a status-based deep-reading archive workflow that separates inventory, first reading, structural reading, chapter-level analysis, craft conversion, and project application.
- ✅ Daily 10-book case-library batch workflow: inventory every new book, select priority works for deeper reading, update the method library, then state how the batch affects the active novel direction before drafting.
- ✅ Male-frequency suspense / puzzle / reasoning execution rules: real evidence, fair clues, information gaps, and credible institutions first.

## 💡 Why This Skill Exists

💡 AI can write fluent prose quickly, but long-form fiction needs more than fluency.

💡 A useful novel-writing agent must:

- ✅ understand the user's creative intent;
- ✅ organize scattered ideas into a working story engine;
- ✅ preserve canon across chapters;
- ✅ separate drafting, revision, and final polish;
- ✅ accept user feedback without rewriting everything unnecessarily;
- ✅ remove AI-like prose only after content is approved;
- ✅ track foreshadowing, timeline, character changes, and unresolved hooks;
- ✅ check quality from structure to prose, not the other way around.

💡 This skill provides that operating system.

## 🔁 Core Workflow

```text
User ideas / suggestions / context
-> AI selects relevant skills and references
-> chapter blueprint and key-information file
-> chapter task card
-> Draft A: complete initial draft
-> user feedback
-> Draft B: content revision
-> user approval
-> Draft C: de-AI final pass
-> continuity record and next-chapter handoff
```

💡 Core principle:

```text
Draft A writes it complete.
Draft B makes it correct.
Draft C makes it human.
```

## 🎯 What The Skill Covers

- ✅ Idea expansion
- ✅ Story engine design
- ✅ Protagonist goal, wound, obstacle, and stakes
- ✅ Genre promise and reader pleasure
- ✅ Long-form outline thinking
- ✅ Chapter task cards
- ✅ Scene beats
- ✅ Draft A initial chapter writing
- ✅ Draft B user-directed revision
- ✅ Draft C de-AI prose polishing
- ✅ Dialogue humanization
- ✅ Continuity records
- ✅ Foreshadowing tracking
- ✅ Timeline management
- ✅ Quality gates
- ✅ Tutorial/source orchestration
- ✅ Long-running project handoff

## 🗂️ Repository Structure

```text
.
├─ SKILL.md
├─ agents/
│  └─ openai.yaml
├─ references/
│  ├─ web-novel-craft.md
│  ├─ excellent-novel-case-methods.md
│  ├─ excellent-novel-case-inventory.json
│  ├─ writer-oriented-literary-analysis-protocol.md
│  └─ literary-deep-reading-workflow.md
├─ README.md
├─ README.zh-CN.md
├─ LICENSE
└─ assets/
   └─ logo.png
```

💡 The repository root is the actual skill package.

## 🚀 Installation

💡 Copy the skill folder into your AI agent's skill directory:

```text
web-novel-writing-guidance-skill/
```

💡 For OpenAI/Codex-style skills, the trigger metadata is in:

```text
web-novel-writing-guidance-skill/SKILL.md
```

## 💬 Example Prompts

```text
Use this web-novel writing guidance skill. I will give you a premise and previous chapter summary. First create a chapter blueprint and key-information file, then write Draft A.
```

```text
Use this web-novel writing guidance skill to revise this chapter according to my feedback. Classify my feedback first, preserve the parts I liked, then produce Draft B.
```

```text
The content direction is approved. Use this web-novel writing guidance skill to perform Draft C de-AI polishing without changing canon, then write the continuity record.
```

## ✅ Quality Philosophy

💡 The skill reviews fiction from large to small:

1. ✅ Reader promise
2. ✅ Chapter purpose
3. ✅ Protagonist goal and pressure
4. ✅ Conflict and situation change
5. ✅ Continuity and canon
6. ✅ Character motivation
7. ✅ Pacing and scene structure
8. ✅ Hook and payoff
9. ✅ Dialogue
10. ✅ Prose naturalness
11. ✅ De-AI residue

💡 It explicitly avoids starting with sentence polish when the story structure is broken.

## 🌐 Chinese README

🌐 Chinese documentation is available in [README.zh-CN.md](README.zh-CN.md).

## 📜 License

💡 MIT License.
