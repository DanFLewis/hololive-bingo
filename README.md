# Hololive Bingo

**Live:** https://danflewis.github.io/hololive-bingo/

A bingo card for watching Calliope Mori's streams, made in October 2020. The squares are her
catchphrases and running jokes. Each time the page loads you get a different card, picked at random from a million shuffles, so
every viewer gets their own.

## Where it came from

This is a fork of [thirdender/bingo-card-generator](https://github.com/thirdender/bingo-card-generator) by Robert
Rothermel, a React app for making printable bingo cards from your own list of phrases. The card layout, print styles
and saved settings are all his work.

What I changed, in an afternoon:

- Swapped the default phrases for the Calliope Mori list and titled the card "Calliope Mori Bingo".
- Hid the editing form so visitors just see a card.
- Showed one random card per page load instead of printing a set.
- Added the page title, description and credits, and deployed it to GitHub Pages.

## Running it

It's a 2020 Create React App project (React 16, react-scripts 3, node-sass), so it needs an old Node version
(Node 14 works).

```
npm install
npm start          # local dev server
npm run deploy     # build and publish to GitHub Pages
```

To make a card for something else, change `title` and `items` in `src/App.js`.
