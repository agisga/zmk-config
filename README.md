# Some ZMK config files

## Layout diagram for my Minidox keymap

- Originally inspired by [miryoku (with MIRYOKU_LAYERS=FLIP, MIRYOKU_NAV=INVERTEDT)](https://github.com/manna-harbour/miryoku/blob/master/data/layers/miryoku-kle-reference-flip-invertedt.png), but pretty far removed at this point.
- Backspace has been moved around to a number of different locations/layers/combos over the years in my keymap, which started because I was experiencing thumb issues resulting from overuse from thumb backspace.
- Heavy reliance on sticky/one-shot keys, because I was experiencies thumb pain due to holding keys for layers, and, besides, I find one-shot Shift very enjoyable to use (gets rid of any delays due to capitalization in the flow of typing).
    * Numbers are accessed from a one-shot NUM layer (left thumb).
    * Symbols that usually require Shift are accessed by: one-shot shift (right thumb) -> one-shot NUM layer (left thumb) -> a right hand finger position on the NUM layer (for example, 5 gives %, 7 gives &, etc).
- Many custom macros for the type of typing I do on the FUN and NAV layers.
- I was relying on many combos for a long time, but eventually I found them less comfortable compared to other alternatives. Now my 6 column keyboards have only 1-2 or no combos, and my 5 column keyboards move the 6th column keys to (mostly) horizontal combos of the inner-most two columns.
- The visualization was produced using <https://caksoylar.github.io/keymap-drawer>.
- My QMK keymaps are available [here](https://github.com/agisga/qmk_userspace). In addition to what is shown below, in QMK I have:
    * [Dynamic macros](https://github.com/qmk/qmk_firmware/blob/master/docs/feature_dynamic_macros.md) on the `fun` layer. (very useful at times!)
    * A `mouse` layer.

![Minidox keymap SVG](./minidox.svg)
