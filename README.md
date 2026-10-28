# Word Deck

A simple flashcard app for practicing vocabulary.

- Tap a card to flip between the word and its meaning
- Mark words as known or study them again
- Add your own words; progress is saved in your browser

It's a single `index.html` file with no setup needed. Open it in any browser.

## Where the words come from

The app reads its word list from a published Google Sheet with these columns:
`word`, `pronunciation`, `meaning`, `example`. Add a row to the sheet and the
new word appears the next time the app opens. If the sheet can't be reached,
the app uses the last list it loaded, or the built-in starter words.
