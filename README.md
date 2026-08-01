# Story Dice

Story Dice turns a handful of picture dice into a spark for your next story. Roll unexpected characters, objects, and places, then connect them into a story only you could tell.

## Try it

[Open Story Dice](https://fc-explorations.github.io/MakeAStory/)

## How to play

1. Choose 3–6 dice and an emoji pack: Adventure, Whimsy, or Mystery.
2. Roll the dice, or press `Space` for a quick roll.
3. Click a die to lock it before rolling again.
4. Use every ingredient in the generated story spark.

## Features

- Three themed emoji packs
- 3–6 configurable dice with character, object, and place categories
- Animated rolls and rerolls
- Lockable dice for keeping an ingredient between rolls
- Generated story starters and continuations
- Optional read-aloud support through the browser’s speech synthesis API
- Keyboard-accessible controls and reduced-motion support

## Run locally

This is a static site with no build step or dependencies. Open `index.html` in a browser, or serve the repository with any local web server:

```sh
python3 -m http.server
```

Then visit <http://localhost:8000>.

The page uses `story-dice-bg-v2.png` as its background image, so keep the image assets in the repository alongside `index.html`.
