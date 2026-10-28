# Word Deck

A simple flashcard app for practicing vocabulary.

- Tap a card to flip between the word and its meaning
- Mark words as known or study them again
- Add your own words; progress is saved in your browser

It's a single `index.html` file with no setup needed. Open it in any browser.

## Where the words come from

The app reads its word list from a Supabase table named `WORD` (all capitals) with the columns
`word`, `pronunciation`, `meaning`, `example`. If Supabase can't be reached, it
falls back to the published Google Sheet, then to the last list it loaded.
