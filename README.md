# Fuzzy: Road to 589 (fan game, chapters 1-6)

A FIVE8NINE fan game for Peter's Arcade (family copy, fully unlocked, no paywall). **Not official.** Fuzzybear ($FUZZY) was created by @fuzzy_dev_ and is run by the Fuzzybear team (@fuzzy_xrp, fuzzyxrp.com); the Fuzzy TCG is by Fuzzycards. All art is drawn in code; no official card art is used. Real people appear only by public handle.

**Not financial advice.** No token, no wallet connection, no purchases, no price talk. Green candles are decoration.

## Status: deliberately unfinished
Chapters 1-6 are built (first several levels only). Chapter 6 is from the Nov 5, 2026 @fuzzy_xrp drop (hex caption MY DECODE: **14 YEARS OF PERSEVERANCE**). The road is not finished.

Live: https://ploug76.github.io/fuzzy-road-to-589/

## Adding a later drop
1. Verify the decode of the new post from the post itself (don't use unverified community readings).
2. In `index.html`, add the next object in `LEVELS`: `id`, `title`, `theme` (night/grid/islands/sea/north/vault, or add one in `TH` + `drawBG`), `speed`, `blurb`, `src` (handle + date), `script` (chunk codes listed above `build()`), `riddle` `{q, cipher, hint, choices:[correct, wrong, wrong]}`.
3. Move `epilogue:true` to the new last chapter.
4. Bump `CACHE` in `sw.js`.

## Controls
Fuzzy auto-runs. JUMP (orange, right; double jump), ACTION (green, left; smash red FUD candles and FUD clouds), BRIDGE (purple, top; build a liquidity bridge over a wide gap, needs a purple X kit). Keyboard: Space/Up = jump, X = action, B = bridge, P = pause.
