# split-kb

This repo contains the hardware design files for a 105 key QMK/VIA enabled split keyboard. The design is inspired by [Keebio Sinc](https://keeb.io/collections/sinc) and [Split111](https://geekhack.org/index.php?topic=103449.0). Unlike Sinc, this keyboard contains a Southpaw numpad, and unlike Split111, the design of this keyboard is open-sourced.

The PCB is designed using KiCAD. Case files for a stacked acrylic case is designed using Shapr3D. You can find the KiCAD project in this `root` directory, DXF drawing files under `case design/v1`, and layout and VIA files in the `layout` directory.

My QMK repo's [split-kb](https://github.com/liangste/qmk_firmware/tree/split-kb) branch contains all the configuration files necessary to run QMK and VIA. This repo only contains hardware designs.

_________________

Finished keyboard with purple top layer, clear mid layers, and wrist rests made with Red Oak hardwood (stained with linseed oil).

![top](https://github.com/liangste/split-kb/blob/main/pictures/pic1.JPG)

![split](https://github.com/liangste/split-kb/blob/main/pictures/pic2.JPG)

Bottom layer showcasing a Elite-PI microcontroller and a TRRS jack for serial connection between the two halves.

![bottom](https://github.com/liangste/split-kb/blob/main/pictures/pic3.JPG)

A snapshot of the PCB design on KiCAD.

![pcb](https://github.com/liangste/split-kb/blob/main/split-kb.png?raw=true)
