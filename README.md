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
nativefier --name 'Todoist Custom' 'https://todoist.com/app/today' --internal-urls '.*' --browserwindow-options '{ "webPreferences": { "spellcheck": false } }' -e 10.1.0 --inject /Users/rolle/Projects/todoist-dracula-theme/style.css --user-agent 'Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_6) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/85.0.4183.102 Safari/537.36' --darwin-dark-mode-support --background-color '#22252e' --icon /Users/rolle/Projects/todoist-dracula-theme/icon.icns
```
