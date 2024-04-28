# My custom sofle keyboard layout

To use it, you need to clone this repository folder to your "qmk_firmware/keyboards/sofle/keymaps" directory

```bash
  git clone https://github.com/FlavioZanoni/kbd-config ${QMK_FIRMWARE_PATH}/keyboards/sofle/keymaps/gallon
```

Then you can compile and flash the firmware to your keyboard.

```bash
   qmk compile -kb sofle -km gallon
   qmk flash -kb sofle -km gallon
```

## Layers

You can better see the layers by uploading the json file inside "/revisions" to the [qmk configurator](https://config.qmk.fm/#/sofle/rev1/LAYOUT)
