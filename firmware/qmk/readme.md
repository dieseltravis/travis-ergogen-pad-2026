# dieseltravis/travis_ergogen_2026

![dieseltravis/travis_ergogen_2026](https://raw.githubusercontent.com/dieseltravis/travis-ergogen-2026/refs/heads/main/travis_erg2026_front.png)

* Keyboard Maintainer: [Travis Hardiman](https://github.com/dieseltravis)
* Hardware Supported: rp2040ce
* Hardware Availability: https://github.com/dieseltravis/travis-ergogen-2026

Make example for this keyboard (after setting up your build environment):

    make dieseltravis/travis_ergogen_2026:default

Flashing example for this keyboard:

    make dieseltravis/travis_ergogen_2026:default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard
* **Physical reset button**: Briefly press the button on the back of the PCB - some may have pads you must short instead
* **Keycode in layout**: Press the key mapped to `RESET` if it is available
