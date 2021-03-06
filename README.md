# Gist Extension

[![Marketplace Version](https://vsmarketplacebadge.apphb.com/version-short/dbankier.vscode-gist.svg)](https://marketplace.visualstudio.com/items?itemName=dbankier.vscode-gist)

Access your GitHub Gists within Visual Studio Code. You can add, edit, and delete public and private gists.

![screencast](https://github.com/dbankier/vscode-gist/raw/master/vscode-gist-open-and-save.gif)

## Installation

Press <kbd>F1</kbd> and narrow down the list commands by typing `extension`. Pick `Extensions: Install Extensions`.
Select the `Gist Extension` extension from the list.

## GitHub Authentication

The plugin requires you authenticate with GitHub. You'll be asked for your username and password the first time you use the extension. This will generate a personal access token on GitHub.

## Usage

### Create Gists

You must have a file open and active to create a gist.

Press <kbd>F1</kbd> and enter the following:

~~~
GIST: Create New Block
~~~

You will be prompted a gist description.

### Open/Edit Gists

Press <kbd>F1</kbd> and enter one fo the following:

~~~
GIST: Open Block
GIST: Open Favorite Block
~~~

All files associated with the gist will be opened in group layout.

Once you have opened an **owned** gist, saving it will commit a new revision.

You can also use the following commands:

~~~
GIST: Delete Block
GIST: Remove From Block
GIST: Add To Block
GIST: Change Block Description
GIST: Open Block In Browser
~~~

## Keybord Shortcuts

While there are no pre-defined keyboard shortcuts, the following commands can be used in your settings:

~~~
extension.openCodeBlock
extension.openFavoriteCodeBlock
extension.createCodeBlock
extension.openCodeBlockInBrowser
extension.deleteCodeBlock
extension.removeFileFromCodeBlock
extension.addToCodeBlock
extension.changeCodeBlockDescription
~~~

## Maintainer
vscode-gist is maintained by [Ken Howard](https://github.com/kenhowardpdx).
