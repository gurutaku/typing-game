# Key Quest

## Edit the game content

All Word Rocket words and Sentence Quest sentences are in `content.json`. You do not need to edit `index.html` to change them.

- Add, edit, or remove items in the `words` array to change the Word Rocket vocabulary.
- Add, edit, or remove items in the `sentences` array to change Sentence Quest.
- The included word pool is curated for kids: everyday vocabulary, animals, nature, science, learning, positive traits, food, and hobbies. The game shuffles the list and runs through the pool before repeating words. Review any additions before publishing.
- Keep each text item in double quotes, separate items with commas, and do not put a comma after the final item.

Example:

```json
{
  "words": ["apple", "planet", "rainbow", "kindness"],
  "sentences": [
    "The quick fox jumps over the log.",
    "I love learning new things!"
  ]
}
```

Keep `index.html` and `content.json` in the same directory. Because the game loads the JSON with `fetch()`, open the site through GitHub Pages or a local web server; opening `index.html` directly as a `file://` URL may prevent the JSON from loading.

## Word Rocket controls

The round is armed automatically when the game loads. The 30-second countdown starts with the first typed character; there is no Start Round button. After a round finishes, use **Fly again** on the results screen to begin another round.
