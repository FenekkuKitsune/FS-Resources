# Flexible Survival Resources

## VSCode Snippets

### Installation Instructions

Installation instructions:
1: Download the RAW snippet .json from this repository
2: Place the .json file in `%AppData%\Code\User\snippets` (merge or replace files if needed)
3: Ensure VSCode setting `editor.tabCompletion` is set to `onlySnippets` or `on`

**DO NOT PULL THIS REPOSITORY INTO YOUR SNIPPETS FOLDER**, snippets are not the only files that will be in this repository, and pulling the entire repo into your VSCode User Snippets folder could potentially cause issues!

### Usage Instructions

1: Type the snippet prefix - i.e. `situation` - where you're wanting to insert the snippet
2: As you're typing, the snippet should eventually appear in the context menu. Once you've found it, hit tab on your keyboard to insert the snippet

Once the snippet is inserted, your cursor will be automatically moved to preset tabstops, sometimes selecting predefined text. Hitting tab again will move you to the next tabstop, until the snippet is finished. You can cancel this at any time by hitting escape, or manually moving the cursor.

Some snippets will have multiple-choice presets, these will show a context menu when you reach them. To select from the menu, use your mouse to scroll and click an option. Hitting tab without selecting any option will default to the first option in the list.

Feel free to offer suggestions for snippets to add.

### Inform 7

#### Inform Prefixes

- `say`         - New Say line
- `ttype`       - Format inline text, bold/italic
- `sayif`       - Inline if statement
- `if`          - If statement
- `badspots`    - Add BadSpots line
- `resolution`  - Set Resolution of event
- `situation`   - Creating a new situation
- `walkintable` - Adding a situation to a walkin/navin table
- `openchoice`  - Creating an open-ended choice tree
- `closechoice` - Creating a yes/no boolean choice
- `trophylist`  - Create a Trophy List / Loot Table
- `triggerend`  - Trigger and ending
- `addend`      - Add an ending
- `newnpc`      - Create a new NPC template
- `newroom`     - Add a new room

### Godot

This snippet file - like the code it is used for - is in BETA and subject to change. The snippets within the file may not always be correct.

#### Godot Prefixes

- `newnpc`      - Create a new NPC template
- `openchoice`  - Create an open-ended choice tree
- `say`         - New Say line
