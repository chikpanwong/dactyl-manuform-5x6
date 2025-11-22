# dactyl-manuform-5x6

## keyboard case
dactyl-configurator: https://github.com/rianadon/dactyl-configurator

link: https://ryanis.cool/dactyl/#manuform

## keycaps
KeyV2: https://github.com/rsheldiii/KeyV2

openSACD keycaps code:
```
include <./includes.scad>

$stem_inner_slop = 0.8;

flared_support() cherry() row_profile("mt3") no_stem_support() translate_u(x=0, y=0, z=0) rotate([0,45,0]) {
    key(true);
}
```

## hotsweap
https://github.com/stingray127/handwirehotswap 

## qmk
QMK MSYS: https://msys.qmk.fm/ 

Layout:
https://config.qmk.fm/#/40percentclub/half_n_half/LAYOUT

QMK frameware docs:
https://docs.qmk.fm/

```
qmk list-keyboards
qmk list-keyboards | grep {keyboard name}
qmk new-keymap -kb {keyboard name} -km {your-name}
qmk compile -kb {keyboard name} -km {your-name}
```
