# Key Quest

## Edit the game content

Update `content.json` to change the words used in **Word Rocket** and the sentences used in **Sentence Quest**.

- Add, edit, or remove entries inside the `words` array.
- Add, edit, or remove entries inside the `sentences` array.
- Keep each entry inside double quotes and separate entries with commas.
- Make sure the JSON remains valid. Do not add a comma after the last entry in an array.

Example:

```json
{
  "words": ["sunshine", "planet", "rainbow"],
  "sentences": [
    "The quick fox jumps over the log.",
    "I can learn something new each day."
  ]
}
```

Keep `index.html` and `content.json` in the same directory. Because the game loads the JSON with `fetch()`, open the site through GitHub Pages or a local web server; opening `index.html` directly as a `file://` URL may prevent the JSON from loading.
