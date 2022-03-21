# RYCpad
[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

![Render](img/RYCpad_render.jpg)
*RYCpad rendered*

RYCpad (pronounced "ricey pad") is a custom mechanical keyboard numpad with through-hole components. It follows my other project [Axon](https://github.com/thatfellarobin/axon) in its emphasis on symmetric layout. RYCpad runs on an ATmega328P using VUSB and QMK.

RYCpad is designed to be printed with a black substrate PCB and clear solder mask, such as [OSHpark's After Dark service](https://docs.oshpark.com/services/afterdark/). There are no ground planes, allowing the traces to stand out. The bottom PCB has windows in the solder mask, so it can be printed at cheaper PCB fabs but still expose the copper.

The .dxf file for laser-cutting an acrylic cover for the components can be found in `doc/`. It will work fine as-is, but for best results the lines should be offset to account for the kerf of the specific laser being used. In my experience, an offset of 0.15 mm may be appropriate.

### Component Libraries

**Symbols:**
- [Keyboard symbols by Hasu](https://github.com/tmk/kicad_lib_tmk)

**Footprints:**
- [Keyswitches by Daprice](https://github.com/daprice/keyswitches.pretty), but modified for my own tastes/uses.
- My own footprints for silkscreen art. Can be found in `lib/`

## License
This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg

If you have built upon this project and have significantly altered the design, the non-commercial clause can be waived with explicit permission.