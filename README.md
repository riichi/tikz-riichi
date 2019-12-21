# Usage

The only command provided is `\DrawHand{height}{description}`, where `height` is the target height of the resulting TikZ figure and `description` is the hand description in following format:

- Any of the `mpsz` changes the current tile color,
- Any of the `0123456789` (for `mps`), `1234567` (for `z`) or `?` draws a tile. If a `*` follows, the tile is drawn rotated. `0` means red five and `?` means tile back,
- `~` makes space of length equal to 0.5 of tile's width.

Putting number before current color is specified or including any other characters in description results in undefined behavior.

Tile images are created by FluffyStuff, available under [https://github.com/FluffyStuff/riichi-mahjong-tiles](https://github.com/FluffyStuff/riichi-mahjong-tiles) and licensed under [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).