# Custom Sofle keyboard layout


<img width="700" height="522" alt="image" src="https://github.com/user-attachments/assets/f0d37b9c-820b-4b74-8afa-bdbc33f58fe9" />

---

To use it, you need to clone this repository folder to your "qmk_firmware/keyboards/sofle/keymaps" directory

```bash
git clone git@github.com:FlavioZanoni/kbd-config.git ${QMK_FIRMWARE_PATH}/keyboards/sofle/keymaps/gallon
```

Then you can compile and flash the firmware to your keyboard.

```bash
qmk compile -kb sofle -km gallon
qmk flash -kb sofle -km gallon
```

## Layers

You can better see the layers by uploading the json file inside "/revisions" to the [qmk configurator](https://config.qmk.fm/#/sofle/rev1/LAYOUT)
