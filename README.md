# RBLXTasteReferences

A curated visual reference library for Roblox thumbnails, icons, and creative formats. Use it to study design choices and inform original work across all games.

**This repository is the visual reference source for thumbnail and icon creation.** Use its images for visual inspiration across every game. Game-specific materials can supply accurate game facts and approved in-game assets, but are not an alternate visual inspiration library.

**This is a visual taste library, not a performance dataset or a list of official Roblox requirements.** Good, Mid, and Bad are curator judgments; they do not prove CTR, play rate, or universal rules.

## Before creating a thumbnail or icon

Use the current conversation and any game-specific materials the user explicitly provides to prefill known game facts and approved assets. For visual direction, use only images in this repository. Do not scan the user's computer or look for local files. Ask only for missing information, and do not invent game features, update details, or claims. If a core fact is unclear, ask before generating.

### Intake prompt

> Before I create this, please share whatever is missing:
> - **Game and core play:** What does the player do, and what genre is it?
> - **USP / player promise:** What makes this game or experience distinct? What should make a player choose it?
> - **Asset placement:** Is this for an ad, Home Recommendation, experience detail page, game icon, or an event?
> - **Update or launch:** What is new, when is it happening, and what must this creative communicate?
> - **Must-show details:** Which character, weapon, map, mechanic, reward, or moment should appear?
> - **Visual direction:** Which examples in RBLXTasteReferences should guide the design? What should the creative feel like?
> - **Game facts and approved assets:** Has the user provided a game-specific repository, brief, or asset set with accurate facts and approved in-game visuals?
> - **Constraints:** What must be included or avoided? Are there approved text, logos, or claims to use?
> - **Output:** What asset type, dimensions, and number of concepts do you need?
>
> Skip questions already answered in the brief or provided project materials. Mark unknowns rather than filling them in by guesswork. Do not search the user's computer for missing materials.

## Keep game facts separate from visual references

Use RBLXTasteReferences as the visual inspiration library for every game's thumbnails and icons. For an ongoing game, the user may provide a separate game-specific repository to ground the work in that game's actual USP, current state, and approved in-game assets. Use that source for factual context and game assets only; do not use it as a second visual inspiration library.

For recurring work, ask for the game's repository link if current facts or approved assets are missing. If the user does not have one, recommend creating it and provide the structure below. A repository is not required for a one-off task when the user has already supplied the needed brief and assets. Never search local folders or files for game information.

Suggested game repository structure:

- GameReferenceRepo/
  - README.md: evergreen game brief, core loop, USP, audience, and art direction
  - ApprovedGameAssets/: actual gameplay, characters, weapons, maps, UI, and other approved in-game assets
  - Updates/
    - YYYY-MM-DD_UpdateName/
      - README.md: what changed, what to feature, timing, and must-show or avoid details
      - ApprovedAssets/: actual assets for that update
    - Add one dated folder for each meaningful update

Keep stable, evergreen information in the game repository's root README.md. Organize approved game assets into clearly named folders. Give each meaningful update its own dated folder. If there is no game-specific repository, use the user's brief and assets they explicitly supplied for that task.

## How to use this visual library

1. Open and inspect the images in this repository. Filenames and labels are clues, not a substitute for viewing them.
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
