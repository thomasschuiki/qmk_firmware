# The default keymap for Redox

## config
qmk config user.keymap=juicybit
qmk config user.keyboard=redox/rev1

## compiling
https://docs.qmk.fm/#/newbs_building_firmware
qmk compile # with defaults set
qmk compile -kb redox/rev1 -km juicybit

## flashing
remember to disconnect second half before flashing
https://docs.qmk.fm/#/newbs_flashing?id=flash-your-keyboard-from-the-command-line
qmk flash
qmk flash -kb redox/rev1 -km juicybit

## testing
https://ciantic.github.io/keymapceditor/#redox
