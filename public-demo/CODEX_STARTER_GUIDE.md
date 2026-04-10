# Codex Starter Guide

This guide is for people who want to use this public demo as a free starter resource in VS Code with Codex.

## Who this is for

This is especially useful if:

- you understand your SharePoint process well
- you know what is frustrating in the current workflow
- you know what result you want
- you do not yet have complete knowledge of every technical tool involved

That was exactly the situation behind this project.

## What this starter pack gives you

- a generic list structure in [`LIST_TEMPLATE.md`](./LIST_TEMPLATE.md)
- sample people data in [`sample-team.csv`](./sample-team.csv)
- sample task data in [`sample-tasks.csv`](./sample-tasks.csv)
- before and after visuals in [`images`](./images)
- a story and presentation script in [`STORY_SCRIPT.md`](./STORY_SCRIPT.md)
- a lightweight demo runner in [`video/index.html`](./video/index.html)

## How to use it in VS Code with Codex

1. Open this folder in VS Code.
2. Keep your own real workflow notes nearby.
3. Compare your current SharePoint list with `LIST_TEMPLATE.md`.
4. Use the sample files as a neutral reference model.
5. Ask Codex to help map your real process into a safer, cleaner app structure.

## Good prompts to start with

### Prompt 1: understand the gap

```text
I currently have a SharePoint list used for operational planning.
The current workflow is manual and hard to visualize.
Based on the files in this folder, help me identify the gap between a raw list workflow and a lightweight planning app.
```

### Prompt 2: adapt the structure

```text
Using LIST_TEMPLATE.md as a reference, help me redesign my current SharePoint list structure so it can support a planning workspace.
Do not assume I know SPFx deeply.
Explain the reasoning in practical terms.
```

### Prompt 3: define the MVP

```text
I know the current process and the result I want, but I do not know every technical detail yet.
Help me define the smallest useful version of a SharePoint-based planning app for this use case.
```

### Prompt 4: move into implementation

```text
Based on this starter pack, help me build a first version in VS Code.
Break the work into small steps and explain which parts are SharePoint structure, which parts are UI, and which parts are optional.
```

### Prompt 5: sanitize for public sharing

```text
Help me create a public-safe version of this internal workflow example.
Replace real names, departments, and process language with generic terms while preserving the transformation pattern.
```

## Practical advice

- Start from the workflow, not the code.
- Be very clear about what is painful in the current list experience.
- Describe what a better day-to-day experience would look like.
- Let Codex help explore the scope and technical path.
- Keep the first version small and usable.

## The main lesson

You do not need perfect technical knowledge before you begin.

If you understand the current process and the desired outcome, Codex can help you bridge a lot of the distance between those two points.
