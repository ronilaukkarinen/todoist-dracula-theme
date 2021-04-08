# 🧛🏻‍♂️ Dracula theme for Todoist

## Development

1. Run `npm install`
2. Run `scss --style compressed style.scss > style.css`

## Mac app

1. Set up Todoist dark theme from settings
2. Git clone this repository
3. Install [nativefier](https://github.com/nativefier/nativefier)
4. Run following command

``` shell
nativefier --name 'Todoist' 'https://todoist.com/app/today' --internal-urls '.*' --browserwindow-options '{ "webPreferences": { "spellcheck": false } }' -e 10.1.0 --inject /Users/rolle/Projects/todoist-dracula-theme/style.css --user-agent 'Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_6) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/85.0.4183.102 Safari/537.36'
```
