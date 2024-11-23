# EDA libraries for Flipper Zero GPIO

## KiCad
Created in KiCad 8

Has both right-angle and straight pin footprints and symbols for both the 8-pin connector, 10-pin connector, and full 18-pin connector. Right-angle in this context means it uses right-angle pin headers leaving the PCB in parallel with the Flipper Zero LCD screen.

Each footprint includes a copy of the mechanical specifications of modules provided by [Flipper](https://docs.flipperzero.one/development/hardware/modules-blueprints) for the immediate board edge around the pin headers. These are on the `User.Drawings` layer.

The schematic symbol includes the GPIO function MUX table.

See the `kicad/` folder for reference photos.


## EagleCAD
Created in 7.6.0 but should cleanly import to any newer EagleCAD release.

Currently has Right-angle Devices for only 8-pin, only 10-pin, and the full 18-pin connections. Right angle in this context means it uses Right-angle pin headers leaving the PCB in parallel with the Flipper Zero LCD screen.

Each Device includes a copy of the mechanical specification of modules provided by [Flipper](https://docs.flipperzero.one/development/hardware/modules-blueprints) for the immediate board edge around the pin headers; both as notes on the `Measures` layer as well as a pre-made outline on a custom `Flipper_GPIO_Dimension` layer (layer 100). Neither of these need to be used and are provided for convenience to easily follow Flipper's guidelines.

The Schematic symbol includes the GPIO function MUX table on the Info layer.

See the `eagle/` folder for reference photos.


## Others
Have you ported this to any other EDA? Make a PR!
