# M808A 8x1 Relay Switcher Card · Amplifiers

Ward-Beck Systems M808A, 1994|27. Wiki page: [M808A on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/WBSps.ca/Github.WardBeckSystems/MODULES.AMPLIFIERS.M808A-8x1-Relay-Switcher-Card/)

| Folder | What is in it | Files |
|---|---|---|
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 1 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 7 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 1 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 1 |

## Pinouts

_Pinouts: the RTO-144 edge connector (connection sheets, connector layouts and rear views, strapping), and the pinout / connections drawings made from them. The module root `RTO.json` lists every contact._

## RTO-144 pinout

Read from 1 pinout picture (each its own `.pinout.json` beside it). Every contact, with where it was read: [`RTO.json`](RTO.json). How a picture becomes this table: [the pinout decision tree](https://github.com/WardBeckSystems/WBSps.ca/blob/main/2026/Engineering/PINOUTS.md).

| Pin | Signal | Kind | Port | Confidence |
|---|---|---|---|---|
| 1 | +24 V CONTROL | power |  | high |
| 2 | CONTROL 1 | control_in | CTL 1 | high |
| 3 | OUTPUT (K1-K4 BUS) | out | OUTPUT B | high |
| 4 | CONTROL 3 | control_in | CTL 3 | high |
| 5 | CONTROL 5 | control_in | CTL 5 | high |
| 6 | OUTPUT (K5-K8 BUS) | out | OUTPUT A | high |
| 7 | CONTROL 7 | control_in | CTL 7 | high |
| 8 | IN 8 | in | IN 8 | high |
| 9 | IN 7 | in | IN 7 | high |
| 10 | IN 6 | in | IN 6 | high |
| 11 | IN 5 | in | IN 5 | high |
| 12 | IN 4 | in | IN 4 | high |
| 13 | IN 3 | in | IN 3 | high |
| 14 | IN 2 | in | IN 2 | high |
| 15 | IN 1 | in | IN 1 | high |
| B | CONTROL 2 | control_in | CTL 2 | high |
| C | OUTPUT (K1-K4 BUS) | out | OUTPUT B | high |
| D | CONTROL 4 | control_in | CTL 4 | high |
| E | CONTROL 6 | control_in | CTL 6 | high |
| F | OUTPUT (K5-K8 BUS) | out | OUTPUT A | high |
| H | CONTROL 8 | control_in | CTL 8 | high |
| J | IN 8 | in | IN 8 | high |
| K | IN 7 | in | IN 7 | high |
| L | IN 6 | in | IN 6 | high |
| M | IN 5 | in | IN 5 | high |
| N | IN 4 | in | IN 4 | high |
| P | IN 3 | in | IN 3 | high |
| R | IN 2 | in | IN 2 | high |
| S | IN 1 | in | IN 1 | high |

**Straps:** J3/J4 BUS LINK: J3 J4

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [M808A.kicad_sym](KICAD/M808A.kicad_sym)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
