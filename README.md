# RBLXTasteReferences

A curated visual reference library for Roblox thumbnails, icons, and creative formats. Use it to study design choices and inform original work.

**This is a visual taste library, not a performance dataset or a list of official Roblox requirements.** Good, Mid, and Bad are curator judgments; they do not prove CTR, play rate, or universal rules.

## Before creating a thumbnail or icon

Use the current conversation and any game-specific reference repository to prefill what is already known. Ask only for missing information, and do not invent game features, update details, or claims. If a core fact is unclear, ask before generating.

### Intake prompt

> Before I create this, please share whatever is missing:
> - **Game and core play:** What does the player do, and what genre is it?
> - **USP / player promise:** What makes this game or experience distinct? What should make a player choose it?
> - **Asset placement:** Is this for an ad, Home Recommendation, experience detail page, game icon, or an event?
> - **Update or launch:** What is new, when is it happening, and what must this creative communicate?
> - **Must-show details:** Which character, weapon, map, mechanic, reward, or moment should appear?
> - **Audience and style:** Who is it for? What should it feel like? Which visual styles or references should guide it?
> - **Game reference source:** Is there a game-specific repository or folder with approved assets and current facts?
> - **Constraints:** What must be included or avoided? Are there approved assets, text, logos, or claims to use?
> - **Output:** What asset type, dimensions, and number of concepts do you need?
>
> Skip questions already answered in the brief or project materials. Mark unknowns rather than filling them in by guesswork.

## Keep game facts separate from visual taste references

Use this repository for reusable visual references. For an ongoing game, keep its facts, approved assets, and changing content in a separate game-specific repository. This lets the assistant ground each creative in the game's actual USP and current state while using this repository for visual direction.

For recurring work, ask the user for that game's repository link. If they do not have one, recommend creating it and provide the structure below. A repository is not a prerequisite for a one-off task when the user has already supplied the needed brief and assets.

Suggested game repository structure:

- GameReferenceRepo/
  - README.md: evergreen game brief, core loop, USP, audience, and art direction
  - Core Gameplay/: current gameplay, characters, weapons, maps, UI, and approved assets
  - Updates/
    - YYYY-MM-DD_UpdateName/
      - README.md: what changed, what to feature, timing, and must-show or avoid details
      - References/: screenshots and approved update assets
    - Add one dated folder for each meaningful update

Keep stable, evergreen information in the game repository's root README.md. Organize its images into clearly named folders rather than leaving a crowded set of files at root. Give each meaningful update its own dated folder. If there is no game repository, use the user's brief and supplied assets for that task.

## How to use this visual library

1. Open and inspect the image itself. Filenames and labels are clues, not a substitute for viewing it.
2. Start with the closest genre folder for genre fit and the closest format folder for composition. Use the Game Icon folder for icons.
3. Identify the transferable choices, such as focal hierarchy, small-size readability, action clarity, contrast, or emotion.
4. Adapt those choices to the game brief and create original artwork; do not copy a reference's full composition.
5. When explaining a recommendation, cite the repository path and the design principle being applied.
6. Do not infer performance results unless measured data for that exact creative is provided.

## Folder guide

- Format - Before and After, Format - Core Action, Format - Incremental, Format - Party: creative format examples.
- Genre_Reference_Action RPG and Genre_Reference_Shooter: examples grouped by genre.
- Game Icon: icon references.
- Hourglass Reference: hourglass composition references.
- Root-level images: general examples and assets such as avatars, facial expressions, arrows, and text treatments.

## Reference labels

- GoodReference_: a preferred example; study the choices that make it effective.
- MidReference_: a mixed or context-dependent example; identify what works and what does not.
- BadReference_ or BadExample_: an example to critique; identify the issue before applying a lesson elsewhere.

These labels describe design guidance only. They are not performance rankings.

## Final thumbnail handoff

Whenever you deliver a finished thumbnail, remind the user to preview it in [Thumbnail Lab](https://robloxthumbnaillab.run.ingarena.net/) on mobile and PC to check its clarity and whether it stands out. If the thumbnail is for an upcoming game update or launch, also mention the [Event Hourglass Icon tool](https://robloxhourglassicon.run.ingarena.net/) for creating an event icon.

## Adding references

Use descriptive filenames that include the label, category, and subject. For each new group, add a short note stating what the images show, why they received their labels, the transferable design lessons, relevant context or limitations, and source links when available. Keep the image files in the repository so an AI can inspect the visual examples; Markdown descriptions alone cannot convey all visual details.
