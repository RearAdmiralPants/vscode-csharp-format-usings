# CSharpFormatUsings for Visual Studio Code
This extension helps to format C# using statements.

## Features
  * Sorts usings in alphabetical order. Doubles will be removed automatically.
  * Remove unnecessary usings.
  * Triggered via context menu or "Format Usings" command.

## Extension Settings
* `sortOrder`: Put namespaces in proper order. Values should be splitted with space. "System" by default.
* `splitGroups`: Insert blank line between using blocks grouped by first part of namespace. True by default.
* `removeUnnecessaryUsings`: Remove unnecessary usings if true. True by default.
* `numEmptyLinesAfterUsings`: the number of empty lines would be preserved between using statements and code block
* `numEmptyLinesBeforeUsings`: The maximum number of empty lines before using statements if there are characters, like comments, before usings.

## Installation of release version
Use instructions from marketplace.

## Installation from sources
1. Install node.js.
2. Run "npm install" from project folder.
3. Run "npm run package" from project folder.
4. Install brand new packed *.vsix bundle through vscode plugins menu option "Install from VSIX".
