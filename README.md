# AI + Historical Research Demo Workspace

This folder contains the small reusable materials for the classroom demo.

The demo question is:

> Where did Lingnan begin: Macau or Canton/Guangzhou?

The point is not to let AI decide the answer. The point is to use AI as a workflow assistant while keeping sources, notes, and claims traceable.

The classroom version is prepared for use without live search or live download during the demo. Scene 1 shows what a source-finding agent should return; Scenes 2 and 3 use the prepared 1908 PDF and evidence record already in this workspace.

## Folder Structure

- `skills/` reusable agent instructions.
- `prompts/` copy-paste prompts for the three demo scenes.
- `sources/` prepared source-candidate record.
- `materials/` the 1908 PDF and reference images used in the demo.
- `examples/` finished examples for backup or comparison.

## Three Demo Scenes

1. Show one credible source candidate found by the source-finding workflow.
2. Read the prepared PDF and make a traceable evidence record.
3. Draft a short source-backed paragraph from the evidence.

## How to Use the Skills

If your agent supports skills, add the folders in `skills/`.

If it does not, open the relevant `SKILL.md`, paste its contents into the chat, and then paste the matching prompt from `prompts/`.

Keep the rule simple:

- AI can search, organize, extract, and draft.
- You inspect the source and make the historical judgment.
- Do not cite AI output as historical evidence.
