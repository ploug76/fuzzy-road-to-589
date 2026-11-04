# Fuzzy: Road to 589 (fan game, chapters 1-5)

A FIVE8NINE fan game for Peter's Arcade (family copy, fully unlocked, no paywall). **Not official.** Fuzzybear ($FUZZY) was created by @fuzzy_dev_ and is run by the Fuzzybear team (@fuzzy_xrp, fuzzyxrp.com); the Fuzzy TCG is by Fuzzycards. All art is drawn in code; no official card art is used. Real people appear only by public handle.

**Not financial advice.** No token, no wallet connection, no purchases, no price talk. Green candles are decoration.

## Status: deliberately unfinished
Chapters 1-5 are built. Chapter 6 waits for the next @fuzzy_xrp riddle drop (projected Thu Nov 5, 2026, ~10:23 AM PT; the Oct 23 picture shows the plaque V·XI).

## Adding the next drop (chapter 6)
1. Verify the decode of the new post from the post itself (don't use unverified community readings).
2. In `index.html`, find `// NOV 5 DROP: add chapter 6 here` in `LEVELS` and add an object: `id`, `title`, `theme` (night/grid/islands/sea/north, or add one in `TH` + `drawBG`), `speed`, `blurb`, `src` (handle + date), `script` (chunk codes listed above `build()`), `riddle` `{q, cipher, hint, choices:[correct, wrong, wrong]}`.
3. Move `epilogue:true` from chapter 5 to the new last chapter (or write a new epilogue).
4. Remove `NEXT_DROP` or point it at the following drop.
5. Bump `CACHE` in `sw.js`.

## Controls
Fuzzy auto-runs. JUMP (orange, right; double jump), ACTION (green, left; smash red FUD candles and FUD clouds), BRIDGE (purple, top; build a liquidity bridge over a wide gap, needs a purple X kit). Keyboard: Space/Up = jump, X = action, B = bridge, P = pause.
