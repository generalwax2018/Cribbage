# Hearth Cribbage

Premium digital cribbage board with selectable designs and animated metal pegs.

## Files

- `index.html` — main game
- `board_luxury.jpg` — Luxury Walnut + Brass board
- `board_maple.jpg` — Sculpted Maple board
- `board_steam.jpg` — Steampunk board
- `board_deco.jpg` — Art Deco board
- `board_classic.jpg` — Classic Three-Track board
- `peg_brass_top.jpg` — Brass peg (You); `peg_brass.jpg` side view
- `peg_steel_top.jpg` — Dark steel peg (Grok); `peg_steel.jpg` side view
- `card_back.jpg` — Card back design
- `table_bg.jpg` — Table background

## Run

Open `index.html` in a browser. All images must be in the same folder.

## Features

- Full two-player cribbage against Grok, to 121
- Dealer alternates each hand; non-dealer leads
- Pegging with 15s, 31s, pairs, runs, go and last card
- Hand and crib scoring: fifteens, pairs, runs, flushes, nobs, his heels
- Grok picks discards and plays using simple scoring heuristics
- Board selector; pegs follow each board's own tracks, one lane per player
- Two metal pegs per player that leapfrog like a real board: on each score the back peg hops hole by hole past the front peg, with a "+N" badge where it lands
- The show is counted hand by hand, with each card combination and its points listed
- Hint button: best discard (by expected hand value) and best pegging play
- Synthesised sound effects with an on/off toggle
- Skunk / double-skunk detection and win/loss stats, saved in the browser
- Board and your hand fit on one screen: side by side on desktop (the board stays in view as you scroll), stacked and compact on tablets and phones
- Remembers your board choice; works on phones
