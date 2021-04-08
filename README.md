# 🧛🏻‍♂️ Dracula theme for Todoist

## Development

1. Run `npm install`
2. Run `scss --style compressed style.scss > style.css`

## Mac app

1. Set up Todoist dark theme from settings
2. Git clone this repository
3. Install [nativefier](https://github.com/nativefier/nativefier)
4. Run following command (Change /Users/rolle/... to correct path)

``` shell
nativefier --name 'Todoist' 'https://todoist.com/app/today' --darwin-dark-mode-support --background-color '#22252e' --browserwindow-options '{ "webPreferences": { "spellcheck": false } }' --inject /Users/rolle/Projects/todoist-dracula-theme/style.css --icon /Users/rolle/Projects/todoist-dracula-theme/icon.icns
```
