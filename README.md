# Flexible Survival Resources
This repository contains extra resources for coding Flexible Survival

## VSCode Snippets
The inform7extension.json file contains snippets for VSCode. Placing that file in `%AppData%\Code\User\snippets` will allow you to autofill code in Inform files specific to Flexible Survival. To make it easier, in VSCode's settings set `editor.tabCompletion` to `onlySnippets` or `on`. If you already have snippets for Inform, copy/paste the snippets from this file into your pre-existing snippets file and resolve any errors.

To use the snippets you must type in the command for the snippet wherever you want the code in the file, for example `situation`, then if you've set the `editor.tabCompletion` setting as above, simply hitting tab will fill in the relevant code for you. Your cursor will be automatically moved to set places in the snippet, and hitting tab again will move your cursor to the next position in the snippet until finished. I've got it set up so it *should* be helpful, but I can always change it if needed.

Currently, there are snippets for:
- `situation` - Creating a new situation
- `walkintable` - Adding a situation to a walkin/navin table
- `openchoice` - Creating an open-ended choice tree
- `closechoice` - Creating a yes/no boolean choice