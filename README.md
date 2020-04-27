# Recursive theme for VS Code

Made to look especially nice with [Recursive Mono](https://github.com/arrowtype/recursive) (or any other code font with nice italics).

## How to start your own theme

**Easy**

https://themer.dev/

**More control**

- duplicate a theme you like within `~/.vscode/extensions/`
- update package.json
- update colors in `themes/________theme.json`

## How to determine the type of a given token

It’s critical to be able to determine type of a given token in order to become efficient in theming. Luckily, it's easy!

> Trigger the scope inspector from the Command Palette with the `Developer: Inspect Editor Tokens and Scopes` [source](https://code.visualstudio.com/api/language-extensions/syntax-highlight-guide#scope-inspector)