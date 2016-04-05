# conversations-ssurl-generator
A standalone web-based app to generate perfectly formatted submission links ("ssURLs") for Bazaarvoice Conversations

## How to use this app:
1. Simply clone the project (i.e. "repo" or "repository") to a local directory
2. drag-n-drop the index.html file into your favorite browser
3. Enjoy!

## How to clone the repo?
From your terminal (command line)
```
git clone https://github.com/arteedecco/conversations-ssurl-generator.git
```

Please report any bugs.

## Revisions
- Only allow users to enter unique data pairs to inject. In other words we don't want users entering duplicate `question=value` combinations since all submission form quesiton ids are unique
- Added validation to the add new question / answer input boxes by adding an inline alert warning if a duplicate combination is entered
- Disable the "Add" button if duplicate combination is entered