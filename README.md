# PokéPal HG — ROM Edition v5

This build uses local graphics extracted from the user's own Pokémon HeartGold dump.

## Changes in v5
- Starter choices are Charmander, Bulbasaur and Squirtle.
- Pikachu is a secret fourth starter that unlocks after 30 visible seconds on the selection screen.
- The pet uses the larger, more detailed HeartGold battle sprite instead of the tiny follower sprite.
- Visible room art is built from textures extracted from HeartGold's room models (bed, TV, game system, window, clock, plant, furniture, wall/floor texture).
- No online Pokémon sprite fallback is used.
- The Train button is removed. Training XP comes from wild battles.
- Forage starts a random wild Pokémon battle using ROM-extracted detailed sprites.
- Wild pool: Caterpie, Pidgey, Rattata, Spearow, Zubat, Bellsprout, Sentret, Hoothoot, Mareep and Wooper.
- Battles use detailed front/back ROM sprites and a ROM-extracted battle-ground background.

## GitHub Pages
Upload the *contents* of this folder to the root of a repo, then enable Settings → Pages → Deploy from a branch → main → /(root).


This build adds a Pokédex-inspired red UI shell, a more discreet hidden Pikachu unlock, and enlarged detailed ROM sprites.


## v6 changes
- More faithful integer-scaled HG room textures and added fridge texture.
- Pokémon walk directly to the bed before sleeping.
- Level-up move learning with four move slots and replacement prompt.
- Poké Mart with money earned from battles.
- Permanent battle death in Mortality Mode with full memorial screen.
