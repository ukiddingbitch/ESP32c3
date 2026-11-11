# ESP32-C3

MIFA-F4 is a development board based on the **Espressif ESP32-C3FH4**, with 4 MB of flash, 2.4 GHz Wi-Fi, and Bluetooth LE. A meandered inverted-F antenna (MIFA) is etched into the PCB. Contacts on both sides of the board edge form the USB-C interface.

## Hardware

| Feature | Specification |
| --- | --- |
| Board size | 24.54 × 29.90 mm |
| PCB | 0.8 mm, two-layer FR-4 with an ENIG finish and castellated edge holes |
| Antenna | Meandered PCB antenna based on TI AN043 |
| Headers | Two rows of eight pins on a 2.54 mm pitch, spaced 20.32 mm apart center to center |
| Buttons | BOOT pulls GPIO9 low. RESET pulls EN low. |
| Assembly | 35 components per board |
| Panel | Six boards in a 3 × 2 layout, 95.62 × 80 mm, 210 component placements |

## Board previews

**MIFA-F4 in the KiCad 3D Viewer**

![Angled view of MIFA-F4 showing the USB-C edge contacts and meandered PCB antenna](docs/F4.png)

**Six-board assembly panel**

![Top copper, silkscreen, and routed outline of the six-board panel](docs/F4-panel.svg)

## Interactive 3D view

Drag the assembled board to rotate it. The copper antenna is raised slightly for visibility in this monochrome model.

```stl
solid F4
facet normal -0.75 -0.66 0
outer loop
vertex -12.22 -14.54 0
vertex -11.94 -14.86 0
vertex -11.94 -14.86 0.71
endloop
endfacet
facet normal -0.23 -0.97 0
outer loop
vertex -11.94 -14.86 0
vertex -11.77 -14.9 0.71
vertex -11.94 -14.86 0.71
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -11.77 -14.9 0
vertex -11.94 -14.86 0
vertex -12.22 -14.54 0
endloop
endfacet
facet normal -0.23 -0.97 0
outer loop
vertex -11.94 -14.86 0
vertex -11.77 -14.9 0
vertex -11.77 -14.9 0.71
endloop
endfacet
facet normal -0.75 -0.66 0
outer loop
vertex -12.22 -14.54 0
vertex -11.94 -14.86 0.71
vertex -12.22 -14.54 0.71
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -11.77 -14.9 0.71
vertex -12.22 -14.54 0.71
vertex -11.94 -14.86 0.71
endloop
endfacet
facet normal -1 0.02 0
outer loop
vertex -12.06 -4.69 -0.02
vertex -12.22 -14.54 0
vertex -12.22 -14.54 0.71
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.95 -4.63 -0.02
vertex -12.22 -14.54 0
vertex -12.06 -4.69 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.42 -4.66 -0.02
vertex -11.77 -14.9 0
vertex -12.22 -14.54 0
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.42 -4.66 -0.02
vertex -12.22 -14.54 0
vertex -10.95 -4.63 -0.02
endloop
endfacet
facet normal -1 0.02 0
outer loop
vertex -12.06 -4.69 -0.02
vertex -12.22 -14.54 0.71
vertex -12.06 -4.69 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.95 -4.64 0.73
vertex -12.06 -4.69 0.73
vertex -12.22 -14.54 0.71
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.43 -4.66 0.73
vertex -12.22 -14.54 0.71
vertex -11.77 -14.9 0.71
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.43 -4.66 0.73
vertex -10.95 -4.64 0.73
vertex -12.22 -14.54 0.71
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -12.06 -4.69 -0.02
vertex -12.17 -5.13 -0.02
vertex -11.83 -5.01 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -12.06 -4.69 -0.02
vertex -12.17 -5.13 -0.02
vertex -10.95 -4.63 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -12.17 -5.13 -0.02
vertex -10.5 -5.1 -0.02
vertex -10.95 -4.63 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -12.06 -4.69 0.73
vertex -11.83 -5.01 0.73
vertex -12.17 -5.13 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.95 -4.64 0.73
vertex -12.17 -5.13 0.73
vertex -12.06 -4.69 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.95 -4.64 0.73
vertex -10.5 -5.1 0.73
vertex -12.17 -5.13 0.73
endloop
endfacet
facet normal -0.27 0.96 0
outer loop
vertex -11.67 -4.58 -0.02
vertex -12.06 -4.69 -0.02
vertex -12.06 -4.69 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -12.06 -4.69 -0.02
vertex -11.83 -5.01 -0.02
vertex -11.67 -4.58 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -11.67 -4.58 -0.02
vertex -12.06 -4.69 -0.02
vertex -10.95 -4.63 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -11.66 -4.58 0.73
vertex -11.83 -5.01 0.73
vertex -12.06 -4.69 0.73
endloop
endfacet
facet normal -0.27 0.96 0
outer loop
vertex -11.67 -4.58 -0.02
vertex -12.06 -4.69 0.73
vertex -11.66 -4.58 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.95 -4.64 0.73
vertex -12.06 -4.69 0.73
vertex -11.66 -4.58 0.73
endloop
endfacet
facet normal -1 -0.03 0
outer loop
vertex -12.11 -2.27 0.73
vertex -12.06 -3.99 -0.02
vertex -12.06 -3.99 0.73
endloop
endfacet
facet normal 0.43 0.9 0
outer loop
vertex -11.68 -4.17 -0.02
vertex -12.06 -3.99 -0.02
vertex -12.06 -3.99 0.73
endloop
endfacet
facet normal -0.45 -0.89 0
outer loop
vertex -12.06 -3.99 -0.02
vertex -11.68 -4.18 0.73
vertex -12.06 -3.99 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -12.17 -3.55 -0.02
vertex -12.06 -3.99 -0.02
vertex -11.83 -3.67 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -12.17 -3.55 -0.02
vertex -12.06 -3.99 -0.02
vertex -10.98 -4.1 -0.02
endloop
endfacet
facet normal -1 -0.03 0
outer loop
vertex -12.11 -2.27 -0.02
vertex -12.06 -3.99 -0.02
vertex -12.11 -2.27 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.91 -2.23 -0.02
vertex -12.06 -3.99 -0.02
vertex -12.11 -2.27 -0.02
endloop
endfacet
facet normal -0.43 -0.9 -0.01
outer loop
vertex -12.06 -3.99 -0.02
vertex -11.68 -4.17 -0.02
vertex -11.68 -4.18 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -11.83 -3.67 -0.02
vertex -12.06 -3.99 -0.02
vertex -11.68 -4.17 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -12.06 -3.99 -0.02
vertex -11.68 -4.17 -0.02
vertex -10.98 -4.1 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.91 -2.23 -0.02
vertex -10.98 -4.1 -0.02
vertex -12.06 -3.99 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -11.83 -3.67 0.73
vertex -12.06 -3.99 0.73
vertex -12.17 -3.55 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.98 -4.1 0.73
vertex -12.06 -3.99 0.73
vertex -12.17 -3.55 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.91 -2.23 0.73
vertex -12.11 -2.27 0.73
vertex -12.06 -3.99 0.73
endloop
endfacet
facet normal 0.45 0.89 0.01
outer loop
vertex -11.68 -4.17 -0.02
vertex -12.06 -3.99 0.73
vertex -11.68 -4.18 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -11.68 -4.18 0.73
vertex -12.06 -3.99 0.73
vertex -11.83 -3.67 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.98 -4.1 0.73
vertex -11.68 -4.18 0.73
vertex -12.06 -3.99 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.91 -2.23 0.73
vertex -12.06 -3.99 0.73
vertex -10.98 -4.1 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -12.17 -3.55 -0.02
vertex -10.98 -4.1 -0.02
vertex -10.51 -3.57 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.51 -3.57 0.73
vertex -10.98 -4.1 0.73
vertex -12.17 -3.55 0.73
endloop
endfacet
facet normal -0.95 0.31 0
outer loop
vertex -11.92 -1.68 -0.02
vertex -12.11 -2.27 -0.02
vertex -12.11 -2.27 0.73
endloop
endfacet
facet normal 0.77 -0.64 0
outer loop
vertex -12.11 -2.27 -0.02
vertex -11.72 -1.8 -0.02
vertex -12.11 -2.27 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -11.92 -1.68 -0.02
vertex -12.11 -2.27 -0.02
vertex -11.6 -2.29 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -11.72 -1.8 -0.02
vertex -12.11 -2.27 -0.02
vertex -11.92 -1.68 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -11.92 -1.68 -0.02
vertex -12.11 -2.27 -0.02
vertex -11.04 -1.75 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -11.04 -1.75 -0.02
vertex -12.11 -2.27 -0.02
vertex -11.72 -1.8 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -12.11 -2.27 -0.02
vertex -10.91 -2.23 -0.02
vertex -11.04 -1.75 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -12.11 -2.27 -0.02
vertex -10.5 -2.29 -0.02
vertex -10.91 -2.23 -0.02
endloop
endfacet
facet normal -0.95 0.31 0
outer loop
vertex -11.92 -1.68 -0.02
vertex -12.11 -2.27 0.73
vertex -11.92 -1.68 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -11.92 -1.68 0.73
vertex -11.6 -2.29 0.73
vertex -12.11 -2.27 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -11.72 -1.8 0.73
vertex -11.92 -1.68 0.73
vertex -12.11 -2.27 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -11.04 -1.75 0.73
vertex -12.11 -2.27 0.73
vertex -11.92 -1.68 0.73
endloop
endfacet
facet normal 0.77 -0.64 0
outer loop
vertex -11.72 -1.8 -0.02
vertex -11.72 -1.8 0.73
vertex -12.11 -2.27 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -11.04 -1.75 0.73
vertex -11.72 -1.8 0.73
vertex -12.11 -2.27 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -11.04 -1.75 0.73
vertex -10.91 -2.23 0.73
vertex -12.11 -2.27 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.91 -2.23 0.73
vertex -10.5 -2.29 0.73
vertex -12.11 -2.27 0.73
endloop
endfacet
facet normal -0.86 -0.51 0
outer loop
vertex -12.15 -1.29 -0.02
vertex -11.92 -1.68 -0.02
vertex -11.92 -1.68 0.73
endloop
endfacet
facet normal -0.86 -0.51 0
outer loop
vertex -11.92 -1.68 -0.02
vertex -11.92 -1.68 0.73
vertex -12.15 -1.29 0.73
endloop
endfacet
facet normal 0.51 0.86 0
outer loop
vertex -11.72 -1.8 -0.02
vertex -11.92 -1.68 -0.02
vertex -11.92 -1.68 0.73
endloop
endfacet
facet normal -0.51 -0.86 0
outer loop
vertex -11.92 -1.68 -0.02
vertex -11.72 -1.8 0.73
vertex -11.92 -1.68 0.73
endloop
endfacet
facet normal -0.86 -0.51 0
outer loop
vertex -12.15 -1.29 -0.02
vertex -11.92 -1.68 -0.02
vertex -12.15 -1.29 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -11.59 -1.31 -0.02
vertex -12.15 -1.29 -0.02
vertex -11.92 -1.68 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -12.15 -1.29 -0.02
vertex -11.92 -1.68 -0.02
vertex -11.04 -1.75 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.88 -1.32 -0.02
vertex -11.92 -1.68 -0.02
vertex -12.15 -1.29 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -11.72 -1.8 -0.02
vertex -11.92 -1.68 -0.02
vertex -11.6 -2.29 -0.02
endloop
endfacet
facet normal -0.51 -0.86 0
outer loop
vertex -11.92 -1.68 -0.02
vertex -11.72 -1.8 -0.02
vertex -11.72 -1.8 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -11.92 -1.68 -0.02
vertex -11.72 -1.8 -0.02
vertex -11.59 -1.31 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -11.72 -1.8 -0.02
vertex -11.92 -1.68 -0.02
vertex -11.04 -1.75 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.88 -1.32 -0.02
vertex -11.04 -1.75 -0.02
vertex -11.92 -1.68 -0.02
endloop
endfacet
facet normal -0.86 -0.51 0
outer loop
vertex -12.15 -1.29 -0.02
vertex -11.92 -1.68 0.73
vertex -12.15 -1.29 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -11.59 -1.31 0.73
vertex -11.92 -1.68 0.73
vertex -12.15 -1.29 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -11.04 -1.75 0.73
vertex -11.92 -1.68 0.73
vertex -12.15 -1.29 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.89 -1.32 0.73
vertex -12.15 -1.29 0.73
vertex -11.92 -1.68 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -11.6 -2.29 0.73
vertex -11.92 -1.68 0.73
vertex -11.72 -1.8 0.73
endloop
endfacet
facet normal 0.51 0.86 0
outer loop
vertex -11.72 -1.8 -0.02
vertex -11.92 -1.68 0.73
vertex -11.72 -1.8 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -11.59 -1.31 0.73
vertex -11.72 -1.8 0.73
vertex -11.92 -1.68 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -11.04 -1.75 0.73
vertex -11.92 -1.68 0.73
vertex -11.72 -1.8 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.89 -1.32 0.73
vertex -11.92 -1.68 0.73
vertex -11.04 -1.75 0.73
endloop
endfacet
facet normal -1 -0.03 0
outer loop
vertex -12.19 0.04 0.73
vertex -12.15 -1.29 -0.02
vertex -12.15 -1.29 0.73
endloop
endfacet
facet normal -1 -0.02 -0.01
outer loop
vertex -12.18 0.02 -0.02
vertex -12.15 -1.29 -0.02
vertex -12.19 0.04 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -12.05 0.4 -0.02
vertex -12.15 -1.29 -0.02
vertex -12.18 0.02 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.98 0.56 -0.02
vertex -12.15 -1.29 -0.02
vertex -12.05 0.4 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -12.15 -1.29 -0.02
vertex -11.04 -1.75 -0.02
vertex -10.54 -1.27 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.98 0.56 -0.02
vertex -10.88 -1.32 -0.02
vertex -12.15 -1.29 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -12.04 0.4 0.73
vertex -12.19 0.04 0.73
vertex -12.15 -1.29 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.98 0.56 0.73
vertex -12.04 0.4 0.73
vertex -12.15 -1.29 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.54 -1.27 0.73
vertex -11.04 -1.75 0.73
vertex -12.15 -1.29 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.98 0.56 0.73
vertex -12.15 -1.29 0.73
vertex -10.89 -1.32 0.73
endloop
endfacet
facet normal -0.95 0.32 -0.02
outer loop
vertex -12.05 0.4 -0.02
vertex -12.18 0.02 -0.02
vertex -12.19 0.04 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -12.05 0.4 -0.02
vertex -12.18 0.02 -0.02
vertex -11.75 0.14 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -12.05 0.4 -0.02
vertex -12.18 0.02 -0.02
vertex -10.98 0.56 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -12.18 0.02 -0.02
vertex -10.52 0.03 -0.02
vertex -10.98 0.56 -0.02
endloop
endfacet
facet normal -0.92 0.38 0.01
outer loop
vertex -12.05 0.4 -0.02
vertex -12.19 0.04 0.73
vertex -12.04 0.4 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -12.04 0.4 0.73
vertex -11.75 0.14 0.73
vertex -12.19 0.04 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.98 0.56 0.73
vertex -12.19 0.04 0.73
vertex -12.04 0.4 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.98 0.56 0.73
vertex -10.53 0.04 0.73
vertex -12.19 0.04 0.73
endloop
endfacet
facet normal -0.61 0.79 0.01
outer loop
vertex -11.71 0.66 -0.02
vertex -12.05 0.4 -0.02
vertex -12.04 0.4 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -12.05 0.4 -0.02
vertex -11.75 0.14 -0.02
vertex -11.71 0.66 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -11.71 0.66 -0.02
vertex -12.05 0.4 -0.02
vertex -10.98 0.56 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -11.71 0.66 0.73
vertex -11.75 0.14 0.73
vertex -12.04 0.4 0.73
endloop
endfacet
facet normal -0.62 0.79 0
outer loop
vertex -11.71 0.66 -0.02
vertex -12.04 0.4 0.73
vertex -11.71 0.66 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.98 0.56 0.73
vertex -12.04 0.4 0.73
vertex -11.71 0.66 0.73
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -12.06 2.93 -0.02
vertex -12.06 1.09 -0.02
vertex -12.06 1.09 0.73
endloop
endfacet
facet normal -0.78 -0.63 0
outer loop
vertex -12.06 1.09 -0.02
vertex -11.71 0.66 0.73
vertex -12.06 1.09 0.73
endloop
endfacet
facet normal -0.04 1 0
outer loop
vertex -11.6 1.11 -0.02
vertex -12.06 1.09 -0.02
vertex -12.06 1.09 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -12.17 1.53 -0.02
vertex -12.06 1.09 -0.02
vertex -11.6 1.11 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -12.17 1.53 -0.02
vertex -12.06 1.09 -0.02
vertex -10.93 1.1 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.95 2.99 -0.02
vertex -12.06 1.09 -0.02
vertex -12.06 2.93 -0.02
endloop
endfacet
facet normal -0.78 -0.63 0
outer loop
vertex -12.06 1.09 -0.02
vertex -11.71 0.66 -0.02
vertex -11.71 0.66 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -12.06 1.09 -0.02
vertex -11.71 0.66 -0.02
vertex -11.6 1.11 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -12.06 1.09 -0.02
vertex -11.71 0.66 -0.02
vertex -10.98 0.56 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.93 1.1 -0.02
vertex -11.6 1.11 -0.02
vertex -12.06 1.09 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -12.06 1.09 -0.02
vertex -10.98 0.56 -0.02
vertex -10.93 1.1 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.95 2.99 -0.02
vertex -10.93 1.1 -0.02
vertex -12.06 1.09 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -11.59 1.11 0.73
vertex -12.06 1.09 0.73
vertex -12.17 1.53 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.94 1.1 0.73
vertex -12.06 1.09 0.73
vertex -12.17 1.53 0.73
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -12.06 2.93 -0.02
vertex -12.06 1.09 0.73
vertex -12.06 2.93 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.95 2.98 0.73
vertex -12.06 2.93 0.73
vertex -12.06 1.09 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -11.59 1.11 0.73
vertex -11.71 0.66 0.73
vertex -12.06 1.09 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.98 0.56 0.73
vertex -11.71 0.66 0.73
vertex -12.06 1.09 0.73
endloop
endfacet
facet normal -0.04 1 0
outer loop
vertex -11.6 1.11 -0.02
vertex -12.06 1.09 0.73
vertex -11.59 1.11 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.94 1.1 0.73
vertex -12.06 1.09 0.73
vertex -11.59 1.11 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.94 1.1 0.73
vertex -10.98 0.56 0.73
vertex -12.06 1.09 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.95 2.98 0.73
vertex -12.06 1.09 0.73
vertex -10.94 1.1 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -12.17 1.53 -0.02
vertex -10.93 1.1 -0.02
vertex -10.59 1.53 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.59 1.53 0.73
vertex -10.94 1.1 0.73
vertex -12.17 1.53 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -12.06 2.93 -0.02
vertex -12.17 2.49 -0.02
vertex -11.68 2.99 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -12.06 2.93 -0.02
vertex -12.17 2.49 -0.02
vertex -10.51 2.52 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -12.06 2.93 0.73
vertex -11.67 2.99 0.73
vertex -12.17 2.49 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.51 2.52 0.73
vertex -12.17 2.49 0.73
vertex -12.06 2.93 0.73
endloop
endfacet
facet normal -0.16 0.99 0
outer loop
vertex -11.68 2.99 -0.02
vertex -12.06 2.93 -0.02
vertex -12.06 2.93 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -11.68 2.99 -0.02
vertex -12.06 2.93 -0.02
vertex -10.95 2.99 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -12.06 2.93 -0.02
vertex -10.51 2.52 -0.02
vertex -10.95 2.99 -0.02
endloop
endfacet
facet normal -0.15 0.99 0
outer loop
vertex -11.68 2.99 -0.02
vertex -12.06 2.93 0.73
vertex -11.67 2.99 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.95 2.98 0.73
vertex -12.06 2.93 0.73
vertex -11.67 2.99 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.95 2.98 0.73
vertex -10.51 2.52 0.73
vertex -12.06 2.93 0.73
endloop
endfacet
facet normal -1 -0.05 0
outer loop
vertex -12.14 5.32 -0.02
vertex -12.06 3.63 -0.02
vertex -12.06 3.63 0.73
endloop
endfacet
facet normal 0.5 0.87 0
outer loop
vertex -11.68 3.41 -0.02
vertex -12.06 3.63 -0.02
vertex -12.06 3.63 0.73
endloop
endfacet
facet normal -0.5 -0.87 0
outer loop
vertex -12.06 3.63 -0.02
vertex -11.68 3.41 0.73
vertex -12.06 3.63 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -12.17 4.07 -0.02
vertex -12.06 3.63 -0.02
vertex -11.75 3.88 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -12.17 4.07 -0.02
vertex -12.06 3.63 -0.02
vertex -10.97 3.51 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.89 5.35 -0.02
vertex -12.06 3.63 -0.02
vertex -12.14 5.32 -0.02
endloop
endfacet
facet normal -0.5 -0.87 0
outer loop
vertex -12.06 3.63 -0.02
vertex -11.68 3.41 -0.02
vertex -11.68 3.41 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -11.75 3.88 -0.02
vertex -12.06 3.63 -0.02
vertex -11.68 3.41 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -12.06 3.63 -0.02
vertex -11.68 3.41 -0.02
vertex -10.97 3.51 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.89 5.35 -0.02
vertex -10.97 3.51 -0.02
vertex -12.06 3.63 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -11.75 3.88 0.73
vertex -12.06 3.63 0.73
vertex -12.17 4.07 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.97 3.51 0.73
vertex -12.06 3.63 0.73
vertex -12.17 4.07 0.73
endloop
endfacet
facet normal -1 -0.05 0
outer loop
vertex -12.14 5.32 -0.02
vertex -12.06 3.63 0.73
vertex -12.14 5.32 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.89 5.35 0.73
vertex -12.14 5.32 0.73
vertex -12.06 3.63 0.73
endloop
endfacet
facet normal 0.5 0.87 0
outer loop
vertex -11.68 3.41 -0.02
vertex -12.06 3.63 0.73
vertex -11.68 3.41 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -11.75 3.88 0.73
vertex -11.68 3.41 0.73
vertex -12.06 3.63 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.97 3.51 0.73
vertex -11.68 3.41 0.73
vertex -12.06 3.63 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.89 5.35 0.73
vertex -12.06 3.63 0.73
vertex -10.97 3.51 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -12.17 4.07 -0.02
vertex -10.97 3.51 -0.02
vertex -10.51 4.05 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.51 4.05 0.73
vertex -10.97 3.51 0.73
vertex -12.17 4.07 0.73
endloop
endfacet
facet normal -0.87 0.49 0
outer loop
vertex -11.92 5.71 -0.02
vertex -12.14 5.32 -0.02
vertex -12.14 5.32 0.73
endloop
endfacet
facet normal 0.87 -0.49 0
outer loop
vertex -12.14 5.32 -0.02
vertex -11.92 5.71 0.73
vertex -12.14 5.32 0.73
endloop
endfacet
facet normal -0.77 0.64 0
outer loop
vertex -11.72 5.82 -0.02
vertex -12.14 5.32 -0.02
vertex -12.14 5.32 0.73
endloop
endfacet
facet normal 0.87 -0.49 0
outer loop
vertex -12.14 5.32 -0.02
vertex -11.92 5.71 -0.02
vertex -11.92 5.71 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -12.14 5.32 -0.02
vertex -11.6 5.33 -0.02
vertex -11.92 5.71 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -11.92 5.71 -0.02
vertex -12.14 5.32 -0.02
vertex -10.52 5.3 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.89 5.35 -0.02
vertex -12.14 5.32 -0.02
vertex -11.72 5.82 -0.02
endloop
endfacet
facet normal -0.87 0.49 0
outer loop
vertex -11.92 5.71 -0.02
vertex -12.14 5.32 0.73
vertex -11.92 5.71 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -11.92 5.71 0.73
vertex -11.6 5.33 0.73
vertex -12.14 5.32 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.52 5.3 0.73
vertex -12.14 5.32 0.73
vertex -11.92 5.71 0.73
endloop
endfacet
facet normal -0.77 0.64 0
outer loop
vertex -11.72 5.82 -0.02
vertex -12.14 5.32 0.73
vertex -11.72 5.82 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.89 5.35 0.73
vertex -11.72 5.82 0.73
vertex -12.14 5.32 0.73
endloop
endfacet
facet normal -0.95 -0.31 0
outer loop
vertex -12.11 6.29 -0.02
vertex -11.92 5.71 -0.02
vertex -11.92 5.71 0.73
endloop
endfacet
facet normal -0.48 0.88 0
outer loop
vertex -11.72 5.82 -0.02
vertex -11.92 5.71 -0.02
vertex -11.92 5.71 0.73
endloop
endfacet
facet normal 0.48 -0.88 0
outer loop
vertex -11.92 5.71 -0.02
vertex -11.72 5.82 0.73
vertex -11.92 5.71 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -12.11 6.29 -0.02
vertex -11.72 5.82 -0.02
vertex -11.92 5.71 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -12.11 6.29 -0.02
vertex -11.92 5.71 -0.02
vertex -11.59 6.31 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -12.11 6.29 -0.02
vertex -11.92 5.71 -0.02
vertex -11.04 5.78 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -11.72 5.82 -0.02
vertex -11.92 5.71 -0.02
vertex -11.6 5.33 -0.02
endloop
endfacet
facet normal 0.48 -0.88 0
outer loop
vertex -11.92 5.71 -0.02
vertex -11.72 5.82 -0.02
vertex -11.72 5.82 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -11.92 5.71 -0.02
vertex -11.72 5.82 -0.02
vertex -11.59 6.31 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -11.72 5.82 -0.02
vertex -11.92 5.71 -0.02
vertex -11.04 5.78 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -11.92 5.71 -0.02
vertex -10.52 5.3 -0.02
vertex -11.04 5.78 -0.02
endloop
endfacet
facet normal -0.95 -0.31 0
outer loop
vertex -12.11 6.29 -0.02
vertex -11.92 5.71 0.73
vertex -12.11 6.29 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -12.11 6.29 0.73
vertex -11.92 5.71 0.73
vertex -11.72 5.82 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -11.59 6.31 0.73
vertex -11.92 5.71 0.73
vertex -12.11 6.29 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -11.04 5.78 0.73
vertex -11.92 5.71 0.73
vertex -12.11 6.29 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -11.6 5.33 0.73
vertex -11.92 5.71 0.73
vertex -11.72 5.82 0.73
endloop
endfacet
facet normal -0.48 0.88 0
outer loop
vertex -11.72 5.82 -0.02
vertex -11.92 5.71 0.73
vertex -11.72 5.82 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -11.59 6.31 0.73
vertex -11.72 5.82 0.73
vertex -11.92 5.71 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -11.04 5.78 0.73
vertex -11.92 5.71 0.73
vertex -11.72 5.82 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -11.04 5.78 0.73
vertex -10.52 5.3 0.73
vertex -11.92 5.71 0.73
endloop
endfacet
facet normal -1 0.03 0
outer loop
vertex -12.06 8.01 -0.02
vertex -12.11 6.29 -0.02
vertex -12.11 6.29 0.73
endloop
endfacet
facet normal 0.77 0.64 0
outer loop
vertex -11.72 5.82 -0.02
vertex -12.11 6.29 -0.02
vertex -12.11 6.29 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.97 8.13 -0.02
vertex -12.11 6.29 -0.02
vertex -12.06 8.01 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.91 6.25 -0.02
vertex -11.72 5.82 -0.02
vertex -12.11 6.29 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -12.11 6.29 -0.02
vertex -11.04 5.78 -0.02
vertex -10.91 6.25 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.97 8.13 -0.02
vertex -10.91 6.25 -0.02
vertex -12.11 6.29 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -12.11 6.29 -0.02
vertex -10.91 6.25 -0.02
vertex -10.5 6.31 -0.02
endloop
endfacet
facet normal -1 0.03 0
outer loop
vertex -12.06 8.01 -0.02
vertex -12.11 6.29 0.73
vertex -12.06 8.01 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.97 8.13 0.73
vertex -12.06 8.01 0.73
vertex -12.11 6.29 0.73
endloop
endfacet
facet normal 0.77 0.64 0
outer loop
vertex -11.72 5.82 -0.02
vertex -12.11 6.29 0.73
vertex -11.72 5.82 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.91 6.25 0.73
vertex -12.11 6.29 0.73
vertex -11.72 5.82 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.91 6.25 0.73
vertex -11.04 5.78 0.73
vertex -12.11 6.29 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.97 8.13 0.73
vertex -12.11 6.29 0.73
vertex -10.91 6.25 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.5 6.31 0.73
vertex -10.91 6.25 0.73
vertex -12.11 6.29 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -12.06 8.01 -0.02
vertex -12.17 7.57 -0.02
vertex -11.75 7.76 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -12.06 8.01 -0.02
vertex -12.17 7.57 -0.02
vertex -10.51 7.6 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -12.06 8.01 0.73
vertex -11.75 7.76 0.73
vertex -12.17 7.57 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.51 7.6 0.73
vertex -12.17 7.57 0.73
vertex -12.06 8.01 0.73
endloop
endfacet
facet normal -0.5 0.87 0
outer loop
vertex -11.68 8.23 -0.02
vertex -12.06 8.01 -0.02
vertex -12.06 8.01 0.73
endloop
endfacet
facet normal 0.5 -0.87 0
outer loop
vertex -12.06 8.01 -0.02
vertex -11.68 8.23 0.73
vertex -12.06 8.01 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -12.06 8.01 -0.02
vertex -11.75 7.76 -0.02
vertex -11.68 8.23 -0.02
endloop
endfacet
facet normal 0.5 -0.87 0
outer loop
vertex -12.06 8.01 -0.02
vertex -11.68 8.23 -0.02
vertex -11.68 8.23 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -11.68 8.23 -0.02
vertex -12.06 8.01 -0.02
vertex -10.97 8.13 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -12.06 8.01 -0.02
vertex -10.51 7.6 -0.02
vertex -10.97 8.13 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -11.68 8.23 0.73
vertex -11.75 7.76 0.73
vertex -12.06 8.01 0.73
endloop
endfacet
facet normal -0.5 0.87 0
outer loop
vertex -11.68 8.23 -0.02
vertex -12.06 8.01 0.73
vertex -11.68 8.23 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.97 8.13 0.73
vertex -12.06 8.01 0.73
vertex -11.68 8.23 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.97 8.13 0.73
vertex -10.51 7.6 0.73
vertex -12.06 8.01 0.73
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -12.06 10.55 -0.02
vertex -12.06 8.71 -0.02
vertex -12.06 8.71 0.73
endloop
endfacet
facet normal 0.27 0.96 0
outer loop
vertex -11.67 8.6 -0.02
vertex -12.06 8.71 -0.02
vertex -12.06 8.71 0.73
endloop
endfacet
facet normal -0.27 -0.96 0
outer loop
vertex -12.06 8.71 -0.02
vertex -11.66 8.6 0.73
vertex -12.06 8.71 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -12.17 9.15 -0.02
vertex -12.06 8.71 -0.02
vertex -11.83 9.03 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -12.17 9.15 -0.02
vertex -12.06 8.71 -0.02
vertex -10.95 8.66 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.94 10.54 -0.02
vertex -12.06 8.71 -0.02
vertex -12.06 10.55 -0.02
endloop
endfacet
facet normal -0.27 -0.96 0
outer loop
vertex -12.06 8.71 -0.02
vertex -11.67 8.6 -0.02
vertex -11.66 8.6 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -11.83 9.03 -0.02
vertex -12.06 8.71 -0.02
vertex -11.67 8.6 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -12.06 8.71 -0.02
vertex -11.67 8.6 -0.02
vertex -10.95 8.66 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.94 10.54 -0.02
vertex -10.95 8.66 -0.02
vertex -12.06 8.71 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -11.83 9.03 0.73
vertex -12.06 8.71 0.73
vertex -12.17 9.15 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.96 8.65 0.73
vertex -12.06 8.71 0.73
vertex -12.17 9.15 0.73
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -12.06 10.55 -0.02
vertex -12.06 8.71 0.73
vertex -12.06 10.55 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.94 10.54 0.73
vertex -12.06 10.55 0.73
vertex -12.06 8.71 0.73
endloop
endfacet
facet normal 0.27 0.96 0
outer loop
vertex -11.67 8.6 -0.02
vertex -12.06 8.71 0.73
vertex -11.66 8.6 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -11.66 8.6 0.73
vertex -12.06 8.71 0.73
vertex -11.83 9.03 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.96 8.65 0.73
vertex -11.66 8.6 0.73
vertex -12.06 8.71 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.94 10.54 0.73
vertex -12.06 8.71 0.73
vertex -10.96 8.65 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -12.17 9.15 -0.02
vertex -10.95 8.66 -0.02
vertex -10.51 9.13 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.51 9.13 0.73
vertex -10.96 8.65 0.73
vertex -12.17 9.15 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -12.06 10.55 -0.02
vertex -12.17 10.11 -0.02
vertex -11.6 10.54 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -12.06 10.55 -0.02
vertex -12.17 10.11 -0.02
vertex -10.94 10.54 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -12.17 10.11 -0.02
vertex -10.6 10.11 -0.02
vertex -10.94 10.54 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -12.06 10.55 0.73
vertex -11.59 10.53 0.73
vertex -12.17 10.11 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.94 10.54 0.73
vertex -12.17 10.11 0.73
vertex -12.06 10.55 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.94 10.54 0.73
vertex -10.6 10.11 0.73
vertex -12.17 10.11 0.73
endloop
endfacet
facet normal -0.02 -1 0
outer loop
vertex -12.06 10.55 -0.02
vertex -11.6 10.54 -0.02
vertex -12.06 10.55 0.73
endloop
endfacet
facet normal -0.78 0.62 0
outer loop
vertex -11.71 10.99 -0.02
vertex -12.06 10.55 -0.02
vertex -12.06 10.55 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -11.71 10.99 -0.02
vertex -12.06 10.55 -0.02
vertex -11.6 10.54 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.94 10.54 -0.02
vertex -12.06 10.55 -0.02
vertex -11.6 10.54 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -11.71 10.99 -0.02
vertex -12.06 10.55 -0.02
vertex -11.01 11.05 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -12.06 10.55 -0.02
vertex -10.94 10.54 -0.02
vertex -11.01 11.05 -0.02
endloop
endfacet
facet normal -0.04 -1 -0.01
outer loop
vertex -11.6 10.54 -0.02
vertex -11.59 10.53 0.73
vertex -12.06 10.55 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -11.59 10.53 0.73
vertex -12.06 10.55 0.73
vertex -11.71 10.99 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.94 10.54 0.73
vertex -11.59 10.53 0.73
vertex -12.06 10.55 0.73
endloop
endfacet
facet normal -0.78 0.62 0
outer loop
vertex -11.71 10.99 -0.02
vertex -12.06 10.55 0.73
vertex -11.71 10.99 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -11.01 11.06 0.73
vertex -12.06 10.55 0.73
vertex -11.71 10.99 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -11.01 11.06 0.73
vertex -10.94 10.54 0.73
vertex -12.06 10.55 0.73
endloop
endfacet
facet normal -0.78 -0.63 0
outer loop
vertex -11.98 11.21 -0.02
vertex -11.98 11.21 0.73
vertex -12.19 11.47 0.73
endloop
endfacet
facet normal 0.63 0.78 0
outer loop
vertex -11.71 10.99 -0.02
vertex -11.98 11.21 -0.02
vertex -11.98 11.21 0.73
endloop
endfacet
facet normal -0.63 -0.78 0
outer loop
vertex -11.98 11.21 -0.02
vertex -11.71 10.99 0.73
vertex -11.98 11.21 0.73
endloop
endfacet
facet normal -0.79 -0.61 -0.01
outer loop
vertex -12.19 11.48 -0.02
vertex -11.98 11.21 -0.02
vertex -12.19 11.47 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -11.97 13.14 -0.02
vertex -11.98 11.21 -0.02
vertex -12.19 11.48 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -12.19 11.48 -0.02
vertex -11.98 11.21 -0.02
vertex -11.75 11.5 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -12.19 11.48 -0.02
vertex -11.98 11.21 -0.02
vertex -11.01 11.05 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -11.01 13.29 -0.02
vertex -11.98 11.21 -0.02
vertex -11.97 13.14 -0.02
endloop
endfacet
facet normal -0.63 -0.78 0
outer loop
vertex -11.98 11.21 -0.02
vertex -11.71 10.99 -0.02
vertex -11.71 10.99 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -11.75 11.5 -0.02
vertex -11.98 11.21 -0.02
vertex -11.71 10.99 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -11.98 11.21 -0.02
vertex -11.71 10.99 -0.02
vertex -11.01 11.05 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -11.01 13.29 -0.02
vertex -11.01 11.05 -0.02
vertex -11.98 11.21 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -11.97 13.14 0.73
vertex -12.19 11.47 0.73
vertex -11.98 11.21 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -11.75 11.5 0.73
vertex -11.98 11.21 0.73
vertex -12.19 11.47 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -11.01 11.06 0.73
vertex -11.98 11.21 0.73
vertex -12.19 11.47 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -11.01 13.29 0.73
vertex -11.97 13.14 0.73
vertex -11.98 11.21 0.73
endloop
endfacet
facet normal 0.63 0.78 0
outer loop
vertex -11.71 10.99 -0.02
vertex -11.98 11.21 0.73
vertex -11.71 10.99 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -11.75 11.5 0.73
vertex -11.71 10.99 0.73
vertex -11.98 11.21 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -11.01 11.06 0.73
vertex -11.71 10.99 0.73
vertex -11.98 11.21 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -11.01 13.29 0.73
vertex -11.98 11.21 0.73
vertex -11.01 11.06 0.73
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -12.19 12.88 0.73
vertex -12.19 11.48 -0.02
vertex -12.19 11.47 0.73
endloop
endfacet
facet normal -1 0.01 -0.01
outer loop
vertex -12.18 12.88 -0.02
vertex -12.19 11.48 -0.02
vertex -12.19 12.88 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -11.97 13.14 -0.02
vertex -12.19 11.48 -0.02
vertex -12.18 12.88 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -12.19 11.48 -0.02
vertex -11.01 11.05 -0.02
vertex -10.56 11.47 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -11.97 13.14 0.73
vertex -12.19 12.88 0.73
vertex -12.19 11.47 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.57 11.47 0.73
vertex -11.01 11.06 0.73
vertex -12.19 11.47 0.73
endloop
endfacet
facet normal -0.78 0.63 -0.01
outer loop
vertex -11.97 13.14 -0.02
vertex -12.18 12.88 -0.02
vertex -12.19 12.88 0.73
endloop
endfacet
facet normal 0.76 -0.65 0.01
outer loop
vertex -12.18 12.88 -0.02
vertex -11.97 13.14 0.73
vertex -12.19 12.88 0.73
endloop
endfacet
facet normal 0.78 -0.63 0
outer loop
vertex -12.18 12.88 -0.02
vertex -11.97 13.14 -0.02
vertex -11.97 13.14 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -11.97 13.14 -0.02
vertex -12.18 12.88 -0.02
vertex -11.62 12.91 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -11.97 13.14 -0.02
vertex -12.18 12.88 -0.02
vertex -11.01 13.29 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -12.18 12.88 -0.02
vertex -10.56 12.87 -0.02
vertex -11.01 13.29 -0.02
endloop
endfacet
facet normal -0.76 0.65 0
outer loop
vertex -11.97 13.14 -0.02
vertex -12.19 12.88 0.73
vertex -11.97 13.14 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -11.97 13.14 0.73
vertex -11.62 12.91 0.73
vertex -12.19 12.88 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -11.01 13.29 0.73
vertex -12.19 12.88 0.73
vertex -11.97 13.14 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -11.01 13.29 0.73
vertex -10.56 12.87 0.73
vertex -12.19 12.88 0.73
endloop
endfacet
facet normal -0.72 0.69 0
outer loop
vertex -11.74 13.38 -0.02
vertex -11.97 13.14 -0.02
vertex -11.97 13.14 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -11.97 13.14 -0.02
vertex -11.62 12.91 -0.02
vertex -11.74 13.38 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -11.74 13.38 -0.02
vertex -11.97 13.14 -0.02
vertex -11.01 13.29 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -11.74 13.38 0.73
vertex -11.62 12.91 0.73
vertex -11.97 13.14 0.73
endloop
endfacet
facet normal -0.72 0.69 0
outer loop
vertex -11.74 13.38 -0.02
vertex -11.97 13.14 0.73
vertex -11.74 13.38 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -11.01 13.29 0.73
vertex -11.97 13.14 0.73
vertex -11.74 13.38 0.73
endloop
endfacet
facet normal -0.96 -0.3 0
outer loop
vertex -12.23 14.36 -0.01
vertex -12.06 13.81 -0.02
vertex -12.06 13.81 0.73
endloop
endfacet
facet normal 0.8 0.6 0
outer loop
vertex -11.74 13.38 -0.02
vertex -12.06 13.81 -0.02
vertex -12.06 13.81 0.73
endloop
endfacet
facet normal -0.8 -0.6 0
outer loop
vertex -12.06 13.81 -0.02
vertex -11.74 13.38 0.73
vertex -12.06 13.81 0.73
endloop
endfacet
facet normal 0.02 -1 0
outer loop
vertex -12.06 13.81 -0.02
vertex -11.57 13.82 -0.02
vertex -12.06 13.81 0.73
endloop
endfacet
facet normal 0 0.02 -1
outer loop
vertex -11.77 15 0
vertex -12.06 13.81 -0.02
vertex -12.23 14.36 -0.01
endloop
endfacet
facet normal 0 -0.02 1
outer loop
vertex -12.23 14.36 -0.01
vertex -12.06 13.81 -0.02
vertex -10.94 13.8 -0.02
endloop
endfacet
facet normal -0.8 -0.6 0
outer loop
vertex -12.06 13.81 -0.02
vertex -11.74 13.38 -0.02
vertex -11.74 13.38 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -12.06 13.81 -0.02
vertex -11.74 13.38 -0.02
vertex -11.57 13.82 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -12.06 13.81 -0.02
vertex -11.74 13.38 -0.02
vertex -11.01 13.29 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.94 13.8 -0.02
vertex -11.57 13.82 -0.02
vertex -12.06 13.81 -0.02
endloop
endfacet
facet normal 0 0.02 -1
outer loop
vertex -11.77 15 0
vertex -10.94 13.8 -0.02
vertex -12.06 13.81 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -12.06 13.81 -0.02
vertex -11.01 13.29 -0.02
vertex -10.94 13.8 -0.02
endloop
endfacet
facet normal -0.96 -0.3 0
outer loop
vertex -12.23 14.36 -0.01
vertex -12.06 13.81 0.73
vertex -12.23 14.36 0.72
endloop
endfacet
facet normal 0 0.02 1
outer loop
vertex -11.77 15 0.71
vertex -12.23 14.36 0.72
vertex -12.06 13.81 0.73
endloop
endfacet
facet normal 0 -0.02 -1
outer loop
vertex -10.94 13.8 0.73
vertex -12.06 13.81 0.73
vertex -12.23 14.36 0.72
endloop
endfacet
facet normal 0.8 0.6 0
outer loop
vertex -11.74 13.38 -0.02
vertex -12.06 13.81 0.73
vertex -11.74 13.38 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -11.57 13.83 0.73
vertex -11.74 13.38 0.73
vertex -12.06 13.81 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -11.01 13.29 0.73
vertex -11.74 13.38 0.73
vertex -12.06 13.81 0.73
endloop
endfacet
facet normal 0.04 -1 0.01
outer loop
vertex -11.57 13.82 -0.02
vertex -11.57 13.83 0.73
vertex -12.06 13.81 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.94 13.8 0.73
vertex -12.06 13.81 0.73
vertex -11.57 13.83 0.73
endloop
endfacet
facet normal 0 0.02 1
outer loop
vertex -11.77 15 0.71
vertex -12.06 13.81 0.73
vertex -10.94 13.8 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.94 13.8 0.73
vertex -11.01 13.29 0.73
vertex -12.06 13.81 0.73
endloop
endfacet
facet normal -0.94 0.34 0
outer loop
vertex -12.03 14.92 0
vertex -12.23 14.36 -0.01
vertex -12.23 14.36 0.72
endloop
endfacet
facet normal -0.01 0.02 -1
outer loop
vertex -11.77 15 0
vertex -12.23 14.36 -0.01
vertex -12.03 14.92 0
endloop
endfacet
facet normal 0.01 0 1
outer loop
vertex -12.23 14.36 -0.01
vertex -10.94 13.8 -0.02
vertex -10.59 14.23 -0.02
endloop
endfacet
facet normal -0.94 0.34 0
outer loop
vertex -12.03 14.92 0
vertex -12.23 14.36 0.72
vertex -12.03 14.92 0.71
endloop
endfacet
facet normal -0.01 0.02 1
outer loop
vertex -11.77 15 0.71
vertex -12.03 14.92 0.71
vertex -12.23 14.36 0.72
endloop
endfacet
facet normal 0.01 0 -1
outer loop
vertex -10.59 14.23 0.73
vertex -10.94 13.8 0.73
vertex -12.23 14.36 0.72
endloop
endfacet
facet normal -0.29 0.96 0
outer loop
vertex -11.77 15 0
vertex -12.03 14.92 0
vertex -12.03 14.92 0.71
endloop
endfacet
facet normal -0.29 0.96 0
outer loop
vertex -11.77 15 0
vertex -12.03 14.92 0.71
vertex -11.77 15 0.71
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -11.77 -14.9 0
vertex 11.77 -14.9 0.71
vertex -11.77 -14.9 0.71
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.43 -9.3 -0.02
vertex -11.77 -14.9 0
vertex -10.42 -4.66 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.43 -9.3 -0.02
vertex 11.77 -14.9 0
vertex -11.77 -14.9 0
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -11.77 -14.9 0
vertex 11.77 -14.9 0
vertex 11.77 -14.9 0.71
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 6.43 -9.3 0.73
vertex -10.43 -4.66 0.73
vertex -11.77 -14.9 0.71
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 6.43 -9.3 0.73
vertex -11.77 -14.9 0.71
vertex 11.77 -14.9 0.71
endloop
endfacet
facet normal -1 -0.02 0.01
outer loop
vertex -11.68 -4.17 -0.02
vertex -11.67 -4.58 -0.02
vertex -11.66 -4.58 0.73
endloop
endfacet
facet normal -1 -0.05 0.01
outer loop
vertex -11.67 -4.58 -0.02
vertex -11.66 -4.58 0.73
vertex -11.68 -4.18 0.73
endloop
endfacet
facet normal -1 -0.02 0
outer loop
vertex -11.68 -4.17 -0.02
vertex -11.67 -4.58 -0.02
vertex -11.68 -4.18 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -11.68 -4.17 -0.02
vertex -11.67 -4.58 -0.02
vertex -10.98 -4.1 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -11.67 -4.58 -0.02
vertex -10.95 -4.63 -0.02
vertex -10.98 -4.1 -0.02
endloop
endfacet
facet normal -1 -0.05 0
outer loop
vertex -11.68 -4.17 -0.02
vertex -11.66 -4.58 0.73
vertex -11.68 -4.18 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.98 -4.1 0.73
vertex -11.66 -4.58 0.73
vertex -11.68 -4.18 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.98 -4.1 0.73
vertex -10.95 -4.64 0.73
vertex -11.66 -4.58 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -11.72 -1.8 -0.02
vertex -11.6 -2.29 -0.02
vertex -11.04 -1.75 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -11.6 -2.29 -0.02
vertex -10.91 -2.23 -0.02
vertex -11.04 -1.75 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -11.04 -1.75 0.73
vertex -11.6 -2.29 0.73
vertex -11.72 -1.8 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -11.04 -1.75 0.73
vertex -10.91 -2.23 0.73
vertex -11.6 -2.29 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -11.59 -1.31 -0.02
vertex -11.72 -1.8 -0.02
vertex -11.04 -1.75 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -11.59 -1.31 0.73
vertex -11.04 -1.75 0.73
vertex -11.72 -1.8 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.88 -1.32 -0.02
vertex -11.59 -1.31 -0.02
vertex -11.04 -1.75 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -11.04 -1.75 0.73
vertex -11.59 -1.31 0.73
vertex -10.89 -1.32 0.73
endloop
endfacet
facet normal -0.97 0.24 0
outer loop
vertex -11.6 1.11 -0.02
vertex -11.71 0.66 -0.02
vertex -11.71 0.66 0.73
endloop
endfacet
facet normal 0.97 -0.26 0
outer loop
vertex -11.71 0.66 -0.02
vertex -11.59 1.11 0.73
vertex -11.71 0.66 0.73
endloop
endfacet
facet normal 0.97 -0.24 -0.01
outer loop
vertex -11.71 0.66 -0.02
vertex -11.6 1.11 -0.02
vertex -11.59 1.11 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -11.6 1.11 -0.02
vertex -11.71 0.66 -0.02
vertex -10.98 0.56 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.93 1.1 -0.02
vertex -11.71 0.66 -0.02
vertex -11.6 1.11 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -11.71 0.66 -0.02
vertex -11.03 0.06 -0.02
vertex -10.98 0.56 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.93 1.1 -0.02
vertex -10.98 0.56 -0.02
vertex -11.71 0.66 -0.02
endloop
endfacet
facet normal -0.97 0.26 0.01
outer loop
vertex -11.6 1.11 -0.02
vertex -11.71 0.66 0.73
vertex -11.59 1.11 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.98 0.56 0.73
vertex -11.71 0.66 0.73
vertex -11.59 1.11 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.94 1.1 0.73
vertex -11.59 1.11 0.73
vertex -11.71 0.66 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.98 0.56 0.73
vertex -11.03 0.06 0.73
vertex -11.71 0.66 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.94 1.1 0.73
vertex -11.71 0.66 0.73
vertex -10.98 0.56 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -11.6 1.11 -0.02
vertex -10.98 0.56 -0.02
vertex -10.93 1.1 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.94 1.1 0.73
vertex -10.98 0.56 0.73
vertex -11.59 1.11 0.73
endloop
endfacet
facet normal -1 0 0.01
outer loop
vertex -11.68 3.41 -0.02
vertex -11.68 2.99 -0.02
vertex -11.67 2.99 0.73
endloop
endfacet
facet normal -1 -0.02 0.01
outer loop
vertex -11.68 2.99 -0.02
vertex -11.67 2.99 0.73
vertex -11.68 3.41 0.73
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -11.68 3.41 -0.02
vertex -11.68 2.99 -0.02
vertex -11.68 3.41 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -11.68 3.41 -0.02
vertex -11.68 2.99 -0.02
vertex -10.95 2.99 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -11.68 3.41 -0.02
vertex -11.68 2.99 -0.02
vertex -10.97 3.51 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -11.68 2.99 -0.02
vertex -10.95 2.99 -0.02
vertex -10.97 3.51 -0.02
endloop
endfacet
facet normal -1 -0.02 0
outer loop
vertex -11.68 3.41 -0.02
vertex -11.67 2.99 0.73
vertex -11.68 3.41 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.95 2.98 0.73
vertex -11.67 2.99 0.73
vertex -11.68 3.41 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.97 3.51 0.73
vertex -11.67 2.99 0.73
vertex -11.68 3.41 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.97 3.51 0.73
vertex -10.95 2.98 0.73
vertex -11.67 2.99 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -11.68 3.41 -0.02
vertex -10.95 2.99 -0.02
vertex -10.97 3.51 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -11.02 3.97 -0.02
vertex -11.68 3.41 -0.02
vertex -10.97 3.51 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.97 3.51 0.73
vertex -10.95 2.98 0.73
vertex -11.68 3.41 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.97 3.51 0.73
vertex -11.68 3.41 0.73
vertex -11.02 3.97 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -11.72 5.82 -0.02
vertex -11.6 5.33 -0.02
vertex -11.04 5.78 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -11.6 5.33 -0.02
vertex -10.89 5.35 -0.02
vertex -11.04 5.78 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -11.04 5.78 0.73
vertex -11.6 5.33 0.73
vertex -11.72 5.82 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -11.04 5.78 0.73
vertex -10.89 5.35 0.73
vertex -11.6 5.33 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -11.59 6.31 -0.02
vertex -11.72 5.82 -0.02
vertex -11.04 5.78 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -11.04 5.78 -0.02
vertex -10.89 5.35 -0.02
vertex -11.72 5.82 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.91 6.25 -0.02
vertex -11.04 5.78 -0.02
vertex -11.72 5.82 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -11.59 6.31 0.73
vertex -11.04 5.78 0.73
vertex -11.72 5.82 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -11.04 5.78 0.73
vertex -11.72 5.82 0.73
vertex -10.89 5.35 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.91 6.25 0.73
vertex -11.72 5.82 0.73
vertex -11.04 5.78 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -11.59 6.31 -0.02
vertex -11.04 5.78 -0.02
vertex -10.91 6.25 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.91 6.25 0.73
vertex -11.04 5.78 0.73
vertex -11.59 6.31 0.73
endloop
endfacet
facet normal -1 0.03 0
outer loop
vertex -11.67 8.6 -0.02
vertex -11.68 8.23 -0.02
vertex -11.68 8.23 0.73
endloop
endfacet
facet normal 1 -0.05 0
outer loop
vertex -11.68 8.23 -0.02
vertex -11.66 8.6 0.73
vertex -11.68 8.23 0.73
endloop
endfacet
facet normal 1 -0.03 -0.01
outer loop
vertex -11.68 8.23 -0.02
vertex -11.67 8.6 -0.02
vertex -11.66 8.6 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -11.67 8.6 -0.02
vertex -11.68 8.23 -0.02
vertex -10.97 8.13 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -11.68 8.23 -0.02
vertex -11.03 7.68 -0.02
vertex -10.97 8.13 -0.02
endloop
endfacet
facet normal -1 0.05 0.01
outer loop
vertex -11.67 8.6 -0.02
vertex -11.68 8.23 0.73
vertex -11.66 8.6 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.97 8.13 0.73
vertex -11.68 8.23 0.73
vertex -11.66 8.6 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.97 8.13 0.73
vertex -11.03 7.68 0.73
vertex -11.68 8.23 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -11.67 8.6 -0.02
vertex -10.97 8.13 -0.02
vertex -10.95 8.66 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.96 8.65 0.73
vertex -10.97 8.13 0.73
vertex -11.66 8.6 0.73
endloop
endfacet
facet normal -0.97 -0.24 0.01
outer loop
vertex -11.71 10.99 -0.02
vertex -11.6 10.54 -0.02
vertex -11.59 10.53 0.73
endloop
endfacet
facet normal 0.97 0.25 -0.01
outer loop
vertex -11.6 10.54 -0.02
vertex -11.71 10.99 0.73
vertex -11.59 10.53 0.73
endloop
endfacet
facet normal 0.97 0.24 0
outer loop
vertex -11.6 10.54 -0.02
vertex -11.71 10.99 -0.02
vertex -11.71 10.99 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -11.71 10.99 -0.02
vertex -11.6 10.54 -0.02
vertex -11.01 11.05 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -11.6 10.54 -0.02
vertex -10.94 10.54 -0.02
vertex -11.01 11.05 -0.02
endloop
endfacet
facet normal -0.97 -0.25 0
outer loop
vertex -11.71 10.99 -0.02
vertex -11.59 10.53 0.73
vertex -11.71 10.99 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -11.01 11.06 0.73
vertex -11.59 10.53 0.73
vertex -11.71 10.99 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -11.01 11.06 0.73
vertex -10.94 10.54 0.73
vertex -11.59 10.53 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.91 11.46 -0.02
vertex -11.71 10.99 -0.02
vertex -11.01 11.05 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.91 11.46 0.73
vertex -11.01 11.06 0.73
vertex -11.71 10.99 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -11.74 13.38 -0.02
vertex -11.62 12.91 -0.02
vertex -11.01 13.29 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -11.62 12.91 -0.02
vertex -10.89 12.9 -0.02
vertex -11.01 13.29 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -11.01 13.29 0.73
vertex -11.62 12.91 0.73
vertex -11.74 13.38 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -11.01 13.29 0.73
vertex -10.9 12.89 0.73
vertex -11.62 12.91 0.73
endloop
endfacet
facet normal -0.93 0.36 0
outer loop
vertex -11.57 13.82 -0.02
vertex -11.74 13.38 -0.02
vertex -11.74 13.38 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -11.57 13.82 -0.02
vertex -11.74 13.38 -0.02
vertex -11.01 13.29 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.94 13.8 -0.02
vertex -11.74 13.38 -0.02
vertex -11.57 13.82 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.94 13.8 -0.02
vertex -11.01 13.29 -0.02
vertex -11.74 13.38 -0.02
endloop
endfacet
facet normal -0.94 0.35 0
outer loop
vertex -11.57 13.82 -0.02
vertex -11.74 13.38 0.73
vertex -11.57 13.83 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -11.01 13.29 0.73
vertex -11.74 13.38 0.73
vertex -11.57 13.83 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.94 13.8 0.73
vertex -11.57 13.83 0.73
vertex -11.74 13.38 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.94 13.8 0.73
vertex -11.74 13.38 0.73
vertex -11.01 13.29 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -11.57 13.82 -0.02
vertex -11.01 13.29 -0.02
vertex -10.94 13.8 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.94 13.8 0.73
vertex -11.01 13.29 0.73
vertex -11.57 13.83 0.73
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -4.7 15 0
vertex -11.77 15 0
vertex -11.77 15 0.71
endloop
endfacet
facet normal 0 0.02 -1
outer loop
vertex -10.45 13.82 -0.02
vertex -10.94 13.8 -0.02
vertex -11.77 15 0
endloop
endfacet
facet normal 0 0.02 -1
outer loop
vertex -4.7 15 0
vertex -10.45 13.82 -0.02
vertex -11.77 15 0
endloop
endfacet
facet normal 0 0.02 1
outer loop
vertex -10.45 13.82 0.73
vertex -11.77 15 0.71
vertex -10.94 13.8 0.73
endloop
endfacet
facet normal 0 0.02 1
outer loop
vertex -4.7 15 0.71
vertex -11.77 15 0.71
vertex -10.45 13.82 0.73
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -4.7 15 0
vertex -11.77 15 0.71
vertex -4.7 15 0.71
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.95 -4.63 -0.02
vertex -10.96 -5.07 -0.02
vertex -10.42 -4.66 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.42 -4.66 -0.02
vertex -10.96 -5.07 -0.02
vertex -10.5 -5.1 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.43 -4.66 0.73
vertex -10.96 -5.07 0.73
vertex -10.95 -4.64 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.43 -4.66 0.73
vertex -10.5 -5.1 0.73
vertex -10.96 -5.07 0.73
endloop
endfacet
facet normal -1 -0.06 0
outer loop
vertex -10.95 -4.63 -0.02
vertex -10.95 -4.64 0.73
vertex -10.98 -4.1 0.73
endloop
endfacet
facet normal 0.06 1 0.01
outer loop
vertex -10.42 -4.66 -0.02
vertex -10.95 -4.63 -0.02
vertex -10.95 -4.64 0.73
endloop
endfacet
facet normal -0.04 -1 -0.01
outer loop
vertex -10.95 -4.63 -0.02
vertex -10.43 -4.66 0.73
vertex -10.95 -4.64 0.73
endloop
endfacet
facet normal -1 -0.06 0
outer loop
vertex -10.95 -4.63 -0.02
vertex -10.98 -4.1 0.73
vertex -10.98 -4.1 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.95 -4.63 -0.02
vertex -10.5 -5.1 -0.02
vertex -10.42 -4.66 -0.02
endloop
endfacet
facet normal -0.06 -1 0
outer loop
vertex -10.42 -4.66 -0.02
vertex -10.43 -4.66 0.73
vertex -10.95 -4.63 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.43 -4.66 0.73
vertex -10.5 -5.1 0.73
vertex -10.95 -4.64 0.73
endloop
endfacet
facet normal 0.04 1 0
outer loop
vertex -10.42 -4.66 -0.02
vertex -10.95 -4.64 0.73
vertex -10.43 -4.66 0.73
endloop
endfacet
facet normal -0.05 1 0
outer loop
vertex -10.98 -4.1 -0.02
vertex -10.98 -4.1 0.73
vertex -10.39 -4.07 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.95 -3.6 -0.02
vertex -10.98 -4.1 -0.02
vertex -10.39 -4.07 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.91 -2.23 -0.02
vertex -10.39 -4.07 -0.02
vertex -10.98 -4.1 -0.02
endloop
endfacet
facet normal -0.05 1 0
outer loop
vertex -10.98 -4.1 -0.02
vertex -10.39 -4.07 0.73
vertex -10.39 -4.07 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.51 -3.57 -0.02
vertex -10.98 -4.1 -0.02
vertex -10.39 -4.07 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.95 -3.6 0.73
vertex -10.39 -4.07 0.73
vertex -10.98 -4.1 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.91 -2.23 0.73
vertex -10.98 -4.1 0.73
vertex -10.39 -4.07 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.51 -3.57 0.73
vertex -10.39 -4.07 0.73
vertex -10.98 -4.1 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.95 -3.6 -0.02
vertex -10.39 -4.07 -0.02
vertex -10.51 -3.57 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.51 -3.57 0.73
vertex -10.39 -4.07 0.73
vertex -10.95 -3.6 0.73
endloop
endfacet
facet normal 0.97 0.26 0
outer loop
vertex -10.91 -2.23 -0.02
vertex -11.04 -1.75 -0.02
vertex -10.91 -2.23 0.73
endloop
endfacet
facet normal -0.97 -0.26 0
outer loop
vertex -10.91 -2.23 -0.02
vertex -10.91 -2.23 0.73
vertex -11.04 -1.75 0.73
endloop
endfacet
facet normal 0.14 0.99 0
outer loop
vertex -10.5 -2.29 -0.02
vertex -10.91 -2.23 -0.02
vertex -10.91 -2.23 0.73
endloop
endfacet
facet normal -0.14 -0.99 0
outer loop
vertex -10.91 -2.23 -0.02
vertex -10.5 -2.29 0.73
vertex -10.91 -2.23 0.73
endloop
endfacet
facet normal -0.97 -0.26 0
outer loop
vertex -10.91 -2.23 -0.02
vertex -11.04 -1.75 0.73
vertex -11.04 -1.75 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.5 -2.29 -0.02
vertex -10.39 -4.07 -0.02
vertex -10.91 -2.23 -0.02
endloop
endfacet
facet normal -0.14 -0.99 0
outer loop
vertex -10.5 -2.29 -0.02
vertex -10.5 -2.29 0.73
vertex -10.91 -2.23 -0.02
endloop
endfacet
facet normal 0.97 0.26 0
outer loop
vertex -11.04 -1.75 -0.02
vertex -11.04 -1.75 0.73
vertex -10.91 -2.23 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.5 -2.29 0.73
vertex -10.91 -2.23 0.73
vertex -10.39 -4.07 0.73
endloop
endfacet
facet normal 0.14 0.99 0
outer loop
vertex -10.5 -2.29 -0.02
vertex -10.91 -2.23 0.73
vertex -10.5 -2.29 0.73
endloop
endfacet
facet normal -0.94 0.35 0
outer loop
vertex -11.04 -1.75 -0.02
vertex -11.04 -1.75 0.73
vertex -10.88 -1.32 -0.02
endloop
endfacet
facet normal 0.94 -0.33 0
outer loop
vertex -11.04 -1.75 -0.02
vertex -10.89 -1.32 0.73
vertex -11.04 -1.75 0.73
endloop
endfacet
facet normal 0.94 -0.35 0.01
outer loop
vertex -11.04 -1.75 -0.02
vertex -10.88 -1.32 -0.02
vertex -10.89 -1.32 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.54 -1.27 -0.02
vertex -11.04 -1.75 -0.02
vertex -10.88 -1.32 -0.02
endloop
endfacet
facet normal -0.94 0.33 -0.01
outer loop
vertex -10.88 -1.32 -0.02
vertex -11.04 -1.75 0.73
vertex -10.89 -1.32 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.54 -1.27 0.73
vertex -10.89 -1.32 0.73
vertex -11.04 -1.75 0.73
endloop
endfacet
facet normal -0.14 0.99 0
outer loop
vertex -10.88 -1.32 -0.02
vertex -10.89 -1.32 0.73
vertex -10.54 -1.27 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.52 0.03 -0.02
vertex -10.88 -1.32 -0.02
vertex -10.98 0.56 -0.02
endloop
endfacet
facet normal -0.15 0.99 0
outer loop
vertex -10.88 -1.32 -0.02
vertex -10.54 -1.27 0.73
vertex -10.54 -1.27 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.52 0.03 -0.02
vertex -10.54 -1.27 -0.02
vertex -10.88 -1.32 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.53 0.04 0.73
vertex -10.98 0.56 0.73
vertex -10.89 -1.32 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.53 0.04 0.73
vertex -10.89 -1.32 0.73
vertex -10.54 -1.27 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.98 0.56 -0.02
vertex -11.03 0.06 -0.02
vertex -10.36 0.53 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.36 0.53 -0.02
vertex -11.03 0.06 -0.02
vertex -10.52 0.03 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.36 0.53 0.73
vertex -11.03 0.06 0.73
vertex -10.98 0.56 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.36 0.53 0.73
vertex -10.53 0.04 0.73
vertex -11.03 0.06 0.73
endloop
endfacet
facet normal -1 0.07 0
outer loop
vertex -10.98 0.56 -0.02
vertex -10.98 0.56 0.73
vertex -10.94 1.1 0.73
endloop
endfacet
facet normal 0.76 0.66 0
outer loop
vertex -10.52 0.03 -0.02
vertex -10.98 0.56 -0.02
vertex -10.98 0.56 0.73
endloop
endfacet
facet normal -0.76 -0.65 0
outer loop
vertex -10.98 0.56 -0.02
vertex -10.53 0.04 0.73
vertex -10.98 0.56 0.73
endloop
endfacet
facet normal 0.05 1 0
outer loop
vertex -10.36 0.53 -0.02
vertex -10.98 0.56 -0.02
vertex -10.98 0.56 0.73
endloop
endfacet
facet normal -1 0.09 -0.01
outer loop
vertex -10.98 0.56 -0.02
vertex -10.94 1.1 0.73
vertex -10.93 1.1 -0.02
endloop
endfacet
facet normal -0.76 -0.66 0
outer loop
vertex -10.52 0.03 -0.02
vertex -10.53 0.04 0.73
vertex -10.98 0.56 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.98 0.56 -0.02
vertex -10.52 0.03 -0.02
vertex -10.36 0.53 -0.02
endloop
endfacet
facet normal 0.76 0.65 0
outer loop
vertex -10.52 0.03 -0.02
vertex -10.98 0.56 0.73
vertex -10.53 0.04 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.36 0.53 0.73
vertex -10.53 0.04 0.73
vertex -10.98 0.56 0.73
endloop
endfacet
facet normal 0.05 1 0
outer loop
vertex -10.36 0.53 -0.02
vertex -10.98 0.56 0.73
vertex -10.36 0.53 0.73
endloop
endfacet
facet normal -0.04 1 0
outer loop
vertex -10.93 1.1 -0.02
vertex -10.94 1.1 0.73
vertex -10.45 1.12 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.86 1.51 -0.02
vertex -10.93 1.1 -0.02
vertex -10.44 1.12 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.42 2.96 -0.02
vertex -10.93 1.1 -0.02
vertex -10.95 2.99 -0.02
endloop
endfacet
facet normal -0.04 1 0
outer loop
vertex -10.93 1.1 -0.02
vertex -10.45 1.12 0.73
vertex -10.44 1.12 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.59 1.53 -0.02
vertex -10.93 1.1 -0.02
vertex -10.44 1.12 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.42 2.96 -0.02
vertex -10.44 1.12 -0.02
vertex -10.93 1.1 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.86 1.51 0.73
vertex -10.45 1.12 0.73
vertex -10.94 1.1 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.43 2.96 0.73
vertex -10.95 2.98 0.73
vertex -10.94 1.1 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.59 1.53 0.73
vertex -10.45 1.12 0.73
vertex -10.94 1.1 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.43 2.96 0.73
vertex -10.94 1.1 0.73
vertex -10.45 1.12 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.86 1.51 -0.02
vertex -10.44 1.12 -0.02
vertex -10.59 1.53 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.59 1.53 0.73
vertex -10.45 1.12 0.73
vertex -10.86 1.51 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.95 2.99 -0.02
vertex -10.96 2.55 -0.02
vertex -10.42 2.96 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.42 2.96 -0.02
vertex -10.96 2.55 -0.02
vertex -10.51 2.52 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.43 2.96 0.73
vertex -10.96 2.55 0.73
vertex -10.95 2.98 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.43 2.96 0.73
vertex -10.51 2.52 0.73
vertex -10.96 2.55 0.73
endloop
endfacet
facet normal -1 -0.04 0
outer loop
vertex -10.95 2.99 -0.02
vertex -10.95 2.98 0.73
vertex -10.97 3.51 0.73
endloop
endfacet
facet normal 0.06 1 0.01
outer loop
vertex -10.42 2.96 -0.02
vertex -10.95 2.99 -0.02
vertex -10.95 2.98 0.73
endloop
endfacet
facet normal -0.04 -1 -0.01
outer loop
vertex -10.95 2.99 -0.02
vertex -10.43 2.96 0.73
vertex -10.95 2.98 0.73
endloop
endfacet
facet normal -1 -0.04 0
outer loop
vertex -10.95 2.99 -0.02
vertex -10.97 3.51 0.73
vertex -10.97 3.51 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.95 2.99 -0.02
vertex -10.51 2.52 -0.02
vertex -10.42 2.96 -0.02
endloop
endfacet
facet normal -0.06 -1 0
outer loop
vertex -10.42 2.96 -0.02
vertex -10.43 2.96 0.73
vertex -10.95 2.99 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.43 2.96 0.73
vertex -10.51 2.52 0.73
vertex -10.95 2.98 0.73
endloop
endfacet
facet normal 0.04 1 0
outer loop
vertex -10.42 2.96 -0.02
vertex -10.95 2.98 0.73
vertex -10.43 2.96 0.73
endloop
endfacet
facet normal -0.07 1 0
outer loop
vertex -10.97 3.51 -0.02
vertex -10.97 3.51 0.73
vertex -10.4 3.55 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -11.02 3.97 -0.02
vertex -10.97 3.51 -0.02
vertex -10.39 3.55 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.89 5.35 -0.02
vertex -10.39 3.55 -0.02
vertex -10.97 3.51 -0.02
endloop
endfacet
facet normal -0.07 1 0
outer loop
vertex -10.97 3.51 -0.02
vertex -10.4 3.55 0.73
vertex -10.39 3.55 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.51 4.05 -0.02
vertex -10.97 3.51 -0.02
vertex -10.39 3.55 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -11.02 3.97 0.73
vertex -10.4 3.55 0.73
vertex -10.97 3.51 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.89 5.35 0.73
vertex -10.97 3.51 0.73
vertex -10.4 3.55 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.51 4.05 0.73
vertex -10.4 3.55 0.73
vertex -10.97 3.51 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -11.02 3.97 -0.02
vertex -10.39 3.55 -0.02
vertex -10.51 4.05 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.51 4.05 0.73
vertex -10.4 3.55 0.73
vertex -11.02 3.97 0.73
endloop
endfacet
facet normal 0.94 0.33 0
outer loop
vertex -10.89 5.35 -0.02
vertex -11.04 5.78 -0.02
vertex -10.89 5.35 0.73
endloop
endfacet
facet normal -0.94 -0.33 0
outer loop
vertex -10.89 5.35 -0.02
vertex -10.89 5.35 0.73
vertex -11.04 5.78 0.73
endloop
endfacet
facet normal 0.13 0.99 0
outer loop
vertex -10.52 5.3 -0.02
vertex -10.89 5.35 -0.02
vertex -10.89 5.35 0.73
endloop
endfacet
facet normal -0.13 -0.99 0
outer loop
vertex -10.89 5.35 -0.02
vertex -10.52 5.3 0.73
vertex -10.89 5.35 0.73
endloop
endfacet
facet normal -0.94 -0.33 0
outer loop
vertex -10.89 5.35 -0.02
vertex -11.04 5.78 0.73
vertex -11.04 5.78 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -11.04 5.78 -0.02
vertex -10.52 5.3 -0.02
vertex -10.89 5.35 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.52 5.3 -0.02
vertex -10.39 3.55 -0.02
vertex -10.89 5.35 -0.02
endloop
endfacet
facet normal -0.13 -0.99 0
outer loop
vertex -10.52 5.3 -0.02
vertex -10.52 5.3 0.73
vertex -10.89 5.35 -0.02
endloop
endfacet
facet normal 0.94 0.33 0
outer loop
vertex -11.04 5.78 -0.02
vertex -11.04 5.78 0.73
vertex -10.89 5.35 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.89 5.35 0.73
vertex -10.52 5.3 0.73
vertex -11.04 5.78 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.52 5.3 0.73
vertex -10.89 5.35 0.73
vertex -10.4 3.55 0.73
endloop
endfacet
facet normal 0.13 0.99 0
outer loop
vertex -10.52 5.3 -0.02
vertex -10.89 5.35 0.73
vertex -10.52 5.3 0.73
endloop
endfacet
facet normal 0.96 -0.27 0
outer loop
vertex -11.04 5.78 -0.02
vertex -10.91 6.25 -0.02
vertex -11.04 5.78 0.73
endloop
endfacet
facet normal -0.96 0.27 0
outer loop
vertex -11.04 5.78 -0.02
vertex -11.04 5.78 0.73
vertex -10.91 6.25 0.73
endloop
endfacet
facet normal -0.96 0.27 0
outer loop
vertex -11.04 5.78 -0.02
vertex -10.91 6.25 0.73
vertex -10.91 6.25 -0.02
endloop
endfacet
facet normal 0.96 -0.27 0
outer loop
vertex -10.91 6.25 -0.02
vertex -10.91 6.25 0.73
vertex -11.04 5.78 0.73
endloop
endfacet
facet normal -0.14 0.99 0
outer loop
vertex -10.91 6.25 -0.02
vertex -10.91 6.25 0.73
vertex -10.5 6.31 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.39 8.09 -0.02
vertex -10.91 6.25 -0.02
vertex -10.97 8.13 -0.02
endloop
endfacet
facet normal -0.14 0.99 0
outer loop
vertex -10.91 6.25 -0.02
vertex -10.5 6.31 0.73
vertex -10.5 6.31 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.39 8.09 -0.02
vertex -10.5 6.31 -0.02
vertex -10.91 6.25 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.4 8.09 0.73
vertex -10.97 8.13 0.73
vertex -10.91 6.25 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.4 8.09 0.73
vertex -10.91 6.25 0.73
vertex -10.5 6.31 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.97 8.13 -0.02
vertex -11.03 7.68 -0.02
vertex -10.39 8.09 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.39 8.09 -0.02
vertex -11.03 7.68 -0.02
vertex -10.51 7.6 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.4 8.09 0.73
vertex -11.03 7.68 0.73
vertex -10.97 8.13 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.4 8.09 0.73
vertex -10.51 7.6 0.73
vertex -11.03 7.68 0.73
endloop
endfacet
facet normal -1 0.02 0
outer loop
vertex -10.97 8.13 -0.02
vertex -10.97 8.13 0.73
vertex -10.96 8.65 0.73
endloop
endfacet
facet normal 0.07 1 0
outer loop
vertex -10.39 8.09 -0.02
vertex -10.97 8.13 -0.02
vertex -10.97 8.13 0.73
endloop
endfacet
facet normal -0.07 -1 0
outer loop
vertex -10.97 8.13 -0.02
vertex -10.4 8.09 0.73
vertex -10.97 8.13 0.73
endloop
endfacet
facet normal -1 0.04 -0.01
outer loop
vertex -10.97 8.13 -0.02
vertex -10.96 8.65 0.73
vertex -10.95 8.66 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.97 8.13 -0.02
vertex -10.51 7.6 -0.02
vertex -10.39 8.09 -0.02
endloop
endfacet
facet normal -0.07 -1 0
outer loop
vertex -10.39 8.09 -0.02
vertex -10.4 8.09 0.73
vertex -10.97 8.13 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.4 8.09 0.73
vertex -10.51 7.6 0.73
vertex -10.97 8.13 0.73
endloop
endfacet
facet normal 0.07 1 0
outer loop
vertex -10.39 8.09 -0.02
vertex -10.97 8.13 0.73
vertex -10.4 8.09 0.73
endloop
endfacet
facet normal -0.06 1 0.01
outer loop
vertex -10.95 8.66 -0.02
vertex -10.96 8.65 0.73
vertex -10.42 8.68 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.95 9.1 -0.02
vertex -10.95 8.66 -0.02
vertex -10.42 8.67 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.44 10.52 -0.02
vertex -10.95 8.66 -0.02
vertex -10.94 10.54 -0.02
endloop
endfacet
facet normal -0.02 1 -0.01
outer loop
vertex -10.95 8.66 -0.02
vertex -10.42 8.68 0.73
vertex -10.42 8.67 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.51 9.13 -0.02
vertex -10.95 8.66 -0.02
vertex -10.42 8.67 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.44 10.52 -0.02
vertex -10.42 8.67 -0.02
vertex -10.95 8.66 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.95 9.1 0.73
vertex -10.42 8.68 0.73
vertex -10.96 8.65 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.44 10.52 0.73
vertex -10.94 10.54 0.73
vertex -10.96 8.65 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.51 9.13 0.73
vertex -10.42 8.68 0.73
vertex -10.96 8.65 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.44 10.52 0.73
vertex -10.96 8.65 0.73
vertex -10.42 8.68 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.95 9.1 -0.02
vertex -10.42 8.67 -0.02
vertex -10.51 9.13 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.51 9.13 0.73
vertex -10.42 8.68 0.73
vertex -10.95 9.1 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.94 10.54 -0.02
vertex -10.86 10.13 -0.02
vertex -10.44 10.52 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.44 10.52 -0.02
vertex -10.86 10.13 -0.02
vertex -10.6 10.11 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.44 10.52 0.73
vertex -10.86 10.13 0.73
vertex -10.94 10.54 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.44 10.52 0.73
vertex -10.6 10.11 0.73
vertex -10.86 10.13 0.73
endloop
endfacet
facet normal 0.99 0.14 0
outer loop
vertex -10.94 10.54 -0.02
vertex -11.01 11.05 -0.02
vertex -10.94 10.54 0.73
endloop
endfacet
facet normal -0.99 -0.13 0
outer loop
vertex -10.94 10.54 -0.02
vertex -10.94 10.54 0.73
vertex -11.01 11.06 0.73
endloop
endfacet
facet normal 0.04 1 0
outer loop
vertex -10.44 10.52 -0.02
vertex -10.94 10.54 -0.02
vertex -10.94 10.54 0.73
endloop
endfacet
facet normal -0.04 -1 0
outer loop
vertex -10.94 10.54 -0.02
vertex -10.44 10.52 0.73
vertex -10.94 10.54 0.73
endloop
endfacet
facet normal -0.99 -0.14 0
outer loop
vertex -10.94 10.54 -0.02
vertex -11.01 11.06 0.73
vertex -11.01 11.05 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.94 10.54 -0.02
vertex -10.6 10.11 -0.02
vertex -10.44 10.52 -0.02
endloop
endfacet
facet normal -0.04 -1 0
outer loop
vertex -10.44 10.52 -0.02
vertex -10.44 10.52 0.73
vertex -10.94 10.54 -0.02
endloop
endfacet
facet normal 0.99 0.13 0
outer loop
vertex -11.01 11.05 -0.02
vertex -11.01 11.06 0.73
vertex -10.94 10.54 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.44 10.52 0.73
vertex -10.6 10.11 0.73
vertex -10.94 10.54 0.73
endloop
endfacet
facet normal 0.04 1 0
outer loop
vertex -10.44 10.52 -0.02
vertex -10.94 10.54 0.73
vertex -10.44 10.52 0.73
endloop
endfacet
facet normal 0.97 -0.24 0
outer loop
vertex -11.01 11.05 -0.02
vertex -10.91 11.46 -0.02
vertex -11.01 11.06 0.73
endloop
endfacet
facet normal -0.97 0.24 0
outer loop
vertex -11.01 11.05 -0.02
vertex -11.01 11.06 0.73
vertex -10.91 11.46 0.73
endloop
endfacet
facet normal -0.97 0.24 0
outer loop
vertex -11.01 11.05 -0.02
vertex -10.91 11.46 0.73
vertex -10.91 11.46 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -11.01 13.29 -0.02
vertex -10.91 11.46 -0.02
vertex -11.01 11.05 -0.02
endloop
endfacet
facet normal 0.97 -0.24 0
outer loop
vertex -10.91 11.46 -0.02
vertex -10.91 11.46 0.73
vertex -11.01 11.06 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -11.01 13.29 0.73
vertex -11.01 11.06 0.73
vertex -10.91 11.46 0.73
endloop
endfacet
facet normal -0.03 1 0
outer loop
vertex -10.91 11.46 -0.02
vertex -10.91 11.46 0.73
vertex -10.57 11.47 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.89 12.9 -0.02
vertex -10.91 11.46 -0.02
vertex -11.01 13.29 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.56 12.87 -0.02
vertex -10.91 11.46 -0.02
vertex -10.89 12.9 -0.02
endloop
endfacet
facet normal -0.03 1 0
outer loop
vertex -10.91 11.46 -0.02
vertex -10.57 11.47 0.73
vertex -10.56 11.47 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.56 12.87 -0.02
vertex -10.56 11.47 -0.02
vertex -10.91 11.46 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.9 12.89 0.73
vertex -11.01 13.29 0.73
vertex -10.91 11.46 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.56 12.87 0.73
vertex -10.9 12.89 0.73
vertex -10.91 11.46 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.56 12.87 0.73
vertex -10.91 11.46 0.73
vertex -10.57 11.47 0.73
endloop
endfacet
facet normal -0.96 -0.27 -0.02
outer loop
vertex -10.89 12.9 -0.02
vertex -10.9 12.89 0.73
vertex -11.01 13.29 0.73
endloop
endfacet
facet normal 0.09 1 0.01
outer loop
vertex -10.56 12.87 -0.02
vertex -10.89 12.9 -0.02
vertex -10.9 12.89 0.73
endloop
endfacet
facet normal -0.06 -1 -0.01
outer loop
vertex -10.89 12.9 -0.02
vertex -10.56 12.87 0.73
vertex -10.9 12.89 0.73
endloop
endfacet
facet normal -0.96 -0.29 0
outer loop
vertex -10.89 12.9 -0.02
vertex -11.01 13.29 0.73
vertex -11.01 13.29 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -11.01 13.29 -0.02
vertex -10.56 12.87 -0.02
vertex -10.89 12.9 -0.02
endloop
endfacet
facet normal -0.09 -1 0
outer loop
vertex -10.56 12.87 -0.02
vertex -10.56 12.87 0.73
vertex -10.89 12.9 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.9 12.89 0.73
vertex -10.56 12.87 0.73
vertex -11.01 13.29 0.73
endloop
endfacet
facet normal 0.06 1 0
outer loop
vertex -10.56 12.87 -0.02
vertex -10.9 12.89 0.73
vertex -10.56 12.87 0.73
endloop
endfacet
facet normal -0.99 0.14 0
outer loop
vertex -11.01 13.29 -0.02
vertex -11.01 13.29 0.73
vertex -10.94 13.8 0.73
endloop
endfacet
facet normal -0.99 0.14 0
outer loop
vertex -11.01 13.29 -0.02
vertex -10.94 13.8 0.73
vertex -10.94 13.8 -0.02
endloop
endfacet
facet normal -0.04 1 0
outer loop
vertex -10.94 13.8 -0.02
vertex -10.94 13.8 0.73
vertex -10.45 13.82 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.86 14.21 -0.02
vertex -10.94 13.8 -0.02
vertex -10.45 13.82 -0.02
endloop
endfacet
facet normal -0.04 1 0
outer loop
vertex -10.94 13.8 -0.02
vertex -10.45 13.82 0.73
vertex -10.45 13.82 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.59 14.23 -0.02
vertex -10.94 13.8 -0.02
vertex -10.45 13.82 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.86 14.21 0.73
vertex -10.45 13.82 0.73
vertex -10.94 13.8 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.59 14.23 0.73
vertex -10.45 13.82 0.73
vertex -10.94 13.8 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.86 14.21 -0.02
vertex -10.45 13.82 -0.02
vertex -10.59 14.23 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.59 14.23 0.73
vertex -10.45 13.82 0.73
vertex -10.86 14.21 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.42 -4.66 -0.02
vertex -10.5 -5.1 -0.02
vertex -9.96 -4.71 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.43 -4.66 0.73
vertex -9.96 -4.71 0.73
vertex -10.5 -5.1 0.73
endloop
endfacet
facet normal 1 -0.05 0.01
outer loop
vertex -10.39 -4.07 -0.02
vertex -10.43 -4.66 0.73
vertex -10.42 -4.66 -0.02
endloop
endfacet
facet normal -1 0.07 -0.01
outer loop
vertex -10.42 -4.66 -0.02
vertex -10.43 -4.66 0.73
vertex -10.39 -4.07 0.73
endloop
endfacet
facet normal -1 0.05 0
outer loop
vertex -10.39 -4.07 -0.02
vertex -10.42 -4.66 -0.02
vertex -10.39 -4.07 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.39 -4.07 -0.02
vertex -10.42 -4.66 -0.02
vertex -9.96 -4.71 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.43 -9.3 -0.02
vertex -10.42 -4.66 -0.02
vertex -10.39 -4.07 -0.02
endloop
endfacet
facet normal 1 -0.07 0
outer loop
vertex -10.39 -4.07 -0.02
vertex -10.39 -4.07 0.73
vertex -10.43 -4.66 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -9.96 -4.71 0.73
vertex -10.43 -4.66 0.73
vertex -10.39 -4.07 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 6.43 -9.3 0.73
vertex -10.39 -4.07 0.73
vertex -10.43 -4.66 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.51 -3.57 -0.02
vertex -10.39 -4.07 -0.02
vertex -9.94 -4.04 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.26 -1.75 -0.02
vertex -10.39 -4.07 -0.02
vertex -10.5 -2.29 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.43 -9.3 -0.02
vertex -10.39 -4.07 -0.02
vertex -10.26 -1.75 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.39 -4.07 -0.02
vertex -9.96 -4.71 -0.02
vertex -9.94 -4.04 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -9.94 -4.04 0.73
vertex -10.39 -4.07 0.73
vertex -10.51 -3.57 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.26 -1.75 0.73
vertex -10.5 -2.29 0.73
vertex -10.39 -4.07 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 6.43 -9.3 0.73
vertex -10.26 -1.75 0.73
vertex -10.39 -4.07 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -9.94 -4.04 0.73
vertex -9.96 -4.71 0.73
vertex -10.39 -4.07 0.73
endloop
endfacet
facet normal 0.91 -0.41 0
outer loop
vertex -10.26 -1.75 -0.02
vertex -10.5 -2.29 0.73
vertex -10.5 -2.29 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.26 -1.75 -0.02
vertex -10.5 -2.29 -0.02
vertex -10.01 -2.28 -0.02
endloop
endfacet
facet normal 0.91 -0.41 0
outer loop
vertex -10.26 -1.75 -0.02
vertex -10.26 -1.75 0.73
vertex -10.5 -2.29 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.01 -2.28 0.73
vertex -10.5 -2.29 0.73
vertex -10.26 -1.75 0.73
endloop
endfacet
facet normal 0.86 0.5 0
outer loop
vertex -10.54 -1.27 -0.02
vertex -10.26 -1.75 0.73
vertex -10.26 -1.75 -0.02
endloop
endfacet
facet normal -0.86 -0.5 0
outer loop
vertex -10.26 -1.75 -0.02
vertex -10.26 -1.75 0.73
vertex -10.54 -1.27 0.73
endloop
endfacet
facet normal -0.86 -0.5 0
outer loop
vertex -10.54 -1.27 -0.02
vertex -10.26 -1.75 -0.02
vertex -10.54 -1.27 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.36 0.53 -0.02
vertex -10.26 -1.75 -0.02
vertex -10.54 -1.27 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.54 -1.27 -0.02
vertex -10.26 -1.75 -0.02
vertex -10.01 -1.33 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -3.39 8.73 0
vertex -10.26 -1.75 -0.02
vertex -10.36 0.53 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.26 -1.75 -0.02
vertex -10.01 -2.28 -0.02
vertex -9.87 -1.81 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.01 -1.33 -0.02
vertex -10.26 -1.75 -0.02
vertex -9.87 -1.81 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.28 -1.75 -0.02
vertex -10.26 -1.75 -0.02
vertex -3.39 8.73 0
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.28 -1.75 -0.02
vertex 6.43 -9.3 -0.02
vertex -10.26 -1.75 -0.02
endloop
endfacet
facet normal 0.86 0.5 0
outer loop
vertex -10.54 -1.27 -0.02
vertex -10.54 -1.27 0.73
vertex -10.26 -1.75 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.36 0.53 0.73
vertex -10.54 -1.27 0.73
vertex -10.26 -1.75 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.01 -1.33 0.73
vertex -10.26 -1.75 0.73
vertex -10.54 -1.27 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -3.39 8.73 0.71
vertex -10.36 0.53 0.73
vertex -10.26 -1.75 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -9.87 -1.81 0.73
vertex -10.01 -2.28 0.73
vertex -10.26 -1.75 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.01 -1.33 0.73
vertex -9.87 -1.81 0.73
vertex -10.26 -1.75 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.28 -1.75 0.73
vertex -3.39 8.73 0.71
vertex -10.26 -1.75 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.28 -1.75 0.73
vertex -10.26 -1.75 0.73
vertex 6.43 -9.3 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.36 0.53 -0.02
vertex -10.54 -1.27 -0.02
vertex -10.52 0.03 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.36 0.53 0.73
vertex -10.53 0.04 0.73
vertex -10.54 -1.27 0.73
endloop
endfacet
facet normal 0.95 -0.3 0.02
outer loop
vertex -10.36 0.53 -0.02
vertex -10.53 0.04 0.73
vertex -10.52 0.03 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.36 0.53 -0.02
vertex -10.52 0.03 -0.02
vertex -10.08 0.17 -0.02
endloop
endfacet
facet normal 0.94 -0.33 0
outer loop
vertex -10.36 0.53 -0.02
vertex -10.36 0.53 0.73
vertex -10.53 0.04 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.36 0.53 0.73
vertex -10.08 0.17 0.73
vertex -10.53 0.04 0.73
endloop
endfacet
facet normal 0.99 0.13 0
outer loop
vertex -10.44 1.12 -0.02
vertex -10.36 0.53 0.73
vertex -10.36 0.53 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.42 2.96 -0.02
vertex -10.36 0.53 -0.02
vertex -10.44 1.12 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.44 1.12 -0.02
vertex -10.36 0.53 -0.02
vertex -9.97 1.12 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -3.39 8.73 0
vertex -10.36 0.53 -0.02
vertex -10.42 2.96 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.36 0.53 -0.02
vertex -10.08 0.17 -0.02
vertex -9.9 0.53 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.36 0.53 -0.02
vertex -9.9 0.53 -0.02
vertex -9.97 1.12 -0.02
endloop
endfacet
facet normal 0.99 0.15 0.01
outer loop
vertex -10.44 1.12 -0.02
vertex -10.45 1.12 0.73
vertex -10.36 0.53 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.43 2.96 0.73
vertex -10.45 1.12 0.73
vertex -10.36 0.53 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -9.97 1.12 0.73
vertex -10.36 0.53 0.73
vertex -10.45 1.12 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -3.39 8.73 0.71
vertex -10.43 2.96 0.73
vertex -10.36 0.53 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -9.9 0.53 0.73
vertex -10.08 0.17 0.73
vertex -10.36 0.53 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -9.97 1.12 0.73
vertex -9.9 0.53 0.73
vertex -10.36 0.53 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.42 2.96 -0.02
vertex -10.51 2.52 -0.02
vertex -9.96 2.91 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.43 2.96 0.73
vertex -9.96 2.91 0.73
vertex -10.51 2.52 0.73
endloop
endfacet
facet normal 1 -0.05 0.01
outer loop
vertex -10.39 3.55 -0.02
vertex -10.43 2.96 0.73
vertex -10.42 2.96 -0.02
endloop
endfacet
facet normal -1 0.05 -0.01
outer loop
vertex -10.42 2.96 -0.02
vertex -10.43 2.96 0.73
vertex -10.4 3.55 0.73
endloop
endfacet
facet normal -1 0.05 -0.01
outer loop
vertex -10.39 3.55 -0.02
vertex -10.42 2.96 -0.02
vertex -10.4 3.55 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.39 3.55 -0.02
vertex -10.42 2.96 -0.02
vertex -9.96 2.91 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -4.14 8.73 0
vertex -10.42 2.96 -0.02
vertex -10.39 3.55 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -3.39 8.73 0
vertex -10.42 2.96 -0.02
vertex -4.14 8.73 0
endloop
endfacet
facet normal 1 -0.05 0.01
outer loop
vertex -10.39 3.55 -0.02
vertex -10.4 3.55 0.73
vertex -10.43 2.96 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -9.96 2.91 0.73
vertex -10.43 2.96 0.73
vertex -10.4 3.55 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -4.14 8.73 0.71
vertex -10.4 3.55 0.73
vertex -10.43 2.96 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -3.39 8.73 0.71
vertex -4.14 8.73 0.71
vertex -10.43 2.96 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.51 4.05 -0.02
vertex -10.39 3.55 -0.02
vertex -10.08 3.85 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.26 5.78 -0.02
vertex -10.39 3.55 -0.02
vertex -10.52 5.3 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -4.14 8.73 0
vertex -10.39 3.55 -0.02
vertex -10.26 5.78 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.39 3.55 -0.02
vertex -9.96 2.91 -0.02
vertex -9.9 3.5 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.39 3.55 -0.02
vertex -9.9 3.5 -0.02
vertex -10.08 3.85 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.08 3.85 0.73
vertex -10.4 3.55 0.73
vertex -10.51 4.05 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.26 5.78 0.73
vertex -10.52 5.3 0.73
vertex -10.4 3.55 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -4.14 8.73 0.71
vertex -10.26 5.78 0.73
vertex -10.4 3.55 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -9.9 3.5 0.73
vertex -9.96 2.91 0.73
vertex -10.4 3.55 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.08 3.85 0.73
vertex -9.9 3.5 0.73
vertex -10.4 3.55 0.73
endloop
endfacet
facet normal 0.88 -0.48 0
outer loop
vertex -10.26 5.78 -0.02
vertex -10.52 5.3 0.73
vertex -10.52 5.3 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.26 5.78 -0.02
vertex -10.52 5.3 -0.02
vertex -10.01 5.34 -0.02
endloop
endfacet
facet normal 0.88 -0.48 0
outer loop
vertex -10.26 5.78 -0.02
vertex -10.26 5.78 0.73
vertex -10.52 5.3 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.26 5.78 0.73
vertex -10.01 5.34 0.73
vertex -10.52 5.3 0.73
endloop
endfacet
facet normal 0.91 0.41 0
outer loop
vertex -10.5 6.31 -0.02
vertex -10.26 5.78 0.73
vertex -10.26 5.78 -0.02
endloop
endfacet
facet normal -0.91 -0.41 0
outer loop
vertex -10.26 5.78 -0.02
vertex -10.26 5.78 0.73
vertex -10.5 6.31 0.73
endloop
endfacet
facet normal -0.91 -0.41 0
outer loop
vertex -10.5 6.31 -0.02
vertex -10.26 5.78 -0.02
vertex -10.5 6.31 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.39 8.09 -0.02
vertex -10.26 5.78 -0.02
vertex -10.5 6.31 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.5 6.31 -0.02
vertex -10.26 5.78 -0.02
vertex -10.01 6.29 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -4.49 8.84 0
vertex -10.26 5.78 -0.02
vertex -10.39 8.09 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.26 5.78 -0.02
vertex -10.01 5.34 -0.02
vertex -9.87 5.81 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.01 6.29 -0.02
vertex -10.26 5.78 -0.02
vertex -9.87 5.81 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -4.14 8.73 0
vertex -10.26 5.78 -0.02
vertex -4.49 8.84 0
endloop
endfacet
facet normal 0.91 0.41 0
outer loop
vertex -10.5 6.31 -0.02
vertex -10.5 6.31 0.73
vertex -10.26 5.78 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.4 8.09 0.73
vertex -10.5 6.31 0.73
vertex -10.26 5.78 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.01 6.29 0.73
vertex -10.26 5.78 0.73
vertex -10.5 6.31 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -4.49 8.84 0.71
vertex -10.4 8.09 0.73
vertex -10.26 5.78 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -9.87 5.81 0.73
vertex -10.01 5.34 0.73
vertex -10.26 5.78 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.01 6.29 0.73
vertex -9.87 5.81 0.73
vertex -10.26 5.78 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -4.14 8.73 0.71
vertex -4.49 8.84 0.71
vertex -10.26 5.78 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.39 8.09 -0.02
vertex -10.51 7.6 -0.02
vertex -10.08 7.79 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.4 8.09 0.73
vertex -10.08 7.79 0.73
vertex -10.51 7.6 0.73
endloop
endfacet
facet normal 1 0.05 0.01
outer loop
vertex -10.42 8.67 -0.02
vertex -10.4 8.09 0.73
vertex -10.39 8.09 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.42 8.67 -0.02
vertex -10.39 8.09 -0.02
vertex -9.97 8.74 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -4.53 9.25 0
vertex -10.39 8.09 -0.02
vertex -10.42 8.67 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.39 8.09 -0.02
vertex -10.08 7.79 -0.02
vertex -9.9 8.15 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.39 8.09 -0.02
vertex -9.9 8.15 -0.02
vertex -9.97 8.74 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -4.53 9.25 0
vertex -4.49 8.84 0
vertex -10.39 8.09 -0.02
endloop
endfacet
facet normal 1 0.03 0
outer loop
vertex -10.42 8.67 -0.02
vertex -10.42 8.68 0.73
vertex -10.4 8.09 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -9.97 8.74 0.73
vertex -10.4 8.09 0.73
vertex -10.42 8.68 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -4.53 9.25 0.71
vertex -10.42 8.68 0.73
vertex -10.4 8.09 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -9.9 8.15 0.73
vertex -10.08 7.79 0.73
vertex -10.4 8.09 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -9.97 8.74 0.73
vertex -9.9 8.15 0.73
vertex -10.4 8.09 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -4.53 9.25 0.71
vertex -10.4 8.09 0.73
vertex -4.49 8.84 0.71
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.51 9.13 -0.02
vertex -10.42 8.67 -0.02
vertex -9.97 8.74 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.29 11.05 -0.02
vertex -10.42 8.67 -0.02
vertex -10.44 10.52 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -4.53 9.25 0
vertex -10.42 8.67 -0.02
vertex -10.29 11.05 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -9.97 8.74 0.73
vertex -10.42 8.68 0.73
vertex -10.51 9.13 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.29 11.05 0.73
vertex -10.44 10.52 0.73
vertex -10.42 8.68 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -4.53 9.25 0.71
vertex -10.29 11.05 0.73
vertex -10.42 8.68 0.73
endloop
endfacet
facet normal 0.96 -0.27 0
outer loop
vertex -10.29 11.05 -0.02
vertex -10.44 10.52 0.73
vertex -10.44 10.52 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.29 11.05 -0.02
vertex -10.44 10.52 -0.02
vertex -9.96 10.53 -0.02
endloop
endfacet
facet normal 0.96 -0.27 0
outer loop
vertex -10.29 11.05 -0.02
vertex -10.29 11.05 0.73
vertex -10.44 10.52 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -9.96 10.53 0.73
vertex -10.44 10.52 0.73
vertex -10.29 11.05 0.73
endloop
endfacet
facet normal 0.84 0.54 0
outer loop
vertex -10.56 11.47 -0.02
vertex -10.29 11.05 0.73
vertex -10.29 11.05 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.29 13.29 -0.02
vertex -10.29 11.05 -0.02
vertex -10.56 11.47 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.56 11.47 -0.02
vertex -10.29 11.05 -0.02
vertex -10.08 11.47 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -4.2 14 0
vertex -10.29 11.05 -0.02
vertex -10.29 13.29 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.29 11.05 -0.02
vertex -9.96 10.53 -0.02
vertex -9.9 11.12 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.29 11.05 -0.02
vertex -9.9 11.12 -0.02
vertex -10.08 11.47 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -4.2 14 0
vertex -4.53 9.25 0
vertex -10.29 11.05 -0.02
endloop
endfacet
facet normal 0.83 0.55 0.01
outer loop
vertex -10.56 11.47 -0.02
vertex -10.57 11.47 0.73
vertex -10.29 11.05 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.29 13.29 0.73
vertex -10.57 11.47 0.73
vertex -10.29 11.05 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.08 11.47 0.73
vertex -10.29 11.05 0.73
vertex -10.57 11.47 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -4.2 14 0.71
vertex -10.29 13.29 0.73
vertex -10.29 11.05 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -9.9 11.12 0.73
vertex -9.96 10.53 0.73
vertex -10.29 11.05 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.08 11.47 0.73
vertex -9.9 11.12 0.73
vertex -10.29 11.05 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -4.2 14 0.71
vertex -10.29 11.05 0.73
vertex -4.53 9.25 0.71
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.29 13.29 -0.02
vertex -10.56 11.47 -0.02
vertex -10.56 12.87 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.29 13.29 0.73
vertex -10.56 12.87 0.73
vertex -10.57 11.47 0.73
endloop
endfacet
facet normal 0.84 -0.54 0
outer loop
vertex -10.29 13.29 -0.02
vertex -10.56 12.87 0.73
vertex -10.56 12.87 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.29 13.29 -0.02
vertex -10.56 12.87 -0.02
vertex -10.01 12.96 -0.02
endloop
endfacet
facet normal 0.84 -0.54 0
outer loop
vertex -10.29 13.29 -0.02
vertex -10.29 13.29 0.73
vertex -10.56 12.87 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.29 13.29 0.73
vertex -10.01 12.96 0.73
vertex -10.56 12.87 0.73
endloop
endfacet
facet normal 0.96 0.29 0
outer loop
vertex -10.45 13.82 -0.02
vertex -10.29 13.29 0.73
vertex -10.29 13.29 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.45 13.82 -0.02
vertex -10.29 13.29 -0.02
vertex -9.97 13.82 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -4.7 15 0
vertex -10.29 13.29 -0.02
vertex -10.45 13.82 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.29 13.29 -0.02
vertex -10.01 12.96 -0.02
vertex -9.87 13.32 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.29 13.29 -0.02
vertex -9.87 13.32 -0.02
vertex -9.97 13.82 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -4.7 15 0
vertex -4.2 14 0
vertex -10.29 13.29 -0.02
endloop
endfacet
facet normal 0.96 0.29 0
outer loop
vertex -10.45 13.82 -0.02
vertex -10.45 13.82 0.73
vertex -10.29 13.29 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -9.97 13.82 0.73
vertex -10.29 13.29 0.73
vertex -10.45 13.82 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -4.7 15 0.71
vertex -10.45 13.82 0.73
vertex -10.29 13.29 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -9.87 13.32 0.73
vertex -10.01 12.96 0.73
vertex -10.29 13.29 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -9.97 13.82 0.73
vertex -9.87 13.32 0.73
vertex -10.29 13.29 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -4.7 15 0.71
vertex -10.29 13.29 0.73
vertex -4.2 14 0.71
endloop
endfacet
facet normal -1 0 0.07
outer loop
vertex -8.44 3 1.69
vertex -8.45 1.59 1.55
vertex -8.44 1.6 1.69
endloop
endfacet
facet normal -0.45 -0.89 0.1
outer loop
vertex -8.44 1.6 1.69
vertex -8.45 1.59 1.55
vertex -8.27 1.5 1.55
endloop
endfacet
facet normal -1 0 0.07
outer loop
vertex -8.44 3 1.69
vertex -8.45 3.01 1.55
vertex -8.45 1.59 1.55
endloop
endfacet
facet normal -0.98 0 -0.18
outer loop
vertex -8.45 3.01 1.55
vertex -8.33 1.61 0.89
vertex -8.45 1.59 1.55
endloop
endfacet
facet normal -0.44 -0.89 -0.11
outer loop
vertex -8.45 1.59 1.55
vertex -8.33 1.61 0.89
vertex -8.27 1.5 1.55
endloop
endfacet
facet normal -0.98 0 0.19
outer loop
vertex -8.31 2.97 2.35
vertex -8.44 3 1.69
vertex -8.44 1.6 1.69
endloop
endfacet
facet normal -0.49 -0.87 0.03
outer loop
vertex -8.44 1.6 1.69
vertex -8.27 1.5 1.55
vertex -8.28 1.51 1.69
endloop
endfacet
facet normal -0.49 -0.86 0.13
outer loop
vertex -8.31 1.63 2.35
vertex -8.44 1.6 1.69
vertex -8.28 1.51 1.69
endloop
endfacet
facet normal -0.98 0 0.19
outer loop
vertex -8.31 2.97 2.35
vertex -8.44 1.6 1.69
vertex -8.31 1.63 2.35
endloop
endfacet
facet normal -0.46 0.88 0.1
outer loop
vertex -8.25 3.1 1.69
vertex -8.45 3.01 1.55
vertex -8.44 3 1.69
endloop
endfacet
facet normal -0.98 0.01 -0.19
outer loop
vertex -8.45 3.01 1.55
vertex -8.32 2.99 0.89
vertex -8.33 1.61 0.89
endloop
endfacet
facet normal -0.5 0.86 -0.12
outer loop
vertex -8.24 3.13 1.54
vertex -8.32 2.99 0.89
vertex -8.45 3.01 1.55
endloop
endfacet
facet normal -0.49 0.86 0.14
outer loop
vertex -8.25 3.1 1.69
vertex -8.24 3.13 1.54
vertex -8.45 3.01 1.55
endloop
endfacet
facet normal -0.46 0.88 0.13
outer loop
vertex -8.31 2.97 2.35
vertex -8.25 3.1 1.69
vertex -8.44 3 1.69
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -7.48 -0.58 0.73
vertex -7.91 -0.96 0.73
vertex -7.95 -0.55 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -7.48 -0.58 0.73
vertex -7.43 -0.96 0.73
vertex -7.91 -0.96 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -7.62 0 0.73
vertex -7.95 -0.55 0.73
vertex -8.14 0 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -7.62 0 0.73
vertex -7.48 -0.58 0.73
vertex -7.95 -0.55 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -7.62 0 0.73
vertex -8.14 0 0.73
vertex -8.13 0.63 0.73
endloop
endfacet
facet normal -0.05 1 -0.04
outer loop
vertex -7.9 0.01 1.29
vertex -7.7 0 0.81
vertex -7.9 -0.01 0.8
endloop
endfacet
facet normal 0.05 1 0
outer loop
vertex -7.9 0.01 1.29
vertex -7.7 0 1.28
vertex -7.7 0 0.81
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -7.65 0.9 0.73
vertex -8.13 0.63 0.73
vertex -8.25 0.9 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -7.62 0 0.73
vertex -8.13 0.63 0.73
vertex -7.72 0.62 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -7.65 0.9 0.73
vertex -7.72 0.62 0.73
vertex -8.13 0.63 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -7.7 1.76 0.73
vertex -8.25 0.9 0.73
vertex -8.19 1.76 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -7.7 1.76 0.73
vertex -7.65 0.9 0.73
vertex -8.25 0.9 0.73
endloop
endfacet
facet normal 0.02 -1 0
outer loop
vertex -7.7 1.11 0.97
vertex -8.2 1.1 0.97
vertex -8.2 1.1 0.83
endloop
endfacet
facet normal 0 -1 0.07
outer loop
vertex -7.7 1.11 0.97
vertex -8.2 1.1 0.83
vertex -7.7 1.1 0.83
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -8.2 1.32 1.48
vertex -8.2 1.1 0.97
vertex -8.2 1.13 1.03
endloop
endfacet
facet normal 0 -0.89 0.45
outer loop
vertex -7.7 1.13 1.03
vertex -8.2 1.13 1.03
vertex -8.2 1.1 0.97
endloop
endfacet
facet normal -0.02 0.92 -0.4
outer loop
vertex -7.7 1.11 0.97
vertex -8.2 1.1 0.97
vertex -8.2 1.32 1.48
endloop
endfacet
facet normal 0.02 -0.95 0.32
outer loop
vertex -7.7 1.13 1.03
vertex -8.2 1.1 0.97
vertex -7.7 1.11 0.97
endloop
endfacet
facet normal -0.02 -0.92 0.39
outer loop
vertex -7.7 1.31 1.48
vertex -8.2 1.32 1.48
vertex -8.2 1.13 1.03
endloop
endfacet
facet normal 0 -0.93 0.37
outer loop
vertex -7.7 1.31 1.48
vertex -8.2 1.13 1.03
vertex -7.7 1.13 1.03
endloop
endfacet
facet normal 0.02 0.83 -0.55
outer loop
vertex -7.7 1.31 1.48
vertex -8.2 1.32 1.48
vertex -8.2 1.36 1.54
endloop
endfacet
facet normal 0.02 0.93 -0.37
outer loop
vertex -7.7 1.11 0.97
vertex -8.2 1.32 1.48
vertex -7.7 1.31 1.48
endloop
endfacet
facet normal -0.89 -0.45 0.03
outer loop
vertex -8.2 1.37 1.67
vertex -8.27 1.5 1.55
vertex -8.2 1.36 1.54
endloop
endfacet
facet normal 0 -1 0.08
outer loop
vertex -7.7 1.36 1.54
vertex -8.2 1.37 1.67
vertex -8.2 1.36 1.54
endloop
endfacet
facet normal 0 0.07 -1
outer loop
vertex -7.7 1.36 1.54
vertex -8.2 1.36 1.54
vertex -8.27 1.5 1.55
endloop
endfacet
facet normal 0 0.77 -0.64
outer loop
vertex -7.7 1.31 1.48
vertex -8.2 1.36 1.54
vertex -7.7 1.36 1.54
endloop
endfacet
facet normal -0.87 -0.49 -0.03
outer loop
vertex -8.28 1.51 1.69
vertex -8.27 1.5 1.55
vertex -8.2 1.37 1.67
endloop
endfacet
facet normal 0 -0.14 0.99
outer loop
vertex -7.7 1.51 1.69
vertex -8.28 1.51 1.69
vertex -8.2 1.37 1.67
endloop
endfacet
facet normal 0 -1 0.08
outer loop
vertex -7.7 1.36 1.54
vertex -7.7 1.37 1.67
vertex -8.2 1.37 1.67
endloop
endfacet
facet normal 0 -0.14 0.99
outer loop
vertex -7.7 1.51 1.69
vertex -8.2 1.37 1.67
vertex -7.7 1.37 1.67
endloop
endfacet
facet normal 0 -0.99 -0.16
outer loop
vertex -8.27 1.5 1.55
vertex -8.33 1.61 0.89
vertex -7.7 1.5 1.55
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -8.33 1.61 0.89
vertex -8.32 2.99 0.89
vertex -5.68 1.6 0.89
endloop
endfacet
facet normal 0 -0.99 -0.16
outer loop
vertex -7.7 1.5 1.55
vertex -8.33 1.61 0.89
vertex -5.68 1.6 0.89
endloop
endfacet
facet normal 0 0.07 -1
outer loop
vertex -7.7 1.36 1.54
vertex -8.27 1.5 1.55
vertex -7.7 1.5 1.55
endloop
endfacet
facet normal 0 -0.98 0.18
outer loop
vertex -8.31 1.63 2.35
vertex -8.28 1.51 1.69
vertex -7.7 1.51 1.69
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -8.31 1.63 2.35
vertex -5.84 2.82 2.35
vertex -8.31 2.97 2.35
endloop
endfacet
facet normal 0 -0.98 0.18
outer loop
vertex -8.31 1.63 2.35
vertex -7.7 1.51 1.69
vertex -6.3 1.51 1.69
endloop
endfacet
facet normal 0 -0.98 0.19
outer loop
vertex -8.31 1.63 2.35
vertex -6.3 1.51 1.69
vertex -5.68 1.64 2.35
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -8.31 1.63 2.35
vertex -5.68 1.64 2.35
vertex -5.84 2.82 2.35
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -7.49 3.72 0.73
vertex -8.2 2.84 0.73
vertex -8.25 3.71 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -7.49 3.72 0.73
vertex -7.55 2.85 0.73
vertex -8.2 2.84 0.73
endloop
endfacet
facet normal -0.01 0.98 -0.21
outer loop
vertex -7.49 3.14 1.54
vertex -8.32 2.99 0.89
vertex -8.24 3.13 1.54
endloop
endfacet
facet normal 0.01 0.97 -0.24
outer loop
vertex -6.75 3.13 1.54
vertex -8.32 2.99 0.89
vertex -7.49 3.14 1.54
endloop
endfacet
facet normal 0 0.98 -0.21
outer loop
vertex -5.67 2.99 0.89
vertex -8.32 2.99 0.89
vertex -6.75 3.13 1.54
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -5.68 1.6 0.89
vertex -8.32 2.99 0.89
vertex -5.67 2.99 0.89
endloop
endfacet
facet normal -0.95 0.3 0
outer loop
vertex -8.25 3.1 1.69
vertex -8.2 3.26 1.66
vertex -8.24 3.13 1.54
endloop
endfacet
facet normal -0.96 0.27 0.02
outer loop
vertex -8.2 3.26 1.66
vertex -8.2 3.27 1.54
vertex -8.24 3.13 1.54
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -8.2 3.27 1.54
vertex -7.49 3.14 1.54
vertex -8.24 3.13 1.54
endloop
endfacet
facet normal -0.01 0.98 0.19
outer loop
vertex -8.31 2.97 2.35
vertex -7.47 3.11 1.69
vertex -8.25 3.1 1.69
endloop
endfacet
facet normal 0 0.19 0.98
outer loop
vertex -8.2 3.26 1.66
vertex -8.25 3.1 1.69
vertex -7.47 3.11 1.69
endloop
endfacet
facet normal 0.06 0.96 0.28
outer loop
vertex -5.84 2.82 2.35
vertex -7.47 3.11 1.69
vertex -8.31 2.97 2.35
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -7.49 3.72 0.73
vertex -8.25 3.71 0.73
vertex -8.17 3.82 0.73
endloop
endfacet
facet normal 0 1 0.07
outer loop
vertex -8.2 3.49 0.97
vertex -7.48 3.5 0.83
vertex -8.2 3.5 0.83
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -8.2 3.29 1.48
vertex -8.2 3.47 1.03
vertex -8.2 3.49 0.97
endloop
endfacet
facet normal 0 0.95 0.32
outer loop
vertex -8.2 3.47 1.03
vertex -7.47 3.49 0.97
vertex -8.2 3.49 0.97
endloop
endfacet
facet normal 0 -0.93 -0.37
outer loop
vertex -8.2 3.49 0.97
vertex -7.46 3.29 1.48
vertex -8.2 3.29 1.48
endloop
endfacet
facet normal 0 1 0.07
outer loop
vertex -8.2 3.49 0.97
vertex -7.47 3.49 0.97
vertex -7.48 3.5 0.83
endloop
endfacet
facet normal 0 -0.93 -0.37
outer loop
vertex -8.2 3.49 0.97
vertex -7.47 3.49 0.97
vertex -7.46 3.29 1.48
endloop
endfacet
facet normal 0 0.93 0.37
outer loop
vertex -8.2 3.29 1.48
vertex -7.47 3.47 1.03
vertex -8.2 3.47 1.03
endloop
endfacet
facet normal 0 0.95 0.32
outer loop
vertex -8.2 3.47 1.03
vertex -7.47 3.47 1.03
vertex -7.47 3.49 0.97
endloop
endfacet
facet normal 0 -0.95 -0.32
outer loop
vertex -8.2 3.29 1.48
vertex -7.47 3.27 1.54
vertex -8.2 3.27 1.54
endloop
endfacet
facet normal 0 0.93 0.37
outer loop
vertex -8.2 3.29 1.48
vertex -7.46 3.29 1.48
vertex -7.47 3.47 1.03
endloop
endfacet
facet normal 0 -0.95 -0.32
outer loop
vertex -8.2 3.29 1.48
vertex -7.46 3.29 1.48
vertex -7.47 3.27 1.54
endloop
endfacet
facet normal 0 1 0.08
outer loop
vertex -8.2 3.27 1.54
vertex -8.2 3.26 1.66
vertex -7.47 3.26 1.66
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -8.2 3.27 1.54
vertex -7.47 3.27 1.54
vertex -7.49 3.14 1.54
endloop
endfacet
facet normal 0 1 0.08
outer loop
vertex -8.2 3.27 1.54
vertex -7.47 3.26 1.66
vertex -7.47 3.27 1.54
endloop
endfacet
facet normal 0 0.2 0.98
outer loop
vertex -8.2 3.26 1.66
vertex -7.47 3.11 1.69
vertex -7.47 3.26 1.66
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -7.49 3.72 0.73
vertex -8.17 3.82 0.73
vertex -7.58 4.09 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -7.48 -0.58 0.73
vertex -6.98 -0.97 0.73
vertex -7.43 -0.96 0.73
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -7.6 -0.66 1.08
vertex -7.6 -0.94 0.81
vertex -7.6 -0.94 1.08
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -7.6 -0.94 1.08
vertex -7.6 -0.94 0.81
vertex -7.2 -0.94 0.81
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -7.6 -0.66 1.08
vertex -7.6 -0.66 0.81
vertex -7.6 -0.94 0.81
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -7.6 -0.94 0.81
vertex -7.6 -0.66 0.81
vertex -7.2 -0.66 0.81
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -7.6 -0.94 0.81
vertex -7.2 -0.66 0.81
vertex -7.2 -0.94 0.81
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -7.6 -0.94 1.08
vertex -7.2 -0.66 1.08
vertex -7.6 -0.66 1.08
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -7.6 -0.94 1.08
vertex -7.2 -0.94 0.81
vertex -7.2 -0.94 1.08
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -7.6 -0.94 1.08
vertex -7.2 -0.94 1.08
vertex -7.2 -0.66 1.08
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -6.95 -0.52 0.73
vertex -6.98 -0.97 0.73
vertex -7.48 -0.58 0.73
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -7.6 -0.66 1.08
vertex -7.2 -0.66 0.81
vertex -7.6 -0.66 0.81
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -7.6 -0.66 1.08
vertex -7.2 -0.66 1.08
vertex -7.2 -0.66 0.81
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -7.7 0 1.26
vertex -7.7 0 0.81
vertex -7.04 0 0.81
endloop
endfacet
facet normal -0.08 -1 0
outer loop
vertex -7.7 0 1.28
vertex -7.7 0 1.26
vertex -7.1 -0.05 1.26
endloop
endfacet
facet normal -0.01 1 0
outer loop
vertex -7.7 0 1.26
vertex -7.7 0 1.28
vertex -7.03 0.01 1.28
endloop
endfacet
facet normal -0.08 -0.99 -0.12
outer loop
vertex -7.7 0 1.26
vertex -7.04 0 0.81
vertex -7.1 -0.05 1.26
endloop
endfacet
facet normal 0.02 0.29 -0.96
outer loop
vertex -7.7 0 1.26
vertex -7.03 0.01 1.28
vertex -7.1 -0.05 1.26
endloop
endfacet
facet normal 0 -0.32 0.95
outer loop
vertex -7.7 0 1.28
vertex -7.1 -0.05 1.26
vertex -7.03 0.01 1.28
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -7.7 1.31 1.48
vertex -7.7 1.13 1.03
vertex -7.7 1.11 0.97
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -7.7 1.37 1.67
vertex -7.7 1.36 1.54
vertex -7.7 1.5 1.55
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -7.7 1.51 1.69
vertex -7.7 1.37 1.67
vertex -7.7 1.5 1.55
endloop
endfacet
facet normal 0 -1 0.07
outer loop
vertex -7.7 1.51 1.69
vertex -7.7 1.5 1.55
vertex -6.3 1.5 1.55
endloop
endfacet
facet normal 0 -0.99 -0.15
outer loop
vertex -7.7 1.5 1.55
vertex -5.68 1.6 0.89
vertex -6.3 1.5 1.55
endloop
endfacet
facet normal 0 -1 0.07
outer loop
vertex -7.7 1.51 1.69
vertex -6.3 1.5 1.55
vertex -6.3 1.51 1.69
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -6.7 3.72 0.73
vertex -7.55 2.85 0.73
vertex -7.49 3.72 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -6.7 3.72 0.73
vertex -6.89 2.82 0.73
vertex -7.55 2.85 0.73
endloop
endfacet
facet normal 0.99 -0.03 -0.14
outer loop
vertex -7.47 3.11 1.69
vertex -7.49 3.14 1.54
vertex -7.47 3.26 1.66
endloop
endfacet
facet normal 0.99 -0.15 -0.01
outer loop
vertex -7.47 3.26 1.66
vertex -7.49 3.14 1.54
vertex -7.47 3.27 1.54
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -7.47 3.27 1.54
vertex -6.75 3.13 1.54
vertex -7.49 3.14 1.54
endloop
endfacet
facet normal 0 0.2 0.98
outer loop
vertex -7.47 3.26 1.66
vertex -7.47 3.11 1.69
vertex -6.75 3.11 1.69
endloop
endfacet
facet normal 0 0.92 0.4
outer loop
vertex -5.84 2.82 2.35
vertex -6.75 3.11 1.69
vertex -7.47 3.11 1.69
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -6.93 4.09 0.73
vertex -7.49 3.72 0.73
vertex -7.58 4.09 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -6.93 4.09 0.73
vertex -6.7 3.72 0.73
vertex -7.49 3.72 0.73
endloop
endfacet
facet normal 0 1 0.07
outer loop
vertex -7.47 3.49 0.97
vertex -6.75 3.5 0.83
vertex -7.48 3.5 0.83
endloop
endfacet
facet normal 0.94 0.31 0.1
outer loop
vertex -7.46 3.29 1.48
vertex -7.47 3.49 0.97
vertex -7.47 3.47 1.03
endloop
endfacet
facet normal -0.01 0.95 0.32
outer loop
vertex -7.47 3.47 1.03
vertex -6.75 3.5 0.97
vertex -7.47 3.49 0.97
endloop
endfacet
facet normal -0.01 -0.93 -0.36
outer loop
vertex -7.47 3.49 0.97
vertex -6.75 3.28 1.48
vertex -7.46 3.29 1.48
endloop
endfacet
facet normal -0.01 1 0
outer loop
vertex -7.47 3.49 0.97
vertex -6.75 3.5 0.97
vertex -6.75 3.5 0.83
endloop
endfacet
facet normal 0.01 -0.92 -0.4
outer loop
vertex -7.47 3.49 0.97
vertex -6.75 3.5 0.97
vertex -6.75 3.28 1.48
endloop
endfacet
facet normal 0 0.93 0.37
outer loop
vertex -7.46 3.29 1.48
vertex -6.75 3.47 1.03
vertex -7.47 3.47 1.03
endloop
endfacet
facet normal 0 0.89 0.45
outer loop
vertex -7.47 3.47 1.03
vertex -6.75 3.47 1.03
vertex -6.75 3.5 0.97
endloop
endfacet
facet normal 0 -0.95 -0.32
outer loop
vertex -7.46 3.29 1.48
vertex -6.75 3.27 1.54
vertex -7.47 3.27 1.54
endloop
endfacet
facet normal 0.01 0.92 0.39
outer loop
vertex -7.46 3.29 1.48
vertex -6.75 3.28 1.48
vertex -6.75 3.47 1.03
endloop
endfacet
facet normal -0.01 -0.99 -0.16
outer loop
vertex -7.46 3.29 1.48
vertex -6.75 3.28 1.48
vertex -6.75 3.27 1.54
endloop
endfacet
facet normal 0 1 0.08
outer loop
vertex -7.47 3.27 1.54
vertex -7.47 3.26 1.66
vertex -6.75 3.26 1.66
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -7.47 3.27 1.54
vertex -6.75 3.27 1.54
vertex -6.75 3.13 1.54
endloop
endfacet
facet normal 0 1 0.08
outer loop
vertex -7.47 3.27 1.54
vertex -6.75 3.26 1.66
vertex -6.75 3.27 1.54
endloop
endfacet
facet normal 0 0.2 0.98
outer loop
vertex -7.47 3.26 1.66
vertex -6.75 3.11 1.69
vertex -6.75 3.26 1.66
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -6.94 4.73 0.73
vertex -7.58 4.09 0.73
vertex -7.57 4.77 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -6.94 4.73 0.73
vertex -6.93 4.09 0.73
vertex -7.58 4.09 0.73
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -7.37 4.27 1.28
vertex -7.36 4.27 0.81
vertex -7.3 4.27 1.26
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -6.7 4.27 1.26
vertex -7.3 4.27 1.26
vertex -7.36 4.27 0.81
endloop
endfacet
facet normal -1 0 -0.02
outer loop
vertex -7.37 4.27 1.28
vertex -7.36 4.74 0.81
vertex -7.36 4.27 0.81
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -6.7 4.73 0.81
vertex -7.36 4.27 0.81
vertex -7.36 4.74 0.81
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -6.7 4.27 1.26
vertex -7.36 4.27 0.81
vertex -6.7 4.27 0.81
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -6.7 4.73 0.81
vertex -6.7 4.27 0.81
vertex -7.36 4.27 0.81
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -6.7 4.27 1.26
vertex -7.37 4.27 1.28
vertex -7.3 4.27 1.26
endloop
endfacet
facet normal -1 0.02 0
outer loop
vertex -7.37 4.27 1.28
vertex -7.36 4.74 1.28
vertex -7.36 4.74 0.81
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -6.7 4.73 1.28
vertex -7.36 4.74 1.28
vertex -7.37 4.27 1.28
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -6.7 4.27 1.26
vertex -6.7 4.27 1.28
vertex -7.37 4.27 1.28
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -6.7 4.73 1.28
vertex -7.37 4.27 1.28
vertex -6.7 4.27 1.28
endloop
endfacet
facet normal 0.16 0.99 0
outer loop
vertex -7.3 4.73 1.26
vertex -7.36 4.74 0.81
vertex -7.36 4.74 1.28
endloop
endfacet
facet normal 0 1 0.02
outer loop
vertex -6.7 4.73 1.26
vertex -7.36 4.74 0.81
vertex -7.3 4.73 1.26
endloop
endfacet
facet normal 0.02 1 0
outer loop
vertex -6.7 4.73 1.26
vertex -6.7 4.73 0.81
vertex -7.36 4.74 0.81
endloop
endfacet
facet normal 0.01 0.91 -0.41
outer loop
vertex -6.7 4.73 1.28
vertex -7.3 4.73 1.26
vertex -7.36 4.74 1.28
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -6.7 4.73 1.28
vertex -6.7 4.73 1.26
vertex -7.3 4.73 1.26
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -6.57 8.74 0.73
vertex -7.35 8.4 0.73
vertex -7.43 8.73 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -6.57 8.74 0.73
vertex -6.65 8.4 0.73
vertex -7.35 8.4 0.73
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -7.36 9.96 1.28
vertex -7.36 8.62 0.81
vertex -7.36 8.64 1.28
endloop
endfacet
facet normal -0.1 -0.99 0.04
outer loop
vertex -6.6 8.56 1.28
vertex -7.36 8.64 1.28
vertex -7.36 8.62 0.81
endloop
endfacet
facet normal -1 0.01 -0.02
outer loop
vertex -7.36 9.96 1.28
vertex -7.35 9.93 0.81
vertex -7.36 8.62 0.81
endloop
endfacet
facet normal 0.03 0 -1
outer loop
vertex -7.35 9.93 0.81
vertex -7 9.02 0.82
vertex -7.36 8.62 0.81
endloop
endfacet
facet normal 0 0.03 -1
outer loop
vertex -7.36 8.62 0.81
vertex -7 9.02 0.82
vertex -6.7 8.73 0.81
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -7.36 8.62 0.81
vertex -6.7 8.73 0.81
vertex -6.6 8.53 0.81
endloop
endfacet
facet normal -0.12 -0.99 0.06
outer loop
vertex -6.6 8.56 1.28
vertex -7.36 8.62 0.81
vertex -6.6 8.53 0.81
endloop
endfacet
facet normal -1 0 -0.07
outer loop
vertex -7.4 9.75 1.89
vertex -7.36 8.64 1.28
vertex -7.4 8.85 1.89
endloop
endfacet
facet normal 0.13 -0.94 0.33
outer loop
vertex -7.4 8.85 1.89
vertex -7.36 8.64 1.28
vertex -6.7 8.73 1.28
endloop
endfacet
facet normal -1 0 -0.07
outer loop
vertex -7.4 9.75 1.89
vertex -7.36 9.96 1.28
vertex -7.36 8.64 1.28
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -7.36 8.64 1.28
vertex -6.6 8.56 1.28
vertex -6.7 8.73 1.28
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -7.4 9.75 1.89
vertex -7.4 8.85 1.89
vertex -6.6 8.85 1.89
endloop
endfacet
facet normal 0 -0.98 0.19
outer loop
vertex -7.4 8.85 1.89
vertex -6.7 8.73 1.28
vertex -6.6 8.85 1.89
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -6.62 10.19 0.73
vertex -7.43 9.82 0.73
vertex -7.38 10.19 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -6.62 10.19 0.73
vertex -6.57 9.81 0.73
vertex -7.43 9.82 0.73
endloop
endfacet
facet normal -0.1 0.99 -0.07
outer loop
vertex -6.6 10.04 1.28
vertex -7.35 9.93 0.81
vertex -7.36 9.96 1.28
endloop
endfacet
facet normal 0 -0.01 -1
outer loop
vertex -7 9.02 0.82
vertex -7.35 9.93 0.81
vertex -6.69 9.8 0.81
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -6.6 10.07 0.81
vertex -6.69 9.8 0.81
vertex -7.35 9.93 0.81
endloop
endfacet
facet normal -0.18 0.98 0.06
outer loop
vertex -6.6 10.04 1.28
vertex -6.6 10.07 0.81
vertex -7.35 9.93 0.81
endloop
endfacet
facet normal 0 0.95 0.33
outer loop
vertex -7.36 9.96 1.28
vertex -7.4 9.75 1.89
vertex -6.6 9.75 1.89
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -6.6 10.04 1.28
vertex -7.36 9.96 1.28
vertex -6.7 9.87 1.28
endloop
endfacet
facet normal 0.13 0.98 0.17
outer loop
vertex -7.36 9.96 1.28
vertex -6.6 9.75 1.89
vertex -6.7 9.87 1.28
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -7.4 9.75 1.89
vertex -6.6 8.85 1.89
vertex -6.6 9.75 1.89
endloop
endfacet
facet normal 0.02 -1 -0.05
outer loop
vertex -6.89 11 1.01
vertex -7.29 10.99 1.01
vertex -7.29 11 0.81
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -6.89 11 1.01
vertex -7.29 11 0.81
vertex -6.89 11 0.81
endloop
endfacet
facet normal 0 -0.71 0.71
outer loop
vertex -6.93 11 1.02
vertex -7.28 11 1.02
vertex -7.29 10.99 1.01
endloop
endfacet
facet normal 0.02 -0.99 0.1
outer loop
vertex -6.93 11 1.02
vertex -7.29 10.99 1.01
vertex -6.89 11 1.01
endloop
endfacet
facet normal -1 -0.01 -0.07
outer loop
vertex -7.59 13.79 1.32
vertex -7.54 12.25 0.89
vertex -7.57 12.19 1.32
endloop
endfacet
facet normal -0.19 -0.97 -0.15
outer loop
vertex -7.57 12.19 1.32
vertex -7.54 12.25 0.89
vertex -7 12.08 1.3
endloop
endfacet
facet normal -0.99 0.01 -0.14
outer loop
vertex -7.59 13.79 1.32
vertex -7.53 13.76 0.89
vertex -7.54 12.25 0.89
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -7.53 13.76 0.89
vertex -6.47 12.24 0.89
vertex -7.54 12.25 0.89
endloop
endfacet
facet normal -0.01 -0.93 -0.37
outer loop
vertex -7 12.08 1.3
vertex -7.54 12.25 0.89
vertex -6.47 12.24 0.89
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -7.57 13.79 1.47
vertex -7.57 12.19 1.32
vertex -7.57 12.21 1.47
endloop
endfacet
facet normal -0.18 -0.97 0.13
outer loop
vertex -7.57 12.21 1.47
vertex -7.57 12.19 1.32
vertex -7 12.08 1.3
endloop
endfacet
facet normal -0.99 -0.01 0.13
outer loop
vertex -7.57 13.79 1.47
vertex -7.59 13.79 1.32
vertex -7.57 12.19 1.32
endloop
endfacet
facet normal -0.99 -0.01 0.16
outer loop
vertex -7.52 13.73 1.89
vertex -7.57 12.21 1.47
vertex -7.5 12.27 1.9
endloop
endfacet
facet normal -0.21 -0.96 0.17
outer loop
vertex -7.5 12.27 1.9
vertex -7.57 12.21 1.47
vertex -7 12.08 1.44
endloop
endfacet
facet normal -0.99 0 0.12
outer loop
vertex -7.52 13.73 1.89
vertex -7.57 13.79 1.47
vertex -7.57 12.21 1.47
endloop
endfacet
facet normal -0.22 -0.97 0
outer loop
vertex -7.57 12.21 1.47
vertex -7 12.08 1.3
vertex -7 12.08 1.44
endloop
endfacet
facet normal -0.18 0 0.98
outer loop
vertex -7.52 13.73 1.89
vertex -7.5 12.27 1.9
vertex -7.49 12.68 1.9
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -7.49 12.68 1.9
vertex -7.5 12.27 1.9
vertex -6.5 12.27 1.9
endloop
endfacet
facet normal 0 -0.92 0.38
outer loop
vertex -7.5 12.27 1.9
vertex -7 12.08 1.44
vertex -6.5 12.27 1.9
endloop
endfacet
facet normal 0 0.01 1
outer loop
vertex -7.52 13.73 1.89
vertex -7.49 12.68 1.9
vertex -6.48 13.74 1.89
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -7.49 12.68 1.9
vertex -6.5 12.27 1.9
vertex -6.51 12.68 1.9
endloop
endfacet
facet normal 0 0.01 1
outer loop
vertex -7.49 12.68 1.9
vertex -6.51 12.68 1.9
vertex -6.48 13.74 1.89
endloop
endfacet
facet normal -0.22 0.97 -0.1
outer loop
vertex -7 13.92 1.3
vertex -7.53 13.76 0.89
vertex -7.59 13.79 1.32
endloop
endfacet
facet normal 0.01 0.93 -0.37
outer loop
vertex -7 13.92 1.3
vertex -6.46 13.75 0.89
vertex -7.53 13.76 0.89
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -7.53 13.76 0.89
vertex -6.46 13.75 0.89
vertex -6.47 12.24 0.89
endloop
endfacet
facet normal -0.22 0.97 0.03
outer loop
vertex -7 13.92 1.44
vertex -7.59 13.79 1.32
vertex -7.57 13.79 1.47
endloop
endfacet
facet normal -0.22 0.98 0
outer loop
vertex -7 13.92 1.44
vertex -7 13.92 1.3
vertex -7.59 13.79 1.32
endloop
endfacet
facet normal -0.21 0.96 0.16
outer loop
vertex -7.52 13.73 1.89
vertex -7 13.92 1.44
vertex -7.57 13.79 1.47
endloop
endfacet
facet normal -0.01 0.92 0.38
outer loop
vertex -6.48 13.74 1.89
vertex -7 13.92 1.44
vertex -7.52 13.73 1.89
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -7.2 -0.66 1.08
vertex -7.2 -0.94 1.08
vertex -7.2 -0.94 0.81
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -7.2 -0.66 1.08
vertex -7.2 -0.94 0.81
vertex -7.2 -0.66 0.81
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -6.64 0 0.73
vertex -7.05 0 0.73
vertex -6.95 -0.52 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -6.64 0 0.73
vertex -7.05 0 0.73
vertex -6.92 0.31 0.73
endloop
endfacet
facet normal 0.65 -0.76 0
outer loop
vertex -7.1 -0.05 1.26
vertex -7.04 0 0.81
vertex -7.03 0.01 1.28
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -6.75 3.11 1.69
vertex -6.75 3.13 1.54
vertex -6.75 3.26 1.66
endloop
endfacet
facet normal 0 0.99 0.13
outer loop
vertex -6.3 3.11 1.69
vertex -6.75 3.13 1.54
vertex -6.75 3.11 1.69
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -6.75 3.26 1.66
vertex -6.75 3.13 1.54
vertex -6.75 3.27 1.54
endloop
endfacet
facet normal -0.02 0.98 0.2
outer loop
vertex -6.3 3.11 1.69
vertex -6.3 3.14 1.54
vertex -6.75 3.13 1.54
endloop
endfacet
facet normal -0.02 0.97 -0.24
outer loop
vertex -6.3 3.14 1.54
vertex -5.67 2.99 0.89
vertex -6.75 3.13 1.54
endloop
endfacet
facet normal 0 0.92 0.4
outer loop
vertex -5.84 2.82 2.35
vertex -6.3 3.11 1.69
vertex -6.75 3.11 1.69
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -6.75 3.28 1.48
vertex -6.75 3.5 0.97
vertex -6.75 3.47 1.03
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -6.34 4.76 0.73
vertex -6.93 4.09 0.73
vertex -6.94 4.73 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -6.34 4.76 0.73
vertex -6.31 4.1 0.73
vertex -6.93 4.09 0.73
endloop
endfacet
facet normal -0.05 -1 0
outer loop
vertex -6.5 4.26 1.29
vertex -6.7 4.27 1.28
vertex -6.7 4.27 0.81
endloop
endfacet
facet normal -0.05 0 -1
outer loop
vertex -6.5 4.74 0.8
vertex -6.7 4.27 0.81
vertex -6.7 4.73 0.81
endloop
endfacet
facet normal -0.05 -1 0
outer loop
vertex -6.5 4.26 1.29
vertex -6.7 4.27 0.81
vertex -6.5 4.26 0.8
endloop
endfacet
facet normal -0.05 0 -1
outer loop
vertex -6.5 4.74 0.8
vertex -6.5 4.26 0.8
vertex -6.7 4.27 0.81
endloop
endfacet
facet normal -0.05 0 1
outer loop
vertex -6.5 4.74 1.29
vertex -6.7 4.73 1.28
vertex -6.7 4.27 1.28
endloop
endfacet
facet normal -0.05 0 1
outer loop
vertex -6.5 4.74 1.29
vertex -6.7 4.27 1.28
vertex -6.5 4.26 1.29
endloop
endfacet
facet normal -0.05 1 0
outer loop
vertex -6.5 4.74 1.29
vertex -6.7 4.73 0.81
vertex -6.7 4.73 1.28
endloop
endfacet
facet normal -0.05 1 0
outer loop
vertex -6.5 4.74 1.29
vertex -6.5 4.74 0.8
vertex -6.7 4.73 0.81
endloop
endfacet
facet normal -0.03 0 -1
outer loop
vertex -6.69 9.8 0.81
vertex -6.7 8.73 0.81
vertex -7 9.02 0.82
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -6.69 9.8 0.81
vertex -6.6 8.53 0.81
vertex -6.7 8.73 0.81
endloop
endfacet
facet normal -0.84 -0.49 0.23
outer loop
vertex -6.6 8.85 1.89
vertex -6.7 8.73 1.28
vertex -6.6 8.56 1.28
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -6.6 10.07 0.81
vertex -6.6 8.53 0.81
vertex -6.69 9.8 0.81
endloop
endfacet
facet normal -0.84 0.49 0.23
outer loop
vertex -6.7 9.87 1.28
vertex -6.6 9.75 1.89
vertex -6.6 10.04 1.28
endloop
endfacet
facet normal 1 -0.05 -0.05
outer loop
vertex -7 11.85 0.97
vertex -7.01 11.82 0.8
vertex -7 11.96 0.85
endloop
endfacet
facet normal 0.99 -0.12 -0.11
outer loop
vertex -6.98 12.03 0.95
vertex -7 11.85 0.97
vertex -7 11.96 0.85
endloop
endfacet
facet normal 0.99 -0.1 0.07
outer loop
vertex -7 12.08 1.3
vertex -7 11.85 0.97
vertex -6.98 12.03 0.95
endloop
endfacet
facet normal 0.22 -0.98 0
outer loop
vertex -7 12.08 1.44
vertex -7 12.08 1.3
vertex -6.41 12.21 1.32
endloop
endfacet
facet normal 0.22 -0.97 -0.1
outer loop
vertex -7 12.08 1.3
vertex -6.47 12.24 0.89
vertex -6.41 12.21 1.32
endloop
endfacet
facet normal 0.22 -0.97 0.03
outer loop
vertex -7 12.08 1.44
vertex -6.41 12.21 1.32
vertex -6.43 12.21 1.47
endloop
endfacet
facet normal 0.21 -0.96 0.17
outer loop
vertex -6.5 12.27 1.9
vertex -7 12.08 1.44
vertex -6.43 12.21 1.47
endloop
endfacet
facet normal -1 -0.07 -0.07
outer loop
vertex -7 14.11 0.96
vertex -7 14.25 0.8
vertex -6.99 14.09 0.83
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -7 14.11 0.96
vertex -7 14.25 0.95
vertex -7 14.25 0.8
endloop
endfacet
facet normal 0.22 0.97 0
outer loop
vertex -6.43 13.79 1.47
vertex -7 13.92 1.3
vertex -7 13.92 1.44
endloop
endfacet
facet normal 0.19 0.97 -0.15
outer loop
vertex -6.43 13.81 1.32
vertex -6.46 13.75 0.89
vertex -7 13.92 1.3
endloop
endfacet
facet normal 0.18 0.97 0.13
outer loop
vertex -6.43 13.79 1.47
vertex -6.43 13.81 1.32
vertex -7 13.92 1.3
endloop
endfacet
facet normal 0.21 0.97 0.14
outer loop
vertex -6.48 13.74 1.89
vertex -6.43 13.79 1.47
vertex -7 13.92 1.44
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -5.84 -5.9 0.73
vertex -6.17 -6.37 0.73
vertex -6.16 -5.9 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -5.84 -5.9 0.73
vertex -5.83 -6.37 0.73
vertex -6.17 -6.37 0.73
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -6.14 -5.87 1.08
vertex -6.14 -6.23 0.8
vertex -6.14 -6.23 1.09
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -5.86 -6.23 1.09
vertex -6.14 -6.23 1.09
vertex -6.14 -6.23 0.8
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -6.14 -5.87 1.08
vertex -6.14 -5.87 0.81
vertex -6.14 -6.23 0.8
endloop
endfacet
facet normal 0 0.03 -1
outer loop
vertex -6.14 -5.87 0.81
vertex -5.86 -6.23 0.8
vertex -6.14 -6.23 0.8
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -5.86 -6.23 1.09
vertex -6.14 -6.23 0.8
vertex -5.86 -6.23 0.8
endloop
endfacet
facet normal 0 0.03 1
outer loop
vertex -6.14 -5.87 1.08
vertex -6.14 -6.23 1.09
vertex -5.86 -6.23 1.09
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -5.84 -5.9 0.73
vertex -6.16 -5.9 0.73
vertex -6.16 -5.42 0.73
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -5.86 -5.87 1.08
vertex -6.14 -5.87 0.81
vertex -6.14 -5.87 1.08
endloop
endfacet
facet normal 0 0.03 -1
outer loop
vertex -6.14 -5.87 0.81
vertex -5.86 -5.88 0.81
vertex -5.86 -6.23 0.8
endloop
endfacet
facet normal 0.04 1 -0.04
outer loop
vertex -5.86 -5.87 1.08
vertex -5.86 -5.88 0.81
vertex -6.14 -5.87 0.81
endloop
endfacet
facet normal 0 0.03 1
outer loop
vertex -6.14 -5.87 1.08
vertex -5.86 -6.23 1.09
vertex -5.86 -5.87 1.08
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -5.84 -5.42 0.73
vertex -5.84 -5.9 0.73
vertex -6.16 -5.42 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -6.51 -3.93 0.73
vertex -5.57 -4.84 0.73
vertex -6.52 -4.77 0.73
endloop
endfacet
facet normal -1 0 0.08
outer loop
vertex -6.54 -2.42 0.8
vertex -6.54 -4.79 0.8
vertex -6.51 -4.75 1.19
endloop
endfacet
facet normal 0 -0.99 0.1
outer loop
vertex -6.54 -4.79 0.8
vertex -3.5 -4.76 1.19
vertex -6.51 -4.75 1.19
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -3.46 -4.79 0.8
vertex -6.54 -4.79 0.8
vertex -6.54 -2.42 0.8
endloop
endfacet
facet normal 0 -1 0.08
outer loop
vertex -6.54 -4.79 0.8
vertex -3.46 -4.79 0.8
vertex -3.5 -4.76 1.19
endloop
endfacet
facet normal -0.83 -0.03 0.55
outer loop
vertex -6.51 -4.75 1.19
vertex -6.42 -4.67 1.33
vertex -6.49 -2.66 1.33
endloop
endfacet
facet normal 0 -0.87 0.5
outer loop
vertex -3.5 -4.76 1.19
vertex -6.42 -4.67 1.33
vertex -6.51 -4.75 1.19
endloop
endfacet
facet normal -0.92 -0.02 0.39
outer loop
vertex -6.51 -4.75 1.19
vertex -6.49 -2.66 1.33
vertex -6.55 -2.62 1.19
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -6.5 -2.43 1.19
vertex -6.51 -4.75 1.19
vertex -6.55 -2.62 1.19
endloop
endfacet
facet normal -0.99 0 0.1
outer loop
vertex -6.54 -2.42 0.8
vertex -6.51 -4.75 1.19
vertex -6.5 -2.43 1.19
endloop
endfacet
facet normal -0.85 -0.04 0.53
outer loop
vertex -6.42 -4.67 1.33
vertex -6.36 -4.63 1.43
vertex -6.45 -2.69 1.43
endloop
endfacet
facet normal 0 -0.93 0.37
outer loop
vertex -3.58 -4.67 1.33
vertex -6.36 -4.63 1.43
vertex -6.42 -4.67 1.33
endloop
endfacet
facet normal -0.93 -0.03 0.36
outer loop
vertex -6.42 -4.67 1.33
vertex -6.45 -2.69 1.43
vertex -6.49 -2.66 1.33
endloop
endfacet
facet normal 0 -0.84 0.54
outer loop
vertex -3.5 -4.76 1.19
vertex -3.58 -4.67 1.33
vertex -6.42 -4.67 1.33
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -6.45 -2.69 1.43
vertex -6.36 -4.63 1.43
vertex -6.33 -2.54 1.43
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -6.33 -2.54 1.43
vertex -6.36 -4.63 1.43
vertex -3.63 -4.61 1.43
endloop
endfacet
facet normal 0.01 -0.86 0.52
outer loop
vertex -3.58 -4.67 1.33
vertex -3.63 -4.61 1.43
vertex -6.36 -4.63 1.43
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -5.56 -3.86 0.73
vertex -5.57 -4.84 0.73
vertex -6.51 -3.93 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -6.47 -2.25 0.73
vertex -6.49 -3.31 0.73
vertex -6.6 -3.16 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -6.47 -2.25 0.73
vertex -5.57 -3.34 0.73
vertex -6.49 -3.31 0.73
endloop
endfacet
facet normal -0.87 0.23 0.44
outer loop
vertex -6.5 -2.43 1.19
vertex -6.55 -2.62 1.19
vertex -6.49 -2.66 1.33
endloop
endfacet
facet normal -0.76 0.47 0.45
outer loop
vertex -6.39 -2.5 1.33
vertex -6.49 -2.66 1.33
vertex -6.45 -2.69 1.43
endloop
endfacet
facet normal -0.62 0.39 0.68
outer loop
vertex -6.5 -2.43 1.19
vertex -6.49 -2.66 1.33
vertex -6.39 -2.5 1.33
endloop
endfacet
facet normal -0.63 0.51 0.58
outer loop
vertex -6.39 -2.5 1.33
vertex -6.45 -2.69 1.43
vertex -6.33 -2.54 1.43
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -5.71 -2.15 0.73
vertex -5.57 -3.34 0.73
vertex -6.47 -2.25 0.73
endloop
endfacet
facet normal 0 1 0.03
outer loop
vertex -3.46 -2.41 0.8
vertex -6.54 -2.42 0.8
vertex -6.5 -2.43 1.19
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -3.46 -2.41 0.8
vertex -3.46 -4.79 0.8
vertex -6.54 -2.42 0.8
endloop
endfacet
facet normal 0 0.89 0.45
outer loop
vertex -6.5 -2.43 1.19
vertex -6.39 -2.5 1.33
vertex -3.6 -2.5 1.33
endloop
endfacet
facet normal 0 1 0.08
outer loop
vertex -3.46 -2.41 0.8
vertex -6.5 -2.43 1.19
vertex -3.5 -2.44 1.19
endloop
endfacet
facet normal 0 0.92 0.4
outer loop
vertex -6.5 -2.43 1.19
vertex -3.6 -2.5 1.33
vertex -3.5 -2.44 1.19
endloop
endfacet
facet normal 0 0.93 0.37
outer loop
vertex -6.39 -2.5 1.33
vertex -6.33 -2.54 1.43
vertex -3.68 -2.53 1.43
endloop
endfacet
facet normal 0 0.96 0.29
outer loop
vertex -6.39 -2.5 1.33
vertex -3.68 -2.53 1.43
vertex -3.6 -2.5 1.33
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -6.33 -2.54 1.43
vertex -3.63 -4.61 1.43
vertex -3.68 -2.53 1.43
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -5.9 -1.85 1.08
vertex -6.3 -1.85 0.81
vertex -6.3 -1.85 1.08
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -5.9 -1.85 1.08
vertex -5.9 -1.85 0.81
vertex -6.3 -1.85 0.81
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -5.82 0.79 0.73
vertex -6.28 0.79 0.73
vertex -6.35 0.9 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -5.81 1.76 0.73
vertex -6.35 0.9 0.73
vertex -6.29 1.76 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -5.75 0.9 0.73
vertex -5.82 0.79 0.73
vertex -6.35 0.9 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -5.81 1.76 0.73
vertex -5.75 0.9 0.73
vertex -6.35 0.9 0.73
endloop
endfacet
facet normal 0.02 -1 0
outer loop
vertex -5.8 1.11 0.97
vertex -6.3 1.1 0.97
vertex -6.3 1.1 0.83
endloop
endfacet
facet normal 0 -1 0.07
outer loop
vertex -5.8 1.11 0.97
vertex -6.3 1.1 0.83
vertex -5.8 1.1 0.83
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -6.3 1.32 1.48
vertex -6.3 1.1 0.97
vertex -6.3 1.13 1.03
endloop
endfacet
facet normal 0 -0.89 0.45
outer loop
vertex -5.8 1.13 1.03
vertex -6.3 1.13 1.03
vertex -6.3 1.1 0.97
endloop
endfacet
facet normal -0.02 0.92 -0.4
outer loop
vertex -5.8 1.11 0.97
vertex -6.3 1.1 0.97
vertex -6.3 1.32 1.48
endloop
endfacet
facet normal 0.02 -0.95 0.32
outer loop
vertex -5.8 1.13 1.03
vertex -6.3 1.1 0.97
vertex -5.8 1.11 0.97
endloop
endfacet
facet normal -0.02 -0.92 0.39
outer loop
vertex -5.8 1.31 1.48
vertex -6.3 1.32 1.48
vertex -6.3 1.13 1.03
endloop
endfacet
facet normal 0 -0.93 0.37
outer loop
vertex -5.8 1.31 1.48
vertex -6.3 1.13 1.03
vertex -5.8 1.13 1.03
endloop
endfacet
facet normal 0.02 0.83 -0.55
outer loop
vertex -5.8 1.31 1.48
vertex -6.3 1.32 1.48
vertex -6.3 1.36 1.54
endloop
endfacet
facet normal 0.02 0.93 -0.37
outer loop
vertex -5.8 1.11 0.97
vertex -6.3 1.32 1.48
vertex -5.8 1.31 1.48
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -6.3 1.37 1.67
vertex -6.3 1.5 1.55
vertex -6.3 1.36 1.54
endloop
endfacet
facet normal 0 -1 0.08
outer loop
vertex -5.8 1.36 1.54
vertex -6.3 1.37 1.67
vertex -6.3 1.36 1.54
endloop
endfacet
facet normal 0 0.07 -1
outer loop
vertex -5.8 1.36 1.54
vertex -6.3 1.36 1.54
vertex -6.3 1.5 1.55
endloop
endfacet
facet normal 0 0.77 -0.64
outer loop
vertex -5.8 1.31 1.48
vertex -6.3 1.36 1.54
vertex -5.8 1.36 1.54
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -6.3 1.51 1.69
vertex -6.3 1.5 1.55
vertex -6.3 1.37 1.67
endloop
endfacet
facet normal 0.01 -0.14 0.99
outer loop
vertex -5.68 1.54 1.69
vertex -6.3 1.51 1.69
vertex -6.3 1.37 1.67
endloop
endfacet
facet normal 0 -1 0.08
outer loop
vertex -5.8 1.36 1.54
vertex -5.8 1.37 1.67
vertex -6.3 1.37 1.67
endloop
endfacet
facet normal 0 -0.12 0.99
outer loop
vertex -5.68 1.54 1.69
vertex -6.3 1.37 1.67
vertex -5.8 1.37 1.67
endloop
endfacet
facet normal 0 0.06 -1
outer loop
vertex -5.8 1.36 1.54
vertex -6.3 1.5 1.55
vertex -5.66 1.54 1.55
endloop
endfacet
facet normal 0.06 -0.99 -0.09
outer loop
vertex -6.3 1.5 1.55
vertex -5.68 1.6 0.89
vertex -5.66 1.54 1.55
endloop
endfacet
facet normal 0.05 -0.99 0.15
outer loop
vertex -5.68 1.64 2.35
vertex -6.3 1.51 1.69
vertex -5.68 1.54 1.69
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -5.75 3.71 0.73
vertex -6.3 2.84 0.73
vertex -6.35 3.71 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -5.75 3.71 0.73
vertex -5.81 2.84 0.73
vertex -6.3 2.84 0.73
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -6.3 3.11 1.69
vertex -6.3 3.26 1.66
vertex -6.3 3.14 1.54
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -6.3 3.26 1.66
vertex -6.3 3.27 1.54
vertex -6.3 3.14 1.54
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -6.3 3.27 1.54
vertex -5.73 3.11 1.54
vertex -6.3 3.14 1.54
endloop
endfacet
facet normal 0.05 0.98 -0.18
outer loop
vertex -5.73 3.11 1.54
vertex -5.67 2.99 0.89
vertex -6.3 3.14 1.54
endloop
endfacet
facet normal 0.01 0.2 0.98
outer loop
vertex -6.3 3.26 1.66
vertex -6.3 3.11 1.69
vertex -5.69 3.07 1.69
endloop
endfacet
facet normal 0.06 0.93 0.37
outer loop
vertex -5.84 2.82 2.35
vertex -5.69 3.07 1.69
vertex -6.3 3.11 1.69
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -5.83 3.82 0.73
vertex -6.35 3.71 0.73
vertex -6.31 4.1 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -5.75 3.71 0.73
vertex -6.35 3.71 0.73
vertex -5.83 3.82 0.73
endloop
endfacet
facet normal 0 1 0.07
outer loop
vertex -6.3 3.49 0.97
vertex -5.8 3.5 0.83
vertex -6.3 3.5 0.83
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -6.3 3.29 1.48
vertex -6.3 3.47 1.03
vertex -6.3 3.49 0.97
endloop
endfacet
facet normal -0.02 0.95 0.32
outer loop
vertex -6.3 3.47 1.03
vertex -5.8 3.5 0.97
vertex -6.3 3.49 0.97
endloop
endfacet
facet normal -0.02 -0.93 -0.37
outer loop
vertex -6.3 3.49 0.97
vertex -5.8 3.28 1.48
vertex -6.3 3.29 1.48
endloop
endfacet
facet normal -0.02 1 0
outer loop
vertex -6.3 3.49 0.97
vertex -5.8 3.5 0.97
vertex -5.8 3.5 0.83
endloop
endfacet
facet normal 0.02 -0.92 -0.4
outer loop
vertex -6.3 3.49 0.97
vertex -5.8 3.5 0.97
vertex -5.8 3.28 1.48
endloop
endfacet
facet normal 0 0.93 0.37
outer loop
vertex -6.3 3.29 1.48
vertex -5.8 3.47 1.03
vertex -6.3 3.47 1.03
endloop
endfacet
facet normal 0 0.89 0.45
outer loop
vertex -6.3 3.47 1.03
vertex -5.8 3.47 1.03
vertex -5.8 3.5 0.97
endloop
endfacet
facet normal 0 -0.95 -0.32
outer loop
vertex -6.3 3.29 1.48
vertex -5.8 3.27 1.54
vertex -6.3 3.27 1.54
endloop
endfacet
facet normal 0.02 0.92 0.39
outer loop
vertex -6.3 3.29 1.48
vertex -5.8 3.28 1.48
vertex -5.8 3.47 1.03
endloop
endfacet
facet normal -0.02 -0.99 -0.16
outer loop
vertex -6.3 3.29 1.48
vertex -5.8 3.28 1.48
vertex -5.8 3.27 1.54
endloop
endfacet
facet normal 0 1 0.08
outer loop
vertex -6.3 3.27 1.54
vertex -6.3 3.26 1.66
vertex -5.8 3.26 1.66
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -6.3 3.27 1.54
vertex -5.8 3.27 1.54
vertex -5.73 3.11 1.54
endloop
endfacet
facet normal 0 1 0.08
outer loop
vertex -6.3 3.27 1.54
vertex -5.8 3.26 1.66
vertex -5.8 3.27 1.54
endloop
endfacet
facet normal 0 0.16 0.99
outer loop
vertex -6.3 3.26 1.66
vertex -5.69 3.07 1.69
vertex -5.8 3.26 1.66
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -6.5 4.26 1.29
vertex -6.5 4.26 0.8
vertex -6.5 4.74 0.8
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -6.5 4.26 1.29
vertex -6.5 4.74 0.8
vertex -6.5 4.74 1.29
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -6.6 10.04 1.28
vertex -6.6 8.56 1.28
vertex -6.6 8.53 0.81
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -6.6 10.04 1.28
vertex -6.6 8.53 0.81
vertex -6.6 10.07 0.81
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -6.6 9.75 1.89
vertex -6.6 8.85 1.89
vertex -6.6 8.56 1.28
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -6.6 9.75 1.89
vertex -6.6 8.56 1.28
vertex -6.6 10.04 1.28
endloop
endfacet
facet normal 0.99 -0.01 -0.14
outer loop
vertex -6.41 12.21 1.32
vertex -6.47 12.24 0.89
vertex -6.46 13.75 0.89
endloop
endfacet
facet normal 0.99 0.01 0.13
outer loop
vertex -6.43 12.21 1.47
vertex -6.41 12.21 1.32
vertex -6.43 13.81 1.32
endloop
endfacet
facet normal 1 0.01 -0.07
outer loop
vertex -6.41 12.21 1.32
vertex -6.46 13.75 0.89
vertex -6.43 13.81 1.32
endloop
endfacet
facet normal 0.99 0 0.16
outer loop
vertex -6.5 12.27 1.9
vertex -6.43 12.21 1.47
vertex -6.43 13.79 1.47
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -6.43 12.21 1.47
vertex -6.43 13.81 1.32
vertex -6.43 13.79 1.47
endloop
endfacet
facet normal 0.18 0 0.98
outer loop
vertex -6.5 12.27 1.9
vertex -6.48 13.74 1.89
vertex -6.51 12.68 1.9
endloop
endfacet
facet normal 0.99 -0.01 0.12
outer loop
vertex -6.5 12.27 1.9
vertex -6.43 13.79 1.47
vertex -6.48 13.74 1.89
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -5.86 -5.87 1.08
vertex -5.86 -6.23 1.09
vertex -5.86 -6.23 0.8
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -5.86 -5.87 1.08
vertex -5.86 -6.23 0.8
vertex -5.86 -5.88 0.81
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -5.56 -3.86 0.73
vertex -5.42 -3.99 0.73
vertex -5.57 -4.84 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -5.42 -3.99 0.73
vertex -5.43 -4.72 0.73
vertex -5.57 -4.84 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -5.71 -2.15 0.73
vertex -5.42 -2.49 0.73
vertex -5.57 -3.34 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -5.4 -3.16 0.73
vertex -5.44 -3.26 0.73
vertex -5.57 -3.34 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -5.42 -2.49 0.73
vertex -5.4 -3.16 0.73
vertex -5.57 -3.34 0.73
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -5.8 1.31 1.48
vertex -5.8 1.13 1.03
vertex -5.8 1.11 0.97
endloop
endfacet
facet normal 0.79 -0.61 0.05
outer loop
vertex -5.8 1.37 1.67
vertex -5.8 1.36 1.54
vertex -5.66 1.54 1.55
endloop
endfacet
facet normal 0.81 -0.58 0.12
outer loop
vertex -5.68 1.54 1.69
vertex -5.8 1.37 1.67
vertex -5.66 1.54 1.55
endloop
endfacet
facet normal 1 -0.01 -0.03
outer loop
vertex -5.66 1.54 1.55
vertex -5.68 1.6 0.89
vertex -5.67 2.99 0.89
endloop
endfacet
facet normal 0.99 0.04 0.14
outer loop
vertex -5.68 1.54 1.69
vertex -5.66 1.54 1.55
vertex -5.73 3.11 1.54
endloop
endfacet
facet normal 1 0.04 0.08
outer loop
vertex -5.66 1.54 1.55
vertex -5.67 2.99 0.89
vertex -5.73 3.11 1.54
endloop
endfacet
facet normal 1 0.01 0
outer loop
vertex -5.68 1.64 2.35
vertex -5.68 1.54 1.69
vertex -5.69 3.07 1.69
endloop
endfacet
facet normal 0.97 0.01 -0.26
outer loop
vertex -5.68 1.54 1.69
vertex -5.73 3.11 1.54
vertex -5.69 3.07 1.69
endloop
endfacet
facet normal 0.96 0.13 0.27
outer loop
vertex -5.68 1.64 2.35
vertex -5.69 3.07 1.69
vertex -5.84 2.82 2.35
endloop
endfacet
facet normal 0.87 0.49 -0.1
outer loop
vertex -5.69 3.07 1.69
vertex -5.73 3.11 1.54
vertex -5.8 3.26 1.66
endloop
endfacet
facet normal 0.92 0.4 0.03
outer loop
vertex -5.8 3.26 1.66
vertex -5.73 3.11 1.54
vertex -5.8 3.27 1.54
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -5.8 3.28 1.48
vertex -5.8 3.5 0.97
vertex -5.8 3.47 1.03
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -4.54 -0.82 0.73
vertex -5.02 -1.11 0.73
vertex -5 -0.82 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -4.54 -0.82 0.73
vertex -4.52 -1.1 0.73
vertex -5.02 -1.11 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -4.25 7.25 0.73
vertex -5.15 5.55 0.73
vertex -5.15 7.25 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -4.25 7.25 0.73
vertex -4.25 5.55 0.73
vertex -5.15 5.55 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -5 5.7 0.84
vertex -5 7.1 0.84
vertex -4.47 7.1 0.84
endloop
endfacet
facet normal -0.02 0.01 -1
outer loop
vertex -5 5.7 0.84
vertex -4.47 7.1 0.84
vertex -4.47 5.7 0.83
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -4.51 -3.93 0.73
vertex -3.49 -4.77 0.73
vertex -4.52 -4.77 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -3.48 -3.94 0.73
vertex -3.49 -4.77 0.73
vertex -4.51 -3.93 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -4.51 -2.43 0.73
vertex -4.49 -3.31 0.73
vertex -4.6 -3.16 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -4.51 -2.43 0.73
vertex -3.51 -3.31 0.73
vertex -4.49 -3.31 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -3.48 -2.44 0.73
vertex -3.51 -3.31 0.73
vertex -4.51 -2.43 0.73
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -4.25 -1.7 1.01
vertex -4.75 -1.7 1.01
vertex -4.75 -1.7 0.81
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -4.25 -1.7 1.01
vertex -4.75 -1.7 0.81
vertex -4.25 -1.7 0.81
endloop
endfacet
facet normal 0.01 -0.7 -0.71
outer loop
vertex -4.26 -1.7 1.02
vertex -4.74 -1.71 1.02
vertex -4.75 -1.7 1.01
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -4.26 -1.7 1.02
vertex -4.75 -1.7 1.01
vertex -4.25 -1.7 1.01
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -4.09 -0.81 0.73
vertex -4.52 -1.1 0.73
vertex -4.54 -0.82 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -4.09 -0.81 0.73
vertex -4.04 -1.12 0.73
vertex -4.52 -1.1 0.73
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -4.75 -1.15 1.01
vertex -4.75 -0.85 0.81
vertex -4.75 -1.15 0.81
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -4.25 -1.15 1.01
vertex -4.75 -1.15 1.01
vertex -4.75 -1.15 0.81
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -4.25 -0.85 0.81
vertex -4.75 -1.15 0.81
vertex -4.75 -0.85 0.81
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -4.25 -1.15 1.01
vertex -4.75 -1.15 0.81
vertex -4.25 -1.15 0.81
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -4.25 -0.85 0.81
vertex -4.25 -1.15 0.81
vertex -4.75 -1.15 0.81
endloop
endfacet
facet normal 0.71 0 -0.71
outer loop
vertex -4.75 -0.85 1.01
vertex -4.74 -1.15 1.02
vertex -4.75 -1.15 1.01
endloop
endfacet
facet normal -0.71 0 0.71
outer loop
vertex -4.74 -0.85 1.02
vertex -4.75 -1.15 1.01
vertex -4.74 -1.15 1.02
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -4.26 -1.15 1.02
vertex -4.74 -1.15 1.02
vertex -4.75 -1.15 1.01
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -4.75 -1.15 1.01
vertex -4.75 -0.85 1.01
vertex -4.75 -0.85 0.81
endloop
endfacet
facet normal -0.71 0 0.71
outer loop
vertex -4.74 -0.85 1.02
vertex -4.75 -0.85 1.01
vertex -4.75 -1.15 1.01
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -4.26 -1.15 1.02
vertex -4.75 -1.15 1.01
vertex -4.25 -1.15 1.01
endloop
endfacet
facet normal 0.71 0 -0.71
outer loop
vertex -4.75 -0.85 1.01
vertex -4.74 -0.85 1.02
vertex -4.74 -1.15 1.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -4.26 -0.85 1.02
vertex -4.74 -0.85 1.02
vertex -4.74 -1.15 1.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -4.26 -0.85 1.02
vertex -4.74 -1.15 1.02
vertex -4.26 -1.15 1.02
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -4.25 -0.85 1.01
vertex -4.75 -0.85 0.81
vertex -4.75 -0.85 1.01
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -4.25 -0.85 1.01
vertex -4.25 -0.85 0.81
vertex -4.75 -0.85 0.81
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -4.26 -0.85 1.02
vertex -4.75 -0.85 1.01
vertex -4.74 -0.85 1.02
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -4.26 -0.85 1.02
vertex -4.25 -0.85 1.01
vertex -4.75 -0.85 1.01
endloop
endfacet
facet normal -1 0.07 0
outer loop
vertex -4.5 5.26 0.86
vertex -4.5 5.24 1.4
vertex -4.47 5.7 0.83
endloop
endfacet
facet normal 0.02 -1 -0.04
outer loop
vertex -4.5 5.26 0.86
vertex -4.09 5.25 1.4
vertex -4.5 5.24 1.4
endloop
endfacet
facet normal -0.04 -0.07 -1
outer loop
vertex -3.93 5.24 0.84
vertex -4.5 5.26 0.86
vertex -4.47 5.7 0.83
endloop
endfacet
facet normal -0.03 -1 0.01
outer loop
vertex -3.93 5.24 0.84
vertex -4.09 5.25 1.4
vertex -4.5 5.26 0.86
endloop
endfacet
facet normal -1 0.05 -0.01
outer loop
vertex -4.47 5.7 0.83
vertex -4.5 5.24 1.4
vertex -4.5 5.35 1.87
endloop
endfacet
facet normal -0.21 -0.95 0.22
outer loop
vertex -4.5 5.24 1.4
vertex -4.23 5.27 1.78
vertex -4.5 5.35 1.87
endloop
endfacet
facet normal 0.02 -1 0.06
outer loop
vertex -4.5 5.24 1.4
vertex -4.09 5.25 1.4
vertex -4.23 5.27 1.78
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -4.5 5.35 1.87
vertex -4.5 5.4 2
vertex -4.5 7.4 2
endloop
endfacet
facet normal -0.35 -0.87 0.34
outer loop
vertex -4.23 5.25 1.89
vertex -4.5 5.4 2
vertex -4.5 5.35 1.87
endloop
endfacet
facet normal -1 0 -0.03
outer loop
vertex -4.47 5.7 0.83
vertex -4.5 5.35 1.87
vertex -4.5 7.44 1.87
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -4.5 5.35 1.87
vertex -4.5 7.4 2
vertex -4.5 7.44 1.87
endloop
endfacet
facet normal -0.33 -0.93 -0.17
outer loop
vertex -4.5 5.35 1.87
vertex -4.23 5.27 1.78
vertex -4.23 5.25 1.89
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -4.5 7.4 2
vertex -4.5 5.4 2
vertex -3.78 6.4 2
endloop
endfacet
facet normal -0.34 -0.87 0.35
outer loop
vertex -4.23 5.25 1.89
vertex -4.23 5.29 1.99
vertex -4.5 5.4 2
endloop
endfacet
facet normal 0.03 -0.02 1
outer loop
vertex -3.78 6.4 2
vertex -4.5 5.4 2
vertex -4.23 5.29 1.99
endloop
endfacet
facet normal -1 0 -0.03
outer loop
vertex -4.47 5.7 0.83
vertex -4.5 7.44 1.87
vertex -4.47 7.1 0.84
endloop
endfacet
facet normal -0.01 0.01 -1
outer loop
vertex -3.93 7.55 0.84
vertex -4.47 5.7 0.83
vertex -4.47 7.1 0.84
endloop
endfacet
facet normal 0.02 0 -1
outer loop
vertex -3.93 7.55 0.84
vertex -3.93 5.24 0.84
vertex -4.47 5.7 0.83
endloop
endfacet
facet normal -1 -0.07 0
outer loop
vertex -4.47 7.1 0.84
vertex -4.5 7.56 1.4
vertex -4.5 7.54 0.86
endloop
endfacet
facet normal -0.04 0.04 -1
outer loop
vertex -3.93 7.55 0.84
vertex -4.47 7.1 0.84
vertex -4.5 7.54 0.86
endloop
endfacet
facet normal -1 -0.05 -0.01
outer loop
vertex -4.47 7.1 0.84
vertex -4.5 7.44 1.87
vertex -4.5 7.56 1.4
endloop
endfacet
facet normal 0.05 1 -0.04
outer loop
vertex -4.5 7.54 0.86
vertex -4.5 7.56 1.4
vertex -4.1 7.54 1.4
endloop
endfacet
facet normal -0.02 1 0.01
outer loop
vertex -4.5 7.54 0.86
vertex -4.1 7.54 1.4
vertex -3.93 7.55 0.84
endloop
endfacet
facet normal -0.23 0.94 0.24
outer loop
vertex -4.5 7.44 1.87
vertex -4.23 7.53 1.78
vertex -4.5 7.56 1.4
endloop
endfacet
facet normal 0.05 1 0.04
outer loop
vertex -4.23 7.53 1.78
vertex -4.1 7.54 1.4
vertex -4.5 7.56 1.4
endloop
endfacet
facet normal -0.32 0.9 0.28
outer loop
vertex -4.5 7.44 1.87
vertex -4.5 7.4 2
vertex -4.23 7.5 1.99
endloop
endfacet
facet normal -0.36 0.92 -0.17
outer loop
vertex -4.5 7.44 1.87
vertex -4.23 7.55 1.89
vertex -4.23 7.53 1.78
endloop
endfacet
facet normal -0.37 0.83 0.42
outer loop
vertex -4.5 7.44 1.87
vertex -4.23 7.5 1.99
vertex -4.23 7.55 1.89
endloop
endfacet
facet normal 0.03 0.02 1
outer loop
vertex -4.23 7.5 1.99
vertex -4.5 7.4 2
vertex -3.78 6.4 2
endloop
endfacet
facet normal 1 0.1 0
outer loop
vertex -4.49 8.84 0
vertex -4.53 9.25 0.71
vertex -4.49 8.84 0.71
endloop
endfacet
facet normal 0.3 0.95 0
outer loop
vertex -4.14 8.73 0
vertex -4.49 8.84 0
vertex -4.49 8.84 0.71
endloop
endfacet
facet normal 1 0.1 0
outer loop
vertex -4.49 8.84 0
vertex -4.53 9.25 0
vertex -4.53 9.25 0.71
endloop
endfacet
facet normal 0.3 0.95 0
outer loop
vertex -4.14 8.73 0
vertex -4.49 8.84 0.71
vertex -4.14 8.73 0.71
endloop
endfacet
facet normal 0.66 -0.75 0
outer loop
vertex -4.53 9.25 0
vertex -4.26 9.49 0.71
vertex -4.53 9.25 0.71
endloop
endfacet
facet normal 0.66 -0.75 0
outer loop
vertex -4.53 9.25 0
vertex -4.26 9.49 0
vertex -4.26 9.49 0.71
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -4.26 9.49 0
vertex -4.53 9.25 0
vertex -4.2 14 0
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -4.26 9.49 0.71
vertex -4.2 14 0.71
vertex -4.53 9.25 0.71
endloop
endfacet
facet normal 0.89 0.45 0
outer loop
vertex -4.2 14 0
vertex -4.7 15 0
vertex -4.7 15 0.71
endloop
endfacet
facet normal 0.89 0.45 0
outer loop
vertex -4.2 14 0
vertex -4.7 15 0.71
vertex -4.2 14 0.71
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -4.25 -1.15 1.01
vertex -4.25 -1.15 0.81
vertex -4.25 -0.85 0.81
endloop
endfacet
facet normal 0.71 0 0.71
outer loop
vertex -4.25 -0.85 1.01
vertex -4.26 -1.15 1.02
vertex -4.25 -1.15 1.01
endloop
endfacet
facet normal -0.71 0 -0.71
outer loop
vertex -4.26 -0.85 1.02
vertex -4.25 -1.15 1.01
vertex -4.26 -1.15 1.02
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -4.25 -1.15 1.01
vertex -4.25 -0.85 0.81
vertex -4.25 -0.85 1.01
endloop
endfacet
facet normal -0.71 0 -0.71
outer loop
vertex -4.26 -0.85 1.02
vertex -4.25 -0.85 1.01
vertex -4.25 -1.15 1.01
endloop
endfacet
facet normal 0.71 0 0.71
outer loop
vertex -4.25 -0.85 1.01
vertex -4.26 -0.85 1.02
vertex -4.26 -1.15 1.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -3.53 2.9 0.73
vertex -3.79 2.43 0.73
vertex -3.79 2.9 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -3.53 2.9 0.73
vertex -3.53 2.38 0.73
vertex -3.79 2.43 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -3.53 3.42 0.73
vertex -3.79 2.9 0.73
vertex -3.79 3.38 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -3.53 3.42 0.73
vertex -3.53 2.9 0.73
vertex -3.79 2.9 0.73
endloop
endfacet
facet normal 0.01 -1 0.02
outer loop
vertex -2.07 5.27 1.4
vertex -4.09 5.25 1.4
vertex -3.93 5.24 0.84
endloop
endfacet
facet normal 0.01 0 -1
outer loop
vertex -2.07 7.56 0.85
vertex -3.93 5.24 0.84
vertex -3.93 7.55 0.84
endloop
endfacet
facet normal 0.01 -1 0.04
outer loop
vertex -2.07 5.27 1.4
vertex -3.93 5.24 0.84
vertex -2.07 5.25 0.85
endloop
endfacet
facet normal 0.01 0 -1
outer loop
vertex -2.07 7.56 0.85
vertex -2.07 5.25 0.85
vertex -3.93 5.24 0.84
endloop
endfacet
facet normal -0.53 -0.83 -0.15
outer loop
vertex -4.23 5.25 1.89
vertex -4.23 5.27 1.78
vertex -4.09 5.25 1.4
endloop
endfacet
facet normal 0.01 -1 0
outer loop
vertex -2.07 5.27 1.4
vertex -4.23 5.25 1.89
vertex -4.09 5.25 1.4
endloop
endfacet
facet normal -0.01 1 0
outer loop
vertex -4.09 5.25 1.4
vertex -4.23 5.25 1.89
vertex -1.72 5.27 1.89
endloop
endfacet
facet normal -0.01 1 0.01
outer loop
vertex -4.09 5.25 1.4
vertex -1.72 5.27 1.89
vertex -2.07 5.27 1.4
endloop
endfacet
facet normal 0.01 -0.93 0.37
outer loop
vertex -1.72 5.27 1.89
vertex -4.23 5.29 1.99
vertex -4.23 5.25 1.89
endloop
endfacet
facet normal 0.01 -1 -0.01
outer loop
vertex -2.07 5.27 1.4
vertex -1.72 5.27 1.89
vertex -4.23 5.25 1.89
endloop
endfacet
facet normal -0.01 -0.01 1
outer loop
vertex -3.78 6.4 2
vertex -4.23 5.29 1.99
vertex -3.46 5.79 2
endloop
endfacet
facet normal 0 -0.01 1
outer loop
vertex -2.9 5.61 2
vertex -3.46 5.79 2
vertex -4.23 5.29 1.99
endloop
endfacet
facet normal 0 -0.03 1
outer loop
vertex -1.73 5.32 1.99
vertex -2.9 5.61 2
vertex -4.23 5.29 1.99
endloop
endfacet
facet normal 0.01 -0.89 0.45
outer loop
vertex -1.72 5.27 1.89
vertex -1.73 5.32 1.99
vertex -4.23 5.29 1.99
endloop
endfacet
facet normal 0.89 0.46 0
outer loop
vertex -3.46 5.79 2
vertex -3.78 6.4 1.87
vertex -3.78 6.4 2
endloop
endfacet
facet normal 0.88 -0.47 0
outer loop
vertex -3.78 6.4 2
vertex -3.78 6.4 1.87
vertex -3.48 6.97 1.87
endloop
endfacet
facet normal 0.88 0.47 0.01
outer loop
vertex -3.46 5.79 2
vertex -3.48 5.83 1.87
vertex -3.78 6.4 1.87
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -3.73 6.44 1.87
vertex -3.78 6.4 1.87
vertex -3.48 5.83 1.87
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -3.48 6.97 1.87
vertex -3.78 6.4 1.87
vertex -3.73 6.44 1.87
endloop
endfacet
facet normal -0.01 0.01 1
outer loop
vertex -4.23 7.5 1.99
vertex -3.78 6.4 2
vertex -3.46 7.01 2
endloop
endfacet
facet normal 0.89 -0.46 0.01
outer loop
vertex -3.78 6.4 2
vertex -3.48 6.97 1.87
vertex -3.46 7.01 2
endloop
endfacet
facet normal 0 1 0.02
outer loop
vertex -2.07 7.55 1.4
vertex -3.93 7.55 0.84
vertex -4.1 7.54 1.4
endloop
endfacet
facet normal -0.01 1 0.02
outer loop
vertex -2.07 7.55 1.4
vertex -2.07 7.56 0.85
vertex -3.93 7.55 0.84
endloop
endfacet
facet normal -0.51 0.84 -0.15
outer loop
vertex -4.1 7.54 1.4
vertex -4.23 7.53 1.78
vertex -4.23 7.55 1.89
endloop
endfacet
facet normal 0 -1 0.02
outer loop
vertex -2.07 7.55 1.4
vertex -4.23 7.55 1.89
vertex -4.1 7.54 1.4
endloop
endfacet
facet normal 0.01 1 -0.02
outer loop
vertex -4.1 7.54 1.4
vertex -4.23 7.55 1.89
vertex -1.72 7.53 1.89
endloop
endfacet
facet normal 0 1 0.04
outer loop
vertex -4.1 7.54 1.4
vertex -1.72 7.53 1.89
vertex -2.07 7.55 1.4
endloop
endfacet
facet normal 0 0.89 0.45
outer loop
vertex -4.23 7.55 1.89
vertex -4.23 7.5 1.99
vertex -1.73 7.49 1.99
endloop
endfacet
facet normal -0.01 -1 -0.04
outer loop
vertex -2.07 7.55 1.4
vertex -1.72 7.53 1.89
vertex -4.23 7.55 1.89
endloop
endfacet
facet normal 0.01 0.93 0.37
outer loop
vertex -4.23 7.55 1.89
vertex -1.73 7.49 1.99
vertex -1.72 7.53 1.89
endloop
endfacet
facet normal 0 0.01 1
outer loop
vertex -2.91 7.19 2
vertex -4.23 7.5 1.99
vertex -3.46 7.01 2
endloop
endfacet
facet normal 0 0.03 1
outer loop
vertex -1.73 7.49 1.99
vertex -4.23 7.5 1.99
vertex -2.91 7.19 2
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -3.39 8.73 0
vertex -4.14 8.73 0
vertex -4.14 8.73 0.71
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -3.39 8.73 0
vertex -4.14 8.73 0.71
vertex -3.39 8.73 0.71
endloop
endfacet
facet normal 1 -0.01 0
outer loop
vertex -4.26 9.49 0
vertex -4.2 14 0.71
vertex -4.26 9.49 0.71
endloop
endfacet
facet normal 1 -0.01 0
outer loop
vertex -4.26 9.49 0
vertex -4.2 14 0
vertex -4.2 14 0.71
endloop
endfacet
facet normal 0.99 0 0.1
outer loop
vertex -3.46 -4.79 0.8
vertex -3.5 -2.44 1.19
vertex -3.5 -4.76 1.19
endloop
endfacet
facet normal 0.99 0 0.1
outer loop
vertex -3.46 -4.79 0.8
vertex -3.46 -2.41 0.8
vertex -3.5 -2.44 1.19
endloop
endfacet
facet normal 0.86 -0.02 0.51
outer loop
vertex -3.45 -2.62 1.19
vertex -3.58 -4.67 1.33
vertex -3.5 -4.76 1.19
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -3.5 -2.44 1.19
vertex -3.45 -2.62 1.19
vertex -3.5 -4.76 1.19
endloop
endfacet
facet normal 0.89 -0.03 0.46
outer loop
vertex -3.51 -2.66 1.33
vertex -3.63 -4.61 1.43
vertex -3.58 -4.67 1.33
endloop
endfacet
facet normal 0.92 -0.03 0.39
outer loop
vertex -3.45 -2.62 1.19
vertex -3.51 -2.66 1.33
vertex -3.58 -4.67 1.33
endloop
endfacet
facet normal 0.93 -0.04 0.36
outer loop
vertex -3.51 -2.66 1.33
vertex -3.55 -2.68 1.43
vertex -3.63 -4.61 1.43
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -3.68 -2.53 1.43
vertex -3.63 -4.61 1.43
vertex -3.55 -2.68 1.43
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -3.48 -2.44 0.73
vertex -3.4 -3.16 0.73
vertex -3.51 -3.31 0.73
endloop
endfacet
facet normal 0.78 0.44 0.46
outer loop
vertex -3.45 -2.62 1.19
vertex -3.6 -2.5 1.33
vertex -3.51 -2.66 1.33
endloop
endfacet
facet normal 0.75 0.21 0.63
outer loop
vertex -3.45 -2.62 1.19
vertex -3.5 -2.44 1.19
vertex -3.6 -2.5 1.33
endloop
endfacet
facet normal 0.69 0.6 0.4
outer loop
vertex -3.51 -2.66 1.33
vertex -3.68 -2.53 1.43
vertex -3.55 -2.68 1.43
endloop
endfacet
facet normal 0.67 0.37 0.65
outer loop
vertex -3.51 -2.66 1.33
vertex -3.6 -2.5 1.33
vertex -3.68 -2.53 1.43
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -2.74 0.08 0.73
vertex -3.07 -0.74 0.73
vertex -3.29 -0.55 0.73
endloop
endfacet
facet normal -0.72 -0.7 0
outer loop
vertex -3.09 -0.24 0.99
vertex -3.52 0.2 1.56
vertex -3.52 0.2 0.81
endloop
endfacet
facet normal -0.71 0.7 0
outer loop
vertex -3 0.73 0.99
vertex -3.52 0.2 0.81
vertex -3.52 0.2 1.56
endloop
endfacet
facet normal -0.21 -0.54 -0.81
outer loop
vertex -3.09 -0.24 0.99
vertex -3.52 0.2 0.81
vertex -2.78 -0.09 0.81
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -2.79 0.52 0.81
vertex -2.78 -0.09 0.81
vertex -3.52 0.2 0.81
endloop
endfacet
facet normal -0.22 0.5 -0.84
outer loop
vertex -3 0.73 0.99
vertex -2.79 0.52 0.81
vertex -3.52 0.2 0.81
endloop
endfacet
facet normal -0.71 -0.71 0.01
outer loop
vertex -2.82 -0.51 0.99
vertex -3.52 0.2 1.56
vertex -3.09 -0.24 0.99
endloop
endfacet
facet normal -0.71 -0.71 0.01
outer loop
vertex -2.56 -0.77 0.99
vertex -3.52 0.2 1.56
vertex -2.82 -0.51 0.99
endloop
endfacet
facet normal -0.71 0.71 0.01
outer loop
vertex -2.74 0.99 0.99
vertex -3 0.73 0.99
vertex -3.52 0.2 1.56
endloop
endfacet
facet normal -0.71 0.71 0.01
outer loop
vertex -2.47 1.26 0.99
vertex -2.74 0.99 0.99
vertex -3.52 0.2 1.56
endloop
endfacet
facet normal -0.71 -0.71 0.01
outer loop
vertex -2.25 -1.08 0.99
vertex -3.52 0.2 1.56
vertex -2.56 -0.77 0.99
endloop
endfacet
facet normal -0.71 -0.71 0.01
outer loop
vertex -3.52 0.2 1.56
vertex -2.25 -1.08 0.99
vertex -2.03 -1.3 0.99
endloop
endfacet
facet normal -0.71 0.71 0.01
outer loop
vertex -2.15 1.58 0.99
vertex -2.47 1.26 0.99
vertex -3.52 0.2 1.56
endloop
endfacet
facet normal -0.69 0.72 0.08
outer loop
vertex -3.52 0.2 1.56
vertex -1.91 1.81 0.99
vertex -2.15 1.58 0.99
endloop
endfacet
facet normal -0.71 -0.71 0.01
outer loop
vertex -3.52 0.2 1.56
vertex -2.03 -1.3 0.99
vertex -1.67 -1.66 0.99
endloop
endfacet
facet normal -0.71 -0.71 0.01
outer loop
vertex -3.52 0.2 1.56
vertex -1.67 -1.66 0.99
vertex 0 -3.32 1.56
endloop
endfacet
facet normal -0.71 0.71 0
outer loop
vertex -3.52 0.2 1.56
vertex -1.58 2.14 0.99
vertex -1.91 1.81 0.99
endloop
endfacet
facet normal -0.71 0.71 0
outer loop
vertex -3.52 0.2 1.56
vertex 0 3.72 1.56
vertex -1.58 2.14 0.99
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -3.52 0.2 1.56
vertex 0 -3.32 1.56
vertex 0 -2.36 1.56
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 0 3.72 1.56
vertex -3.52 0.2 1.56
vertex 0 -2.36 1.56
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -2.96 1.26 0.73
vertex -3.31 0.86 0.73
vertex -3.29 0.95 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -2.96 1.26 0.73
vertex -2.74 0.32 0.73
vertex -3.31 0.86 0.73
endloop
endfacet
facet normal 1 0.03 -0.03
outer loop
vertex -3.6 2.9 1.08
vertex -3.59 2.6 1.09
vertex -3.6 2.6 0.8
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -3.6 2.9 1.08
vertex -3.6 2.6 0.8
vertex -3.6 2.9 0.81
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -3.6 3.2 1.09
vertex -3.6 2.9 1.08
vertex -3.6 2.9 0.81
endloop
endfacet
facet normal 1 0.03 -0.03
outer loop
vertex -3.6 3.2 1.09
vertex -3.6 2.9 0.81
vertex -3.61 3.2 0.8
endloop
endfacet
facet normal 0.3 0.92 0.24
outer loop
vertex -2.9 5.61 2
vertex -3.48 5.83 1.87
vertex -3.46 5.79 2
endloop
endfacet
facet normal -0.93 -0.38 0.02
outer loop
vertex -3.49 5.87 2.19
vertex -3.73 6.44 1.87
vertex -3.48 5.83 1.87
endloop
endfacet
facet normal -0.32 -0.94 0.11
outer loop
vertex -2.91 5.67 2.19
vertex -3.49 5.87 2.19
vertex -3.48 5.83 1.87
endloop
endfacet
facet normal 0.29 0.92 0.26
outer loop
vertex -2.9 5.61 2
vertex -2.91 5.65 1.87
vertex -3.48 5.83 1.87
endloop
endfacet
facet normal -0.3 -0.95 0.06
outer loop
vertex -2.91 5.67 2.19
vertex -3.48 5.83 1.87
vertex -2.91 5.65 1.87
endloop
endfacet
facet normal -0.85 -0.36 0.39
outer loop
vertex -3.44 5.86 2.29
vertex -3.73 6.44 2.19
vertex -3.49 5.87 2.19
endloop
endfacet
facet normal -0.29 -0.96 0.05
outer loop
vertex -2.91 5.7 2.29
vertex -3.44 5.86 2.29
vertex -3.49 5.87 2.19
endloop
endfacet
facet normal -0.92 -0.39 0
outer loop
vertex -3.49 5.87 2.19
vertex -3.73 6.44 2.19
vertex -3.73 6.44 1.87
endloop
endfacet
facet normal -0.31 -0.91 0.27
outer loop
vertex -2.91 5.7 2.29
vertex -3.49 5.87 2.19
vertex -2.91 5.67 2.19
endloop
endfacet
facet normal -0.57 -0.29 0.77
outer loop
vertex -3.35 5.92 2.38
vertex -3.69 6.38 2.3
vertex -3.44 5.86 2.29
endloop
endfacet
facet normal -0.12 -0.76 0.63
outer loop
vertex -2.86 5.84 2.38
vertex -3.35 5.92 2.38
vertex -3.44 5.86 2.29
endloop
endfacet
facet normal -0.9 -0.43 0.09
outer loop
vertex -3.44 5.86 2.29
vertex -3.69 6.38 2.3
vertex -3.73 6.44 2.19
endloop
endfacet
facet normal -0.15 -0.5 0.86
outer loop
vertex -2.86 5.84 2.38
vertex -3.44 5.86 2.29
vertex -2.91 5.7 2.29
endloop
endfacet
facet normal -0.6 -0.31 0.74
outer loop
vertex -3.35 5.92 2.38
vertex -3.58 6.36 2.38
vertex -3.69 6.38 2.3
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -2.42 6.36 2.38
vertex -3.58 6.36 2.38
vertex -3.35 5.92 2.38
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -2.54 6.02 2.38
vertex -3.35 5.92 2.38
vertex -2.86 5.84 2.38
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -2.42 6.36 2.38
vertex -3.35 5.92 2.38
vertex -2.54 6.02 2.38
endloop
endfacet
facet normal -0.9 0.43 0
outer loop
vertex -3.73 6.44 2.19
vertex -3.48 6.97 1.87
vertex -3.73 6.44 1.87
endloop
endfacet
facet normal -0.79 0.38 0.49
outer loop
vertex -3.69 6.38 2.3
vertex -3.49 6.94 2.19
vertex -3.73 6.44 2.19
endloop
endfacet
facet normal -0.9 0.43 0.01
outer loop
vertex -3.73 6.44 2.19
vertex -3.49 6.94 2.19
vertex -3.48 6.97 1.87
endloop
endfacet
facet normal -0.54 0.24 0.81
outer loop
vertex -3.58 6.36 2.38
vertex -3.47 6.92 2.29
vertex -3.69 6.38 2.3
endloop
endfacet
facet normal -0.89 0.37 0.25
outer loop
vertex -3.69 6.38 2.3
vertex -3.47 6.92 2.29
vertex -3.49 6.94 2.19
endloop
endfacet
facet normal -0.77 0.25 0.59
outer loop
vertex -3.58 6.36 2.38
vertex -3.43 6.83 2.38
vertex -3.47 6.92 2.29
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -2.55 6.82 2.38
vertex -3.43 6.83 2.38
vertex -3.58 6.36 2.38
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -2.55 6.82 2.38
vertex -3.58 6.36 2.38
vertex -2.42 6.36 2.38
endloop
endfacet
facet normal 0.19 -0.95 0.26
outer loop
vertex -3.46 7.01 2
vertex -3.48 6.97 1.87
vertex -2.79 7.11 1.87
endloop
endfacet
facet normal -0.2 0.98 0.09
outer loop
vertex -2.79 7.11 1.87
vertex -3.48 6.97 1.87
vertex -3.49 6.94 2.19
endloop
endfacet
facet normal 0.23 -0.72 0.66
outer loop
vertex -3.46 7.01 2
vertex -2.79 7.11 1.87
vertex -2.91 7.19 2
endloop
endfacet
facet normal -0.06 0.98 0.21
outer loop
vertex -2.62 6.97 2.3
vertex -3.49 6.94 2.19
vertex -3.47 6.92 2.29
endloop
endfacet
facet normal -0.06 0.93 0.35
outer loop
vertex -2.79 7.11 1.87
vertex -3.49 6.94 2.19
vertex -2.62 7 2.19
endloop
endfacet
facet normal -0.07 0.96 0.26
outer loop
vertex -2.62 6.97 2.3
vertex -2.62 7 2.19
vertex -3.49 6.94 2.19
endloop
endfacet
facet normal -0.03 0.7 0.71
outer loop
vertex -2.62 6.85 2.39
vertex -3.47 6.92 2.29
vertex -3.43 6.83 2.38
endloop
endfacet
facet normal -0.04 0.6 0.8
outer loop
vertex -2.62 6.85 2.39
vertex -2.62 6.97 2.3
vertex -3.47 6.92 2.29
endloop
endfacet
facet normal 0 -0.32 0.95
outer loop
vertex -2.62 6.85 2.39
vertex -3.43 6.83 2.38
vertex -2.55 6.82 2.38
endloop
endfacet
facet normal -0.29 0.96 0
outer loop
vertex -3.06 8.83 0
vertex -3.39 8.73 0
vertex -3.39 8.73 0.71
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 3.39 8.72 0
vertex -3.39 8.73 0
vertex -3.06 8.83 0
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 3.39 8.72 0
vertex 9.34 0.56 -0.02
vertex -3.39 8.73 0
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.34 0.56 -0.02
vertex 9.28 -1.75 -0.02
vertex -3.39 8.73 0
endloop
endfacet
facet normal -0.31 0.95 -0.01
outer loop
vertex -3.06 8.83 0
vertex -3.39 8.73 0.71
vertex -3.05 8.84 0.71
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 3.4 8.73 0.71
vertex -3.05 8.84 0.71
vertex -3.39 8.73 0.71
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 3.4 8.73 0.71
vertex -3.39 8.73 0.71
vertex 9.34 0.55 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.34 0.55 0.73
vertex -3.39 8.73 0.71
vertex 9.28 -1.75 0.73
endloop
endfacet
facet normal -1 -0.01 -0.03
outer loop
vertex -3.28 10.52 0
vertex -3.27 9.49 0
vertex -3.29 9.49 0.71
endloop
endfacet
facet normal -0.66 -0.75 -0.02
outer loop
vertex -3.27 9.49 0
vertex -3.02 9.25 0.71
vertex -3.29 9.49 0.71
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -3.28 10.52 0
vertex -3.02 9.25 0
vertex -3.27 9.49 0
endloop
endfacet
facet normal -0.69 -0.72 0
outer loop
vertex -3.27 9.49 0
vertex -3.02 9.25 0
vertex -3.02 9.25 0.71
endloop
endfacet
facet normal -1 0.01 0
outer loop
vertex -3.28 10.52 0
vertex -3.29 9.49 0.71
vertex -3.28 10.52 0.71
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -3.28 10.52 0.71
vertex -3.29 9.49 0.71
vertex -3.02 9.25 0.71
endloop
endfacet
facet normal -0.06 1 0
outer loop
vertex -2.94 10.54 -0.01
vertex -3.28 10.52 0
vertex -3.28 10.52 0.71
endloop
endfacet
facet normal -0.03 -0.01 -1
outer loop
vertex -2.94 10.54 -0.01
vertex -3.02 9.25 0
vertex -3.28 10.52 0
endloop
endfacet
facet normal -0.03 -0.01 1
outer loop
vertex -2.96 10.54 0.72
vertex -3.28 10.52 0.71
vertex -3.02 9.25 0.71
endloop
endfacet
facet normal -0.06 1 0
outer loop
vertex -2.94 10.54 -0.01
vertex -3.28 10.52 0.71
vertex -2.96 10.54 0.72
endloop
endfacet
facet normal -0.99 -0.11 0
outer loop
vertex -3.34 12.5 0
vertex -3.28 11.97 0
vertex -3.28 11.97 0.71
endloop
endfacet
facet normal -0.54 -0.84 0
outer loop
vertex -3.28 11.97 0
vertex -3.17 11.9 0.71
vertex -3.28 11.97 0.71
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -3.34 12.5 0
vertex -3.17 11.9 0
vertex -3.28 11.97 0
endloop
endfacet
facet normal -0.54 -0.84 0
outer loop
vertex -3.28 11.97 0
vertex -3.17 11.9 0
vertex -3.17 11.9 0.71
endloop
endfacet
facet normal -0.99 -0.11 0
outer loop
vertex -3.34 12.5 0
vertex -3.28 11.97 0.71
vertex -3.34 12.5 0.71
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -3.34 12.5 0.71
vertex -3.28 11.97 0.71
vertex -3.17 11.9 0.71
endloop
endfacet
facet normal -0.93 0.37 0
outer loop
vertex -3.04 13.25 0
vertex -3.34 12.5 0
vertex -3.34 12.5 0.71
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -3.04 13.25 0
vertex -3.17 11.9 0
vertex -3.34 12.5 0
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -3.04 13.25 0.71
vertex -3.34 12.5 0.71
vertex -3.17 11.9 0.71
endloop
endfacet
facet normal -0.93 0.37 0
outer loop
vertex -3.04 13.25 0
vertex -3.34 12.5 0.71
vertex -3.04 13.25 0.71
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -2.37 -4 0.73
vertex -2.67 -4.5 0.73
vertex -2.67 -4 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -2.37 -4 0.73
vertex -2.38 -4.52 0.73
vertex -2.67 -4.5 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -2.38 -3.49 0.73
vertex -2.67 -4 0.73
vertex -2.67 -3.5 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -2.38 -3.49 0.73
vertex -2.37 -4 0.73
vertex -2.67 -4 0.73
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -2.64 -4.06 1.08
vertex -2.64 -3.7 0.8
vertex -2.64 -4.05 0.81
endloop
endfacet
facet normal -0.04 -1 -0.04
outer loop
vertex -2.64 -4.06 1.08
vertex -2.64 -4.05 0.81
vertex -2.36 -4.06 0.81
endloop
endfacet
facet normal 0 -0.03 -1
outer loop
vertex -2.36 -4.06 0.81
vertex -2.64 -4.05 0.81
vertex -2.64 -3.7 0.8
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -2.64 -4.06 1.08
vertex -2.64 -3.7 1.09
vertex -2.64 -3.7 0.8
endloop
endfacet
facet normal 0 -0.03 1
outer loop
vertex -2.36 -4.06 1.08
vertex -2.64 -3.7 1.09
vertex -2.64 -4.06 1.08
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -2.64 -4.06 1.08
vertex -2.36 -4.06 0.81
vertex -2.36 -4.06 1.08
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -2.64 -3.7 1.09
vertex -2.36 -3.7 0.8
vertex -2.64 -3.7 0.8
endloop
endfacet
facet normal 0 -0.03 -1
outer loop
vertex -2.36 -4.06 0.81
vertex -2.64 -3.7 0.8
vertex -2.36 -3.7 0.8
endloop
endfacet
facet normal 0 -0.03 1
outer loop
vertex -2.36 -4.06 1.08
vertex -2.36 -3.7 1.09
vertex -2.64 -3.7 1.09
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -2.64 -3.7 1.09
vertex -2.36 -3.7 1.09
vertex -2.36 -3.7 0.8
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -2.49 -0.15 0.73
vertex -2.79 -1.05 0.73
vertex -3.07 -0.74 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -2.18 -0.49 0.73
vertex -2.79 -1.05 0.73
vertex -2.49 -0.15 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -2.49 -0.15 0.73
vertex -3.07 -0.74 0.73
vertex -2.74 0.08 0.73
endloop
endfacet
facet normal -0.71 -0.71 0
outer loop
vertex -2.83 -0.5 0.81
vertex -2.82 -0.51 0.99
vertex -3.09 -0.24 0.99
endloop
endfacet
facet normal -0.1 -0.99 -0.05
outer loop
vertex -2.33 -0.55 0.8
vertex -2.82 -0.51 0.99
vertex -2.83 -0.5 0.81
endloop
endfacet
facet normal -0.52 0.06 -0.85
outer loop
vertex -2.83 -0.5 0.81
vertex -3.09 -0.24 0.99
vertex -2.78 -0.09 0.81
endloop
endfacet
facet normal -0.02 0 -1
outer loop
vertex -2.78 -0.09 0.81
vertex -2.33 -0.55 0.8
vertex -2.83 -0.5 0.81
endloop
endfacet
facet normal -0.36 -0.36 -0.86
outer loop
vertex -2.33 -0.55 0.8
vertex -2.56 -0.77 0.99
vertex -2.82 -0.51 0.99
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -2.79 0.52 0.81
vertex -2.44 0.2 0.81
vertex -2.78 -0.09 0.81
endloop
endfacet
facet normal -0.01 0.01 -1
outer loop
vertex -2.44 0.2 0.81
vertex -2.33 -0.55 0.8
vertex -2.78 -0.09 0.81
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -2.41 0.66 0.73
vertex -2.74 0.32 0.73
vertex -2.96 1.26 0.73
endloop
endfacet
facet normal -0.37 0.37 -0.86
outer loop
vertex -2.74 0.99 0.99
vertex -2.79 0.52 0.81
vertex -3 0.73 0.99
endloop
endfacet
facet normal -0.99 0.11 0
outer loop
vertex -2.74 0.99 0.99
vertex -2.74 0.99 0.8
vertex -2.79 0.52 0.81
endloop
endfacet
facet normal 0.02 -0.02 -1
outer loop
vertex -2.74 0.99 0.8
vertex -2.44 0.79 0.81
vertex -2.79 0.52 0.81
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -2.44 0.79 0.81
vertex -2.44 0.2 0.81
vertex -2.79 0.52 0.81
endloop
endfacet
facet normal -0.71 0.71 0
outer loop
vertex -2.74 0.99 0.8
vertex -2.74 0.99 0.99
vertex -2.47 1.26 0.99
endloop
endfacet
facet normal 0.02 -0.01 -1
outer loop
vertex -2.26 1.08 0.81
vertex -2.44 0.79 0.81
vertex -2.74 0.99 0.8
endloop
endfacet
facet normal -0.1 0.64 -0.76
outer loop
vertex -2.74 0.99 0.8
vertex -2.47 1.26 0.99
vertex -2.26 1.08 0.81
endloop
endfacet
facet normal 1 0.03 -0.03
outer loop
vertex -2.9 3.46 1.08
vertex -2.89 3.1 1.09
vertex -2.9 3.1 0.8
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -2.9 3.46 1.08
vertex -2.9 3.1 0.8
vertex -2.9 3.46 0.81
endloop
endfacet
facet normal -0.43 0.85 0.3
outer loop
vertex -2.9 5.61 2
vertex -2.45 5.88 1.87
vertex -2.91 5.65 1.87
endloop
endfacet
facet normal 0.49 -0.87 0.05
outer loop
vertex -2.43 5.94 2.19
vertex -2.91 5.67 2.19
vertex -2.91 5.65 1.87
endloop
endfacet
facet normal 0.44 -0.89 0.14
outer loop
vertex -2.43 5.94 2.19
vertex -2.91 5.65 1.87
vertex -2.45 5.88 1.87
endloop
endfacet
facet normal -0.46 0.86 0.2
outer loop
vertex -2.45 5.85 2
vertex -2.45 5.88 1.87
vertex -2.9 5.61 2
endloop
endfacet
facet normal 0.01 -0.01 1
outer loop
vertex -1.73 5.32 1.99
vertex -2.45 5.85 2
vertex -2.9 5.61 2
endloop
endfacet
facet normal 0.41 -0.87 0.26
outer loop
vertex -2.49 5.9 2.29
vertex -2.91 5.7 2.29
vertex -2.91 5.67 2.19
endloop
endfacet
facet normal 0.49 -0.87 -0.05
outer loop
vertex -2.49 5.9 2.29
vertex -2.91 5.67 2.19
vertex -2.43 5.94 2.19
endloop
endfacet
facet normal 0.28 -0.59 0.76
outer loop
vertex -2.49 5.9 2.29
vertex -2.86 5.84 2.38
vertex -2.91 5.7 2.29
endloop
endfacet
facet normal 0.28 -0.5 0.82
outer loop
vertex -2.54 6.02 2.38
vertex -2.86 5.84 2.38
vertex -2.49 5.9 2.29
endloop
endfacet
facet normal -0.44 -0.89 0.14
outer loop
vertex -2.91 7.19 2
vertex -2.79 7.11 1.87
vertex -2.47 6.95 1.87
endloop
endfacet
facet normal 0.5 0.87 0.03
outer loop
vertex -2.62 7 2.19
vertex -2.48 6.92 2.19
vertex -2.79 7.11 1.87
endloop
endfacet
facet normal 0.45 0.89 0.1
outer loop
vertex -2.48 6.92 2.19
vertex -2.47 6.95 1.87
vertex -2.79 7.11 1.87
endloop
endfacet
facet normal -0.45 -0.89 0.1
outer loop
vertex -2.91 7.19 2
vertex -2.47 6.95 1.87
vertex -2.46 6.96 2
endloop
endfacet
facet normal 0.01 0.01 1
outer loop
vertex -1.73 7.49 1.99
vertex -2.91 7.19 2
vertex -2.46 6.96 2
endloop
endfacet
facet normal 0.48 0.84 0.23
outer loop
vertex -2.48 6.92 2.19
vertex -2.62 7 2.19
vertex -2.62 6.97 2.3
endloop
endfacet
facet normal 0.35 0.56 0.75
outer loop
vertex -2.55 6.82 2.38
vertex -2.62 6.97 2.3
vertex -2.62 6.85 2.39
endloop
endfacet
facet normal 0.5 0.82 0.27
outer loop
vertex -2.5 6.9 2.29
vertex -2.48 6.92 2.19
vertex -2.62 6.97 2.3
endloop
endfacet
facet normal 0.39 0.57 0.72
outer loop
vertex -2.5 6.9 2.29
vertex -2.62 6.97 2.3
vertex -2.55 6.82 2.38
endloop
endfacet
facet normal -1 0.09 0.01
outer loop
vertex -3.02 9.25 0
vertex -3.06 8.83 0
vertex -3.05 8.84 0.71
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 3.02 9.25 0
vertex -3.06 8.83 0
vertex -3.02 9.25 0
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 3.02 9.25 0
vertex 3.06 8.83 0
vertex -3.06 8.83 0
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 3.39 8.72 0
vertex -3.06 8.83 0
vertex 3.06 8.83 0
endloop
endfacet
facet normal -1 0.07 0
outer loop
vertex -3.02 9.25 0
vertex -3.05 8.84 0.71
vertex -3.02 9.25 0.71
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 3.01 9.25 0.71
vertex -3.02 9.25 0.71
vertex -3.05 8.84 0.71
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 3.01 9.25 0.71
vertex -3.05 8.84 0.71
vertex 3.06 8.83 0.71
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 3.4 8.73 0.71
vertex 3.06 8.83 0.71
vertex -3.05 8.84 0.71
endloop
endfacet
facet normal 0 -0.01 -1
outer loop
vertex 2.96 10.54 -0.01
vertex -3.02 9.25 0
vertex -2.94 10.54 -0.01
endloop
endfacet
facet normal 0 -0.01 -1
outer loop
vertex 2.96 10.54 -0.01
vertex 3.02 9.25 0
vertex -3.02 9.25 0
endloop
endfacet
facet normal 0 -0.01 1
outer loop
vertex 2.94 10.54 0.72
vertex -2.96 10.54 0.72
vertex -3.02 9.25 0.71
endloop
endfacet
facet normal 0 -0.01 1
outer loop
vertex 2.94 10.54 0.72
vertex -3.02 9.25 0.71
vertex 3.01 9.25 0.71
endloop
endfacet
facet normal -0.84 -0.54 -0.02
outer loop
vertex -3.1 10.79 0
vertex -2.94 10.54 -0.01
vertex -2.96 10.54 0.72
endloop
endfacet
facet normal 0 0.04 -1
outer loop
vertex 3.1 10.79 0
vertex -2.94 10.54 -0.01
vertex -3.1 10.79 0
endloop
endfacet
facet normal 0 0.04 -1
outer loop
vertex 3.1 10.79 0
vertex 2.96 10.54 -0.01
vertex -2.94 10.54 -0.01
endloop
endfacet
facet normal -0.87 -0.49 0
outer loop
vertex -3.1 10.79 0
vertex -2.96 10.54 0.72
vertex -3.1 10.79 0.71
endloop
endfacet
facet normal 0 0.04 1
outer loop
vertex 3.1 10.79 0.71
vertex -3.1 10.79 0.71
vertex -2.96 10.54 0.72
endloop
endfacet
facet normal 0 0.04 1
outer loop
vertex 3.1 10.79 0.71
vertex -2.96 10.54 0.72
vertex 2.94 10.54 0.72
endloop
endfacet
facet normal -1 -0.01 0
outer loop
vertex -3.11 11.77 0
vertex -3.1 10.79 0
vertex -3.1 10.79 0.71
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 3.11 11.77 0
vertex -3.1 10.79 0
vertex -3.11 11.77 0
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 3.11 11.77 0
vertex 3.1 10.79 0
vertex -3.1 10.79 0
endloop
endfacet
facet normal -1 -0.01 0
outer loop
vertex -3.11 11.77 0
vertex -3.1 10.79 0.71
vertex -3.11 11.77 0.71
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 3.11 11.77 0.71
vertex -3.11 11.77 0.71
vertex -3.1 10.79 0.71
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 3.11 11.77 0.71
vertex -3.1 10.79 0.71
vertex 3.1 10.79 0.71
endloop
endfacet
facet normal -0.91 -0.42 0
outer loop
vertex -3.17 11.9 0
vertex -3.11 11.77 0
vertex -3.11 11.77 0.71
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -3.04 13.25 0
vertex -3.11 11.77 0
vertex -3.17 11.9 0
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 3.05 13.25 0
vertex -3.11 11.77 0
vertex -3.04 13.25 0
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 3.05 13.25 0
vertex 3.11 11.77 0
vertex -3.11 11.77 0
endloop
endfacet
facet normal -0.91 -0.42 0
outer loop
vertex -3.17 11.9 0
vertex -3.11 11.77 0.71
vertex -3.17 11.9 0.71
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -3.04 13.25 0.71
vertex -3.17 11.9 0.71
vertex -3.11 11.77 0.71
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 3.05 13.25 0.71
vertex -3.04 13.25 0.71
vertex -3.11 11.77 0.71
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 3.05 13.25 0.71
vertex -3.11 11.77 0.71
vertex 3.11 11.77 0.71
endloop
endfacet
facet normal 0 1 0
outer loop
vertex 3.05 13.25 0
vertex -3.04 13.25 0
vertex -3.04 13.25 0.71
endloop
endfacet
facet normal 0 1 0
outer loop
vertex 3.05 13.25 0
vertex -3.04 13.25 0.71
vertex 3.05 13.25 0.71
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -2.36 -4.06 1.08
vertex -2.36 -4.06 0.81
vertex -2.36 -3.7 0.8
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -2.36 -4.06 1.08
vertex -2.36 -3.7 0.8
vertex -2.36 -3.7 1.09
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -2.18 -0.49 0.73
vertex -1.93 -0.73 0.73
vertex -2.51 -1.31 0.73
endloop
endfacet
facet normal -0.99 -0.15 0
outer loop
vertex -2.25 -1.08 0.99
vertex -2.33 -0.55 0.8
vertex -2.25 -1.08 0.8
endloop
endfacet
facet normal -0.64 -0.77 0
outer loop
vertex -1.62 -1.6 0.81
vertex -2.25 -1.08 0.99
vertex -2.25 -1.08 0.8
endloop
endfacet
facet normal 0.08 1 0
outer loop
vertex -2.25 -1.08 0.8
vertex -2.25 -1.08 0.99
vertex -1.75 -1.12 0.81
endloop
endfacet
facet normal -0.71 -0.71 0
outer loop
vertex -2.03 -1.3 0.99
vertex -2.25 -1.08 0.99
vertex -2.25 -1.08 0.8
endloop
endfacet
facet normal 0.02 0 -1
outer loop
vertex -2.33 -0.55 0.8
vertex -1.75 -1.12 0.81
vertex -2.25 -1.08 0.8
endloop
endfacet
facet normal 0.02 0.01 -1
outer loop
vertex -1.75 -1.12 0.81
vertex -1.62 -1.6 0.81
vertex -2.25 -1.08 0.8
endloop
endfacet
facet normal -0.04 -0.68 -0.74
outer loop
vertex -2.03 -1.3 0.99
vertex -2.25 -1.08 0.8
vertex -1.75 -1.12 0.81
endloop
endfacet
facet normal -0.36 -0.36 -0.86
outer loop
vertex -2.25 -1.08 0.99
vertex -2.56 -0.77 0.99
vertex -2.33 -0.55 0.8
endloop
endfacet
facet normal -0.65 -0.65 -0.4
outer loop
vertex -1.62 -1.6 0.81
vertex -1.67 -1.66 0.99
vertex -2.25 -1.08 0.99
endloop
endfacet
facet normal 0.34 0.34 0.87
outer loop
vertex -1.75 -1.12 0.81
vertex -2.25 -1.08 0.99
vertex -2.03 -1.3 0.99
endloop
endfacet
facet normal 0.04 0.02 -1
outer loop
vertex -2.44 0.2 0.81
vertex -1.99 -0.8 0.81
vertex -2.33 -0.55 0.8
endloop
endfacet
facet normal 0.07 0.05 -1
outer loop
vertex -2.33 -0.55 0.8
vertex -1.99 -0.8 0.81
vertex -1.75 -1.12 0.81
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -0.61 2.31 0.73
vertex 0 -2.47 0.73
vertex -2.49 -0.15 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 0 2.87 0.73
vertex -0.61 2.31 0.73
vertex -2.49 -0.15 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 2.49 -0.15 0.73
vertex -2.49 -0.15 0.73
vertex 0 -2.47 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 2.49 -0.15 0.73
vertex 0 2.87 0.73
vertex -2.49 -0.15 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -2.26 1.08 0.81
vertex -2.44 0.2 0.81
vertex -2.44 0.79 0.81
endloop
endfacet
facet normal -0.04 0.01 -1
outer loop
vertex -1.99 1.24 0.8
vertex -2.44 0.2 0.81
vertex -2.26 1.08 0.81
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -1.75 -1.12 0.81
vertex -1.99 -0.8 0.81
vertex -2.44 0.2 0.81
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -1.11 -1.76 0.81
vertex -1.75 -1.12 0.81
vertex -2.44 0.2 0.81
endloop
endfacet
facet normal 0.02 -0.02 -1
outer loop
vertex -2.44 0.2 0.81
vertex -1.99 1.24 0.8
vertex -0.01 2.93 0.81
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 0 -2.37 0.81
vertex -1.11 -1.76 0.81
vertex -2.44 0.2 0.81
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -2.44 0.2 0.81
vertex -0.01 2.93 0.81
vertex 0 -2.37 0.81
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -1.83 1.23 0.73
vertex -2.06 1.03 0.73
vertex -2.4 1.82 0.73
endloop
endfacet
facet normal -0.39 0.39 -0.84
outer loop
vertex -2.26 1.08 0.81
vertex -2.47 1.26 0.99
vertex -2.15 1.58 0.99
endloop
endfacet
facet normal -0.98 0.21 0
outer loop
vertex -2.26 1.08 0.81
vertex -2.15 1.58 0.99
vertex -2.15 1.58 0.8
endloop
endfacet
facet normal -0.03 -0.01 -1
outer loop
vertex -1.99 1.24 0.8
vertex -2.26 1.08 0.81
vertex -2.15 1.58 0.8
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -2.12 2.11 0.73
vertex -1.54 1.53 0.73
vertex -2.4 1.82 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -1.54 1.53 0.73
vertex -1.83 1.23 0.73
vertex -2.4 1.82 0.73
endloop
endfacet
facet normal 0.07 -1 0
outer loop
vertex -2.15 1.58 0.8
vertex -1.69 1.61 0.81
vertex -2.15 1.58 0.99
endloop
endfacet
facet normal -0.69 0.72 0
outer loop
vertex -1.91 1.81 0.99
vertex -2.15 1.58 0.8
vertex -2.15 1.58 0.99
endloop
endfacet
facet normal 0.02 0.01 -1
outer loop
vertex -2.15 1.58 0.8
vertex -1.69 1.61 0.81
vertex -1.99 1.24 0.8
endloop
endfacet
facet normal -0.03 0.65 -0.76
outer loop
vertex -1.91 1.81 0.99
vertex -1.69 1.61 0.81
vertex -2.15 1.58 0.8
endloop
endfacet
facet normal 0.36 -0.37 0.85
outer loop
vertex -1.69 1.61 0.81
vertex -1.91 1.81 0.99
vertex -2.15 1.58 0.99
endloop
endfacet
facet normal -0.07 -1 0.04
outer loop
vertex -2.07 5.25 0.85
vertex -1.64 5.24 1.4
vertex -2.07 5.27 1.4
endloop
endfacet
facet normal -0.04 0 -1
outer loop
vertex -1.53 7.1 0.83
vertex -2.07 5.25 0.85
vertex -2.07 7.56 0.85
endloop
endfacet
facet normal 0.02 -1 -0.03
outer loop
vertex -1.5 5.26 0.86
vertex -1.64 5.24 1.4
vertex -2.07 5.25 0.85
endloop
endfacet
facet normal 0.02 -0.04 -1
outer loop
vertex -1.53 5.7 0.84
vertex -1.5 5.26 0.86
vertex -2.07 5.25 0.85
endloop
endfacet
facet normal -0.01 -0.01 -1
outer loop
vertex -1.53 7.1 0.83
vertex -1.53 5.7 0.84
vertex -2.07 5.25 0.85
endloop
endfacet
facet normal 0.07 1 -0.05
outer loop
vertex -2.07 5.27 1.4
vertex -1.77 5.27 1.78
vertex -1.64 5.24 1.4
endloop
endfacet
facet normal -0.07 -1 0.05
outer loop
vertex -1.64 5.24 1.4
vertex -1.72 5.27 1.89
vertex -2.07 5.27 1.4
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -2.07 5.27 1.4
vertex -1.72 5.27 1.89
vertex -1.77 5.27 1.78
endloop
endfacet
facet normal -0.92 0.38 0.09
outer loop
vertex -2.22 6.4 2
vertex -2.45 5.88 1.87
vertex -2.45 5.85 2
endloop
endfacet
facet normal 0.93 -0.36 0.01
outer loop
vertex -2.43 5.94 2.19
vertex -2.45 5.88 1.87
vertex -2.24 6.42 1.87
endloop
endfacet
facet normal -0.91 0.36 0.2
outer loop
vertex -2.22 6.4 2
vertex -2.24 6.42 1.87
vertex -2.45 5.88 1.87
endloop
endfacet
facet normal 0.01 0 1
outer loop
vertex -2.22 6.4 2
vertex -2.45 5.85 2
vertex -1.73 5.32 1.99
endloop
endfacet
facet normal 0.86 -0.34 0.38
outer loop
vertex -2.31 6.37 2.3
vertex -2.49 5.9 2.29
vertex -2.43 5.94 2.19
endloop
endfacet
facet normal 0.95 -0.29 0.13
outer loop
vertex -2.27 6.46 2.19
vertex -2.43 5.94 2.19
vertex -2.24 6.42 1.87
endloop
endfacet
facet normal 0.95 -0.29 0.11
outer loop
vertex -2.31 6.37 2.3
vertex -2.43 5.94 2.19
vertex -2.27 6.46 2.19
endloop
endfacet
facet normal 0.65 -0.26 0.71
outer loop
vertex -2.31 6.37 2.3
vertex -2.54 6.02 2.38
vertex -2.49 5.9 2.29
endloop
endfacet
facet normal 0.59 -0.21 0.78
outer loop
vertex -2.42 6.36 2.38
vertex -2.54 6.02 2.38
vertex -2.31 6.37 2.3
endloop
endfacet
facet normal -0.92 -0.39 0.08
outer loop
vertex -2.46 6.96 2
vertex -2.24 6.42 1.87
vertex -2.22 6.4 2
endloop
endfacet
facet normal 0.91 0.42 0.03
outer loop
vertex -2.48 6.92 2.19
vertex -2.27 6.46 2.19
vertex -2.24 6.42 1.87
endloop
endfacet
facet normal -0.91 -0.4 0.1
outer loop
vertex -2.46 6.96 2
vertex -2.47 6.95 1.87
vertex -2.24 6.42 1.87
endloop
endfacet
facet normal 0.92 0.4 0.07
outer loop
vertex -2.48 6.92 2.19
vertex -2.24 6.42 1.87
vertex -2.47 6.95 1.87
endloop
endfacet
facet normal 0.01 0 1
outer loop
vertex -1.73 7.49 1.99
vertex -2.46 6.96 2
vertex -2.22 6.4 2
endloop
endfacet
facet normal 0.02 0 1
outer loop
vertex -1.73 7.49 1.99
vertex -2.22 6.4 2
vertex -1.73 5.32 1.99
endloop
endfacet
facet normal 0.79 0.29 0.53
outer loop
vertex -2.5 6.9 2.29
vertex -2.31 6.37 2.3
vertex -2.27 6.46 2.19
endloop
endfacet
facet normal 0.88 0.4 0.26
outer loop
vertex -2.5 6.9 2.29
vertex -2.27 6.46 2.19
vertex -2.48 6.92 2.19
endloop
endfacet
facet normal 0.57 0.16 0.81
outer loop
vertex -2.55 6.82 2.38
vertex -2.42 6.36 2.38
vertex -2.31 6.37 2.3
endloop
endfacet
facet normal 0.72 0.27 0.64
outer loop
vertex -2.55 6.82 2.38
vertex -2.31 6.37 2.3
vertex -2.5 6.9 2.29
endloop
endfacet
facet normal -0.02 1 0.02
outer loop
vertex -2.07 7.56 0.85
vertex -2.07 7.55 1.4
vertex -1.64 7.56 1.4
endloop
endfacet
facet normal 0.02 0.07 -1
outer loop
vertex -1.5 7.54 0.86
vertex -1.53 7.1 0.83
vertex -2.07 7.56 0.85
endloop
endfacet
facet normal 0.04 1 -0.03
outer loop
vertex -2.07 7.56 0.85
vertex -1.64 7.56 1.4
vertex -1.5 7.54 0.86
endloop
endfacet
facet normal 0.02 -1 -0.07
outer loop
vertex -1.64 7.56 1.4
vertex -1.77 7.53 1.78
vertex -2.07 7.55 1.4
endloop
endfacet
facet normal -0.02 1 0.06
outer loop
vertex -2.07 7.55 1.4
vertex -1.72 7.53 1.89
vertex -1.64 7.56 1.4
endloop
endfacet
facet normal -0.15 -0.99 0.07
outer loop
vertex -2.07 7.55 1.4
vertex -1.77 7.53 1.78
vertex -1.72 7.53 1.89
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -1.3 -1.36 0.73
vertex -1.65 -2.19 0.73
vertex -1.91 -1.92 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -0.83 -1.84 0.73
vertex -1.34 -2.48 0.73
vertex -1.65 -2.19 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -1.06 -1.61 0.73
vertex -1.65 -2.19 0.73
vertex -1.3 -1.36 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -1.06 -1.61 0.73
vertex -0.83 -1.84 0.73
vertex -1.65 -2.19 0.73
endloop
endfacet
facet normal -0.65 -0.65 -0.4
outer loop
vertex -1.32 -2.01 0.99
vertex -1.67 -1.66 0.99
vertex -1.62 -1.6 0.81
endloop
endfacet
facet normal -0.03 -0.01 -1
outer loop
vertex -1.38 -1.43 0.8
vertex -1.62 -1.6 0.81
vertex -1.75 -1.12 0.81
endloop
endfacet
facet normal -0.15 -0.49 -0.86
outer loop
vertex -1.32 -2.01 0.99
vertex -1.62 -1.6 0.81
vertex -1.11 -1.76 0.81
endloop
endfacet
facet normal -0.01 -0.04 -1
outer loop
vertex -1.38 -1.43 0.8
vertex -1.11 -1.76 0.81
vertex -1.62 -1.6 0.81
endloop
endfacet
facet normal -0.71 -0.71 0.01
outer loop
vertex 0 -3.32 1.56
vertex -1.67 -1.66 0.99
vertex -1.32 -2.01 0.99
endloop
endfacet
facet normal 0.16 0.16 0.97
outer loop
vertex -1.75 -1.12 0.81
vertex -1.11 -1.76 0.81
vertex -1.38 -1.43 0.8
endloop
endfacet
facet normal -0.06 0.07 -1
outer loop
vertex -1.99 1.24 0.8
vertex -1.69 1.61 0.81
vertex -0.01 2.93 0.81
endloop
endfacet
facet normal -0.37 0.37 -0.86
outer loop
vertex -1.58 2.14 0.99
vertex -1.69 1.61 0.81
vertex -1.91 1.81 0.99
endloop
endfacet
facet normal -0.98 0.19 0.04
outer loop
vertex -1.58 2.14 0.99
vertex -1.59 2.13 0.81
vertex -1.69 1.61 0.81
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -1.04 2.27 0.81
vertex -1.69 1.61 0.81
vertex -1.59 2.13 0.81
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -1.32 1.9 0.81
vertex -1.69 1.61 0.81
vertex -1.04 2.27 0.81
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -1.69 1.61 0.81
vertex -1.32 1.9 0.81
vertex -0.01 2.93 0.81
endloop
endfacet
facet normal -0.71 0.71 0
outer loop
vertex -1.23 2.49 0.99
vertex -1.59 2.13 0.81
vertex -1.58 2.14 0.99
endloop
endfacet
facet normal -0.14 0.55 -0.82
outer loop
vertex -1.23 2.49 0.99
vertex -1.04 2.27 0.81
vertex -1.59 2.13 0.81
endloop
endfacet
facet normal -0.71 0.71 0
outer loop
vertex 0 3.72 1.56
vertex -1.23 2.49 0.99
vertex -1.58 2.14 0.99
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -1.21 3.02 0.73
vertex -0.97 2.09 0.73
vertex -1.54 2.69 0.73
endloop
endfacet
facet normal 0.96 0.08 0.25
outer loop
vertex -1.53 5.7 0.84
vertex -1.64 5.24 1.4
vertex -1.5 5.26 0.86
endloop
endfacet
facet normal 0.1 0.99 -0.04
outer loop
vertex -1.64 5.24 1.4
vertex -1.77 5.27 1.78
vertex -1.72 5.27 1.89
endloop
endfacet
facet normal 0.99 -0.04 0.16
outer loop
vertex -1.53 5.7 0.84
vertex -1.72 5.27 1.89
vertex -1.64 5.24 1.4
endloop
endfacet
facet normal 1 0 0.1
outer loop
vertex -1.72 7.53 1.89
vertex -1.73 5.32 1.99
vertex -1.72 5.27 1.89
endloop
endfacet
facet normal 0.98 0 0.18
outer loop
vertex -1.53 7.1 0.83
vertex -1.72 5.27 1.89
vertex -1.53 5.7 0.84
endloop
endfacet
facet normal 0.98 0 0.18
outer loop
vertex -1.53 7.1 0.83
vertex -1.72 7.53 1.89
vertex -1.72 5.27 1.89
endloop
endfacet
facet normal 1 0 0.1
outer loop
vertex -1.72 7.53 1.89
vertex -1.73 7.49 1.99
vertex -1.73 5.32 1.99
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -0.85 7.25 0.73
vertex -1.75 5.55 0.73
vertex -1.75 7.25 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -0.85 7.25 0.73
vertex -0.4 5.61 0.73
vertex -1.75 5.55 0.73
endloop
endfacet
facet normal 0.02 -0.01 -1
outer loop
vertex -1 7.1 0.84
vertex -1.53 5.7 0.84
vertex -1.53 7.1 0.83
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -1 7.1 0.84
vertex -1 5.7 0.84
vertex -1.53 5.7 0.84
endloop
endfacet
facet normal 0.96 -0.08 0.25
outer loop
vertex -1.5 7.54 0.86
vertex -1.64 7.56 1.4
vertex -1.53 7.1 0.83
endloop
endfacet
facet normal 0.99 0.03 0.16
outer loop
vertex -1.53 7.1 0.83
vertex -1.64 7.56 1.4
vertex -1.72 7.53 1.89
endloop
endfacet
facet normal -0.1 0.99 0.04
outer loop
vertex -1.64 7.56 1.4
vertex -1.77 7.53 1.78
vertex -1.72 7.53 1.89
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -0.52 -2.15 0.73
vertex -1.11 -2.73 0.73
vertex -1.34 -2.48 0.73
endloop
endfacet
facet normal -0.71 -0.71 -0.04
outer loop
vertex -1.06 -2.26 0.81
vertex -1.05 -2.28 0.99
vertex -1.32 -2.01 0.99
endloop
endfacet
facet normal -0.1 -0.99 -0.1
outer loop
vertex -0.57 -2.31 0.8
vertex -1.05 -2.28 0.99
vertex -1.06 -2.26 0.81
endloop
endfacet
facet normal -0.61 -0.06 -0.79
outer loop
vertex -1.06 -2.26 0.81
vertex -1.32 -2.01 0.99
vertex -1.11 -1.76 0.81
endloop
endfacet
facet normal -0.02 0 -1
outer loop
vertex -1.11 -1.76 0.81
vertex -0.57 -2.31 0.8
vertex -1.06 -2.26 0.81
endloop
endfacet
facet normal -0.71 -0.71 0.01
outer loop
vertex 0 -3.32 1.56
vertex -1.32 -2.01 0.99
vertex -1.05 -2.28 0.99
endloop
endfacet
facet normal -0.36 -0.36 -0.86
outer loop
vertex -0.57 -2.31 0.8
vertex -0.79 -2.54 0.99
vertex -1.05 -2.28 0.99
endloop
endfacet
facet normal -0.71 -0.71 0.01
outer loop
vertex 0 -3.32 1.56
vertex -1.05 -2.28 0.99
vertex -0.79 -2.54 0.99
endloop
endfacet
facet normal 0.02 0.04 -1
outer loop
vertex -1.11 -1.76 0.81
vertex 0 -2.37 0.81
vertex -0.57 -2.31 0.8
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -1.32 1.9 0.81
vertex -1.04 2.27 0.81
vertex -0.01 2.93 0.81
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -1.21 3.02 0.73
vertex -0.61 2.31 0.73
vertex -0.97 2.09 0.73
endloop
endfacet
facet normal -0.38 0.37 -0.85
outer loop
vertex -0.97 2.76 0.99
vertex -1.04 2.27 0.81
vertex -1.23 2.49 0.99
endloop
endfacet
facet normal -0.99 0.14 0
outer loop
vertex -0.97 2.76 0.99
vertex -0.97 2.76 0.81
vertex -1.04 2.27 0.81
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -0.97 2.76 0.81
vertex -0.68 2.55 0.81
vertex -1.04 2.27 0.81
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -0.01 2.93 0.81
vertex -1.04 2.27 0.81
vertex -0.68 2.55 0.81
endloop
endfacet
facet normal -0.72 0.69 0.06
outer loop
vertex 0 3.72 1.56
vertex -0.97 2.76 0.99
vertex -1.23 2.49 0.99
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -1.21 3.02 0.73
vertex -0.39 2.72 0.73
vertex -0.61 2.31 0.73
endloop
endfacet
facet normal -0.69 0.72 0
outer loop
vertex -0.97 2.76 0.81
vertex -0.97 2.76 0.99
vertex -0.7 3.02 0.99
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -0.52 2.83 0.81
vertex -0.68 2.55 0.81
vertex -0.97 2.76 0.81
endloop
endfacet
facet normal -0.1 0.63 -0.77
outer loop
vertex -0.97 2.76 0.81
vertex -0.7 3.02 0.99
vertex -0.52 2.83 0.81
endloop
endfacet
facet normal -0.69 0.72 -0.03
outer loop
vertex 0 3.72 1.56
vertex -0.7 3.02 0.99
vertex -0.97 2.76 0.99
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -0.58 4.7 0.73
vertex -1.06 4.29 0.73
vertex -1.05 4.76 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -0.58 4.7 0.73
vertex -0.74 4.29 0.73
vertex -1.06 4.29 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -0.52 5.16 0.73
vertex -1.05 4.76 0.73
vertex -1.07 5.22 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -0.52 5.16 0.73
vertex -0.58 4.7 0.73
vertex -1.05 4.76 0.73
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -1.04 5 1.08
vertex -1.04 4.6 0.81
vertex -1.04 4.6 1.08
endloop
endfacet
facet normal 0.13 -0.99 0
outer loop
vertex -0.67 4.65 1.09
vertex -1.04 4.6 1.08
vertex -1.04 4.6 0.81
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -1.04 5 1.08
vertex -1.04 5 0.81
vertex -1.04 4.6 0.81
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -1.04 5 0.81
vertex -0.66 4.65 0.81
vertex -1.04 4.6 0.81
endloop
endfacet
facet normal 0.13 -0.99 0
outer loop
vertex -0.67 4.65 1.09
vertex -1.04 4.6 0.81
vertex -0.66 4.65 0.81
endloop
endfacet
facet normal -0.03 0 1
outer loop
vertex -1.04 5 1.08
vertex -1.04 4.6 1.08
vertex -0.67 4.65 1.09
endloop
endfacet
facet normal -0.18 0.98 0
outer loop
vertex -0.5 5.1 1.08
vertex -1.04 5 0.81
vertex -1.04 5 1.08
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -1.04 5 0.81
vertex -0.49 5.1 0.81
vertex -0.66 4.65 0.81
endloop
endfacet
facet normal -0.18 0.98 -0.01
outer loop
vertex -0.5 5.1 1.08
vertex -0.49 5.1 0.81
vertex -1.04 5 0.81
endloop
endfacet
facet normal 0 0.02 1
outer loop
vertex -1.04 5 1.08
vertex -0.67 4.65 1.09
vertex -0.5 5.1 1.08
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -1.13 12.38 -0.02
vertex -1.13 10.4 -0.02
vertex -0.51 10.4 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -1.13 12.38 -0.02
vertex -0.51 10.4 -0.02
vertex -0.49 12.25 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 0 -2.47 0.73
vertex -0.77 -3.05 0.73
vertex -0.52 -2.15 0.73
endloop
endfacet
facet normal -0.99 -0.1 -0.04
outer loop
vertex -0.53 -2.79 0.99
vertex -0.57 -2.31 0.8
vertex -0.52 -2.81 0.81
endloop
endfacet
facet normal -0.7 -0.71 0.04
outer loop
vertex 0 -3.32 0.81
vertex -0.53 -2.79 0.99
vertex -0.52 -2.81 0.81
endloop
endfacet
facet normal -0.01 -0.02 -1
outer loop
vertex -0.57 -2.31 0.8
vertex 0.02 -2.65 0.8
vertex -0.52 -2.81 0.81
endloop
endfacet
facet normal -0.01 -0.01 -1
outer loop
vertex 0.02 -2.65 0.8
vertex 0 -3.32 0.81
vertex -0.52 -2.81 0.81
endloop
endfacet
facet normal -0.36 -0.37 -0.86
outer loop
vertex -0.53 -2.79 0.99
vertex -0.79 -2.54 0.99
vertex -0.57 -2.31 0.8
endloop
endfacet
facet normal -0.69 -0.72 -0.03
outer loop
vertex 0 -3.32 1.56
vertex -0.79 -2.54 0.99
vertex -0.53 -2.79 0.99
endloop
endfacet
facet normal -0.71 -0.71 0
outer loop
vertex 0 -3.32 1.56
vertex -0.53 -2.79 0.99
vertex 0 -3.32 0.81
endloop
endfacet
facet normal 0.02 0.04 -1
outer loop
vertex -0.57 -2.31 0.8
vertex 0 -2.37 0.81
vertex 0.02 -2.65 0.8
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 2.49 -0.15 0.73
vertex 0 -2.47 0.73
vertex -0.61 2.31 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 2.49 -0.15 0.73
vertex -0.61 2.31 0.73
vertex 0 2.87 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -0.01 2.93 0.81
vertex -0.68 2.55 0.81
vertex -0.52 2.83 0.81
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 0 2.87 0.73
vertex -0.39 2.72 0.73
vertex -0.78 3.45 0.73
endloop
endfacet
facet normal -0.41 0.39 -0.82
outer loop
vertex -0.52 2.83 0.81
vertex -0.7 3.02 0.99
vertex -0.44 3.29 0.99
endloop
endfacet
facet normal -0.99 0.17 0
outer loop
vertex -0.52 2.83 0.81
vertex -0.44 3.29 0.99
vertex -0.44 3.29 0.81
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -0.01 2.93 0.81
vertex -0.52 2.83 0.81
vertex -0.44 3.29 0.81
endloop
endfacet
facet normal -0.72 0.69 0.03
outer loop
vertex 0 3.72 1.56
vertex -0.44 3.29 0.99
vertex -0.7 3.02 0.99
endloop
endfacet
facet normal -0.7 0.72 0
outer loop
vertex 0 3.72 0.81
vertex -0.44 3.29 0.81
vertex -0.44 3.29 0.99
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 0 3.72 0.81
vertex -0.01 2.93 0.81
vertex -0.44 3.29 0.81
endloop
endfacet
facet normal -0.7 0.72 0
outer loop
vertex 0 3.72 1.56
vertex 0 3.72 0.81
vertex -0.44 3.29 0.99
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -0.04 5.12 0.73
vertex -0.58 4.7 0.73
vertex -0.52 5.16 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -0.04 5.12 0.73
vertex -0.03 4.65 0.73
vertex -0.58 4.7 0.73
endloop
endfacet
facet normal -0.94 0.35 -0.03
outer loop
vertex -0.5 5.1 1.08
vertex -0.66 4.65 0.81
vertex -0.67 4.65 1.09
endloop
endfacet
facet normal 0.24 -0.97 0.01
outer loop
vertex -0.06 4.8 1.09
vertex -0.67 4.65 1.09
vertex -0.66 4.65 0.81
endloop
endfacet
facet normal -0.93 0.35 -0.03
outer loop
vertex -0.5 5.1 1.08
vertex -0.49 5.1 0.81
vertex -0.66 4.65 0.81
endloop
endfacet
facet normal -0.02 0.01 -1
outer loop
vertex -0.49 5.1 0.81
vertex -0.06 4.8 0.8
vertex -0.66 4.65 0.81
endloop
endfacet
facet normal 0.24 -0.97 0
outer loop
vertex -0.06 4.8 1.09
vertex -0.66 4.65 0.81
vertex -0.06 4.8 0.8
endloop
endfacet
facet normal -0.01 0.02 1
outer loop
vertex -0.5 5.1 1.08
vertex -0.67 4.65 1.09
vertex -0.06 4.8 1.09
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -0.04 5.61 0.73
vertex -0.52 5.16 0.73
vertex -0.4 5.61 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -0.04 5.61 0.73
vertex -0.04 5.12 0.73
vertex -0.52 5.16 0.73
endloop
endfacet
facet normal -0.14 0.99 -0.01
outer loop
vertex -0.06 5.16 1.08
vertex -0.49 5.1 0.81
vertex -0.5 5.1 1.08
endloop
endfacet
facet normal 0 0.03 -1
outer loop
vertex -0.49 5.1 0.81
vertex -0.06 5.15 0.81
vertex -0.06 4.8 0.8
endloop
endfacet
facet normal -0.12 0.99 -0.04
outer loop
vertex -0.06 5.16 1.08
vertex -0.06 5.15 0.81
vertex -0.49 5.1 0.81
endloop
endfacet
facet normal 0 0.03 1
outer loop
vertex -0.5 5.1 1.08
vertex -0.06 4.8 1.09
vertex -0.06 5.16 1.08
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -0.49 12.25 -0.02
vertex -0.51 10.4 -0.02
vertex -0.01 10.4 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -0.01 12.25 0.73
vertex -0.38 10.4 0.73
vertex -0.38 12.25 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -0.01 12.25 0.73
vertex 0.01 10.4 0.73
vertex -0.38 10.4 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -0.49 12.25 -0.02
vertex -0.01 10.4 -0.02
vertex 0.01 12.25 -0.02
endloop
endfacet
facet normal 0.7 -0.71 0
outer loop
vertex 0.52 -2.81 0.99
vertex 0 -3.32 1.56
vertex 0 -3.32 0.81
endloop
endfacet
facet normal 0.02 -0.02 -1
outer loop
vertex 0.02 -2.65 0.8
vertex 0.54 -2.79 0.81
vertex 0 -3.32 0.81
endloop
endfacet
facet normal 0.7 -0.71 0
outer loop
vertex 0.52 -2.81 0.99
vertex 0 -3.32 0.81
vertex 0.54 -2.79 0.81
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 3.52 0.2 1.56
vertex 0 -2.36 1.56
vertex 0 -3.32 1.56
endloop
endfacet
facet normal 0.71 -0.71 0.01
outer loop
vertex 0.79 -2.54 0.99
vertex 0 -3.32 1.56
vertex 0.52 -2.81 0.99
endloop
endfacet
facet normal 0.72 -0.69 0.05
outer loop
vertex 1.06 -2.26 0.99
vertex 0 -3.32 1.56
vertex 0.79 -2.54 0.99
endloop
endfacet
facet normal 0.69 -0.72 -0.05
outer loop
vertex 1.32 -2.01 0.99
vertex 0 -3.32 1.56
vertex 1.06 -2.26 0.99
endloop
endfacet
facet normal 0.71 -0.71 0.01
outer loop
vertex 0 -3.32 1.56
vertex 1.32 -2.01 0.99
vertex 1.68 -1.65 0.99
endloop
endfacet
facet normal 0.71 -0.71 0.01
outer loop
vertex 0 -3.32 1.56
vertex 1.68 -1.65 0.99
vertex 2.03 -1.3 0.99
endloop
endfacet
facet normal 0.71 -0.71 0.01
outer loop
vertex 0 -3.32 1.56
vertex 2.03 -1.3 0.99
vertex 3.52 0.2 1.56
endloop
endfacet
facet normal 0 0.04 -1
outer loop
vertex 0.02 -2.65 0.8
vertex 0 -2.37 0.81
vertex 0.58 -2.3 0.81
endloop
endfacet
facet normal 0.02 0 -1
outer loop
vertex 0.02 -2.65 0.8
vertex 0.58 -2.3 0.81
vertex 0.54 -2.79 0.81
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 0.52 -2.15 0.73
vertex 0.78 -3.05 0.73
vertex 0 -2.47 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -0.01 2.93 0.81
vertex 2.44 0.2 0.81
vertex 0 -2.37 0.81
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 1.11 -1.76 0.81
vertex 0.58 -2.3 0.81
vertex 0 -2.37 0.81
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 1.74 -1.13 0.81
vertex 1.11 -1.76 0.81
vertex 0 -2.37 0.81
endloop
endfacet
facet normal 0.05 -0.07 -1
outer loop
vertex 1.99 -0.8 0.8
vertex 1.74 -1.13 0.81
vertex 0 -2.37 0.81
endloop
endfacet
facet normal -0.02 0.02 -1
outer loop
vertex 2.44 0.2 0.81
vertex 1.99 -0.8 0.8
vertex 0 -2.37 0.81
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 0 3.72 1.56
vertex 0 -2.36 1.56
vertex 3.52 0.2 1.56
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 0.78 3.46 0.73
vertex 0.39 2.72 0.73
vertex 0 2.87 0.73
endloop
endfacet
facet normal -0.02 0 -1
outer loop
vertex 0 3.72 0.81
vertex 0.44 3.29 0.8
vertex -0.01 2.93 0.81
endloop
endfacet
facet normal -0.02 -0.01 -1
outer loop
vertex -0.01 2.93 0.81
vertex 0.51 2.84 0.8
vertex 0.68 2.55 0.8
endloop
endfacet
facet normal -0.11 -0.18 -0.98
outer loop
vertex -0.01 2.93 0.81
vertex 0.68 2.55 0.8
vertex 1.04 2.27 0.81
endloop
endfacet
facet normal -0.02 0 -1
outer loop
vertex 0.51 2.84 0.8
vertex -0.01 2.93 0.81
vertex 0.44 3.29 0.8
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -0.01 2.93 0.81
vertex 1.04 2.27 0.81
vertex 1.33 1.89 0.81
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -0.01 2.93 0.81
vertex 1.33 1.89 0.81
vertex 1.7 1.61 0.81
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -0.01 2.93 0.81
vertex 1.7 1.61 0.81
vertex 2.44 0.2 0.81
endloop
endfacet
facet normal 0.7 0.72 0
outer loop
vertex 0.44 3.29 0.99
vertex 0 3.72 0.81
vertex 0 3.72 1.56
endloop
endfacet
facet normal 0.7 0.72 0
outer loop
vertex 0.44 3.29 0.99
vertex 0.44 3.29 0.8
vertex 0 3.72 0.81
endloop
endfacet
facet normal 0.72 0.69 0.03
outer loop
vertex 0.7 3.02 0.99
vertex 0.44 3.29 0.99
vertex 0 3.72 1.56
endloop
endfacet
facet normal 0.69 0.72 -0.03
outer loop
vertex 0.97 2.76 0.99
vertex 0.7 3.02 0.99
vertex 0 3.72 1.56
endloop
endfacet
facet normal 0.72 0.69 0.06
outer loop
vertex 1.23 2.49 0.99
vertex 0.97 2.76 0.99
vertex 0 3.72 1.56
endloop
endfacet
facet normal 0.7 0.72 -0.04
outer loop
vertex 0 3.72 1.56
vertex 1.59 2.14 0.99
vertex 1.23 2.49 0.99
endloop
endfacet
facet normal 0.71 0.71 0.01
outer loop
vertex 0 3.72 1.56
vertex 1.92 1.81 0.99
vertex 1.59 2.14 0.99
endloop
endfacet
facet normal 0.71 0.71 0.01
outer loop
vertex 0 3.72 1.56
vertex 3.52 0.2 1.56
vertex 1.92 1.81 0.99
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -0.06 5.16 1.08
vertex -0.06 4.8 1.09
vertex -0.06 4.8 0.8
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -0.06 5.16 1.08
vertex -0.06 4.8 0.8
vertex -0.06 5.15 0.81
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 0.01 12.25 -0.02
vertex -0.01 10.4 -0.02
vertex 0.37 10.4 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 0.49 12.25 0.73
vertex 0.01 10.4 0.73
vertex -0.01 12.25 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 0.49 12.25 0.73
vertex 0.51 10.4 0.73
vertex 0.01 10.4 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 0.01 12.25 -0.02
vertex 0.37 10.4 -0.02
vertex 0.37 12.25 -0.02
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 0.7 -4.7 1.08
vertex 0.7 -5.1 0.81
vertex 0.7 -5.1 1.08
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 0.7 -4.7 1.08
vertex 0.7 -4.7 0.81
vertex 0.7 -5.1 0.81
endloop
endfacet
facet normal 0.71 -0.71 0
outer loop
vertex 0.79 -2.54 0.99
vertex 0.52 -2.81 0.99
vertex 0.54 -2.79 0.81
endloop
endfacet
facet normal 0.62 -0.05 -0.79
outer loop
vertex 0.79 -2.54 0.99
vertex 0.54 -2.79 0.81
vertex 0.58 -2.3 0.81
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 1.34 -2.48 0.73
vertex 1.11 -2.73 0.73
vertex 0.52 -2.15 0.73
endloop
endfacet
facet normal 0.01 -0.59 -0.81
outer loop
vertex 1.04 -2.29 0.81
vertex 0.79 -2.54 0.99
vertex 0.58 -2.3 0.81
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 1.11 -1.76 0.81
vertex 1.04 -2.29 0.81
vertex 0.58 -2.3 0.81
endloop
endfacet
facet normal 0.72 -0.69 0.04
outer loop
vertex 1.04 -2.29 0.81
vertex 1.06 -2.26 0.99
vertex 0.79 -2.54 0.99
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 1.65 -2.18 0.73
vertex 1.34 -2.48 0.73
vertex 0.83 -1.83 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 1.06 -1.6 0.73
vertex 1.65 -2.18 0.73
vertex 0.83 -1.83 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 1.21 3.02 0.73
vertex 0.66 2.4 0.73
vertex 0.39 2.72 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 1.54 2.69 0.73
vertex 0.98 2.09 0.73
vertex 0.66 2.4 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 1.21 3.02 0.73
vertex 1.54 2.69 0.73
vertex 0.66 2.4 0.73
endloop
endfacet
facet normal 0.02 0.01 -1
outer loop
vertex 0.68 2.55 0.8
vertex 0.51 2.84 0.8
vertex 0.97 2.76 0.81
endloop
endfacet
facet normal 0.03 0 -1
outer loop
vertex 0.97 2.76 0.81
vertex 1.04 2.27 0.81
vertex 0.68 2.55 0.8
endloop
endfacet
facet normal 0.65 0.1 -0.75
outer loop
vertex 0.44 3.29 0.8
vertex 0.7 3.02 0.99
vertex 0.51 2.84 0.8
endloop
endfacet
facet normal 0.41 0.42 -0.81
outer loop
vertex 0.51 2.84 0.8
vertex 0.7 3.02 0.99
vertex 0.97 2.76 0.99
endloop
endfacet
facet normal 0.17 0.99 0
outer loop
vertex 0.51 2.84 0.8
vertex 0.97 2.76 0.99
vertex 0.97 2.76 0.81
endloop
endfacet
facet normal 0.72 0.69 0
outer loop
vertex 0.44 3.29 0.8
vertex 0.44 3.29 0.99
vertex 0.7 3.02 0.99
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 1.75 7.25 0.73
vertex 0.85 5.55 0.73
vertex 0.85 7.25 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 1.75 7.25 0.73
vertex 1.75 5.55 0.73
vertex 0.85 5.55 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 1.12 12.38 0.73
vertex 0.51 10.4 0.73
vertex 0.49 12.25 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 1.12 12.38 0.73
vertex 1.12 10.4 0.73
vertex 0.51 10.4 0.73
endloop
endfacet
facet normal 0.03 -1 -0.03
outer loop
vertex 1.76 -5.2 1.08
vertex 1.4 -5.21 1.09
vertex 1.4 -5.2 0.8
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex 1.76 -5.2 1.08
vertex 1.4 -5.2 0.8
vertex 1.76 -5.2 0.81
endloop
endfacet
facet normal 0.99 -0.13 -0.09
outer loop
vertex 1.11 -1.76 0.81
vertex 1.06 -2.26 0.99
vertex 1.04 -2.29 0.81
endloop
endfacet
facet normal 0.34 -0.35 -0.88
outer loop
vertex 1.11 -1.76 0.81
vertex 1.32 -2.01 0.99
vertex 1.06 -2.26 0.99
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 1.3 -1.36 0.73
vertex 1.65 -2.18 0.73
vertex 1.06 -1.6 0.73
endloop
endfacet
facet normal 0.34 -0.34 -0.87
outer loop
vertex 1.68 -1.65 0.99
vertex 1.32 -2.01 0.99
vertex 1.11 -1.76 0.81
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 1.74 -1.13 0.81
vertex 1.38 -1.43 0.81
vertex 1.11 -1.76 0.81
endloop
endfacet
facet normal 0.27 -0.92 -0.29
outer loop
vertex 1.68 -1.65 0.99
vertex 1.11 -1.76 0.81
vertex 1.62 -1.61 0.81
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 1.11 -1.76 0.81
vertex 1.74 -1.13 0.81
vertex 1.62 -1.61 0.81
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 1.3 -1.36 0.73
vertex 1.91 -1.92 0.73
vertex 1.65 -2.18 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 1.33 1.89 0.81
vertex 1.04 2.27 0.81
vertex 1.7 1.61 0.81
endloop
endfacet
facet normal 0.63 0.09 -0.77
outer loop
vertex 1.23 2.49 0.99
vertex 1.04 2.27 0.81
vertex 0.97 2.76 0.81
endloop
endfacet
facet normal 0.37 0.38 -0.85
outer loop
vertex 1.59 2.14 0.99
vertex 1.04 2.27 0.81
vertex 1.23 2.49 0.99
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 1.7 1.61 0.81
vertex 1.04 2.27 0.81
vertex 1.58 2.14 0.81
endloop
endfacet
facet normal 0.23 0.97 -0.01
outer loop
vertex 1.59 2.14 0.99
vertex 1.58 2.14 0.81
vertex 1.04 2.27 0.81
endloop
endfacet
facet normal 0.72 0.69 0
outer loop
vertex 1.23 2.49 0.99
vertex 0.97 2.76 0.81
vertex 0.97 2.76 0.99
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 1 5.7 0.84
vertex 1 7.1 0.84
vertex 1.53 7.1 0.84
endloop
endfacet
facet normal -0.02 0.01 -1
outer loop
vertex 1 5.7 0.84
vertex 1.53 7.1 0.84
vertex 1.53 5.7 0.83
endloop
endfacet
facet normal 0.6 -0.72 -0.36
outer loop
vertex 2.25 -1.08 0.8
vertex 1.68 -1.65 0.99
vertex 1.62 -1.61 0.81
endloop
endfacet
facet normal -0.02 0.01 -1
outer loop
vertex 1.74 -1.13 0.81
vertex 2.25 -1.08 0.8
vertex 1.62 -1.61 0.81
endloop
endfacet
facet normal 0.71 -0.71 0
outer loop
vertex 2.25 -1.08 0.8
vertex 2.24 -1.09 0.99
vertex 1.68 -1.65 0.99
endloop
endfacet
facet normal 0.34 -0.34 -0.87
outer loop
vertex 2.24 -1.09 0.99
vertex 2.03 -1.3 0.99
vertex 1.74 -1.13 0.81
endloop
endfacet
facet normal 0.12 -0.12 -0.98
outer loop
vertex 1.99 -0.8 0.8
vertex 2.33 -0.54 0.81
vertex 1.74 -1.13 0.81
endloop
endfacet
facet normal 0.1 -0.99 -0.05
outer loop
vertex 2.24 -1.09 0.99
vertex 1.74 -1.13 0.81
vertex 2.25 -1.08 0.8
endloop
endfacet
facet normal -0.02 0.02 -1
outer loop
vertex 1.74 -1.13 0.81
vertex 2.33 -0.54 0.81
vertex 2.25 -1.08 0.8
endloop
endfacet
facet normal 0.71 -0.71 0.01
outer loop
vertex 3.52 0.2 1.56
vertex 2.03 -1.3 0.99
vertex 2.24 -1.09 0.99
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 2.18 -0.49 0.73
vertex 2.51 -1.31 0.73
vertex 1.93 -0.73 0.73
endloop
endfacet
facet normal 0.03 0 -1
outer loop
vertex 2.44 0.2 0.81
vertex 2.33 -0.54 0.81
vertex 1.99 -0.8 0.8
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 2.4 1.83 0.73
vertex 1.83 1.24 0.73
vertex 1.78 1.67 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 2.4 1.83 0.73
vertex 2.06 1.03 0.73
vertex 1.83 1.24 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 1.7 1.61 0.81
vertex 1.99 1.24 0.81
vertex 2.44 0.2 0.81
endloop
endfacet
facet normal -0.02 -0.02 -1
outer loop
vertex 2.17 1.56 0.8
vertex 1.99 1.24 0.81
vertex 1.7 1.61 0.81
endloop
endfacet
facet normal -0.05 -0.02 -1
outer loop
vertex 1.99 1.24 0.81
vertex 2.25 1.09 0.8
vertex 2.44 0.2 0.81
endloop
endfacet
facet normal -0.04 -0.01 -1
outer loop
vertex 2.25 1.09 0.8
vertex 1.99 1.24 0.81
vertex 2.17 1.56 0.8
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 2.12 2.11 0.73
vertex 2.4 1.83 0.73
vertex 1.78 1.67 0.73
endloop
endfacet
facet normal 0.56 0.13 -0.82
outer loop
vertex 1.92 1.81 0.99
vertex 1.7 1.61 0.81
vertex 1.58 2.14 0.81
endloop
endfacet
facet normal 0.37 0.37 -0.86
outer loop
vertex 2.15 1.58 0.99
vertex 1.7 1.61 0.81
vertex 1.92 1.81 0.99
endloop
endfacet
facet normal 0.1 0.99 -0.09
outer loop
vertex 2.15 1.58 0.99
vertex 2.17 1.56 0.8
vertex 1.7 1.61 0.81
endloop
endfacet
facet normal 0.71 0.71 -0.04
outer loop
vertex 1.92 1.81 0.99
vertex 1.58 2.14 0.81
vertex 1.59 2.14 0.99
endloop
endfacet
facet normal 0.71 0.71 0.01
outer loop
vertex 3.52 0.2 1.56
vertex 2.15 1.58 0.99
vertex 1.92 1.81 0.99
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 1.7 4.45 1.01
vertex 1.7 3.95 1.01
vertex 1.7 3.95 0.81
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 1.7 4.45 1.01
vertex 1.7 3.95 0.81
vertex 1.7 4.45 0.81
endloop
endfacet
facet normal 0.7 0.01 -0.71
outer loop
vertex 1.7 4.44 1.02
vertex 1.71 3.96 1.02
vertex 1.7 3.95 1.01
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 1.7 4.44 1.02
vertex 1.7 3.95 1.01
vertex 1.7 4.45 1.01
endloop
endfacet
facet normal -0.96 0.08 0.25
outer loop
vertex 1.5 5.26 0.86
vertex 1.64 5.24 1.4
vertex 1.53 5.7 0.83
endloop
endfacet
facet normal -0.04 -1 -0.03
outer loop
vertex 2.07 5.24 0.84
vertex 1.64 5.24 1.4
vertex 1.5 5.26 0.86
endloop
endfacet
facet normal -0.04 -0.07 -1
outer loop
vertex 2.07 5.24 0.84
vertex 1.5 5.26 0.86
vertex 1.53 5.7 0.83
endloop
endfacet
facet normal -0.1 0.99 -0.04
outer loop
vertex 1.72 5.27 1.89
vertex 1.77 5.27 1.78
vertex 1.64 5.24 1.4
endloop
endfacet
facet normal -0.05 1 -0.06
outer loop
vertex 1.64 5.24 1.4
vertex 1.77 5.27 1.78
vertex 2.07 5.26 1.4
endloop
endfacet
facet normal -0.99 -0.03 0.16
outer loop
vertex 1.53 5.7 0.83
vertex 1.64 5.24 1.4
vertex 1.72 5.27 1.89
endloop
endfacet
facet normal 0.05 -1 0.05
outer loop
vertex 2.07 5.26 1.4
vertex 1.72 5.27 1.89
vertex 1.64 5.24 1.4
endloop
endfacet
facet normal 0.05 -1 0.04
outer loop
vertex 2.07 5.24 0.84
vertex 2.07 5.26 1.4
vertex 1.64 5.24 1.4
endloop
endfacet
facet normal 0.08 1 0.04
outer loop
vertex 2.07 5.26 1.4
vertex 1.77 5.27 1.78
vertex 1.72 5.27 1.89
endloop
endfacet
facet normal -1 0 0.1
outer loop
vertex 1.72 5.27 1.89
vertex 1.73 5.31 1.99
vertex 1.73 7.48 1.99
endloop
endfacet
facet normal -0.01 -0.93 0.37
outer loop
vertex 4.23 5.25 1.89
vertex 1.73 5.31 1.99
vertex 1.72 5.27 1.89
endloop
endfacet
facet normal -0.98 0 0.18
outer loop
vertex 1.53 5.7 0.83
vertex 1.72 5.27 1.89
vertex 1.72 7.53 1.89
endloop
endfacet
facet normal -1 0 0.1
outer loop
vertex 1.72 5.27 1.89
vertex 1.73 7.48 1.99
vertex 1.72 7.53 1.89
endloop
endfacet
facet normal 0 -1 0.02
outer loop
vertex 4.09 5.25 1.4
vertex 1.72 5.27 1.89
vertex 2.07 5.26 1.4
endloop
endfacet
facet normal 0.01 1 -0.01
outer loop
vertex 2.07 5.26 1.4
vertex 1.72 5.27 1.89
vertex 4.23 5.25 1.89
endloop
endfacet
facet normal -0.01 -1 0
outer loop
vertex 4.09 5.25 1.4
vertex 4.23 5.25 1.89
vertex 1.72 5.27 1.89
endloop
endfacet
facet normal -0.02 0 1
outer loop
vertex 1.73 7.48 1.99
vertex 1.73 5.31 1.99
vertex 2.22 6.4 2
endloop
endfacet
facet normal -0.01 0 1
outer loop
vertex 2.22 6.4 2
vertex 1.73 5.31 1.99
vertex 2.46 5.84 2
endloop
endfacet
facet normal -0.01 -0.01 1
outer loop
vertex 2.91 5.61 2
vertex 2.46 5.84 2
vertex 1.73 5.31 1.99
endloop
endfacet
facet normal 0 -0.03 1
outer loop
vertex 4.23 5.3 1.99
vertex 2.91 5.61 2
vertex 1.73 5.31 1.99
endloop
endfacet
facet normal 0 -0.89 0.45
outer loop
vertex 4.23 5.25 1.89
vertex 4.23 5.3 1.99
vertex 1.73 5.31 1.99
endloop
endfacet
facet normal -0.98 0 0.18
outer loop
vertex 1.53 5.7 0.83
vertex 1.72 7.53 1.89
vertex 1.53 7.1 0.84
endloop
endfacet
facet normal -0.01 0.01 -1
outer loop
vertex 2.07 7.55 0.84
vertex 1.53 5.7 0.83
vertex 1.53 7.1 0.84
endloop
endfacet
facet normal 0.02 0 -1
outer loop
vertex 2.07 7.55 0.84
vertex 2.07 5.24 0.84
vertex 1.53 5.7 0.83
endloop
endfacet
facet normal -0.96 -0.08 0.25
outer loop
vertex 1.53 7.1 0.84
vertex 1.64 7.56 1.4
vertex 1.5 7.54 0.86
endloop
endfacet
facet normal -0.04 0.04 -1
outer loop
vertex 2.07 7.55 0.84
vertex 1.53 7.1 0.84
vertex 1.5 7.54 0.86
endloop
endfacet
facet normal -0.99 0.04 0.16
outer loop
vertex 1.53 7.1 0.84
vertex 1.72 7.53 1.89
vertex 1.64 7.56 1.4
endloop
endfacet
facet normal -0.02 1 -0.03
outer loop
vertex 1.5 7.54 0.86
vertex 1.64 7.56 1.4
vertex 2.07 7.55 0.84
endloop
endfacet
facet normal 0.1 0.99 0.04
outer loop
vertex 1.72 7.53 1.89
vertex 1.77 7.53 1.78
vertex 1.64 7.56 1.4
endloop
endfacet
facet normal -0.07 -1 -0.05
outer loop
vertex 2.07 7.53 1.4
vertex 1.77 7.53 1.78
vertex 1.64 7.56 1.4
endloop
endfacet
facet normal 0.07 1 0.05
outer loop
vertex 1.64 7.56 1.4
vertex 1.72 7.53 1.89
vertex 2.07 7.53 1.4
endloop
endfacet
facet normal 0.07 1 0.04
outer loop
vertex 2.07 7.55 0.84
vertex 1.64 7.56 1.4
vertex 2.07 7.53 1.4
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex 2.07 7.53 1.4
vertex 1.72 7.53 1.89
vertex 1.77 7.53 1.78
endloop
endfacet
facet normal -0.01 0.89 0.45
outer loop
vertex 1.72 7.53 1.89
vertex 1.73 7.48 1.99
vertex 4.23 7.51 1.99
endloop
endfacet
facet normal 0.01 -1 0.01
outer loop
vertex 4.09 7.55 1.4
vertex 1.72 7.53 1.89
vertex 2.07 7.53 1.4
endloop
endfacet
facet normal -0.01 1 -0.01
outer loop
vertex 2.07 7.53 1.4
vertex 1.72 7.53 1.89
vertex 4.23 7.55 1.89
endloop
endfacet
facet normal 0.01 -1 0
outer loop
vertex 4.09 7.55 1.4
vertex 4.23 7.55 1.89
vertex 1.72 7.53 1.89
endloop
endfacet
facet normal -0.01 0.93 0.37
outer loop
vertex 1.72 7.53 1.89
vertex 4.23 7.51 1.99
vertex 4.23 7.55 1.89
endloop
endfacet
facet normal -0.01 0 1
outer loop
vertex 1.73 7.48 1.99
vertex 2.22 6.4 2
vertex 2.46 6.96 2
endloop
endfacet
facet normal -0.01 0.01 1
outer loop
vertex 2.91 7.19 2
vertex 1.73 7.48 1.99
vertex 2.46 6.96 2
endloop
endfacet
facet normal 0 0.03 1
outer loop
vertex 4.23 7.51 1.99
vertex 1.73 7.48 1.99
vertex 2.91 7.19 2
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 2.86 -5.72 0.73
vertex 2.54 -6.21 0.73
vertex 2.54 -5.72 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 2.86 -5.72 0.73
vertex 2.86 -6.21 0.73
vertex 2.54 -6.21 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 2.86 -5.72 0.73
vertex 2.54 -5.72 0.73
vertex 2.33 -5.21 0.73
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 2.56 -5.4 1.09
vertex 2.56 -5.76 0.81
vertex 2.56 -5.75 1.08
endloop
endfacet
facet normal -0.04 -1 0.04
outer loop
vertex 2.84 -5.76 1.08
vertex 2.56 -5.75 1.08
vertex 2.56 -5.76 0.81
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 2.56 -5.4 1.09
vertex 2.56 -5.4 0.8
vertex 2.56 -5.76 0.81
endloop
endfacet
facet normal 0 -0.03 -1
outer loop
vertex 2.56 -5.4 0.8
vertex 2.84 -5.76 0.81
vertex 2.56 -5.76 0.81
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex 2.84 -5.76 1.08
vertex 2.56 -5.76 0.81
vertex 2.84 -5.76 0.81
endloop
endfacet
facet normal 0 -0.03 1
outer loop
vertex 2.56 -5.4 1.09
vertex 2.56 -5.75 1.08
vertex 2.84 -5.76 1.08
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 2.87 -5.23 0.73
vertex 2.86 -5.72 0.73
vertex 2.33 -5.21 0.73
endloop
endfacet
facet normal 0 1 0
outer loop
vertex 2.84 -5.4 1.09
vertex 2.56 -5.4 0.8
vertex 2.56 -5.4 1.09
endloop
endfacet
facet normal 0 -0.03 -1
outer loop
vertex 2.56 -5.4 0.8
vertex 2.84 -5.4 0.8
vertex 2.84 -5.76 0.81
endloop
endfacet
facet normal 0 1 0
outer loop
vertex 2.84 -5.4 1.09
vertex 2.84 -5.4 0.8
vertex 2.56 -5.4 0.8
endloop
endfacet
facet normal 0 -0.03 1
outer loop
vertex 2.56 -5.4 1.09
vertex 2.84 -5.76 1.08
vertex 2.84 -5.4 1.09
endloop
endfacet
facet normal 0.71 -0.71 0
outer loop
vertex 2.56 -0.77 0.99
vertex 2.24 -1.09 0.99
vertex 2.25 -1.08 0.8
endloop
endfacet
facet normal 0.57 -0.07 -0.82
outer loop
vertex 2.56 -0.77 0.99
vertex 2.25 -1.08 0.8
vertex 2.33 -0.54 0.81
endloop
endfacet
facet normal 0.71 -0.71 0.01
outer loop
vertex 3.52 0.2 1.56
vertex 2.24 -1.09 0.99
vertex 2.56 -0.77 0.99
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 2.49 -0.15 0.73
vertex 2.79 -1.05 0.73
vertex 2.18 -0.49 0.73
endloop
endfacet
facet normal 0.03 -0.6 -0.8
outer loop
vertex 2.81 -0.52 0.81
vertex 2.56 -0.77 0.99
vertex 2.33 -0.54 0.81
endloop
endfacet
facet normal -0.03 0 -1
outer loop
vertex 2.44 0.2 0.81
vertex 2.78 -0.1 0.8
vertex 2.33 -0.54 0.81
endloop
endfacet
facet normal 0 -0.02 -1
outer loop
vertex 2.78 -0.1 0.8
vertex 2.81 -0.52 0.81
vertex 2.33 -0.54 0.81
endloop
endfacet
facet normal 0.71 -0.71 0
outer loop
vertex 2.81 -0.52 0.81
vertex 2.83 -0.5 0.99
vertex 2.56 -0.77 0.99
endloop
endfacet
facet normal 0.71 -0.71 0.01
outer loop
vertex 3.52 0.2 1.56
vertex 2.56 -0.77 0.99
vertex 2.83 -0.5 0.99
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 2.49 -0.15 0.73
vertex 3.07 -0.74 0.73
vertex 2.79 -1.05 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 2.74 0.08 0.73
vertex 3.07 -0.74 0.73
vertex 2.49 -0.15 0.73
endloop
endfacet
facet normal 0.05 0 -1
outer loop
vertex 2.25 1.09 0.8
vertex 2.44 0.79 0.81
vertex 2.44 0.2 0.81
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 2.44 0.79 0.81
vertex 2.79 0.52 0.81
vertex 2.44 0.2 0.81
endloop
endfacet
facet normal -0.01 0.02 -1
outer loop
vertex 2.79 0.52 0.81
vertex 2.78 -0.1 0.8
vertex 2.44 0.2 0.81
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 2.96 1.27 0.73
vertex 2.74 0.32 0.73
vertex 2.41 0.65 0.73
endloop
endfacet
facet normal 0.02 -0.02 -1
outer loop
vertex 2.44 0.79 0.81
vertex 2.25 1.09 0.8
vertex 2.74 0.99 0.81
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 2.74 0.99 0.81
vertex 2.79 0.52 0.81
vertex 2.44 0.79 0.81
endloop
endfacet
facet normal 0.6 0.1 -0.79
outer loop
vertex 2.17 1.56 0.8
vertex 2.47 1.26 0.99
vertex 2.25 1.09 0.8
endloop
endfacet
facet normal 0.4 0.4 -0.82
outer loop
vertex 2.25 1.09 0.8
vertex 2.47 1.26 0.99
vertex 2.74 0.99 0.99
endloop
endfacet
facet normal 0.2 0.98 0
outer loop
vertex 2.25 1.09 0.8
vertex 2.74 0.99 0.99
vertex 2.74 0.99 0.81
endloop
endfacet
facet normal 0.71 0.71 0
outer loop
vertex 2.17 1.56 0.8
vertex 2.15 1.58 0.99
vertex 2.47 1.26 0.99
endloop
endfacet
facet normal 0.71 0.71 0.01
outer loop
vertex 3.52 0.2 1.56
vertex 2.47 1.26 0.99
vertex 2.15 1.58 0.99
endloop
endfacet
facet normal 0.71 0.71 0.01
outer loop
vertex 3.52 0.2 1.56
vertex 2.74 0.99 0.99
vertex 2.47 1.26 0.99
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 2.4 4.15 1.01
vertex 2.4 3.65 1.01
vertex 2.4 3.65 0.81
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 2.4 4.15 1.01
vertex 2.4 3.65 0.81
vertex 2.4 4.15 0.81
endloop
endfacet
facet normal 0.7 0.01 -0.71
outer loop
vertex 2.4 4.14 1.02
vertex 2.41 3.66 1.02
vertex 2.4 3.65 1.01
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 2.4 4.14 1.02
vertex 2.4 3.65 1.01
vertex 2.4 4.15 1.01
endloop
endfacet
facet normal 0 -1 0.04
outer loop
vertex 4.09 5.25 1.4
vertex 2.07 5.26 1.4
vertex 2.07 5.24 0.84
endloop
endfacet
facet normal 0.01 0 -1
outer loop
vertex 3.93 7.56 0.85
vertex 2.07 5.24 0.84
vertex 2.07 7.55 0.84
endloop
endfacet
facet normal 0.01 -1 0
outer loop
vertex 4.09 5.25 1.4
vertex 2.07 5.24 0.84
vertex 3.93 5.25 0.85
endloop
endfacet
facet normal 0.01 0 -1
outer loop
vertex 3.93 7.56 0.85
vertex 3.93 5.25 0.85
vertex 2.07 5.24 0.84
endloop
endfacet
facet normal 0 1 0
outer loop
vertex 2.07 5.26 1.4
vertex 4.23 5.25 1.89
vertex 4.09 5.25 1.4
endloop
endfacet
facet normal 0.94 0.35 -0.01
outer loop
vertex 2.46 5.84 2
vertex 2.44 5.89 1.87
vertex 2.24 6.42 1.87
endloop
endfacet
facet normal 0.44 0.86 0.26
outer loop
vertex 2.91 5.61 2
vertex 2.44 5.89 1.87
vertex 2.46 5.84 2
endloop
endfacet
facet normal -0.94 -0.35 0.01
outer loop
vertex 2.43 5.93 2.19
vertex 2.24 6.42 1.87
vertex 2.44 5.89 1.87
endloop
endfacet
facet normal -0.47 -0.88 0.09
outer loop
vertex 2.91 5.67 2.19
vertex 2.43 5.93 2.19
vertex 2.44 5.89 1.87
endloop
endfacet
facet normal 0.45 0.86 0.23
outer loop
vertex 2.91 5.61 2
vertex 2.9 5.65 1.87
vertex 2.44 5.89 1.87
endloop
endfacet
facet normal -0.46 -0.88 0.07
outer loop
vertex 2.91 5.67 2.19
vertex 2.44 5.89 1.87
vertex 2.9 5.65 1.87
endloop
endfacet
facet normal 0.9 0.39 0.2
outer loop
vertex 2.46 5.84 2
vertex 2.24 6.42 1.87
vertex 2.22 6.4 2
endloop
endfacet
facet normal -0.85 -0.27 0.46
outer loop
vertex 2.49 5.91 2.29
vertex 2.27 6.44 2.19
vertex 2.43 5.93 2.19
endloop
endfacet
facet normal -0.45 -0.89 0.09
outer loop
vertex 2.91 5.7 2.29
vertex 2.49 5.91 2.29
vertex 2.43 5.93 2.19
endloop
endfacet
facet normal -0.95 -0.3 0.11
outer loop
vertex 2.43 5.93 2.19
vertex 2.27 6.44 2.19
vertex 2.24 6.42 1.87
endloop
endfacet
facet normal -0.46 -0.85 0.26
outer loop
vertex 2.91 5.7 2.29
vertex 2.43 5.93 2.19
vertex 2.91 5.67 2.19
endloop
endfacet
facet normal -0.66 -0.27 0.7
outer loop
vertex 2.54 6.02 2.38
vertex 2.31 6.38 2.3
vertex 2.49 5.91 2.29
endloop
endfacet
facet normal -0.3 -0.52 0.8
outer loop
vertex 2.85 5.84 2.38
vertex 2.54 6.02 2.38
vertex 2.49 5.91 2.29
endloop
endfacet
facet normal -0.92 -0.36 0.14
outer loop
vertex 2.49 5.91 2.29
vertex 2.31 6.38 2.3
vertex 2.27 6.44 2.19
endloop
endfacet
facet normal -0.3 -0.6 0.74
outer loop
vertex 2.85 5.84 2.38
vertex 2.49 5.91 2.29
vertex 2.91 5.7 2.29
endloop
endfacet
facet normal -0.6 -0.21 0.77
outer loop
vertex 2.54 6.02 2.38
vertex 2.42 6.36 2.38
vertex 2.31 6.38 2.3
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 3.58 6.36 2.38
vertex 2.42 6.36 2.38
vertex 2.54 6.02 2.38
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 3.35 5.93 2.38
vertex 2.54 6.02 2.38
vertex 2.85 5.84 2.38
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 3.58 6.36 2.38
vertex 2.54 6.02 2.38
vertex 3.35 5.93 2.38
endloop
endfacet
facet normal 0.91 -0.4 0.08
outer loop
vertex 2.22 6.4 2
vertex 2.24 6.42 1.87
vertex 2.47 6.94 1.87
endloop
endfacet
facet normal -0.91 0.4 0.06
outer loop
vertex 2.27 6.44 2.19
vertex 2.47 6.94 1.87
vertex 2.24 6.42 1.87
endloop
endfacet
facet normal 0.91 -0.39 0.13
outer loop
vertex 2.22 6.4 2
vertex 2.47 6.94 1.87
vertex 2.46 6.96 2
endloop
endfacet
facet normal -0.8 0.35 0.48
outer loop
vertex 2.31 6.38 2.3
vertex 2.48 6.92 2.19
vertex 2.27 6.44 2.19
endloop
endfacet
facet normal -0.91 0.4 0.05
outer loop
vertex 2.27 6.44 2.19
vertex 2.48 6.92 2.19
vertex 2.47 6.94 1.87
endloop
endfacet
facet normal -0.55 0.22 0.81
outer loop
vertex 2.42 6.36 2.38
vertex 2.5 6.9 2.29
vertex 2.31 6.38 2.3
endloop
endfacet
facet normal -0.91 0.34 0.25
outer loop
vertex 2.31 6.38 2.3
vertex 2.5 6.9 2.29
vertex 2.48 6.92 2.19
endloop
endfacet
facet normal -0.76 0.21 0.61
outer loop
vertex 2.42 6.36 2.38
vertex 2.55 6.82 2.38
vertex 2.5 6.9 2.29
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 3.43 6.83 2.38
vertex 2.55 6.82 2.38
vertex 2.42 6.36 2.38
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 3.43 6.83 2.38
vertex 2.42 6.36 2.38
vertex 3.58 6.36 2.38
endloop
endfacet
facet normal 0.45 -0.88 0.17
outer loop
vertex 2.46 6.96 2
vertex 2.47 6.94 1.87
vertex 2.8 7.11 1.87
endloop
endfacet
facet normal -0.46 0.89 0.07
outer loop
vertex 2.48 6.92 2.19
vertex 2.8 7.11 1.87
vertex 2.47 6.94 1.87
endloop
endfacet
facet normal 0.45 -0.88 0.16
outer loop
vertex 2.46 6.96 2
vertex 2.8 7.11 1.87
vertex 2.91 7.19 2
endloop
endfacet
facet normal -0.5 0.82 0.27
outer loop
vertex 2.5 6.9 2.29
vertex 2.62 6.97 2.3
vertex 2.48 6.92 2.19
endloop
endfacet
facet normal -0.5 0.87 0.02
outer loop
vertex 2.48 6.92 2.19
vertex 2.62 7 2.19
vertex 2.8 7.11 1.87
endloop
endfacet
facet normal -0.48 0.84 0.23
outer loop
vertex 2.62 7 2.19
vertex 2.48 6.92 2.19
vertex 2.62 6.97 2.3
endloop
endfacet
facet normal -0.39 0.57 0.72
outer loop
vertex 2.5 6.9 2.29
vertex 2.55 6.82 2.38
vertex 2.62 6.97 2.3
endloop
endfacet
facet normal -0.23 0.54 0.81
outer loop
vertex 2.55 6.82 2.38
vertex 2.62 6.85 2.38
vertex 2.62 6.97 2.3
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 3.43 6.83 2.38
vertex 2.62 6.85 2.38
vertex 2.55 6.82 2.38
endloop
endfacet
facet normal -0.01 1 0.04
outer loop
vertex 4.09 7.55 1.4
vertex 2.07 7.55 0.84
vertex 2.07 7.53 1.4
endloop
endfacet
facet normal -0.01 1 0.02
outer loop
vertex 4.09 7.55 1.4
vertex 3.93 7.56 0.85
vertex 2.07 7.55 0.84
endloop
endfacet
facet normal -0.01 1 0
outer loop
vertex 2.07 7.53 1.4
vertex 4.23 7.55 1.89
vertex 4.09 7.55 1.4
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 2.84 -5.4 1.09
vertex 2.84 -5.76 1.08
vertex 2.84 -5.76 0.81
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 2.84 -5.4 1.09
vertex 2.84 -5.76 0.81
vertex 2.84 -5.4 0.8
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 2.74 0.08 0.73
vertex 3.3 -0.54 0.73
vertex 3.07 -0.74 0.73
endloop
endfacet
facet normal 0.99 0.07 -0.12
outer loop
vertex 2.78 -0.1 0.8
vertex 2.83 -0.5 0.99
vertex 2.81 -0.52 0.81
endloop
endfacet
facet normal 0.36 -0.36 -0.86
outer loop
vertex 2.78 -0.1 0.8
vertex 3.09 -0.24 0.99
vertex 2.83 -0.5 0.99
endloop
endfacet
facet normal 0.71 -0.71 0.01
outer loop
vertex 3.52 0.2 1.56
vertex 2.83 -0.5 0.99
vertex 3.09 -0.24 0.99
endloop
endfacet
facet normal 0.24 -0.56 -0.8
outer loop
vertex 3.52 0.2 0.81
vertex 3.09 -0.24 0.99
vertex 2.78 -0.1 0.8
endloop
endfacet
facet normal 0.01 0.02 -1
outer loop
vertex 2.79 0.52 0.81
vertex 3.52 0.2 0.81
vertex 2.78 -0.1 0.8
endloop
endfacet
facet normal 0.72 -0.7 0
outer loop
vertex 3.52 0.2 1.56
vertex 3.09 -0.24 0.99
vertex 3.52 0.2 0.81
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 3.31 0.86 0.73
vertex 2.74 0.32 0.73
vertex 2.96 1.27 0.73
endloop
endfacet
facet normal 0.61 0.07 -0.79
outer loop
vertex 3 0.73 0.99
vertex 2.79 0.52 0.81
vertex 2.74 0.99 0.81
endloop
endfacet
facet normal 0.22 0.5 -0.84
outer loop
vertex 3.52 0.2 0.81
vertex 2.79 0.52 0.81
vertex 3 0.73 0.99
endloop
endfacet
facet normal 0.71 0.71 0
outer loop
vertex 3 0.73 0.99
vertex 2.74 0.99 0.81
vertex 2.74 0.99 0.99
endloop
endfacet
facet normal 0.71 0.71 0.01
outer loop
vertex 3.52 0.2 1.56
vertex 3 0.73 0.99
vertex 2.74 0.99 0.99
endloop
endfacet
facet normal 0.71 0.7 0
outer loop
vertex 3.52 0.2 1.56
vertex 3.52 0.2 0.81
vertex 3 0.73 0.99
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 3.29 0.96 0.73
vertex 3.31 0.86 0.73
vertex 2.96 1.27 0.73
endloop
endfacet
facet normal -0.29 0.91 0.3
outer loop
vertex 3.45 5.78 2
vertex 2.9 5.65 1.87
vertex 2.91 5.61 2
endloop
endfacet
facet normal 0.33 -0.94 0.05
outer loop
vertex 3.5 5.88 2.19
vertex 2.91 5.67 2.19
vertex 2.9 5.65 1.87
endloop
endfacet
facet normal -0.28 0.92 0.29
outer loop
vertex 3.45 5.78 2
vertex 3.48 5.83 1.87
vertex 2.9 5.65 1.87
endloop
endfacet
facet normal 0.29 -0.95 0.13
outer loop
vertex 3.5 5.88 2.19
vertex 2.9 5.65 1.87
vertex 3.48 5.83 1.87
endloop
endfacet
facet normal 0 -0.01 1
outer loop
vertex 4.23 5.3 1.99
vertex 3.45 5.78 2
vertex 2.91 5.61 2
endloop
endfacet
facet normal 0.26 -0.92 0.28
outer loop
vertex 3.44 5.85 2.29
vertex 2.91 5.7 2.29
vertex 2.91 5.67 2.19
endloop
endfacet
facet normal 0.33 -0.94 -0.08
outer loop
vertex 3.44 5.85 2.29
vertex 2.91 5.67 2.19
vertex 3.5 5.88 2.19
endloop
endfacet
facet normal 0.09 -0.51 0.86
outer loop
vertex 3.35 5.93 2.38
vertex 2.85 5.84 2.38
vertex 2.91 5.7 2.29
endloop
endfacet
facet normal 0.18 -0.64 0.75
outer loop
vertex 3.35 5.93 2.38
vertex 2.91 5.7 2.29
vertex 3.44 5.85 2.29
endloop
endfacet
facet normal -0.16 -0.77 0.61
outer loop
vertex 2.91 7.19 2
vertex 2.8 7.11 1.87
vertex 3.48 6.97 1.87
endloop
endfacet
facet normal 0.18 0.89 0.41
outer loop
vertex 3.48 6.97 1.87
vertex 2.8 7.11 1.87
vertex 2.62 7 2.19
endloop
endfacet
facet normal -0.3 -0.92 0.24
outer loop
vertex 2.91 7.19 2
vertex 3.48 6.97 1.87
vertex 3.46 7.01 2
endloop
endfacet
facet normal 0 0.01 1
outer loop
vertex 4.23 7.51 1.99
vertex 2.91 7.19 2
vertex 3.46 7.01 2
endloop
endfacet
facet normal 0.06 0.96 0.26
outer loop
vertex 3.47 6.92 2.29
vertex 2.62 7 2.19
vertex 2.62 6.97 2.3
endloop
endfacet
facet normal 0.07 0.99 0.09
outer loop
vertex 3.48 6.97 1.87
vertex 2.62 7 2.19
vertex 3.5 6.94 2.19
endloop
endfacet
facet normal 0.07 0.97 0.21
outer loop
vertex 3.47 6.92 2.29
vertex 3.5 6.94 2.19
vertex 2.62 7 2.19
endloop
endfacet
facet normal 0.01 0.55 0.83
outer loop
vertex 3.43 6.83 2.38
vertex 2.62 6.97 2.3
vertex 2.62 6.85 2.38
endloop
endfacet
facet normal 0.05 0.7 0.72
outer loop
vertex 3.43 6.83 2.38
vertex 3.47 6.92 2.29
vertex 2.62 6.97 2.3
endloop
endfacet
facet normal 0.99 0.12 0
outer loop
vertex 3.06 8.83 0
vertex 3.01 9.25 0.71
vertex 3.06 8.83 0.71
endloop
endfacet
facet normal 0.32 0.95 0
outer loop
vertex 3.39 8.72 0
vertex 3.06 8.83 0
vertex 3.06 8.83 0.71
endloop
endfacet
facet normal 1 0.09 0.01
outer loop
vertex 3.06 8.83 0
vertex 3.02 9.25 0
vertex 3.01 9.25 0.71
endloop
endfacet
facet normal 0.28 0.96 -0.02
outer loop
vertex 3.39 8.72 0
vertex 3.06 8.83 0.71
vertex 3.4 8.73 0.71
endloop
endfacet
facet normal 0.66 -0.75 0.01
outer loop
vertex 3.02 9.25 0
vertex 3.28 9.49 0.71
vertex 3.01 9.25 0.71
endloop
endfacet
facet normal 0.03 -0.01 -1
outer loop
vertex 3.28 10.52 0
vertex 3.02 9.25 0
vertex 2.96 10.54 -0.01
endloop
endfacet
facet normal 0.68 -0.73 0
outer loop
vertex 3.02 9.25 0
vertex 3.28 9.49 0
vertex 3.28 9.49 0.71
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 3.28 10.52 0
vertex 3.28 9.49 0
vertex 3.02 9.25 0
endloop
endfacet
facet normal 0.03 -0.01 1
outer loop
vertex 3.28 10.52 0.71
vertex 2.94 10.54 0.72
vertex 3.01 9.25 0.71
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 3.28 10.52 0.71
vertex 3.01 9.25 0.71
vertex 3.28 9.49 0.71
endloop
endfacet
facet normal 0.84 -0.54 0.02
outer loop
vertex 2.96 10.54 -0.01
vertex 3.1 10.79 0.71
vertex 2.94 10.54 0.72
endloop
endfacet
facet normal 0.06 1 0
outer loop
vertex 3.28 10.52 0
vertex 2.96 10.54 -0.01
vertex 2.94 10.54 0.72
endloop
endfacet
facet normal 0.87 -0.49 0
outer loop
vertex 2.96 10.54 -0.01
vertex 3.1 10.79 0
vertex 3.1 10.79 0.71
endloop
endfacet
facet normal 0.06 1 0
outer loop
vertex 3.28 10.52 0
vertex 2.94 10.54 0.72
vertex 3.28 10.52 0.71
endloop
endfacet
facet normal 1 -0.01 0
outer loop
vertex 3.1 10.79 0
vertex 3.11 11.77 0.71
vertex 3.1 10.79 0.71
endloop
endfacet
facet normal 1 -0.01 0
outer loop
vertex 3.1 10.79 0
vertex 3.11 11.77 0
vertex 3.11 11.77 0.71
endloop
endfacet
facet normal 0.91 -0.42 0
outer loop
vertex 3.11 11.77 0
vertex 3.17 11.9 0.71
vertex 3.11 11.77 0.71
endloop
endfacet
facet normal 0.91 -0.42 0
outer loop
vertex 3.11 11.77 0
vertex 3.17 11.9 0
vertex 3.17 11.9 0.71
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 3.05 13.25 0
vertex 3.17 11.9 0
vertex 3.11 11.77 0
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 3.05 13.25 0.71
vertex 3.11 11.77 0.71
vertex 3.17 11.9 0.71
endloop
endfacet
facet normal 0.54 -0.84 0
outer loop
vertex 3.17 11.9 0
vertex 3.28 11.97 0.71
vertex 3.17 11.9 0.71
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 3.05 13.25 0
vertex 3.34 12.5 0
vertex 3.17 11.9 0
endloop
endfacet
facet normal 0.54 -0.84 0
outer loop
vertex 3.17 11.9 0
vertex 3.28 11.97 0
vertex 3.28 11.97 0.71
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 3.34 12.5 0
vertex 3.28 11.97 0
vertex 3.17 11.9 0
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 3.05 13.25 0.71
vertex 3.17 11.9 0.71
vertex 3.34 12.5 0.71
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 3.34 12.5 0.71
vertex 3.17 11.9 0.71
vertex 3.28 11.97 0.71
endloop
endfacet
facet normal 0.93 0.36 0
outer loop
vertex 3.34 12.5 0
vertex 3.05 13.25 0
vertex 3.05 13.25 0.71
endloop
endfacet
facet normal 0.93 0.36 0
outer loop
vertex 3.34 12.5 0
vertex 3.05 13.25 0.71
vertex 3.34 12.5 0.71
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 4.04 -3.44 0.73
vertex 3.55 -3.83 0.73
vertex 3.54 -3.37 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 4.04 -3.44 0.73
vertex 4.04 -3.81 0.73
vertex 3.55 -3.83 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 4 -2.95 0.73
vertex 3.51 -2.91 0.73
vertex 3.54 -3.37 0.73
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 3.6 -3.5 1.08
vertex 3.6 -3.5 0.81
vertex 3.6 -3.1 0.81
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 3.6 -3.5 1.08
vertex 3.6 -3.1 0.81
vertex 3.6 -3.1 1.08
endloop
endfacet
facet normal -0.88 0.47 -0.02
outer loop
vertex 3.78 6.4 2
vertex 3.48 5.83 1.87
vertex 3.45 5.78 2
endloop
endfacet
facet normal 0.93 -0.38 0
outer loop
vertex 3.5 5.88 2.19
vertex 3.48 5.83 1.87
vertex 3.73 6.44 1.87
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 3.73 6.44 1.87
vertex 3.48 5.83 1.87
vertex 3.78 6.4 1.87
endloop
endfacet
facet normal -0.88 0.47 0
outer loop
vertex 3.78 6.4 2
vertex 3.78 6.4 1.87
vertex 3.48 5.83 1.87
endloop
endfacet
facet normal 0.01 -0.01 1
outer loop
vertex 3.78 6.4 2
vertex 3.45 5.78 2
vertex 4.23 5.3 1.99
endloop
endfacet
facet normal 0.83 -0.41 0.38
outer loop
vertex 3.69 6.37 2.3
vertex 3.44 5.85 2.29
vertex 3.5 5.88 2.19
endloop
endfacet
facet normal 0.93 -0.37 0.02
outer loop
vertex 3.73 6.46 2.19
vertex 3.5 5.88 2.19
vertex 3.73 6.44 1.87
endloop
endfacet
facet normal 0.93 -0.37 0.04
outer loop
vertex 3.69 6.37 2.3
vertex 3.5 5.88 2.19
vertex 3.73 6.46 2.19
endloop
endfacet
facet normal 0.54 -0.28 0.79
outer loop
vertex 3.69 6.37 2.3
vertex 3.35 5.93 2.38
vertex 3.44 5.85 2.29
endloop
endfacet
facet normal 0.58 -0.31 0.76
outer loop
vertex 3.58 6.36 2.38
vertex 3.35 5.93 2.38
vertex 3.69 6.37 2.3
endloop
endfacet
facet normal 0.9 0.43 -0.03
outer loop
vertex 3.5 6.94 2.19
vertex 3.73 6.46 2.19
vertex 3.73 6.44 1.87
endloop
endfacet
facet normal 0.9 0.43 -0.02
outer loop
vertex 3.5 6.94 2.19
vertex 3.73 6.44 1.87
vertex 3.48 6.97 1.87
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 3.48 6.97 1.87
vertex 3.73 6.44 1.87
vertex 3.78 6.4 1.87
endloop
endfacet
facet normal 0.78 0.32 0.54
outer loop
vertex 3.47 6.92 2.29
vertex 3.69 6.37 2.3
vertex 3.73 6.46 2.19
endloop
endfacet
facet normal 0.85 0.41 0.34
outer loop
vertex 3.47 6.92 2.29
vertex 3.73 6.46 2.19
vertex 3.5 6.94 2.19
endloop
endfacet
facet normal 0.57 0.18 0.8
outer loop
vertex 3.43 6.83 2.38
vertex 3.58 6.36 2.38
vertex 3.69 6.37 2.3
endloop
endfacet
facet normal 0.72 0.3 0.62
outer loop
vertex 3.43 6.83 2.38
vertex 3.69 6.37 2.3
vertex 3.47 6.92 2.29
endloop
endfacet
facet normal -0.88 -0.47 0.01
outer loop
vertex 3.46 7.01 2
vertex 3.48 6.97 1.87
vertex 3.78 6.4 1.87
endloop
endfacet
facet normal -0.89 -0.46 0
outer loop
vertex 3.46 7.01 2
vertex 3.78 6.4 1.87
vertex 3.78 6.4 2
endloop
endfacet
facet normal 0.01 0.01 1
outer loop
vertex 4.23 7.51 1.99
vertex 3.46 7.01 2
vertex 3.78 6.4 2
endloop
endfacet
facet normal -0.01 1 -0.01
outer loop
vertex 4.14 8.73 0
vertex 3.39 8.72 0
vertex 3.4 8.73 0.71
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 4.14 8.73 0
vertex 9.36 3.52 -0.02
vertex 3.39 8.72 0
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.37 2.98 -0.02
vertex 9.34 0.56 -0.02
vertex 3.39 8.72 0
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.36 3.52 -0.02
vertex 9.37 2.98 -0.02
vertex 3.39 8.72 0
endloop
endfacet
facet normal 0 1 0
outer loop
vertex 4.14 8.73 0
vertex 3.4 8.73 0.71
vertex 4.14 8.73 0.71
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 4.14 8.73 0.71
vertex 3.4 8.73 0.71
vertex 9.36 3.52 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.37 2.97 0.73
vertex 3.4 8.73 0.71
vertex 9.34 0.55 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.36 3.52 0.73
vertex 3.4 8.73 0.71
vertex 9.37 2.97 0.73
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 3.28 9.49 0
vertex 3.28 10.52 0.71
vertex 3.28 9.49 0.71
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 3.28 9.49 0
vertex 3.28 10.52 0
vertex 3.28 10.52 0.71
endloop
endfacet
facet normal 0.99 -0.11 0
outer loop
vertex 3.28 11.97 0
vertex 3.34 12.5 0.71
vertex 3.28 11.97 0.71
endloop
endfacet
facet normal 0.99 -0.11 0
outer loop
vertex 3.28 11.97 0
vertex 3.34 12.5 0
vertex 3.34 12.5 0.71
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 4.56 -3.46 0.73
vertex 4.04 -3.81 0.73
vertex 4.04 -3.44 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 4.56 -3.46 0.73
vertex 4.63 -3.87 0.73
vertex 4.04 -3.81 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 4.62 -2.9 0.73
vertex 4.04 -3.44 0.73
vertex 4 -2.95 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 4.62 -2.9 0.73
vertex 4.56 -3.46 0.73
vertex 4.04 -3.44 0.73
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 4.16 -3.5 1.08
vertex 4.16 -3.1 0.81
vertex 4.16 -3.5 0.81
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex 4.16 -3.5 1.08
vertex 4.16 -3.5 0.81
vertex 4.44 -3.5 0.81
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 4.44 -3.5 0.81
vertex 4.16 -3.5 0.81
vertex 4.16 -3.1 0.81
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 4.16 -3.5 1.08
vertex 4.16 -3.1 1.08
vertex 4.16 -3.1 0.81
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 4.44 -3.5 1.08
vertex 4.16 -3.1 1.08
vertex 4.16 -3.5 1.08
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex 4.16 -3.5 1.08
vertex 4.44 -3.5 0.81
vertex 4.44 -3.5 1.08
endloop
endfacet
facet normal 0 1 0
outer loop
vertex 4.16 -3.1 1.08
vertex 4.44 -3.1 0.81
vertex 4.16 -3.1 0.81
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 4.44 -3.5 0.81
vertex 4.16 -3.1 0.81
vertex 4.44 -3.1 0.81
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 4.44 -3.5 1.08
vertex 4.44 -3.1 1.08
vertex 4.16 -3.1 1.08
endloop
endfacet
facet normal 0 1 0
outer loop
vertex 4.16 -3.1 1.08
vertex 4.44 -3.1 1.08
vertex 4.44 -3.1 0.81
endloop
endfacet
facet normal 0.02 -1 -0.01
outer loop
vertex 4.5 5.26 0.86
vertex 4.09 5.25 1.4
vertex 3.93 5.25 0.85
endloop
endfacet
facet normal -0.04 0 -1
outer loop
vertex 4.47 7.1 0.83
vertex 3.93 5.25 0.85
vertex 3.93 7.56 0.85
endloop
endfacet
facet normal 0.02 -0.04 -1
outer loop
vertex 4.47 5.7 0.84
vertex 4.5 5.26 0.86
vertex 3.93 5.25 0.85
endloop
endfacet
facet normal -0.01 -0.01 -1
outer loop
vertex 4.47 7.1 0.83
vertex 4.47 5.7 0.84
vertex 3.93 5.25 0.85
endloop
endfacet
facet normal 0.53 -0.83 -0.15
outer loop
vertex 4.09 5.25 1.4
vertex 4.23 5.27 1.78
vertex 4.23 5.25 1.89
endloop
endfacet
facet normal -0.02 -1 0.06
outer loop
vertex 4.23 5.27 1.78
vertex 4.09 5.25 1.4
vertex 4.5 5.24 1.4
endloop
endfacet
facet normal -0.02 -1 -0.04
outer loop
vertex 4.5 5.26 0.86
vertex 4.5 5.24 1.4
vertex 4.09 5.25 1.4
endloop
endfacet
facet normal 0.36 -0.92 -0.17
outer loop
vertex 4.5 5.36 1.87
vertex 4.23 5.25 1.89
vertex 4.23 5.27 1.78
endloop
endfacet
facet normal 0.23 -0.94 0.24
outer loop
vertex 4.5 5.36 1.87
vertex 4.23 5.27 1.78
vertex 4.5 5.24 1.4
endloop
endfacet
facet normal 0.37 -0.83 0.42
outer loop
vertex 4.5 5.36 1.87
vertex 4.23 5.3 1.99
vertex 4.23 5.25 1.89
endloop
endfacet
facet normal -0.03 -0.02 1
outer loop
vertex 3.78 6.4 2
vertex 4.23 5.3 1.99
vertex 4.5 5.4 2
endloop
endfacet
facet normal 0.32 -0.9 0.28
outer loop
vertex 4.5 5.36 1.87
vertex 4.5 5.4 2
vertex 4.23 5.3 1.99
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 5.15 7.25 0.73
vertex 4.25 5.55 0.73
vertex 4.25 7.25 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 5.15 7.25 0.73
vertex 5.15 5.55 0.73
vertex 4.25 5.55 0.73
endloop
endfacet
facet normal -0.03 0.02 1
outer loop
vertex 4.5 7.4 2
vertex 4.23 7.51 1.99
vertex 3.78 6.4 2
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 4.5 7.4 2
vertex 3.78 6.4 2
vertex 4.5 5.4 2
endloop
endfacet
facet normal 0.03 1 0.01
outer loop
vertex 3.93 7.56 0.85
vertex 4.09 7.55 1.4
vertex 4.5 7.54 0.86
endloop
endfacet
facet normal 0.02 0.07 -1
outer loop
vertex 4.5 7.54 0.86
vertex 4.47 7.1 0.83
vertex 3.93 7.56 0.85
endloop
endfacet
facet normal 0.53 0.83 -0.15
outer loop
vertex 4.23 7.55 1.89
vertex 4.23 7.53 1.78
vertex 4.09 7.55 1.4
endloop
endfacet
facet normal -0.02 1 0.06
outer loop
vertex 4.5 7.56 1.4
vertex 4.09 7.55 1.4
vertex 4.23 7.53 1.78
endloop
endfacet
facet normal -0.02 1 -0.04
outer loop
vertex 4.5 7.54 0.86
vertex 4.09 7.55 1.4
vertex 4.5 7.56 1.4
endloop
endfacet
facet normal 0.33 0.93 -0.17
outer loop
vertex 4.5 7.45 1.87
vertex 4.23 7.53 1.78
vertex 4.23 7.55 1.89
endloop
endfacet
facet normal 0.21 0.95 0.22
outer loop
vertex 4.5 7.56 1.4
vertex 4.23 7.53 1.78
vertex 4.5 7.45 1.87
endloop
endfacet
facet normal 0.34 0.87 0.35
outer loop
vertex 4.23 7.55 1.89
vertex 4.23 7.51 1.99
vertex 4.5 7.4 2
endloop
endfacet
facet normal 0.35 0.87 0.34
outer loop
vertex 4.23 7.55 1.89
vertex 4.5 7.4 2
vertex 4.5 7.45 1.87
endloop
endfacet
facet normal -0.3 0.95 0
outer loop
vertex 4.49 8.84 0
vertex 4.14 8.73 0
vertex 4.14 8.73 0.71
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.27 5.78 -0.02
vertex 4.14 8.73 0
vertex 4.49 8.84 0
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.27 5.78 -0.02
vertex 9.36 3.52 -0.02
vertex 4.14 8.73 0
endloop
endfacet
facet normal -0.3 0.95 0
outer loop
vertex 4.49 8.84 0
vertex 4.14 8.73 0.71
vertex 4.49 8.84 0.71
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.28 5.79 0.73
vertex 4.49 8.84 0.71
vertex 4.14 8.73 0.71
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.28 5.79 0.73
vertex 4.14 8.73 0.71
vertex 9.36 3.52 0.73
endloop
endfacet
facet normal -1 -0.01 0
outer loop
vertex 4.2 14 0
vertex 4.26 9.49 0
vertex 4.26 9.49 0.71
endloop
endfacet
facet normal -0.65 -0.76 0
outer loop
vertex 4.26 9.49 0
vertex 4.54 9.25 0.71
vertex 4.26 9.49 0.71
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 4.2 14 0
vertex 4.54 9.24 0
vertex 4.26 9.49 0
endloop
endfacet
facet normal -0.67 -0.75 0.01
outer loop
vertex 4.26 9.49 0
vertex 4.54 9.24 0
vertex 4.54 9.25 0.71
endloop
endfacet
facet normal -1 -0.01 0
outer loop
vertex 4.2 14 0
vertex 4.26 9.49 0.71
vertex 4.2 14 0.71
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 4.2 14 0.71
vertex 4.26 9.49 0.71
vertex 4.54 9.25 0.71
endloop
endfacet
facet normal -0.89 0.45 0
outer loop
vertex 4.7 15 0
vertex 4.2 14 0
vertex 4.2 14 0.71
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 4.2 14 0
vertex 9.3 11.04 -0.02
vertex 4.54 9.24 0
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.3 13.29 -0.02
vertex 4.2 14 0
vertex 4.7 15 0
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.3 13.29 -0.02
vertex 9.3 11.04 -0.02
vertex 4.2 14 0
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 4.2 14 0.71
vertex 4.54 9.25 0.71
vertex 9.31 11.05 0.73
endloop
endfacet
facet normal -0.89 0.45 0
outer loop
vertex 4.7 15 0
vertex 4.2 14 0.71
vertex 4.7 15 0.71
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.31 13.29 0.73
vertex 4.7 15 0.71
vertex 4.2 14 0.71
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.31 13.29 0.73
vertex 4.2 14 0.71
vertex 9.31 11.05 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 5.3 -3.54 0.73
vertex 4.63 -3.87 0.73
vertex 4.56 -3.46 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 5.3 -3.54 0.73
vertex 5.3 -4.02 0.73
vertex 4.63 -3.87 0.73
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 4.44 -3.5 1.08
vertex 4.44 -3.5 0.81
vertex 4.44 -3.1 0.81
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 4.44 -3.5 1.08
vertex 4.44 -3.1 0.81
vertex 4.44 -3.1 1.08
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 5.22 -2.55 0.73
vertex 4.62 -2.9 0.73
vertex 4.92 -2.59 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 5.22 -2.55 0.73
vertex 5.34 -2.98 0.73
vertex 4.62 -2.9 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 5.1 4.21 0.73
vertex 4.65 3.38 0.73
vertex 4.66 4.22 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 5.1 4.21 0.73
vertex 5.1 3.38 0.73
vertex 4.65 3.38 0.73
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 4.74 3.42 1.28
vertex 4.74 4.18 0.81
vertex 4.74 3.42 0.81
endloop
endfacet
facet normal 0.23 -0.97 0
outer loop
vertex 4.99 3.48 1.28
vertex 4.74 3.42 1.28
vertex 4.74 3.42 0.81
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 5.05 4.03 0.81
vertex 4.74 3.42 0.81
vertex 4.74 4.18 0.81
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 5.05 4.03 0.81
vertex 4.99 3.5 0.81
vertex 4.74 3.42 0.81
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 5.94 3.49 0.81
vertex 4.74 3.42 0.81
vertex 4.99 3.5 0.81
endloop
endfacet
facet normal 0 -0.99 0.13
outer loop
vertex 6.01 3.48 1.28
vertex 4.99 3.48 1.28
vertex 4.74 3.42 0.81
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.26 3.42 0.81
vertex 4.74 3.42 0.81
vertex 5.94 3.49 0.81
endloop
endfacet
facet normal 0 -0.99 0.13
outer loop
vertex 6.01 3.48 1.28
vertex 4.74 3.42 0.81
vertex 6.26 3.42 0.81
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 4.74 3.42 1.28
vertex 4.74 4.18 1.28
vertex 4.74 4.18 0.81
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 4.99 4.12 1.28
vertex 4.74 4.18 1.28
vertex 4.74 3.42 1.28
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 4.99 4.12 1.28
vertex 4.74 3.42 1.28
vertex 4.99 3.48 1.28
endloop
endfacet
facet normal 0.23 0.97 0
outer loop
vertex 4.99 4.12 1.28
vertex 4.74 4.18 0.81
vertex 4.74 4.18 1.28
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 5.94 4.11 0.81
vertex 5.05 4.03 0.81
vertex 4.74 4.18 0.81
endloop
endfacet
facet normal 0 0.99 0.13
outer loop
vertex 6.01 4.12 1.28
vertex 4.74 4.18 0.81
vertex 4.99 4.12 1.28
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.26 4.18 0.81
vertex 5.94 4.11 0.81
vertex 4.74 4.18 0.81
endloop
endfacet
facet normal 0 0.99 0.13
outer loop
vertex 6.01 4.12 1.28
vertex 6.26 4.18 0.81
vertex 4.74 4.18 0.81
endloop
endfacet
facet normal 1 0.07 0
outer loop
vertex 4.47 5.7 0.84
vertex 4.5 5.24 1.4
vertex 4.5 5.26 0.86
endloop
endfacet
facet normal 1 0.05 -0.01
outer loop
vertex 4.47 5.7 0.84
vertex 4.5 5.36 1.87
vertex 4.5 5.24 1.4
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 4.5 7.45 1.87
vertex 4.5 5.4 2
vertex 4.5 5.36 1.87
endloop
endfacet
facet normal 1 0 -0.03
outer loop
vertex 4.47 7.1 0.83
vertex 4.5 5.36 1.87
vertex 4.47 5.7 0.84
endloop
endfacet
facet normal 1 0 -0.03
outer loop
vertex 4.47 7.1 0.83
vertex 4.5 7.45 1.87
vertex 4.5 5.36 1.87
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 4.5 7.45 1.87
vertex 4.5 7.4 2
vertex 4.5 5.4 2
endloop
endfacet
facet normal 0.02 -0.01 -1
outer loop
vertex 5 7.1 0.84
vertex 4.47 5.7 0.84
vertex 4.47 7.1 0.83
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 5 7.1 0.84
vertex 5 5.7 0.84
vertex 4.47 5.7 0.84
endloop
endfacet
facet normal 1 -0.07 0
outer loop
vertex 4.5 7.54 0.86
vertex 4.5 7.56 1.4
vertex 4.47 7.1 0.83
endloop
endfacet
facet normal 1 -0.05 -0.01
outer loop
vertex 4.47 7.1 0.83
vertex 4.5 7.56 1.4
vertex 4.5 7.45 1.87
endloop
endfacet
facet normal -0.99 0.12 0
outer loop
vertex 4.54 9.24 0
vertex 4.49 8.84 0
vertex 4.49 8.84 0.71
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.36 8.12 -0.02
vertex 4.49 8.84 0
vertex 4.54 9.24 0
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.36 8.12 -0.02
vertex 9.27 5.78 -0.02
vertex 4.49 8.84 0
endloop
endfacet
facet normal -0.99 0.12 0
outer loop
vertex 4.54 9.24 0
vertex 4.49 8.84 0.71
vertex 4.54 9.25 0.71
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.36 8.12 0.73
vertex 4.54 9.25 0.71
vertex 4.49 8.84 0.71
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.36 8.12 0.73
vertex 4.49 8.84 0.71
vertex 9.28 5.79 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.37 8.66 -0.02
vertex 9.36 8.12 -0.02
vertex 4.54 9.24 0
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.38 10.51 -0.02
vertex 9.37 8.66 -0.02
vertex 4.54 9.24 0
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.3 11.04 -0.02
vertex 9.38 10.51 -0.02
vertex 4.54 9.24 0
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.36 8.66 0.73
vertex 4.54 9.25 0.71
vertex 9.36 8.12 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.38 10.52 0.73
vertex 4.54 9.25 0.71
vertex 9.36 8.66 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.31 11.05 0.73
vertex 4.54 9.25 0.71
vertex 9.38 10.52 0.73
endloop
endfacet
facet normal 0 1 0
outer loop
vertex 11.77 15 0
vertex 4.7 15 0
vertex 4.7 15 0.71
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.39 13.83 -0.02
vertex 9.3 13.29 -0.02
vertex 4.7 15 0
endloop
endfacet
facet normal 0 0.02 -1
outer loop
vertex 11.77 15 0
vertex 9.39 13.83 -0.02
vertex 4.7 15 0
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.38 13.82 0.73
vertex 4.7 15 0.71
vertex 9.31 13.29 0.73
endloop
endfacet
facet normal 0 0.02 1
outer loop
vertex 11.77 15 0.71
vertex 4.7 15 0.71
vertex 9.38 13.82 0.73
endloop
endfacet
facet normal 0 1 0
outer loop
vertex 11.77 15 0
vertex 4.7 15 0.71
vertex 11.77 15 0.71
endloop
endfacet
facet normal -1 -0.05 -0.04
outer loop
vertex 5.19 -3.8 1.29
vertex 5.2 -3.6 0.81
vertex 5.21 -3.8 0.8
endloop
endfacet
facet normal -1 0.05 0
outer loop
vertex 5.19 -3.8 1.29
vertex 5.2 -3.6 1.28
vertex 5.2 -3.6 0.81
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 5.2 -3.6 1.26
vertex 5.2 -3.6 0.81
vertex 5.2 -2.94 0.81
endloop
endfacet
facet normal 1 -0.08 0
outer loop
vertex 5.2 -3.6 1.28
vertex 5.2 -3.6 1.26
vertex 5.25 -3 1.26
endloop
endfacet
facet normal -1 -0.01 0
outer loop
vertex 5.2 -3.6 1.26
vertex 5.2 -3.6 1.28
vertex 5.19 -2.93 1.28
endloop
endfacet
facet normal 0.99 -0.08 -0.12
outer loop
vertex 5.2 -3.6 1.26
vertex 5.2 -2.94 0.81
vertex 5.25 -3 1.26
endloop
endfacet
facet normal -0.29 0.02 -0.96
outer loop
vertex 5.2 -3.6 1.26
vertex 5.19 -2.93 1.28
vertex 5.25 -3 1.26
endloop
endfacet
facet normal 0.32 0 0.95
outer loop
vertex 5.2 -3.6 1.28
vertex 5.25 -3 1.26
vertex 5.19 -2.93 1.28
endloop
endfacet
facet normal 0.76 0.65 0
outer loop
vertex 5.25 -3 1.26
vertex 5.2 -2.94 0.81
vertex 5.19 -2.93 1.28
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 5.94 3.49 0.81
vertex 4.99 3.5 0.81
vertex 5.05 4.03 0.81
endloop
endfacet
facet normal -1 0 0.1
outer loop
vertex 5.05 4.2 1.89
vertex 4.99 3.48 1.28
vertex 5.05 3.4 1.89
endloop
endfacet
facet normal 0 -0.99 -0.13
outer loop
vertex 5.95 3.4 1.89
vertex 5.05 3.4 1.89
vertex 4.99 3.48 1.28
endloop
endfacet
facet normal -1 0 0.1
outer loop
vertex 5.05 4.2 1.89
vertex 4.99 4.12 1.28
vertex 4.99 3.48 1.28
endloop
endfacet
facet normal 0 -0.99 -0.13
outer loop
vertex 5.95 3.4 1.89
vertex 4.99 3.48 1.28
vertex 6.01 3.48 1.28
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 5.95 4.2 1.89
vertex 5.05 4.2 1.89
vertex 5.05 3.4 1.89
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 5.95 4.2 1.89
vertex 5.05 3.4 1.89
vertex 5.95 3.4 1.89
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 5.05 4.03 0.81
vertex 5.94 4.11 0.81
vertex 5.94 3.49 0.81
endloop
endfacet
facet normal 0 0.99 -0.13
outer loop
vertex 5.95 4.2 1.89
vertex 4.99 4.12 1.28
vertex 5.05 4.2 1.89
endloop
endfacet
facet normal 0 0.99 -0.13
outer loop
vertex 5.95 4.2 1.89
vertex 6.01 4.12 1.28
vertex 4.99 4.12 1.28
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.17 -1.73 0.73
vertex 5.83 -1.74 0.73
vertex 5.85 -1.27 0.73
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 5.85 -1.05 1.01
vertex 5.85 -1.55 0.81
vertex 5.85 -1.55 1.01
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex 6.15 -1.55 1.01
vertex 5.85 -1.55 1.01
vertex 5.85 -1.55 0.81
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 5.85 -1.05 1.01
vertex 5.85 -1.05 0.81
vertex 5.85 -1.55 0.81
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 5.85 -1.05 0.81
vertex 6.15 -1.55 0.81
vertex 5.85 -1.55 0.81
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex 6.15 -1.55 1.01
vertex 5.85 -1.55 0.81
vertex 6.15 -1.55 0.81
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 5.85 -1.06 1.02
vertex 5.85 -1.55 1.01
vertex 5.85 -1.54 1.02
endloop
endfacet
facet normal 0 -0.71 0.71
outer loop
vertex 5.85 -1.54 1.02
vertex 5.85 -1.55 1.01
vertex 6.15 -1.55 1.01
endloop
endfacet
facet normal 0 0.71 -0.71
outer loop
vertex 5.85 -1.55 1.01
vertex 5.85 -1.54 1.02
vertex 6.15 -1.54 1.02
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 5.85 -1.06 1.02
vertex 5.85 -1.05 1.01
vertex 5.85 -1.55 1.01
endloop
endfacet
facet normal 0 0.71 -0.71
outer loop
vertex 5.85 -1.55 1.01
vertex 6.15 -1.54 1.02
vertex 6.15 -1.55 1.01
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 5.85 -1.06 1.02
vertex 5.85 -1.54 1.02
vertex 6.15 -1.54 1.02
endloop
endfacet
facet normal 0 -0.71 0.71
outer loop
vertex 5.85 -1.54 1.02
vertex 6.15 -1.55 1.01
vertex 6.15 -1.54 1.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.16 -0.6 0.73
vertex 5.85 -1.27 0.73
vertex 5.84 -0.6 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.17 -1.73 0.73
vertex 5.85 -1.27 0.73
vertex 6.16 -1.27 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.16 -0.6 0.73
vertex 6.16 -1.27 0.73
vertex 5.85 -1.27 0.73
endloop
endfacet
facet normal 0 1 0
outer loop
vertex 6.15 -1.05 1.01
vertex 5.85 -1.05 0.81
vertex 5.85 -1.05 1.01
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 5.85 -1.05 0.81
vertex 6.15 -1.05 0.81
vertex 6.15 -1.55 0.81
endloop
endfacet
facet normal 0 1 0
outer loop
vertex 6.15 -1.05 1.01
vertex 6.15 -1.05 0.81
vertex 5.85 -1.05 0.81
endloop
endfacet
facet normal 0 -0.71 -0.71
outer loop
vertex 5.85 -1.06 1.02
vertex 5.85 -1.05 1.01
vertex 6.15 -1.05 1.01
endloop
endfacet
facet normal 0 0.71 0.71
outer loop
vertex 5.85 -1.05 1.01
vertex 5.85 -1.06 1.02
vertex 6.15 -1.06 1.02
endloop
endfacet
facet normal 0 0.71 0.71
outer loop
vertex 5.85 -1.05 1.01
vertex 6.15 -1.06 1.02
vertex 6.15 -1.05 1.01
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 5.85 -1.06 1.02
vertex 6.15 -1.54 1.02
vertex 6.15 -1.06 1.02
endloop
endfacet
facet normal 0 -0.71 -0.71
outer loop
vertex 5.85 -1.06 1.02
vertex 6.15 -1.05 1.01
vertex 6.15 -1.06 1.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.16 0.1 0.73
vertex 5.84 -0.6 0.73
vertex 5.84 0.1 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.16 0.1 0.73
vertex 6.16 -0.6 0.73
vertex 5.84 -0.6 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.16 0.1 0.73
vertex 5.84 0.1 0.73
vertex 5.84 0.61 0.73
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 5.86 0.4 1.09
vertex 5.86 0.04 0.81
vertex 5.86 0.05 1.08
endloop
endfacet
facet normal -0.04 -1 0.04
outer loop
vertex 6.14 0.04 1.08
vertex 5.86 0.05 1.08
vertex 5.86 0.04 0.81
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 5.86 0.4 1.09
vertex 5.86 0.4 0.8
vertex 5.86 0.04 0.81
endloop
endfacet
facet normal 0 -0.03 -1
outer loop
vertex 5.86 0.4 0.8
vertex 6.14 0.04 0.81
vertex 5.86 0.04 0.81
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex 6.14 0.04 1.08
vertex 5.86 0.04 0.81
vertex 6.14 0.04 0.81
endloop
endfacet
facet normal 0 -0.03 1
outer loop
vertex 5.86 0.4 1.09
vertex 5.86 0.05 1.08
vertex 6.14 0.04 1.08
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.16 0.61 0.73
vertex 6.16 0.1 0.73
vertex 5.84 0.61 0.73
endloop
endfacet
facet normal 0 1 0
outer loop
vertex 6.14 0.4 1.09
vertex 5.86 0.4 0.8
vertex 5.86 0.4 1.09
endloop
endfacet
facet normal 0 -0.03 -1
outer loop
vertex 5.86 0.4 0.8
vertex 6.14 0.4 0.8
vertex 6.14 0.04 0.81
endloop
endfacet
facet normal 0 1 0
outer loop
vertex 6.14 0.4 1.09
vertex 6.14 0.4 0.8
vertex 5.86 0.4 0.8
endloop
endfacet
facet normal 0 -0.03 1
outer loop
vertex 5.86 0.4 1.09
vertex 6.14 0.04 1.08
vertex 6.14 0.4 1.09
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 5.85 1.25 1.01
vertex 5.85 1.75 0.81
vertex 5.85 1.25 0.81
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex 5.85 1.25 1.01
vertex 5.85 1.25 0.81
vertex 6.15 1.25 0.81
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.15 1.25 0.81
vertex 5.85 1.25 0.81
vertex 5.85 1.75 0.81
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 5.85 1.26 1.02
vertex 5.85 1.75 1.01
vertex 5.85 1.25 1.01
endloop
endfacet
facet normal 0 -0.71 0.71
outer loop
vertex 6.15 1.25 1.01
vertex 5.85 1.26 1.02
vertex 5.85 1.25 1.01
endloop
endfacet
facet normal 0 0.71 -0.71
outer loop
vertex 6.15 1.26 1.02
vertex 5.85 1.25 1.01
vertex 5.85 1.26 1.02
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 5.85 1.25 1.01
vertex 5.85 1.75 1.01
vertex 5.85 1.75 0.81
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex 5.85 1.25 1.01
vertex 6.15 1.25 0.81
vertex 6.15 1.25 1.01
endloop
endfacet
facet normal 0 0.71 -0.71
outer loop
vertex 6.15 1.26 1.02
vertex 6.15 1.25 1.01
vertex 5.85 1.25 1.01
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 5.85 1.26 1.02
vertex 5.85 1.74 1.02
vertex 5.85 1.75 1.01
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 6.15 1.26 1.02
vertex 5.85 1.74 1.02
vertex 5.85 1.26 1.02
endloop
endfacet
facet normal 0 -0.71 0.71
outer loop
vertex 6.15 1.25 1.01
vertex 6.15 1.26 1.02
vertex 5.85 1.26 1.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.17 1.78 0.73
vertex 5.83 1.77 0.73
vertex 5.88 2.05 0.73
endloop
endfacet
facet normal 0 1 0
outer loop
vertex 5.85 1.75 1.01
vertex 6.15 1.75 0.81
vertex 5.85 1.75 0.81
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.15 1.25 0.81
vertex 5.85 1.75 0.81
vertex 6.15 1.75 0.81
endloop
endfacet
facet normal 0 -0.71 -0.71
outer loop
vertex 6.15 1.75 1.01
vertex 5.85 1.74 1.02
vertex 5.85 1.75 1.01
endloop
endfacet
facet normal 0 0.71 0.71
outer loop
vertex 6.15 1.74 1.02
vertex 5.85 1.75 1.01
vertex 5.85 1.74 1.02
endloop
endfacet
facet normal 0 1 0
outer loop
vertex 5.85 1.75 1.01
vertex 6.15 1.75 1.01
vertex 6.15 1.75 0.81
endloop
endfacet
facet normal 0 0.71 0.71
outer loop
vertex 6.15 1.74 1.02
vertex 6.15 1.75 1.01
vertex 5.85 1.75 1.01
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 6.15 1.26 1.02
vertex 6.15 1.74 1.02
vertex 5.85 1.74 1.02
endloop
endfacet
facet normal 0 -0.71 -0.71
outer loop
vertex 6.15 1.75 1.01
vertex 6.15 1.74 1.02
vertex 5.85 1.74 1.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.17 1.78 0.73
vertex 5.88 2.05 0.73
vertex 6.12 2.05 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.35 4.21 0.73
vertex 5.9 3.38 0.73
vertex 5.91 4.22 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.35 4.21 0.73
vertex 6.35 3.38 0.73
vertex 5.9 3.38 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.26 4.18 0.81
vertex 5.94 3.49 0.81
vertex 5.94 4.11 0.81
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.26 4.18 0.81
vertex 6.26 3.42 0.81
vertex 5.94 3.49 0.81
endloop
endfacet
facet normal 1 0 0.1
outer loop
vertex 6.01 4.12 1.28
vertex 5.95 3.4 1.89
vertex 6.01 3.48 1.28
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 6.26 4.18 1.28
vertex 6.01 4.12 1.28
vertex 6.01 3.48 1.28
endloop
endfacet
facet normal -0.23 -0.97 0
outer loop
vertex 6.26 3.42 1.28
vertex 6.01 3.48 1.28
vertex 6.26 3.42 0.81
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 6.26 4.18 1.28
vertex 6.01 3.48 1.28
vertex 6.26 3.42 1.28
endloop
endfacet
facet normal 1 0 0.1
outer loop
vertex 6.01 4.12 1.28
vertex 5.95 4.2 1.89
vertex 5.95 3.4 1.89
endloop
endfacet
facet normal -0.23 0.97 0
outer loop
vertex 6.26 4.18 1.28
vertex 6.26 4.18 0.81
vertex 6.01 4.12 1.28
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.35 -4.08 -0.02
vertex 9.37 -4.64 -0.02
vertex 6.43 -9.3 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.92 -4.64 -0.02
vertex 6.43 -9.3 -0.02
vertex 9.37 -4.64 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.28 -1.75 -0.02
vertex 9.35 -4.08 -0.02
vertex 6.43 -9.3 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.06 -4.69 -0.02
vertex 6.43 -9.3 -0.02
vertex 9.92 -4.64 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.22 -14.55 0
vertex 11.77 -14.9 0
vertex 6.43 -9.3 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.06 -4.69 -0.02
vertex 12.22 -14.55 0
vertex 6.43 -9.3 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.34 -4.09 0.73
vertex 6.43 -9.3 0.73
vertex 9.37 -4.65 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.92 -4.65 0.73
vertex 9.37 -4.65 0.73
vertex 6.43 -9.3 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.28 -1.75 0.73
vertex 6.43 -9.3 0.73
vertex 9.34 -4.09 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 12.06 -4.69 0.73
vertex 9.92 -4.65 0.73
vertex 6.43 -9.3 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 12.23 -14.54 0.71
vertex 6.43 -9.3 0.73
vertex 11.77 -14.9 0.71
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 12.06 -4.69 0.73
vertex 6.43 -9.3 0.73
vertex 12.23 -14.54 0.71
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 6.15 -1.05 1.01
vertex 6.15 -1.55 1.01
vertex 6.15 -1.55 0.81
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 6.15 -1.05 1.01
vertex 6.15 -1.55 0.81
vertex 6.15 -1.05 0.81
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 6.15 -1.06 1.02
vertex 6.15 -1.54 1.02
vertex 6.15 -1.55 1.01
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 6.15 -1.06 1.02
vertex 6.15 -1.55 1.01
vertex 6.15 -1.05 1.01
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 6.14 0.4 1.09
vertex 6.14 0.04 1.08
vertex 6.14 0.04 0.81
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 6.14 0.4 1.09
vertex 6.14 0.04 0.81
vertex 6.14 0.4 0.8
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 6.15 1.25 1.01
vertex 6.15 1.25 0.81
vertex 6.15 1.75 0.81
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 6.15 1.26 1.02
vertex 6.15 1.25 1.01
vertex 6.15 1.75 1.01
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 6.15 1.25 1.01
vertex 6.15 1.75 0.81
vertex 6.15 1.75 1.01
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 6.15 1.26 1.02
vertex 6.15 1.75 1.01
vertex 6.15 1.74 1.02
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 6.26 3.42 1.28
vertex 6.26 3.42 0.81
vertex 6.26 4.18 0.81
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 6.26 3.42 1.28
vertex 6.26 4.18 0.81
vertex 6.26 4.18 1.28
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 7 12.13 0.73
vertex 6.5 11.83 0.73
vertex 6.48 12.12 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 7 12.13 0.73
vertex 7 11.83 0.73
vertex 6.5 11.83 0.73
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 7 4.05 1.01
vertex 7 3.55 1.01
vertex 7 3.55 0.81
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 7 4.05 1.01
vertex 7 3.55 0.81
vertex 7 4.05 0.81
endloop
endfacet
facet normal 0.7 0.01 -0.71
outer loop
vertex 7 4.04 1.02
vertex 7.01 3.56 1.02
vertex 7 3.55 1.01
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 7 4.04 1.02
vertex 7 3.55 1.01
vertex 7 4.05 1.01
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 7.51 12.14 0.73
vertex 7 11.83 0.73
vertex 7 12.13 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 7.51 12.14 0.73
vertex 7.5 11.83 0.73
vertex 7 11.83 0.73
endloop
endfacet
facet normal -1 0 -0.05
outer loop
vertex 6.88 11.85 1.01
vertex 6.89 12.15 0.81
vertex 6.89 11.85 0.81
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex 7.29 11.85 1.01
vertex 6.88 11.85 1.01
vertex 6.89 11.85 0.81
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 7.29 12.15 0.81
vertex 6.89 11.85 0.81
vertex 6.89 12.15 0.81
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex 7.29 11.85 1.01
vertex 6.89 11.85 0.81
vertex 7.29 11.85 0.81
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 7.29 12.15 0.81
vertex 7.29 11.85 0.81
vertex 6.89 11.85 0.81
endloop
endfacet
facet normal 0.2 -0.01 -0.98
outer loop
vertex 6.89 12.15 1.01
vertex 6.93 11.85 1.02
vertex 6.88 11.85 1.01
endloop
endfacet
facet normal -0.2 0.01 0.98
outer loop
vertex 6.94 12.15 1.02
vertex 6.88 11.85 1.01
vertex 6.93 11.85 1.02
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex 7.29 11.85 1.01
vertex 6.93 11.85 1.02
vertex 6.88 11.85 1.01
endloop
endfacet
facet normal -1 0.03 0
outer loop
vertex 6.88 11.85 1.01
vertex 6.89 12.15 1.01
vertex 6.89 12.15 0.81
endloop
endfacet
facet normal -0.2 0.01 0.98
outer loop
vertex 6.94 12.15 1.02
vertex 6.89 12.15 1.01
vertex 6.88 11.85 1.01
endloop
endfacet
facet normal 0.2 -0.01 -0.98
outer loop
vertex 6.89 12.15 1.01
vertex 6.94 12.15 1.02
vertex 6.93 11.85 1.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 7.28 12.15 1.02
vertex 6.94 12.15 1.02
vertex 6.93 11.85 1.02
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex 7.28 11.85 1.02
vertex 6.93 11.85 1.02
vertex 7.29 11.85 1.01
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 7.28 12.15 1.02
vertex 6.93 11.85 1.02
vertex 7.28 11.85 1.02
endloop
endfacet
facet normal 0 1 0
outer loop
vertex 7.29 12.15 1.01
vertex 6.89 12.15 0.81
vertex 6.89 12.15 1.01
endloop
endfacet
facet normal 0 1 0
outer loop
vertex 7.29 12.15 1.01
vertex 7.29 12.15 0.81
vertex 6.89 12.15 0.81
endloop
endfacet
facet normal 0 1 0
outer loop
vertex 7.29 12.15 1.01
vertex 6.89 12.15 1.01
vertex 6.94 12.15 1.02
endloop
endfacet
facet normal 0 1 0
outer loop
vertex 7.28 12.15 1.02
vertex 7.29 12.15 1.01
vertex 6.94 12.15 1.02
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex 7.29 12.7 1.01
vertex 6.89 12.7 1.01
vertex 6.89 12.7 0.81
endloop
endfacet
facet normal 0.02 -1 -0.05
outer loop
vertex 7.29 12.7 1.01
vertex 6.89 12.7 0.81
vertex 7.29 12.71 0.81
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex 7.29 12.7 1.01
vertex 6.94 12.7 1.02
vertex 6.89 12.7 1.01
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex 7.28 12.7 1.02
vertex 6.94 12.7 1.02
vertex 7.29 12.7 1.01
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 7.29 11.85 1.01
vertex 7.29 11.85 0.81
vertex 7.29 12.15 0.81
endloop
endfacet
facet normal 0.71 0 0.71
outer loop
vertex 7.29 12.15 1.01
vertex 7.28 11.85 1.02
vertex 7.29 11.85 1.01
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 7.29 11.85 1.01
vertex 7.29 12.15 0.81
vertex 7.29 12.15 1.01
endloop
endfacet
facet normal 0.71 0 0.71
outer loop
vertex 7.29 12.15 1.01
vertex 7.28 12.15 1.02
vertex 7.28 11.85 1.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 8.92 -4.13 -0.02
vertex 8.94 -4.65 -0.02
vertex 9.35 -4.08 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 8.94 -4.65 -0.02
vertex 9.37 -4.64 -0.02
vertex 9.35 -4.08 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.34 -4.09 0.73
vertex 8.94 -4.65 0.73
vertex 8.92 -4.13 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.34 -4.09 0.73
vertex 9.37 -4.65 0.73
vertex 8.94 -4.65 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 8.89 -1.81 -0.02
vertex 8.98 -2.2 -0.02
vertex 9.28 -1.75 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 8.98 -2.2 -0.02
vertex 9.41 -2.26 -0.02
vertex 9.28 -1.75 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.28 -1.75 0.73
vertex 8.98 -2.2 0.73
vertex 8.89 -1.81 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.28 -1.75 0.73
vertex 9.4 -2.26 0.73
vertex 8.98 -2.2 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 8.98 -1.4 -0.02
vertex 8.89 -1.81 -0.02
vertex 9.28 -1.75 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 8.98 -1.4 0.73
vertex 9.28 -1.75 0.73
vertex 8.89 -1.81 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.43 -1.3 -0.02
vertex 8.98 -1.4 -0.02
vertex 9.28 -1.75 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.42 -1.3 0.73
vertex 9.28 -1.75 0.73
vertex 8.98 -1.4 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 8.94 1.06 -0.02
vertex 8.91 0.56 -0.02
vertex 9.34 0.56 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 8.91 0.56 -0.02
vertex 9.27 0.07 -0.02
vertex 9.34 0.56 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.34 0.55 0.73
vertex 8.91 0.56 0.73
vertex 8.94 1.06 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.34 0.55 0.73
vertex 9.27 0.07 0.73
vertex 8.91 0.56 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 8.94 1.06 -0.02
vertex 9.34 0.56 -0.02
vertex 9.39 1.13 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.38 1.12 0.73
vertex 9.34 0.55 0.73
vertex 8.94 1.06 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 8.92 3.49 -0.02
vertex 8.94 2.97 -0.02
vertex 9.36 3.52 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 8.94 2.97 -0.02
vertex 9.37 2.98 -0.02
vertex 9.36 3.52 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.36 3.52 0.73
vertex 8.94 2.97 0.73
vertex 8.92 3.49 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.36 3.52 0.73
vertex 9.37 2.97 0.73
vertex 8.94 2.97 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.28 3.96 -0.02
vertex 8.92 3.49 -0.02
vertex 9.36 3.52 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.28 3.96 0.73
vertex 9.36 3.52 0.73
vertex 8.92 3.49 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 8.89 5.81 -0.02
vertex 8.98 5.42 -0.02
vertex 9.27 5.78 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 8.98 5.42 -0.02
vertex 9.42 5.34 -0.02
vertex 9.27 5.78 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.28 5.79 0.73
vertex 8.98 5.42 0.73
vertex 8.89 5.81 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.28 5.79 0.73
vertex 9.42 5.34 0.73
vertex 8.98 5.42 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 8.98 6.22 -0.02
vertex 8.89 5.81 -0.02
vertex 9.27 5.78 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 8.98 6.22 0.73
vertex 9.28 5.79 0.73
vertex 8.89 5.81 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 8.98 6.22 -0.02
vertex 9.27 5.78 -0.02
vertex 9.41 6.27 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.41 6.27 0.73
vertex 9.28 5.79 0.73
vertex 8.98 6.22 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 8.94 8.68 -0.02
vertex 8.91 8.18 -0.02
vertex 9.37 8.66 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 8.91 8.18 -0.02
vertex 9.27 7.69 -0.02
vertex 9.36 8.12 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 8.91 8.18 -0.02
vertex 9.36 8.12 -0.02
vertex 9.37 8.66 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.36 8.66 0.73
vertex 8.91 8.18 0.73
vertex 8.94 8.68 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.36 8.12 0.73
vertex 9.27 7.69 0.73
vertex 8.91 8.18 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.36 8.66 0.73
vertex 9.36 8.12 0.73
vertex 8.91 8.18 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 8.92 11.11 -0.02
vertex 8.94 10.6 -0.02
vertex 9.3 11.04 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.3 11.04 -0.02
vertex 8.94 10.6 -0.02
vertex 9.38 10.51 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.31 11.05 0.73
vertex 8.94 10.6 0.73
vertex 8.92 11.11 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.31 11.05 0.73
vertex 9.38 10.52 0.73
vertex 8.94 10.6 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.41 11.46 -0.02
vertex 8.92 11.11 -0.02
vertex 9.3 11.04 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.41 11.46 0.73
vertex 9.31 11.05 0.73
vertex 8.92 11.11 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 8.88 13.34 -0.02
vertex 8.98 13.04 -0.02
vertex 9.3 13.29 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 8.98 13.04 -0.02
vertex 9.41 12.89 -0.02
vertex 9.3 13.29 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.31 13.29 0.73
vertex 8.98 13.04 0.73
vertex 8.88 13.34 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.31 13.29 0.73
vertex 9.41 12.88 0.73
vertex 8.98 13.04 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 8.94 13.76 -0.02
vertex 8.88 13.34 -0.02
vertex 9.3 13.29 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.31 13.29 0.73
vertex 8.88 13.34 0.73
vertex 8.94 13.76 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 8.94 13.76 -0.02
vertex 9.3 13.29 -0.02
vertex 9.39 13.83 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.38 13.82 0.73
vertex 9.31 13.29 0.73
vertex 8.94 13.76 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.37 -4.64 -0.02
vertex 9.35 -5.07 -0.02
vertex 9.83 -5.11 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.37 -4.65 0.73
vertex 9.83 -5.11 0.73
vertex 9.35 -5.07 0.73
endloop
endfacet
facet normal -1 -0.05 0
outer loop
vertex 9.37 -4.64 -0.02
vertex 9.37 -4.65 0.73
vertex 9.34 -4.09 0.73
endloop
endfacet
facet normal 0 1 0.01
outer loop
vertex 9.92 -4.64 -0.02
vertex 9.37 -4.64 -0.02
vertex 9.37 -4.65 0.73
endloop
endfacet
facet normal 0 -1 -0.01
outer loop
vertex 9.37 -4.64 -0.02
vertex 9.92 -4.65 0.73
vertex 9.37 -4.65 0.73
endloop
endfacet
facet normal -1 -0.04 -0.01
outer loop
vertex 9.37 -4.64 -0.02
vertex 9.34 -4.09 0.73
vertex 9.35 -4.08 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.37 -4.64 -0.02
vertex 9.83 -5.11 -0.02
vertex 9.92 -4.64 -0.02
endloop
endfacet
facet normal 0 -1 -0.01
outer loop
vertex 9.92 -4.64 -0.02
vertex 9.92 -4.65 0.73
vertex 9.37 -4.64 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.92 -4.65 0.73
vertex 9.83 -5.11 0.73
vertex 9.37 -4.65 0.73
endloop
endfacet
facet normal 0 1 0.01
outer loop
vertex 9.92 -4.64 -0.02
vertex 9.37 -4.65 0.73
vertex 9.92 -4.65 0.73
endloop
endfacet
facet normal -0.02 1 0.01
outer loop
vertex 9.35 -4.08 -0.02
vertex 9.34 -4.09 0.73
vertex 9.95 -4.08 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.35 -3.61 -0.02
vertex 9.35 -4.08 -0.02
vertex 9.82 -3.57 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.28 -1.75 -0.02
vertex 9.41 -2.26 -0.02
vertex 9.35 -4.08 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.41 -2.26 -0.02
vertex 9.95 -4.08 -0.02
vertex 9.35 -4.08 -0.02
endloop
endfacet
facet normal 0 1 0
outer loop
vertex 9.35 -4.08 -0.02
vertex 9.95 -4.08 0.73
vertex 9.95 -4.08 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.82 -3.57 -0.02
vertex 9.35 -4.08 -0.02
vertex 9.95 -4.08 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.83 -3.57 0.73
vertex 9.34 -4.09 0.73
vertex 9.35 -3.61 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.28 -1.75 0.73
vertex 9.34 -4.09 0.73
vertex 9.4 -2.26 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.4 -2.26 0.73
vertex 9.34 -4.09 0.73
vertex 9.95 -4.08 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.83 -3.57 0.73
vertex 9.95 -4.08 0.73
vertex 9.34 -4.09 0.73
endloop
endfacet
facet normal 0.97 0.25 0.01
outer loop
vertex 9.41 -2.26 -0.02
vertex 9.28 -1.75 -0.02
vertex 9.4 -2.26 0.73
endloop
endfacet
facet normal -0.97 -0.23 -0.01
outer loop
vertex 9.41 -2.26 -0.02
vertex 9.4 -2.26 0.73
vertex 9.28 -1.75 0.73
endloop
endfacet
facet normal 0.02 1 0
outer loop
vertex 9.84 -2.27 -0.02
vertex 9.41 -2.26 -0.02
vertex 9.4 -2.26 0.73
endloop
endfacet
facet normal -0.02 -1 0
outer loop
vertex 9.41 -2.26 -0.02
vertex 9.84 -2.27 0.73
vertex 9.4 -2.26 0.73
endloop
endfacet
facet normal -0.97 -0.25 0
outer loop
vertex 9.41 -2.26 -0.02
vertex 9.28 -1.75 0.73
vertex 9.28 -1.75 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.84 -2.27 -0.02
vertex 9.95 -4.08 -0.02
vertex 9.41 -2.26 -0.02
endloop
endfacet
facet normal -0.02 -1 0
outer loop
vertex 9.84 -2.27 -0.02
vertex 9.84 -2.27 0.73
vertex 9.41 -2.26 -0.02
endloop
endfacet
facet normal 0.97 0.23 0
outer loop
vertex 9.28 -1.75 -0.02
vertex 9.28 -1.75 0.73
vertex 9.4 -2.26 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.84 -2.27 0.73
vertex 9.4 -2.26 0.73
vertex 9.95 -4.08 0.73
endloop
endfacet
facet normal 0.02 1 0
outer loop
vertex 9.84 -2.27 -0.02
vertex 9.4 -2.26 0.73
vertex 9.84 -2.27 0.73
endloop
endfacet
facet normal -0.95 0.32 0
outer loop
vertex 9.28 -1.75 -0.02
vertex 9.28 -1.75 0.73
vertex 9.43 -1.3 -0.02
endloop
endfacet
facet normal 0.95 -0.3 0
outer loop
vertex 9.28 -1.75 -0.02
vertex 9.42 -1.3 0.73
vertex 9.28 -1.75 0.73
endloop
endfacet
facet normal 0.95 -0.32 0.01
outer loop
vertex 9.28 -1.75 -0.02
vertex 9.43 -1.3 -0.02
vertex 9.42 -1.3 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.34 0.56 -0.02
vertex 9.43 -1.3 -0.02
vertex 9.28 -1.75 -0.02
endloop
endfacet
facet normal -0.95 0.3 -0.01
outer loop
vertex 9.43 -1.3 -0.02
vertex 9.28 -1.75 0.73
vertex 9.42 -1.3 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.34 0.55 0.73
vertex 9.28 -1.75 0.73
vertex 9.42 -1.3 0.73
endloop
endfacet
facet normal -0.03 1 0
outer loop
vertex 9.43 -1.3 -0.02
vertex 9.42 -1.3 0.73
vertex 9.8 -1.29 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.34 0.56 -0.02
vertex 9.8 -1.28 -0.02
vertex 9.43 -1.3 -0.02
endloop
endfacet
facet normal -0.05 1 0.01
outer loop
vertex 9.43 -1.3 -0.02
vertex 9.8 -1.29 0.73
vertex 9.8 -1.28 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.34 0.55 0.73
vertex 9.42 -1.3 0.73
vertex 9.8 -1.29 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.34 0.56 -0.02
vertex 9.27 0.07 -0.02
vertex 9.79 0.03 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.34 0.55 0.73
vertex 9.79 0.04 0.73
vertex 9.27 0.07 0.73
endloop
endfacet
facet normal -1 0.07 0
outer loop
vertex 9.34 0.56 -0.02
vertex 9.34 0.55 0.73
vertex 9.38 1.12 0.73
endloop
endfacet
facet normal 0.76 0.65 0.01
outer loop
vertex 9.79 0.03 -0.02
vertex 9.34 0.56 -0.02
vertex 9.34 0.55 0.73
endloop
endfacet
facet normal -0.75 -0.66 -0.01
outer loop
vertex 9.34 0.56 -0.02
vertex 9.79 0.04 0.73
vertex 9.34 0.55 0.73
endloop
endfacet
facet normal 0.03 1 0.01
outer loop
vertex 9.97 0.54 -0.02
vertex 9.34 0.56 -0.02
vertex 9.34 0.55 0.73
endloop
endfacet
facet normal -1 0.09 -0.01
outer loop
vertex 9.34 0.56 -0.02
vertex 9.38 1.12 0.73
vertex 9.39 1.13 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.37 2.98 -0.02
vertex 9.39 1.13 -0.02
vertex 9.34 0.56 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.79 0.03 -0.02
vertex 9.8 -1.28 -0.02
vertex 9.34 0.56 -0.02
endloop
endfacet
facet normal -0.76 -0.65 0.01
outer loop
vertex 9.79 0.03 -0.02
vertex 9.79 0.04 0.73
vertex 9.34 0.56 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.34 0.56 -0.02
vertex 9.79 0.03 -0.02
vertex 9.97 0.54 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.37 2.97 0.73
vertex 9.34 0.55 0.73
vertex 9.38 1.12 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.79 0.04 0.73
vertex 9.34 0.55 0.73
vertex 9.8 -1.29 0.73
endloop
endfacet
facet normal 0.75 0.66 -0.01
outer loop
vertex 9.79 0.03 -0.02
vertex 9.34 0.55 0.73
vertex 9.79 0.04 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.97 0.54 0.73
vertex 9.79 0.04 0.73
vertex 9.34 0.55 0.73
endloop
endfacet
facet normal 0.02 1 0
outer loop
vertex 9.97 0.54 -0.02
vertex 9.34 0.55 0.73
vertex 9.97 0.54 0.73
endloop
endfacet
facet normal 0.04 1 0.01
outer loop
vertex 9.39 1.13 -0.02
vertex 9.38 1.12 0.73
vertex 9.89 1.1 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.46 1.51 -0.02
vertex 9.39 1.13 -0.02
vertex 9.75 1.53 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.92 2.98 -0.02
vertex 9.39 1.13 -0.02
vertex 9.37 2.98 -0.02
endloop
endfacet
facet normal 0.06 1 0
outer loop
vertex 9.39 1.13 -0.02
vertex 9.89 1.1 0.73
vertex 9.9 1.1 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.75 1.53 -0.02
vertex 9.39 1.13 -0.02
vertex 9.9 1.1 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.92 2.98 -0.02
vertex 9.9 1.1 -0.02
vertex 9.39 1.13 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.75 1.53 0.73
vertex 9.38 1.12 0.73
vertex 9.46 1.51 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.91 2.97 0.73
vertex 9.37 2.97 0.73
vertex 9.38 1.12 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.75 1.53 0.73
vertex 9.89 1.1 0.73
vertex 9.38 1.12 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.91 2.97 0.73
vertex 9.38 1.12 0.73
vertex 9.89 1.1 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.37 2.98 -0.02
vertex 9.35 2.55 -0.02
vertex 9.83 2.51 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.37 2.97 0.73
vertex 9.83 2.51 0.73
vertex 9.35 2.55 0.73
endloop
endfacet
facet normal -1 -0.02 0
outer loop
vertex 9.37 2.98 -0.02
vertex 9.37 2.97 0.73
vertex 9.36 3.52 0.73
endloop
endfacet
facet normal 0 1 0.01
outer loop
vertex 9.92 2.98 -0.02
vertex 9.37 2.98 -0.02
vertex 9.37 2.97 0.73
endloop
endfacet
facet normal 0 -1 -0.01
outer loop
vertex 9.37 2.98 -0.02
vertex 9.91 2.97 0.73
vertex 9.37 2.97 0.73
endloop
endfacet
facet normal -1 -0.02 0
outer loop
vertex 9.37 2.98 -0.02
vertex 9.36 3.52 0.73
vertex 9.36 3.52 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.37 2.98 -0.02
vertex 9.83 2.51 -0.02
vertex 9.92 2.98 -0.02
endloop
endfacet
facet normal 0 -1 -0.01
outer loop
vertex 9.92 2.98 -0.02
vertex 9.91 2.97 0.73
vertex 9.37 2.98 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.91 2.97 0.73
vertex 9.83 2.51 0.73
vertex 9.37 2.97 0.73
endloop
endfacet
facet normal 0 1 0.01
outer loop
vertex 9.92 2.98 -0.02
vertex 9.37 2.97 0.73
vertex 9.91 2.97 0.73
endloop
endfacet
facet normal -0.02 1 0
outer loop
vertex 9.36 3.52 -0.02
vertex 9.36 3.52 0.73
vertex 9.95 3.53 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.28 3.96 -0.02
vertex 9.36 3.52 -0.02
vertex 9.82 4.05 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.27 5.78 -0.02
vertex 9.42 5.34 -0.02
vertex 9.36 3.52 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.82 5.31 -0.02
vertex 9.36 3.52 -0.02
vertex 9.42 5.34 -0.02
endloop
endfacet
facet normal -0.03 1 0.01
outer loop
vertex 9.36 3.52 -0.02
vertex 9.95 3.53 0.73
vertex 9.95 3.54 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.82 4.05 -0.02
vertex 9.36 3.52 -0.02
vertex 9.95 3.54 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.82 5.31 -0.02
vertex 9.95 3.54 -0.02
vertex 9.36 3.52 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.82 4.05 0.73
vertex 9.36 3.52 0.73
vertex 9.28 3.96 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.28 5.79 0.73
vertex 9.36 3.52 0.73
vertex 9.42 5.34 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.81 5.31 0.73
vertex 9.42 5.34 0.73
vertex 9.36 3.52 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.82 4.05 0.73
vertex 9.95 3.53 0.73
vertex 9.36 3.52 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.81 5.31 0.73
vertex 9.36 3.52 0.73
vertex 9.95 3.53 0.73
endloop
endfacet
facet normal 0.95 0.32 0
outer loop
vertex 9.42 5.34 -0.02
vertex 9.27 5.78 -0.02
vertex 9.42 5.34 0.73
endloop
endfacet
facet normal -0.95 -0.3 0
outer loop
vertex 9.42 5.34 -0.02
vertex 9.42 5.34 0.73
vertex 9.28 5.79 0.73
endloop
endfacet
facet normal 0.07 1 0
outer loop
vertex 9.82 5.31 -0.02
vertex 9.42 5.34 -0.02
vertex 9.42 5.34 0.73
endloop
endfacet
facet normal -0.08 -1 0
outer loop
vertex 9.42 5.34 -0.02
vertex 9.81 5.31 0.73
vertex 9.42 5.34 0.73
endloop
endfacet
facet normal -0.95 -0.32 0.02
outer loop
vertex 9.42 5.34 -0.02
vertex 9.28 5.79 0.73
vertex 9.27 5.78 -0.02
endloop
endfacet
facet normal -0.07 -1 0
outer loop
vertex 9.82 5.31 -0.02
vertex 9.81 5.31 0.73
vertex 9.42 5.34 -0.02
endloop
endfacet
facet normal 0.95 0.3 -0.02
outer loop
vertex 9.27 5.78 -0.02
vertex 9.28 5.79 0.73
vertex 9.42 5.34 0.73
endloop
endfacet
facet normal 0.08 1 0
outer loop
vertex 9.82 5.31 -0.02
vertex 9.42 5.34 0.73
vertex 9.81 5.31 0.73
endloop
endfacet
facet normal 0.96 -0.27 -0.01
outer loop
vertex 9.27 5.78 -0.02
vertex 9.41 6.27 -0.02
vertex 9.28 5.79 0.73
endloop
endfacet
facet normal -0.97 0.26 0.01
outer loop
vertex 9.27 5.78 -0.02
vertex 9.28 5.79 0.73
vertex 9.41 6.27 0.73
endloop
endfacet
facet normal -0.96 0.27 0
outer loop
vertex 9.27 5.78 -0.02
vertex 9.41 6.27 0.73
vertex 9.41 6.27 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.36 8.12 -0.02
vertex 9.41 6.27 -0.02
vertex 9.27 5.78 -0.02
endloop
endfacet
facet normal 0.97 -0.26 0
outer loop
vertex 9.41 6.27 -0.02
vertex 9.41 6.27 0.73
vertex 9.28 5.79 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.36 8.12 0.73
vertex 9.28 5.79 0.73
vertex 9.41 6.27 0.73
endloop
endfacet
facet normal -0.05 1 0
outer loop
vertex 9.41 6.27 -0.02
vertex 9.41 6.27 0.73
vertex 9.84 6.29 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.36 8.12 -0.02
vertex 9.84 6.29 -0.02
vertex 9.41 6.27 -0.02
endloop
endfacet
facet normal -0.05 1 0
outer loop
vertex 9.41 6.27 -0.02
vertex 9.84 6.29 0.73
vertex 9.84 6.29 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.36 8.12 0.73
vertex 9.41 6.27 0.73
vertex 9.84 6.29 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.36 8.12 -0.02
vertex 9.27 7.69 -0.02
vertex 9.82 7.59 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.36 8.12 0.73
vertex 9.82 7.59 0.73
vertex 9.27 7.69 0.73
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 9.36 8.12 -0.02
vertex 9.36 8.12 0.73
vertex 9.36 8.66 0.73
endloop
endfacet
facet normal 0.03 1 0
outer loop
vertex 9.95 8.1 -0.02
vertex 9.36 8.12 -0.02
vertex 9.36 8.12 0.73
endloop
endfacet
facet normal -0.03 -1 0
outer loop
vertex 9.36 8.12 -0.02
vertex 9.94 8.1 0.73
vertex 9.36 8.12 0.73
endloop
endfacet
facet normal -1 0.02 -0.01
outer loop
vertex 9.36 8.12 -0.02
vertex 9.36 8.66 0.73
vertex 9.37 8.66 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.95 8.1 -0.02
vertex 9.84 6.29 -0.02
vertex 9.36 8.12 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.36 8.12 -0.02
vertex 9.82 7.59 -0.02
vertex 9.95 8.1 -0.02
endloop
endfacet
facet normal -0.03 -1 0
outer loop
vertex 9.95 8.1 -0.02
vertex 9.94 8.1 0.73
vertex 9.36 8.12 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.94 8.1 0.73
vertex 9.36 8.12 0.73
vertex 9.84 6.29 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.94 8.1 0.73
vertex 9.82 7.59 0.73
vertex 9.36 8.12 0.73
endloop
endfacet
facet normal 0.03 1 0
outer loop
vertex 9.95 8.1 -0.02
vertex 9.36 8.12 0.73
vertex 9.94 8.1 0.73
endloop
endfacet
facet normal 0 1 0
outer loop
vertex 9.37 8.66 -0.02
vertex 9.36 8.66 0.73
vertex 9.92 8.66 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.35 9.09 -0.02
vertex 9.37 8.66 -0.02
vertex 9.81 9.13 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.9 10.53 -0.02
vertex 9.37 8.66 -0.02
vertex 9.38 10.51 -0.02
endloop
endfacet
facet normal 0 1 0
outer loop
vertex 9.37 8.66 -0.02
vertex 9.92 8.66 0.73
vertex 9.92 8.66 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.81 9.13 -0.02
vertex 9.37 8.66 -0.02
vertex 9.92 8.66 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.9 10.53 -0.02
vertex 9.92 8.66 -0.02
vertex 9.37 8.66 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.81 9.13 0.73
vertex 9.36 8.66 0.73
vertex 9.35 9.09 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.89 10.53 0.73
vertex 9.38 10.52 0.73
vertex 9.36 8.66 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.81 9.13 0.73
vertex 9.92 8.66 0.73
vertex 9.36 8.66 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.89 10.53 0.73
vertex 9.36 8.66 0.73
vertex 9.92 8.66 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.38 10.51 -0.02
vertex 9.46 10.13 -0.02
vertex 9.75 10.11 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.38 10.52 0.73
vertex 9.75 10.11 0.73
vertex 9.46 10.13 0.73
endloop
endfacet
facet normal 0.99 0.15 0
outer loop
vertex 9.38 10.51 -0.02
vertex 9.3 11.04 -0.02
vertex 9.38 10.52 0.73
endloop
endfacet
facet normal -0.99 -0.13 0
outer loop
vertex 9.38 10.51 -0.02
vertex 9.38 10.52 0.73
vertex 9.31 11.05 0.73
endloop
endfacet
facet normal -0.04 1 -0.01
outer loop
vertex 9.9 10.53 -0.02
vertex 9.38 10.51 -0.02
vertex 9.38 10.52 0.73
endloop
endfacet
facet normal 0.02 -1 0.01
outer loop
vertex 9.38 10.51 -0.02
vertex 9.89 10.53 0.73
vertex 9.38 10.52 0.73
endloop
endfacet
facet normal -0.99 -0.15 0.02
outer loop
vertex 9.38 10.51 -0.02
vertex 9.31 11.05 0.73
vertex 9.3 11.04 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.38 10.51 -0.02
vertex 9.75 10.11 -0.02
vertex 9.9 10.53 -0.02
endloop
endfacet
facet normal 0.04 -1 0
outer loop
vertex 9.9 10.53 -0.02
vertex 9.89 10.53 0.73
vertex 9.38 10.51 -0.02
endloop
endfacet
facet normal 0.99 0.13 -0.01
outer loop
vertex 9.3 11.04 -0.02
vertex 9.31 11.05 0.73
vertex 9.38 10.52 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.89 10.53 0.73
vertex 9.75 10.11 0.73
vertex 9.38 10.52 0.73
endloop
endfacet
facet normal -0.02 1 0
outer loop
vertex 9.9 10.53 -0.02
vertex 9.38 10.52 0.73
vertex 9.89 10.53 0.73
endloop
endfacet
facet normal 0.97 -0.25 -0.01
outer loop
vertex 9.3 11.04 -0.02
vertex 9.41 11.46 -0.02
vertex 9.31 11.05 0.73
endloop
endfacet
facet normal -0.97 0.24 0.01
outer loop
vertex 9.3 11.04 -0.02
vertex 9.31 11.05 0.73
vertex 9.41 11.46 0.73
endloop
endfacet
facet normal -0.97 0.25 0
outer loop
vertex 9.3 11.04 -0.02
vertex 9.41 11.46 0.73
vertex 9.41 11.46 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.3 13.29 -0.02
vertex 9.41 11.46 -0.02
vertex 9.3 11.04 -0.02
endloop
endfacet
facet normal 0.97 -0.24 0
outer loop
vertex 9.41 11.46 -0.02
vertex 9.41 11.46 0.73
vertex 9.31 11.05 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.31 13.29 0.73
vertex 9.31 11.05 0.73
vertex 9.41 11.46 0.73
endloop
endfacet
facet normal -0.03 1 0
outer loop
vertex 9.41 11.46 -0.02
vertex 9.41 11.46 0.73
vertex 9.77 11.47 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.41 12.89 -0.02
vertex 9.41 11.46 -0.02
vertex 9.3 13.29 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.77 12.88 -0.02
vertex 9.41 11.46 -0.02
vertex 9.41 12.89 -0.02
endloop
endfacet
facet normal -0.03 1 0
outer loop
vertex 9.41 11.46 -0.02
vertex 9.77 11.47 0.73
vertex 9.77 11.47 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.77 12.88 -0.02
vertex 9.77 11.47 -0.02
vertex 9.41 11.46 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.41 12.88 0.73
vertex 9.31 13.29 0.73
vertex 9.41 11.46 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.77 12.88 0.73
vertex 9.41 12.88 0.73
vertex 9.41 11.46 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.77 12.88 0.73
vertex 9.41 11.46 0.73
vertex 9.77 11.47 0.73
endloop
endfacet
facet normal -0.97 -0.24 0
outer loop
vertex 9.41 12.89 -0.02
vertex 9.41 12.88 0.73
vertex 9.31 13.29 0.73
endloop
endfacet
facet normal 0.03 1 0.01
outer loop
vertex 9.77 12.88 -0.02
vertex 9.41 12.89 -0.02
vertex 9.41 12.88 0.73
endloop
endfacet
facet normal 0 -1 -0.01
outer loop
vertex 9.41 12.89 -0.02
vertex 9.77 12.88 0.73
vertex 9.41 12.88 0.73
endloop
endfacet
facet normal -0.96 -0.27 0.01
outer loop
vertex 9.41 12.89 -0.02
vertex 9.31 13.29 0.73
vertex 9.3 13.29 -0.02
endloop
endfacet
facet normal -0.03 -1 0
outer loop
vertex 9.77 12.88 -0.02
vertex 9.77 12.88 0.73
vertex 9.41 12.89 -0.02
endloop
endfacet
facet normal 0 1 0
outer loop
vertex 9.77 12.88 -0.02
vertex 9.41 12.88 0.73
vertex 9.77 12.88 0.73
endloop
endfacet
facet normal -0.99 0.13 0.01
outer loop
vertex 9.3 13.29 -0.02
vertex 9.31 13.29 0.73
vertex 9.38 13.82 0.73
endloop
endfacet
facet normal -0.99 0.16 -0.01
outer loop
vertex 9.3 13.29 -0.02
vertex 9.38 13.82 0.73
vertex 9.39 13.83 -0.02
endloop
endfacet
facet normal 0.02 1 0.01
outer loop
vertex 9.39 13.83 -0.02
vertex 9.38 13.82 0.73
vertex 9.89 13.81 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.46 14.21 -0.02
vertex 9.39 13.83 -0.02
vertex 9.74 14.23 -0.02
endloop
endfacet
facet normal 0.04 1 0
outer loop
vertex 9.39 13.83 -0.02
vertex 9.89 13.81 0.73
vertex 9.9 13.81 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.74 14.23 -0.02
vertex 9.39 13.83 -0.02
vertex 9.9 13.81 -0.02
endloop
endfacet
facet normal 0 0.02 -1
outer loop
vertex 11.77 15 0
vertex 9.9 13.81 -0.02
vertex 9.39 13.83 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.74 14.23 0.73
vertex 9.38 13.82 0.73
vertex 9.46 14.21 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.74 14.23 0.73
vertex 9.89 13.81 0.73
vertex 9.38 13.82 0.73
endloop
endfacet
facet normal 0 0.02 1
outer loop
vertex 11.77 15 0.71
vertex 9.38 13.82 0.73
vertex 9.89 13.81 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.92 -4.64 -0.02
vertex 9.83 -5.11 -0.02
vertex 10.35 -4.72 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.92 -4.64 -0.02
vertex 9.83 -5.11 -0.02
vertex 12.06 -4.69 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.83 -5.11 -0.02
vertex 12.17 -5.13 -0.02
vertex 12.06 -4.69 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 10.35 -4.72 0.73
vertex 9.83 -5.11 0.73
vertex 9.92 -4.65 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.06 -4.69 0.73
vertex 9.83 -5.11 0.73
vertex 9.92 -4.65 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.06 -4.69 0.73
vertex 12.17 -5.13 0.73
vertex 9.83 -5.11 0.73
endloop
endfacet
facet normal 1 -0.05 0
outer loop
vertex 9.95 -4.08 -0.02
vertex 9.92 -4.65 0.73
vertex 9.92 -4.64 -0.02
endloop
endfacet
facet normal -1 0.05 0
outer loop
vertex 9.92 -4.64 -0.02
vertex 9.92 -4.65 0.73
vertex 9.95 -4.08 0.73
endloop
endfacet
facet normal -1 0.05 0
outer loop
vertex 9.95 -4.08 -0.02
vertex 9.92 -4.64 -0.02
vertex 9.95 -4.08 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.95 -4.08 -0.02
vertex 9.92 -4.64 -0.02
vertex 10.35 -4.72 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.95 -4.08 -0.02
vertex 9.92 -4.64 -0.02
vertex 11.74 -4.56 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 11.75 -4.19 -0.02
vertex 9.92 -4.64 -0.02
vertex 9.95 -4.08 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 11.75 -4.19 -0.02
vertex 11.74 -4.56 -0.02
vertex 9.92 -4.64 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.92 -4.64 -0.02
vertex 12.06 -4.69 -0.02
vertex 11.74 -4.56 -0.02
endloop
endfacet
facet normal 1 -0.05 0
outer loop
vertex 9.95 -4.08 -0.02
vertex 9.95 -4.08 0.73
vertex 9.92 -4.65 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 10.35 -4.72 0.73
vertex 9.92 -4.65 0.73
vertex 9.95 -4.08 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 11.75 -4.2 0.73
vertex 9.92 -4.65 0.73
vertex 9.95 -4.08 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 11.75 -4.2 0.73
vertex 11.74 -4.56 0.73
vertex 9.92 -4.65 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 11.74 -4.56 0.73
vertex 12.06 -4.69 0.73
vertex 9.92 -4.65 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.82 -3.57 -0.02
vertex 9.95 -4.08 -0.02
vertex 10.38 -4.05 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.82 -3.57 -0.02
vertex 9.95 -4.08 -0.02
vertex 12.06 -3.99 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.11 -2.27 -0.02
vertex 9.95 -4.08 -0.02
vertex 9.84 -2.27 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.95 -4.08 -0.02
vertex 10.35 -4.72 -0.02
vertex 10.38 -4.05 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.95 -4.08 -0.02
vertex 11.74 -4.56 -0.02
vertex 11.75 -4.19 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.95 -4.08 -0.02
vertex 11.75 -4.19 -0.02
vertex 12.06 -3.99 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.11 -2.27 -0.02
vertex 12.06 -3.99 -0.02
vertex 9.95 -4.08 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 10.38 -4.05 0.73
vertex 9.95 -4.08 0.73
vertex 9.83 -3.57 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.17 -3.55 0.73
vertex 9.95 -4.08 0.73
vertex 9.83 -3.57 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 12.11 -2.26 0.73
vertex 9.84 -2.27 0.73
vertex 9.95 -4.08 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 10.38 -4.05 0.73
vertex 10.35 -4.72 0.73
vertex 9.95 -4.08 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.06 -3.99 0.73
vertex 11.75 -4.2 0.73
vertex 9.95 -4.08 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.17 -3.55 0.73
vertex 12.06 -3.99 0.73
vertex 9.95 -4.08 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 12.11 -2.26 0.73
vertex 9.95 -4.08 0.73
vertex 12.06 -3.99 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.82 -3.57 -0.02
vertex 12.06 -3.99 -0.02
vertex 12.17 -3.55 -0.02
endloop
endfacet
facet normal 0.92 -0.39 0
outer loop
vertex 10.06 -1.75 -0.02
vertex 9.84 -2.27 0.73
vertex 9.84 -2.27 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 10.06 -1.75 -0.02
vertex 9.84 -2.27 -0.02
vertex 10.3 -2.28 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 11.78 -1.8 -0.02
vertex 9.84 -2.27 -0.02
vertex 10.06 -1.75 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 10.06 -1.75 -0.02
vertex 9.84 -2.27 -0.02
vertex 12.11 -2.27 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 11.78 -1.8 -0.02
vertex 12.11 -2.27 -0.02
vertex 9.84 -2.27 -0.02
endloop
endfacet
facet normal 0.92 -0.39 0
outer loop
vertex 10.06 -1.75 -0.02
vertex 10.06 -1.75 0.73
vertex 9.84 -2.27 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 10.3 -2.28 0.73
vertex 9.84 -2.27 0.73
vertex 10.06 -1.75 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 11.78 -1.8 0.73
vertex 10.06 -1.75 0.73
vertex 9.84 -2.27 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 11.92 -1.67 0.73
vertex 9.84 -2.27 0.73
vertex 10.06 -1.75 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 11.78 -1.8 0.73
vertex 9.84 -2.27 0.73
vertex 12.11 -2.26 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 11.92 -1.67 0.73
vertex 12.11 -2.26 0.73
vertex 9.84 -2.27 0.73
endloop
endfacet
facet normal 0.88 0.48 0
outer loop
vertex 9.8 -1.28 -0.02
vertex 10.06 -1.75 0.73
vertex 10.06 -1.75 -0.02
endloop
endfacet
facet normal -0.87 -0.49 0
outer loop
vertex 10.06 -1.75 -0.02
vertex 10.06 -1.75 0.73
vertex 9.8 -1.29 0.73
endloop
endfacet
facet normal -0.88 -0.48 -0.01
outer loop
vertex 9.8 -1.28 -0.02
vertex 10.06 -1.75 -0.02
vertex 9.8 -1.29 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.97 0.54 -0.02
vertex 10.06 -1.75 -0.02
vertex 9.8 -1.28 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.8 -1.28 -0.02
vertex 10.06 -1.75 -0.02
vertex 10.3 -1.32 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.8 -1.28 -0.02
vertex 10.06 -1.75 -0.02
vertex 11.92 -1.67 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.05 0.4 -0.02
vertex 10.06 -1.75 -0.02
vertex 9.97 0.54 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 10.06 -1.75 -0.02
vertex 10.3 -2.28 -0.02
vertex 10.45 -1.81 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 10.3 -1.32 -0.02
vertex 10.06 -1.75 -0.02
vertex 10.45 -1.81 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 10.06 -1.75 -0.02
vertex 11.92 -1.67 -0.02
vertex 11.78 -1.8 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 10.06 -1.75 -0.02
vertex 12.11 -2.27 -0.02
vertex 11.92 -1.67 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.05 0.4 -0.02
vertex 11.92 -1.67 -0.02
vertex 10.06 -1.75 -0.02
endloop
endfacet
facet normal 0.87 0.49 0.01
outer loop
vertex 9.8 -1.28 -0.02
vertex 9.8 -1.29 0.73
vertex 10.06 -1.75 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.97 0.54 0.73
vertex 9.8 -1.29 0.73
vertex 10.06 -1.75 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 10.3 -1.32 0.73
vertex 10.06 -1.75 0.73
vertex 9.8 -1.29 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.15 -1.28 0.73
vertex 10.06 -1.75 0.73
vertex 9.8 -1.29 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 12.05 0.4 0.73
vertex 9.97 0.54 0.73
vertex 10.06 -1.75 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 10.45 -1.81 0.73
vertex 10.3 -2.28 0.73
vertex 10.06 -1.75 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 10.3 -1.32 0.73
vertex 10.45 -1.81 0.73
vertex 10.06 -1.75 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 11.78 -1.8 0.73
vertex 11.92 -1.67 0.73
vertex 10.06 -1.75 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.15 -1.28 0.73
vertex 11.92 -1.67 0.73
vertex 10.06 -1.75 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 12.05 0.4 0.73
vertex 10.06 -1.75 0.73
vertex 11.92 -1.67 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 9.97 0.54 -0.02
vertex 9.8 -1.28 -0.02
vertex 9.79 0.03 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.8 -1.28 -0.02
vertex 11.92 -1.67 -0.02
vertex 12.15 -1.29 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.97 0.54 0.73
vertex 9.79 0.04 0.73
vertex 9.8 -1.29 0.73
endloop
endfacet
facet normal 0.94 -0.33 0
outer loop
vertex 9.97 0.54 -0.02
vertex 9.79 0.04 0.73
vertex 9.79 0.03 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.97 0.54 -0.02
vertex 9.79 0.03 -0.02
vertex 10.24 0.17 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.97 0.54 -0.02
vertex 9.79 0.03 -0.02
vertex 12.19 0.03 -0.02
endloop
endfacet
facet normal 0.94 -0.34 0
outer loop
vertex 9.97 0.54 -0.02
vertex 9.97 0.54 0.73
vertex 9.79 0.04 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 10.24 0.17 0.73
vertex 9.79 0.04 0.73
vertex 9.97 0.54 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.19 0.03 0.73
vertex 9.79 0.04 0.73
vertex 9.97 0.54 0.73
endloop
endfacet
facet normal 0.99 0.12 0
outer loop
vertex 9.9 1.1 -0.02
vertex 9.97 0.54 0.73
vertex 9.97 0.54 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.9 1.1 -0.02
vertex 9.97 0.54 -0.02
vertex 10.34 1.14 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.9 1.1 -0.02
vertex 9.97 0.54 -0.02
vertex 11.78 0.68 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.97 0.54 -0.02
vertex 10.24 0.17 -0.02
vertex 10.43 0.55 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.97 0.54 -0.02
vertex 10.43 0.55 -0.02
vertex 10.34 1.14 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.97 0.54 -0.02
vertex 12.05 0.4 -0.02
vertex 11.78 0.68 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.97 0.54 -0.02
vertex 12.19 0.03 -0.02
vertex 12.05 0.4 -0.02
endloop
endfacet
facet normal 0.99 0.14 0.01
outer loop
vertex 9.9 1.1 -0.02
vertex 9.89 1.1 0.73
vertex 9.97 0.54 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 10.34 1.14 0.73
vertex 9.97 0.54 0.73
vertex 9.89 1.1 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 11.78 0.68 0.73
vertex 9.97 0.54 0.73
vertex 9.89 1.1 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 10.43 0.55 0.73
vertex 10.24 0.17 0.73
vertex 9.97 0.54 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 10.34 1.14 0.73
vertex 10.43 0.55 0.73
vertex 9.97 0.54 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 11.78 0.68 0.73
vertex 12.05 0.4 0.73
vertex 9.97 0.54 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.05 0.4 0.73
vertex 12.19 0.03 0.73
vertex 9.97 0.54 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.75 1.53 -0.02
vertex 9.9 1.1 -0.02
vertex 12.17 1.53 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.06 2.93 -0.02
vertex 9.9 1.1 -0.02
vertex 9.92 2.98 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 11.69 1.13 -0.02
vertex 11.78 0.68 -0.02
vertex 9.9 1.1 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.9 1.1 -0.02
vertex 11.78 0.68 -0.02
vertex 12.06 1.09 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 12.06 1.09 -0.02
vertex 11.69 1.13 -0.02
vertex 9.9 1.1 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.9 1.1 -0.02
vertex 12.06 1.09 -0.02
vertex 12.17 1.53 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.06 2.93 -0.02
vertex 12.06 1.09 -0.02
vertex 9.9 1.1 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.17 1.53 0.73
vertex 9.89 1.1 0.73
vertex 9.75 1.53 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 12.06 2.93 0.73
vertex 9.91 2.97 0.73
vertex 9.89 1.1 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 11.69 1.13 0.73
vertex 9.89 1.1 0.73
vertex 11.78 0.68 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.06 1.09 0.73
vertex 11.78 0.68 0.73
vertex 9.89 1.1 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.06 1.09 0.73
vertex 9.89 1.1 0.73
vertex 11.69 1.13 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.17 1.53 0.73
vertex 12.06 1.09 0.73
vertex 9.89 1.1 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 12.06 2.93 0.73
vertex 9.89 1.1 0.73
vertex 12.06 1.09 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.92 2.98 -0.02
vertex 9.83 2.51 -0.02
vertex 10.35 2.9 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.92 2.98 -0.02
vertex 9.83 2.51 -0.02
vertex 12.06 2.93 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.83 2.51 -0.02
vertex 12.17 2.49 -0.02
vertex 12.06 2.93 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 10.35 2.9 0.73
vertex 9.83 2.51 0.73
vertex 9.91 2.97 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.06 2.93 0.73
vertex 9.83 2.51 0.73
vertex 9.91 2.97 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.06 2.93 0.73
vertex 12.17 2.49 0.73
vertex 9.83 2.51 0.73
endloop
endfacet
facet normal 1 -0.05 0.01
outer loop
vertex 9.95 3.54 -0.02
vertex 9.91 2.97 0.73
vertex 9.92 2.98 -0.02
endloop
endfacet
facet normal -1 0.07 -0.01
outer loop
vertex 9.92 2.98 -0.02
vertex 9.91 2.97 0.73
vertex 9.95 3.53 0.73
endloop
endfacet
facet normal -1 0.05 0
outer loop
vertex 9.95 3.54 -0.02
vertex 9.92 2.98 -0.02
vertex 9.95 3.53 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.95 3.54 -0.02
vertex 9.92 2.98 -0.02
vertex 10.35 2.9 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.95 3.54 -0.02
vertex 9.92 2.98 -0.02
vertex 11.75 2.99 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.92 2.98 -0.02
vertex 12.06 2.93 -0.02
vertex 11.75 2.99 -0.02
endloop
endfacet
facet normal 1 -0.07 0
outer loop
vertex 9.95 3.54 -0.02
vertex 9.95 3.53 0.73
vertex 9.91 2.97 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 10.35 2.9 0.73
vertex 9.91 2.97 0.73
vertex 9.95 3.53 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 11.75 2.99 0.73
vertex 9.91 2.97 0.73
vertex 9.95 3.53 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 11.75 2.99 0.73
vertex 12.06 2.93 0.73
vertex 9.91 2.97 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.82 4.05 -0.02
vertex 9.95 3.54 -0.02
vertex 10.24 3.85 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.82 4.05 -0.02
vertex 9.95 3.54 -0.02
vertex 12.06 3.63 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.14 5.32 -0.02
vertex 9.95 3.54 -0.02
vertex 9.82 5.31 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.95 3.54 -0.02
vertex 10.35 2.9 -0.02
vertex 10.42 3.49 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 10.24 3.85 -0.02
vertex 9.95 3.54 -0.02
vertex 10.42 3.49 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.95 3.54 -0.02
vertex 11.75 2.99 -0.02
vertex 11.76 3.38 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.95 3.54 -0.02
vertex 11.76 3.38 -0.02
vertex 12.06 3.63 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.14 5.32 -0.02
vertex 12.06 3.63 -0.02
vertex 9.95 3.54 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 10.24 3.85 0.73
vertex 9.95 3.53 0.73
vertex 9.82 4.05 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.06 3.63 0.73
vertex 9.95 3.53 0.73
vertex 9.82 4.05 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 12.14 5.32 0.73
vertex 9.81 5.31 0.73
vertex 9.95 3.53 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 10.42 3.49 0.73
vertex 10.35 2.9 0.73
vertex 9.95 3.53 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 10.24 3.85 0.73
vertex 10.42 3.49 0.73
vertex 9.95 3.53 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 11.76 3.38 0.73
vertex 11.75 2.99 0.73
vertex 9.95 3.53 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.06 3.63 0.73
vertex 11.76 3.38 0.73
vertex 9.95 3.53 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 12.14 5.32 0.73
vertex 9.95 3.53 0.73
vertex 12.06 3.63 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.82 4.05 -0.02
vertex 12.06 3.63 -0.02
vertex 12.17 4.07 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.17 4.07 0.73
vertex 12.06 3.63 0.73
vertex 9.82 4.05 0.73
endloop
endfacet
facet normal 0.89 -0.45 0.01
outer loop
vertex 10.06 5.78 -0.02
vertex 9.81 5.31 0.73
vertex 9.82 5.31 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 10.06 5.78 -0.02
vertex 9.82 5.31 -0.02
vertex 10.31 5.35 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 11.78 5.82 -0.02
vertex 9.82 5.31 -0.02
vertex 10.06 5.78 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 10.06 5.78 -0.02
vertex 9.82 5.31 -0.02
vertex 11.92 5.71 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 11.78 5.82 -0.02
vertex 12.14 5.32 -0.02
vertex 9.82 5.31 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.82 5.31 -0.02
vertex 12.14 5.32 -0.02
vertex 11.92 5.71 -0.02
endloop
endfacet
facet normal 0.88 -0.47 0
outer loop
vertex 10.06 5.78 -0.02
vertex 10.06 5.78 0.73
vertex 9.81 5.31 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 10.31 5.35 0.73
vertex 9.81 5.31 0.73
vertex 10.06 5.78 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 11.78 5.82 0.73
vertex 10.06 5.78 0.73
vertex 9.81 5.31 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 11.92 5.71 0.73
vertex 9.81 5.31 0.73
vertex 10.06 5.78 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 11.78 5.82 0.73
vertex 9.81 5.31 0.73
vertex 12.14 5.32 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 11.92 5.71 0.73
vertex 12.14 5.32 0.73
vertex 9.81 5.31 0.73
endloop
endfacet
facet normal 0.92 0.4 0
outer loop
vertex 9.84 6.29 -0.02
vertex 10.06 5.78 0.73
vertex 10.06 5.78 -0.02
endloop
endfacet
facet normal -0.92 -0.4 0
outer loop
vertex 10.06 5.78 -0.02
vertex 10.06 5.78 0.73
vertex 9.84 6.29 0.73
endloop
endfacet
facet normal -0.92 -0.4 0
outer loop
vertex 9.84 6.29 -0.02
vertex 10.06 5.78 -0.02
vertex 9.84 6.29 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.84 6.29 -0.02
vertex 10.06 5.78 -0.02
vertex 10.31 6.29 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 11.78 5.82 -0.02
vertex 10.06 5.78 -0.02
vertex 9.84 6.29 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.84 6.29 -0.02
vertex 10.06 5.78 -0.02
vertex 11.92 5.71 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 10.06 5.78 -0.02
vertex 10.31 5.35 -0.02
vertex 10.45 5.81 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 10.31 6.29 -0.02
vertex 10.06 5.78 -0.02
vertex 10.45 5.81 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 10.06 5.78 -0.02
vertex 11.92 5.71 -0.02
vertex 11.78 5.82 -0.02
endloop
endfacet
facet normal 0.92 0.4 0
outer loop
vertex 9.84 6.29 -0.02
vertex 9.84 6.29 0.73
vertex 10.06 5.78 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 10.31 6.29 0.73
vertex 10.06 5.78 0.73
vertex 9.84 6.29 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 11.78 5.82 0.73
vertex 9.84 6.29 0.73
vertex 10.06 5.78 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 11.92 5.71 0.73
vertex 10.06 5.78 0.73
vertex 9.84 6.29 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 10.45 5.81 0.73
vertex 10.31 5.35 0.73
vertex 10.06 5.78 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 10.31 6.29 0.73
vertex 10.45 5.81 0.73
vertex 10.06 5.78 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 11.78 5.82 0.73
vertex 11.92 5.71 0.73
vertex 10.06 5.78 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.11 6.29 -0.02
vertex 9.84 6.29 -0.02
vertex 9.95 8.1 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.11 6.29 -0.02
vertex 11.78 5.82 -0.02
vertex 9.84 6.29 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.84 6.29 -0.02
vertex 11.92 5.71 -0.02
vertex 12.11 6.29 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 12.11 6.28 0.73
vertex 9.94 8.1 0.73
vertex 9.84 6.29 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 12.11 6.28 0.73
vertex 9.84 6.29 0.73
vertex 11.78 5.82 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.11 6.28 0.73
vertex 11.92 5.71 0.73
vertex 9.84 6.29 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.95 8.1 -0.02
vertex 9.82 7.59 -0.02
vertex 10.24 7.79 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.95 8.1 -0.02
vertex 9.82 7.59 -0.02
vertex 12.17 7.57 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 10.24 7.79 0.73
vertex 9.82 7.59 0.73
vertex 9.94 8.1 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.17 7.57 0.73
vertex 9.82 7.59 0.73
vertex 9.94 8.1 0.73
endloop
endfacet
facet normal 1 0.05 0.01
outer loop
vertex 9.92 8.66 -0.02
vertex 9.94 8.1 0.73
vertex 9.95 8.1 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.92 8.66 -0.02
vertex 9.95 8.1 -0.02
vertex 10.43 8.17 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.92 8.66 -0.02
vertex 9.95 8.1 -0.02
vertex 11.76 8.25 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 11.75 8.58 -0.02
vertex 9.95 8.1 -0.02
vertex 9.92 8.66 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.95 8.1 -0.02
vertex 10.24 7.79 -0.02
vertex 10.43 8.17 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 11.75 8.58 -0.02
vertex 11.76 8.25 -0.02
vertex 9.95 8.1 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.95 8.1 -0.02
vertex 12.06 8.01 -0.02
vertex 11.76 8.25 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.06 8.01 -0.02
vertex 12.11 6.29 -0.02
vertex 9.95 8.1 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.95 8.1 -0.02
vertex 12.17 7.57 -0.02
vertex 12.06 8.01 -0.02
endloop
endfacet
facet normal 1 0.04 0
outer loop
vertex 9.92 8.66 -0.02
vertex 9.92 8.66 0.73
vertex 9.94 8.1 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 10.43 8.17 0.73
vertex 9.94 8.1 0.73
vertex 9.92 8.66 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 11.76 8.25 0.73
vertex 9.94 8.1 0.73
vertex 9.92 8.66 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 11.74 8.58 0.73
vertex 9.92 8.66 0.73
vertex 9.94 8.1 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 10.43 8.17 0.73
vertex 10.24 7.79 0.73
vertex 9.94 8.1 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 11.74 8.58 0.73
vertex 9.94 8.1 0.73
vertex 11.76 8.25 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 11.76 8.25 0.73
vertex 12.06 8.01 0.73
vertex 9.94 8.1 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 12.06 8.01 0.73
vertex 9.94 8.1 0.73
vertex 12.11 6.28 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.06 8.01 0.73
vertex 12.17 7.57 0.73
vertex 9.94 8.1 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.81 9.13 -0.02
vertex 9.92 8.66 -0.02
vertex 10.34 8.76 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.81 9.13 -0.02
vertex 9.92 8.66 -0.02
vertex 12.17 9.15 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.06 10.55 -0.02
vertex 9.92 8.66 -0.02
vertex 9.9 10.53 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.92 8.66 -0.02
vertex 10.43 8.17 -0.02
vertex 10.34 8.76 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.92 8.66 -0.02
vertex 11.76 8.25 -0.02
vertex 11.75 8.58 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.92 8.66 -0.02
vertex 11.75 8.58 -0.02
vertex 12.06 8.71 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.92 8.66 -0.02
vertex 12.06 8.71 -0.02
vertex 12.17 9.15 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.06 10.55 -0.02
vertex 12.06 8.71 -0.02
vertex 9.92 8.66 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 10.34 8.76 0.73
vertex 9.92 8.66 0.73
vertex 9.81 9.13 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.17 9.15 0.73
vertex 9.92 8.66 0.73
vertex 9.81 9.13 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 12.06 10.55 0.73
vertex 9.89 10.53 0.73
vertex 9.92 8.66 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 10.34 8.76 0.73
vertex 10.43 8.17 0.73
vertex 9.92 8.66 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 11.74 8.58 0.73
vertex 11.76 8.25 0.73
vertex 9.92 8.66 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.06 8.71 0.73
vertex 11.74 8.58 0.73
vertex 9.92 8.66 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.17 9.15 0.73
vertex 12.06 8.71 0.73
vertex 9.92 8.66 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 12.06 10.55 0.73
vertex 9.92 8.66 0.73
vertex 12.06 8.71 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.9 10.53 -0.02
vertex 9.75 10.11 -0.02
vertex 12.17 10.11 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.17 10.11 0.73
vertex 9.75 10.11 0.73
vertex 9.89 10.53 0.73
endloop
endfacet
facet normal 0.97 -0.24 0.01
outer loop
vertex 10.03 11.06 -0.02
vertex 9.89 10.53 0.73
vertex 9.9 10.53 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 10.03 11.06 -0.02
vertex 9.9 10.53 -0.02
vertex 10.35 10.51 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 11.69 10.51 -0.02
vertex 9.9 10.53 -0.02
vertex 10.03 11.06 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 10.03 11.06 -0.02
vertex 9.9 10.53 -0.02
vertex 12.06 10.55 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 11.69 10.51 -0.02
vertex 12.06 10.55 -0.02
vertex 9.9 10.53 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.9 10.53 -0.02
vertex 12.17 10.11 -0.02
vertex 12.06 10.55 -0.02
endloop
endfacet
facet normal 0.97 -0.24 0.01
outer loop
vertex 10.03 11.06 -0.02
vertex 10.02 11.06 0.73
vertex 9.89 10.53 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 10.02 11.06 0.73
vertex 10.35 10.51 0.73
vertex 9.89 10.53 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 11.69 10.51 0.73
vertex 10.02 11.06 0.73
vertex 9.89 10.53 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 11.78 10.95 0.73
vertex 9.89 10.53 0.73
vertex 10.02 11.06 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 11.69 10.51 0.73
vertex 9.89 10.53 0.73
vertex 12.06 10.55 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 11.78 10.95 0.73
vertex 12.06 10.55 0.73
vertex 9.89 10.53 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.06 10.55 0.73
vertex 12.17 10.11 0.73
vertex 9.89 10.53 0.73
endloop
endfacet
facet normal 0.84 0.54 0.01
outer loop
vertex 9.77 11.47 -0.02
vertex 10.02 11.06 0.73
vertex 10.03 11.06 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 10.03 13.3 -0.02
vertex 10.03 11.06 -0.02
vertex 9.77 11.47 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.77 11.47 -0.02
vertex 10.03 11.06 -0.02
vertex 10.24 11.47 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.77 11.47 -0.02
vertex 10.03 11.06 -0.02
vertex 12.19 11.48 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 11.97 13.14 -0.02
vertex 10.03 11.06 -0.02
vertex 10.03 13.3 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 10.03 11.06 -0.02
vertex 10.35 10.51 -0.02
vertex 10.42 11.11 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 10.24 11.47 -0.02
vertex 10.03 11.06 -0.02
vertex 10.42 11.11 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 11.78 10.95 -0.02
vertex 11.69 10.51 -0.02
vertex 10.03 11.06 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 10.03 11.06 -0.02
vertex 12.06 10.55 -0.02
vertex 11.78 10.95 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 10.03 11.06 -0.02
vertex 11.78 10.95 -0.02
vertex 11.98 11.21 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 10.03 11.06 -0.02
vertex 11.98 11.21 -0.02
vertex 12.19 11.48 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 11.97 13.14 -0.02
vertex 11.98 11.21 -0.02
vertex 10.03 11.06 -0.02
endloop
endfacet
facet normal 0.85 0.52 0
outer loop
vertex 9.77 11.47 -0.02
vertex 9.77 11.47 0.73
vertex 10.02 11.06 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 10.03 13.3 0.73
vertex 9.77 11.47 0.73
vertex 10.02 11.06 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 10.24 11.47 0.73
vertex 10.02 11.06 0.73
vertex 9.77 11.47 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.19 11.48 0.73
vertex 10.02 11.06 0.73
vertex 9.77 11.47 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 11.97 13.14 0.73
vertex 10.03 13.3 0.73
vertex 10.02 11.06 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 10.42 11.11 0.73
vertex 10.35 10.51 0.73
vertex 10.02 11.06 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 10.24 11.47 0.73
vertex 10.42 11.11 0.73
vertex 10.02 11.06 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 11.78 10.95 0.73
vertex 10.02 11.06 0.73
vertex 11.69 10.51 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 11.98 11.2 0.73
vertex 11.78 10.95 0.73
vertex 10.02 11.06 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.19 11.48 0.73
vertex 11.98 11.2 0.73
vertex 10.02 11.06 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 11.97 13.14 0.73
vertex 10.02 11.06 0.73
vertex 11.98 11.2 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 10.03 13.3 -0.02
vertex 9.77 11.47 -0.02
vertex 9.77 12.88 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 10.03 13.3 0.73
vertex 9.77 12.88 0.73
vertex 9.77 11.47 0.73
endloop
endfacet
facet normal 0.85 -0.53 0
outer loop
vertex 10.03 13.3 -0.02
vertex 9.77 12.88 0.73
vertex 9.77 12.88 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 10.03 13.3 -0.02
vertex 9.77 12.88 -0.02
vertex 10.31 12.97 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 10.03 13.3 -0.02
vertex 9.77 12.88 -0.02
vertex 11.97 13.14 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.77 12.88 -0.02
vertex 12.18 12.88 -0.02
vertex 11.97 13.14 -0.02
endloop
endfacet
facet normal 0.85 -0.53 0
outer loop
vertex 10.03 13.3 -0.02
vertex 10.03 13.3 0.73
vertex 9.77 12.88 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 10.31 12.97 0.73
vertex 9.77 12.88 0.73
vertex 10.03 13.3 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 11.97 13.14 0.73
vertex 9.77 12.88 0.73
vertex 10.03 13.3 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 11.97 13.14 0.73
vertex 12.18 12.88 0.73
vertex 9.77 12.88 0.73
endloop
endfacet
facet normal 0.97 0.25 0
outer loop
vertex 9.9 13.81 -0.02
vertex 10.03 13.3 0.73
vertex 10.03 13.3 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.9 13.81 -0.02
vertex 10.03 13.3 -0.02
vertex 10.35 13.83 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 11.67 13.86 -0.02
vertex 10.03 13.3 -0.02
vertex 9.9 13.81 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.9 13.81 -0.02
vertex 10.03 13.3 -0.02
vertex 12.06 13.81 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 10.03 13.3 -0.02
vertex 10.31 12.97 -0.02
vertex 10.46 13.34 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 10.03 13.3 -0.02
vertex 10.46 13.34 -0.02
vertex 10.35 13.83 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 11.67 13.86 -0.02
vertex 11.78 13.39 -0.02
vertex 10.03 13.3 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 10.03 13.3 -0.02
vertex 11.97 13.14 -0.02
vertex 11.78 13.39 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 10.03 13.3 -0.02
vertex 11.78 13.39 -0.02
vertex 12.06 13.81 -0.02
endloop
endfacet
facet normal 0.96 0.26 0.01
outer loop
vertex 9.9 13.81 -0.02
vertex 9.89 13.81 0.73
vertex 10.03 13.3 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 10.35 13.83 0.73
vertex 10.03 13.3 0.73
vertex 9.89 13.81 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 11.67 13.86 0.73
vertex 9.89 13.81 0.73
vertex 10.03 13.3 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.06 13.81 0.73
vertex 10.03 13.3 0.73
vertex 9.89 13.81 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 10.46 13.34 0.73
vertex 10.31 12.97 0.73
vertex 10.03 13.3 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 10.35 13.83 0.73
vertex 10.46 13.34 0.73
vertex 10.03 13.3 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 11.67 13.86 0.73
vertex 10.03 13.3 0.73
vertex 11.78 13.39 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 11.78 13.39 0.73
vertex 11.97 13.14 0.73
vertex 10.03 13.3 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.06 13.81 0.73
vertex 11.78 13.39 0.73
vertex 10.03 13.3 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 9.74 14.23 -0.02
vertex 9.9 13.81 -0.02
vertex 12.06 13.81 -0.02
endloop
endfacet
facet normal 0 0.02 -1
outer loop
vertex 11.77 15 0
vertex 11.67 13.86 -0.02
vertex 9.9 13.81 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.06 13.81 0.73
vertex 9.89 13.81 0.73
vertex 9.74 14.23 0.73
endloop
endfacet
facet normal 0 0.02 1
outer loop
vertex 11.77 15 0.71
vertex 9.89 13.81 0.73
vertex 11.67 13.86 0.73
endloop
endfacet
facet normal 0 -0.02 1
outer loop
vertex 9.74 14.23 -0.02
vertex 12.06 13.81 -0.02
vertex 12.23 14.36 -0.01
endloop
endfacet
facet normal 0 -0.02 -1
outer loop
vertex 12.23 14.36 0.72
vertex 12.06 13.81 0.73
vertex 9.74 14.23 0.73
endloop
endfacet
facet normal 0.2 -0.98 0
outer loop
vertex 11.77 -14.9 0
vertex 11.97 -14.86 0.71
vertex 11.77 -14.9 0.71
endloop
endfacet
facet normal 0.2 -0.98 0
outer loop
vertex 11.77 -14.9 0
vertex 11.97 -14.86 0
vertex 11.97 -14.86 0.71
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.22 -14.55 0
vertex 11.97 -14.86 0
vertex 11.77 -14.9 0
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 12.23 -14.54 0.71
vertex 11.77 -14.9 0.71
vertex 11.97 -14.86 0.71
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 11.74 -4.56 -0.02
vertex 11.83 -5.01 -0.02
vertex 12.06 -4.69 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 12.06 -4.69 -0.02
vertex 11.83 -5.01 -0.02
vertex 12.17 -5.13 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.06 -4.69 0.73
vertex 11.83 -5.01 0.73
vertex 11.74 -4.56 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.06 -4.69 0.73
vertex 12.17 -5.13 0.73
vertex 11.83 -5.01 0.73
endloop
endfacet
facet normal -1 0.03 0
outer loop
vertex 11.75 -4.19 -0.02
vertex 11.74 -4.56 -0.02
vertex 11.74 -4.56 0.73
endloop
endfacet
facet normal 1 -0.03 0
outer loop
vertex 11.74 -4.56 -0.02
vertex 11.75 -4.2 0.73
vertex 11.74 -4.56 0.73
endloop
endfacet
facet normal 0.38 0.93 0
outer loop
vertex 12.06 -4.69 -0.02
vertex 11.74 -4.56 -0.02
vertex 11.74 -4.56 0.73
endloop
endfacet
facet normal -0.38 -0.93 0
outer loop
vertex 11.74 -4.56 -0.02
vertex 12.06 -4.69 0.73
vertex 11.74 -4.56 0.73
endloop
endfacet
facet normal 1 -0.03 0
outer loop
vertex 11.74 -4.56 -0.02
vertex 11.75 -4.19 -0.02
vertex 11.75 -4.2 0.73
endloop
endfacet
facet normal -0.38 -0.93 0
outer loop
vertex 11.74 -4.56 -0.02
vertex 12.06 -4.69 -0.02
vertex 12.06 -4.69 0.73
endloop
endfacet
facet normal -1 0.03 0
outer loop
vertex 11.75 -4.19 -0.02
vertex 11.74 -4.56 0.73
vertex 11.75 -4.2 0.73
endloop
endfacet
facet normal 0.38 0.93 0
outer loop
vertex 12.06 -4.69 -0.02
vertex 11.74 -4.56 0.73
vertex 12.06 -4.69 0.73
endloop
endfacet
facet normal -0.56 0.83 0.01
outer loop
vertex 11.75 -4.19 -0.02
vertex 11.75 -4.2 0.73
vertex 12.06 -3.99 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 11.75 -4.19 -0.02
vertex 12.06 -3.99 -0.02
vertex 11.83 -3.67 -0.02
endloop
endfacet
facet normal -0.54 0.84 0
outer loop
vertex 12.06 -3.99 -0.02
vertex 11.75 -4.19 -0.02
vertex 12.06 -3.99 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 11.83 -3.67 0.73
vertex 12.06 -3.99 0.73
vertex 11.75 -4.2 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 11.83 -3.67 -0.02
vertex 12.06 -3.99 -0.02
vertex 12.17 -3.55 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.17 -3.55 0.73
vertex 12.06 -3.99 0.73
vertex 11.83 -3.67 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 11.69 -2.33 -0.02
vertex 11.92 -1.67 -0.02
vertex 11.78 -1.8 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 11.92 -1.67 -0.02
vertex 11.69 -2.33 -0.02
vertex 12.11 -2.27 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 11.78 -1.8 0.73
vertex 11.92 -1.67 0.73
vertex 11.69 -2.33 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 11.92 -1.67 0.73
vertex 12.11 -2.26 0.73
vertex 11.69 -2.33 0.73
endloop
endfacet
facet normal 0.82 0.57 0
outer loop
vertex 12.11 -2.27 -0.02
vertex 11.78 -1.8 -0.02
vertex 11.78 -1.8 0.73
endloop
endfacet
facet normal -0.81 -0.58 0
outer loop
vertex 11.78 -1.8 -0.02
vertex 12.11 -2.26 0.73
vertex 11.78 -1.8 0.73
endloop
endfacet
facet normal -0.68 0.73 0
outer loop
vertex 11.92 -1.67 -0.02
vertex 11.78 -1.8 -0.02
vertex 11.78 -1.8 0.73
endloop
endfacet
facet normal 0.68 -0.73 0
outer loop
vertex 11.78 -1.8 -0.02
vertex 11.92 -1.67 0.73
vertex 11.78 -1.8 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 11.69 -1.27 -0.02
vertex 11.78 -1.8 -0.02
vertex 11.92 -1.67 -0.02
endloop
endfacet
facet normal -0.82 -0.57 0.01
outer loop
vertex 11.78 -1.8 -0.02
vertex 12.11 -2.27 -0.02
vertex 12.11 -2.26 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 11.92 -1.67 -0.02
vertex 12.11 -2.27 -0.02
vertex 11.78 -1.8 -0.02
endloop
endfacet
facet normal 0.68 -0.73 0
outer loop
vertex 11.78 -1.8 -0.02
vertex 11.92 -1.67 -0.02
vertex 11.92 -1.67 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 11.92 -1.67 0.73
vertex 11.78 -1.8 0.73
vertex 11.69 -1.27 0.73
endloop
endfacet
facet normal 0.81 0.58 -0.01
outer loop
vertex 12.11 -2.27 -0.02
vertex 11.78 -1.8 0.73
vertex 12.11 -2.26 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 11.92 -1.67 0.73
vertex 11.78 -1.8 0.73
vertex 12.11 -2.26 0.73
endloop
endfacet
facet normal -0.68 0.73 0
outer loop
vertex 11.92 -1.67 -0.02
vertex 11.78 -1.8 0.73
vertex 11.92 -1.67 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 11.69 -1.27 -0.02
vertex 11.92 -1.67 -0.02
vertex 12.15 -1.29 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 11.69 -1.27 0.73
vertex 12.15 -1.28 0.73
vertex 11.92 -1.67 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 11.78 0.68 -0.02
vertex 11.75 0.14 -0.02
vertex 12.05 0.4 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 12.05 0.4 -0.02
vertex 11.75 0.14 -0.02
vertex 12.19 0.03 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.05 0.4 0.73
vertex 11.75 0.14 0.73
vertex 11.78 0.68 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.05 0.4 0.73
vertex 12.19 0.03 0.73
vertex 11.75 0.14 0.73
endloop
endfacet
facet normal -0.98 -0.2 0
outer loop
vertex 11.69 1.13 -0.02
vertex 11.78 0.68 -0.02
vertex 11.78 0.68 0.73
endloop
endfacet
facet normal 0.98 0.2 0
outer loop
vertex 11.78 0.68 -0.02
vertex 11.69 1.13 0.73
vertex 11.78 0.68 0.73
endloop
endfacet
facet normal 0.72 0.69 0
outer loop
vertex 12.05 0.4 -0.02
vertex 11.78 0.68 -0.02
vertex 11.78 0.68 0.73
endloop
endfacet
facet normal -0.72 -0.69 0
outer loop
vertex 11.78 0.68 -0.02
vertex 12.05 0.4 0.73
vertex 11.78 0.68 0.73
endloop
endfacet
facet normal 0.83 -0.56 0
outer loop
vertex 11.78 0.68 -0.02
vertex 12.06 1.09 0.73
vertex 11.78 0.68 0.73
endloop
endfacet
facet normal 0.98 0.2 0
outer loop
vertex 11.78 0.68 -0.02
vertex 11.69 1.13 -0.02
vertex 11.69 1.13 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 11.69 1.13 -0.02
vertex 11.78 0.68 -0.02
vertex 12.06 1.09 -0.02
endloop
endfacet
facet normal -0.72 -0.69 0
outer loop
vertex 11.78 0.68 -0.02
vertex 12.05 0.4 -0.02
vertex 12.05 0.4 0.73
endloop
endfacet
facet normal 0.83 -0.56 0
outer loop
vertex 11.78 0.68 -0.02
vertex 12.06 1.09 -0.02
vertex 12.06 1.09 0.73
endloop
endfacet
facet normal -0.98 -0.2 0
outer loop
vertex 11.69 1.13 -0.02
vertex 11.78 0.68 0.73
vertex 11.69 1.13 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.06 1.09 0.73
vertex 11.78 0.68 0.73
vertex 11.69 1.13 0.73
endloop
endfacet
facet normal 0.72 0.69 0
outer loop
vertex 12.05 0.4 -0.02
vertex 11.78 0.68 0.73
vertex 12.05 0.4 0.73
endloop
endfacet
facet normal 0.11 0.99 0
outer loop
vertex 12.06 1.09 -0.02
vertex 11.69 1.13 -0.02
vertex 11.69 1.13 0.73
endloop
endfacet
facet normal -0.11 -0.99 0
outer loop
vertex 11.69 1.13 -0.02
vertex 12.06 1.09 0.73
vertex 11.69 1.13 0.73
endloop
endfacet
facet normal -0.11 -0.99 0
outer loop
vertex 11.69 1.13 -0.02
vertex 12.06 1.09 -0.02
vertex 12.06 1.09 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 11.69 1.13 -0.02
vertex 12.06 1.09 -0.02
vertex 12.17 1.53 -0.02
endloop
endfacet
facet normal 0.11 0.99 0
outer loop
vertex 12.06 1.09 -0.02
vertex 11.69 1.13 0.73
vertex 12.06 1.09 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.17 1.53 0.73
vertex 12.06 1.09 0.73
vertex 11.69 1.13 0.73
endloop
endfacet
facet normal -1 0.03 0
outer loop
vertex 11.76 3.38 -0.02
vertex 11.75 2.99 -0.02
vertex 11.75 2.99 0.73
endloop
endfacet
facet normal 1 -0.03 0
outer loop
vertex 11.75 2.99 -0.02
vertex 11.76 3.38 0.73
vertex 11.75 2.99 0.73
endloop
endfacet
facet normal 0.19 0.98 0
outer loop
vertex 12.06 2.93 -0.02
vertex 11.75 2.99 -0.02
vertex 11.75 2.99 0.73
endloop
endfacet
facet normal -0.19 -0.98 0
outer loop
vertex 11.75 2.99 -0.02
vertex 12.06 2.93 0.73
vertex 11.75 2.99 0.73
endloop
endfacet
facet normal 1 -0.03 0
outer loop
vertex 11.75 2.99 -0.02
vertex 11.76 3.38 -0.02
vertex 11.76 3.38 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 12.06 2.93 -0.02
vertex 11.75 2.99 -0.02
vertex 12.17 2.49 -0.02
endloop
endfacet
facet normal -0.19 -0.98 0
outer loop
vertex 11.75 2.99 -0.02
vertex 12.06 2.93 -0.02
vertex 12.06 2.93 0.73
endloop
endfacet
facet normal -1 0.03 0
outer loop
vertex 11.76 3.38 -0.02
vertex 11.75 2.99 0.73
vertex 11.76 3.38 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.06 2.93 0.73
vertex 12.17 2.49 0.73
vertex 11.75 2.99 0.73
endloop
endfacet
facet normal 0.19 0.98 0
outer loop
vertex 12.06 2.93 -0.02
vertex 11.75 2.99 0.73
vertex 12.06 2.93 0.73
endloop
endfacet
facet normal -0.64 0.77 0
outer loop
vertex 11.76 3.38 -0.02
vertex 11.76 3.38 0.73
vertex 12.06 3.63 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 11.75 3.88 -0.02
vertex 11.76 3.38 -0.02
vertex 12.06 3.63 -0.02
endloop
endfacet
facet normal -0.64 0.77 0
outer loop
vertex 12.06 3.63 -0.02
vertex 11.76 3.38 -0.02
vertex 12.06 3.63 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 11.75 3.88 0.73
vertex 12.06 3.63 0.73
vertex 11.76 3.38 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 11.75 3.88 -0.02
vertex 12.06 3.63 -0.02
vertex 12.17 4.07 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.17 4.07 0.73
vertex 12.06 3.63 0.73
vertex 11.75 3.88 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 11.69 5.29 -0.02
vertex 11.92 5.71 -0.02
vertex 11.78 5.82 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 11.92 5.71 -0.02
vertex 11.69 5.29 -0.02
vertex 12.14 5.32 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 11.78 5.82 0.73
vertex 11.92 5.71 0.73
vertex 11.69 5.29 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.14 5.32 0.73
vertex 11.69 5.29 0.73
vertex 11.92 5.71 0.73
endloop
endfacet
facet normal 0.81 0.58 0
outer loop
vertex 12.14 5.32 -0.02
vertex 11.78 5.82 -0.02
vertex 11.78 5.82 0.73
endloop
endfacet
facet normal 0.62 0.79 0
outer loop
vertex 11.92 5.71 -0.02
vertex 11.78 5.82 -0.02
vertex 11.78 5.82 0.73
endloop
endfacet
facet normal -0.62 -0.79 0
outer loop
vertex 11.78 5.82 -0.02
vertex 11.92 5.71 0.73
vertex 11.78 5.82 0.73
endloop
endfacet
facet normal -0.81 0.58 0
outer loop
vertex 11.78 5.82 -0.02
vertex 11.78 5.82 0.73
vertex 12.11 6.28 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 11.69 6.35 -0.02
vertex 11.78 5.82 -0.02
vertex 11.92 5.71 -0.02
endloop
endfacet
facet normal -0.62 -0.79 0
outer loop
vertex 11.78 5.82 -0.02
vertex 11.92 5.71 -0.02
vertex 11.92 5.71 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.11 6.29 -0.02
vertex 11.92 5.71 -0.02
vertex 11.78 5.82 -0.02
endloop
endfacet
facet normal -0.82 0.57 0.01
outer loop
vertex 12.11 6.29 -0.02
vertex 11.78 5.82 -0.02
vertex 12.11 6.28 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 11.92 5.71 0.73
vertex 11.78 5.82 0.73
vertex 11.69 6.35 0.73
endloop
endfacet
facet normal 0.81 0.58 0
outer loop
vertex 12.14 5.32 -0.02
vertex 11.78 5.82 0.73
vertex 12.14 5.32 0.73
endloop
endfacet
facet normal 0.62 0.79 0
outer loop
vertex 11.92 5.71 -0.02
vertex 11.78 5.82 0.73
vertex 11.92 5.71 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 12.11 6.28 0.73
vertex 11.78 5.82 0.73
vertex 11.92 5.71 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 11.69 6.35 -0.02
vertex 11.92 5.71 -0.02
vertex 12.11 6.29 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.11 6.28 0.73
vertex 11.92 5.71 0.73
vertex 11.69 6.35 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 11.76 8.25 -0.02
vertex 11.75 7.76 -0.02
vertex 12.06 8.01 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 12.06 8.01 -0.02
vertex 11.75 7.76 -0.02
vertex 12.17 7.57 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.06 8.01 0.73
vertex 11.75 7.76 0.73
vertex 11.76 8.25 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.06 8.01 0.73
vertex 12.17 7.57 0.73
vertex 11.75 7.76 0.73
endloop
endfacet
facet normal -1 -0.03 0
outer loop
vertex 11.75 8.58 -0.02
vertex 11.76 8.25 -0.02
vertex 11.76 8.25 0.73
endloop
endfacet
facet normal 1 0.06 0
outer loop
vertex 11.76 8.25 -0.02
vertex 11.74 8.58 0.73
vertex 11.76 8.25 0.73
endloop
endfacet
facet normal 0.62 0.78 0
outer loop
vertex 12.06 8.01 -0.02
vertex 11.76 8.25 -0.02
vertex 11.76 8.25 0.73
endloop
endfacet
facet normal -0.62 -0.78 0
outer loop
vertex 11.76 8.25 -0.02
vertex 12.06 8.01 0.73
vertex 11.76 8.25 0.73
endloop
endfacet
facet normal 1 0.03 0.01
outer loop
vertex 11.76 8.25 -0.02
vertex 11.75 8.58 -0.02
vertex 11.74 8.58 0.73
endloop
endfacet
facet normal -0.62 -0.78 0
outer loop
vertex 11.76 8.25 -0.02
vertex 12.06 8.01 -0.02
vertex 12.06 8.01 0.73
endloop
endfacet
facet normal -1 -0.06 -0.01
outer loop
vertex 11.75 8.58 -0.02
vertex 11.76 8.25 0.73
vertex 11.74 8.58 0.73
endloop
endfacet
facet normal 0.62 0.78 0
outer loop
vertex 12.06 8.01 -0.02
vertex 11.76 8.25 0.73
vertex 12.06 8.01 0.73
endloop
endfacet
facet normal -0.38 0.93 -0.01
outer loop
vertex 11.75 8.58 -0.02
vertex 11.74 8.58 0.73
vertex 12.06 8.71 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 11.75 8.58 -0.02
vertex 12.06 8.71 -0.02
vertex 11.83 9.03 -0.02
endloop
endfacet
facet normal -0.39 0.92 0
outer loop
vertex 12.06 8.71 -0.02
vertex 11.75 8.58 -0.02
vertex 12.06 8.71 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 11.83 9.03 0.73
vertex 12.06 8.71 0.73
vertex 11.74 8.58 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 11.83 9.03 -0.02
vertex 12.06 8.71 -0.02
vertex 12.17 9.15 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.17 9.15 0.73
vertex 12.06 8.71 0.73
vertex 11.83 9.03 0.73
endloop
endfacet
facet normal -0.98 0.2 0
outer loop
vertex 11.78 10.95 -0.02
vertex 11.69 10.51 -0.02
vertex 11.69 10.51 0.73
endloop
endfacet
facet normal 0.98 -0.2 0
outer loop
vertex 11.69 10.51 -0.02
vertex 11.78 10.95 0.73
vertex 11.69 10.51 0.73
endloop
endfacet
facet normal -0.11 0.99 0
outer loop
vertex 12.06 10.55 -0.02
vertex 11.69 10.51 -0.02
vertex 11.69 10.51 0.73
endloop
endfacet
facet normal 0.11 -0.99 0
outer loop
vertex 11.69 10.51 -0.02
vertex 12.06 10.55 0.73
vertex 11.69 10.51 0.73
endloop
endfacet
facet normal 0.98 -0.2 0
outer loop
vertex 11.69 10.51 -0.02
vertex 11.78 10.95 -0.02
vertex 11.78 10.95 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 11.69 10.51 -0.02
vertex 12.06 10.55 -0.02
vertex 11.78 10.95 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 12.06 10.55 -0.02
vertex 11.69 10.51 -0.02
vertex 12.17 10.11 -0.02
endloop
endfacet
facet normal 0.11 -0.99 0
outer loop
vertex 11.69 10.51 -0.02
vertex 12.06 10.55 -0.02
vertex 12.06 10.55 0.73
endloop
endfacet
facet normal -0.98 0.2 0
outer loop
vertex 11.78 10.95 -0.02
vertex 11.69 10.51 0.73
vertex 11.78 10.95 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 11.78 10.95 0.73
vertex 12.06 10.55 0.73
vertex 11.69 10.51 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.06 10.55 0.73
vertex 12.17 10.11 0.73
vertex 11.69 10.51 0.73
endloop
endfacet
facet normal -0.11 0.99 0
outer loop
vertex 12.06 10.55 -0.02
vertex 11.69 10.51 0.73
vertex 12.06 10.55 0.73
endloop
endfacet
facet normal 0.82 0.57 0
outer loop
vertex 12.06 10.55 -0.02
vertex 11.78 10.95 -0.02
vertex 11.78 10.95 0.73
endloop
endfacet
facet normal -0.79 0.61 0
outer loop
vertex 11.98 11.21 -0.02
vertex 11.78 10.95 -0.02
vertex 11.78 10.95 0.73
endloop
endfacet
facet normal 0.78 -0.62 0
outer loop
vertex 11.78 10.95 -0.02
vertex 11.98 11.2 0.73
vertex 11.78 10.95 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 11.75 11.5 -0.02
vertex 11.78 10.95 -0.02
vertex 11.98 11.21 -0.02
endloop
endfacet
facet normal 0.79 -0.61 -0.01
outer loop
vertex 11.78 10.95 -0.02
vertex 11.98 11.21 -0.02
vertex 11.98 11.2 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 11.75 11.5 0.73
vertex 11.98 11.2 0.73
vertex 11.78 10.95 0.73
endloop
endfacet
facet normal 0.82 0.57 0
outer loop
vertex 12.06 10.55 -0.02
vertex 11.78 10.95 0.73
vertex 12.06 10.55 0.73
endloop
endfacet
facet normal -0.78 0.62 0.01
outer loop
vertex 11.98 11.21 -0.02
vertex 11.78 10.95 0.73
vertex 11.98 11.2 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 11.75 11.5 -0.02
vertex 11.98 11.21 -0.02
vertex 12.19 11.48 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.19 11.48 0.73
vertex 11.98 11.2 0.73
vertex 11.75 11.5 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 11.78 13.39 -0.02
vertex 11.75 12.84 -0.02
vertex 11.97 13.14 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 11.97 13.14 -0.02
vertex 11.75 12.84 -0.02
vertex 12.18 12.88 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 11.97 13.14 0.73
vertex 11.75 12.84 0.73
vertex 11.78 13.39 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 11.97 13.14 0.73
vertex 12.18 12.88 0.73
vertex 11.75 12.84 0.73
endloop
endfacet
facet normal 0.97 0.23 0
outer loop
vertex 11.78 13.39 -0.02
vertex 11.67 13.86 0.73
vertex 11.78 13.39 0.73
endloop
endfacet
facet normal 0.8 0.61 0
outer loop
vertex 11.97 13.14 -0.02
vertex 11.78 13.39 -0.02
vertex 11.78 13.39 0.73
endloop
endfacet
facet normal -0.8 -0.61 0
outer loop
vertex 11.78 13.39 -0.02
vertex 11.97 13.14 0.73
vertex 11.78 13.39 0.73
endloop
endfacet
facet normal -0.83 0.55 0
outer loop
vertex 11.78 13.39 -0.02
vertex 11.78 13.39 0.73
vertex 12.06 13.81 0.73
endloop
endfacet
facet normal 0.97 0.23 0
outer loop
vertex 11.78 13.39 -0.02
vertex 11.67 13.86 -0.02
vertex 11.67 13.86 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 11.67 13.86 -0.02
vertex 11.78 13.39 -0.02
vertex 12.06 13.81 -0.02
endloop
endfacet
facet normal -0.8 -0.61 0
outer loop
vertex 11.78 13.39 -0.02
vertex 11.97 13.14 -0.02
vertex 11.97 13.14 0.73
endloop
endfacet
facet normal -0.83 0.55 0
outer loop
vertex 12.06 13.81 -0.02
vertex 11.78 13.39 -0.02
vertex 12.06 13.81 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.06 13.81 0.73
vertex 11.78 13.39 0.73
vertex 11.67 13.86 0.73
endloop
endfacet
facet normal 0.8 0.61 0
outer loop
vertex 11.97 13.14 -0.02
vertex 11.78 13.39 0.73
vertex 11.97 13.14 0.73
endloop
endfacet
facet normal -0.13 -0.99 0
outer loop
vertex 11.67 13.86 -0.02
vertex 12.06 13.81 0.73
vertex 11.67 13.86 0.73
endloop
endfacet
facet normal 0 0.02 -1
outer loop
vertex 11.77 15 0
vertex 12.06 13.81 -0.02
vertex 11.67 13.86 -0.02
endloop
endfacet
facet normal -0.13 -0.99 0
outer loop
vertex 11.67 13.86 -0.02
vertex 12.06 13.81 -0.02
vertex 12.06 13.81 0.73
endloop
endfacet
facet normal 0 0.02 1
outer loop
vertex 11.77 15 0.71
vertex 11.67 13.86 0.73
vertex 12.06 13.81 0.73
endloop
endfacet
facet normal 0.33 0.94 0
outer loop
vertex 12.03 14.91 0
vertex 11.77 15 0
vertex 11.77 15 0.71
endloop
endfacet
facet normal 0 0.02 -1
outer loop
vertex 11.77 15 0
vertex 12.23 14.36 -0.01
vertex 12.06 13.81 -0.02
endloop
endfacet
facet normal 0.01 0.02 -1
outer loop
vertex 12.03 14.91 0
vertex 12.23 14.36 -0.01
vertex 11.77 15 0
endloop
endfacet
facet normal 0 0.02 1
outer loop
vertex 11.77 15 0.71
vertex 12.06 13.81 0.73
vertex 12.23 14.36 0.72
endloop
endfacet
facet normal 0.01 0.02 1
outer loop
vertex 12.03 14.91 0.71
vertex 11.77 15 0.71
vertex 12.23 14.36 0.72
endloop
endfacet
facet normal 0.33 0.94 0
outer loop
vertex 12.03 14.91 0
vertex 11.77 15 0.71
vertex 12.03 14.91 0.71
endloop
endfacet
facet normal 0.78 -0.63 0
outer loop
vertex 11.97 -14.86 0
vertex 12.23 -14.54 0.71
vertex 11.97 -14.86 0.71
endloop
endfacet
facet normal 0.78 -0.63 0
outer loop
vertex 11.97 -14.86 0
vertex 12.22 -14.55 0
vertex 12.23 -14.54 0.71
endloop
endfacet
facet normal 1 0.02 -0.01
outer loop
vertex 12.22 -14.55 0
vertex 12.06 -4.69 -0.02
vertex 12.23 -14.54 0.71
endloop
endfacet
facet normal 1 0.02 0
outer loop
vertex 12.23 -14.54 0.71
vertex 12.06 -4.69 -0.02
vertex 12.06 -4.69 0.73
endloop
endfacet
facet normal 1 -0.03 0
outer loop
vertex 12.06 -3.99 -0.02
vertex 12.11 -2.26 0.73
vertex 12.06 -3.99 0.73
endloop
endfacet
facet normal 1 -0.03 0
outer loop
vertex 12.06 -3.99 -0.02
vertex 12.11 -2.27 -0.02
vertex 12.11 -2.26 0.73
endloop
endfacet
facet normal 0.95 0.31 0
outer loop
vertex 12.11 -2.27 -0.02
vertex 11.92 -1.67 0.73
vertex 12.11 -2.26 0.73
endloop
endfacet
facet normal 0.95 0.3 0
outer loop
vertex 12.11 -2.27 -0.02
vertex 11.92 -1.67 -0.02
vertex 11.92 -1.67 0.73
endloop
endfacet
facet normal -0.86 0.52 0
outer loop
vertex 12.15 -1.29 -0.02
vertex 11.92 -1.67 -0.02
vertex 11.92 -1.67 0.73
endloop
endfacet
facet normal 0.86 -0.51 0
outer loop
vertex 11.92 -1.67 -0.02
vertex 12.15 -1.28 0.73
vertex 11.92 -1.67 0.73
endloop
endfacet
facet normal 0.86 -0.52 0.01
outer loop
vertex 11.92 -1.67 -0.02
vertex 12.15 -1.29 -0.02
vertex 12.15 -1.28 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.05 0.4 -0.02
vertex 12.15 -1.29 -0.02
vertex 11.92 -1.67 -0.02
endloop
endfacet
facet normal -0.86 0.51 -0.01
outer loop
vertex 12.15 -1.29 -0.02
vertex 11.92 -1.67 0.73
vertex 12.15 -1.28 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 12.05 0.4 0.73
vertex 11.92 -1.67 0.73
vertex 12.15 -1.28 0.73
endloop
endfacet
facet normal 1 -0.03 0
outer loop
vertex 12.15 -1.29 -0.02
vertex 12.19 0.03 0.73
vertex 12.15 -1.28 0.73
endloop
endfacet
facet normal 1 -0.03 0
outer loop
vertex 12.15 -1.29 -0.02
vertex 12.19 0.03 -0.02
vertex 12.19 0.03 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.19 0.03 -0.02
vertex 12.15 -1.29 -0.02
vertex 12.05 0.4 -0.02
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 12.19 0.03 0.73
vertex 12.05 0.4 0.73
vertex 12.15 -1.28 0.73
endloop
endfacet
facet normal -0.94 -0.35 0
outer loop
vertex 12.05 0.4 -0.02
vertex 12.19 0.03 -0.02
vertex 12.19 0.03 0.73
endloop
endfacet
facet normal 0.94 0.35 0
outer loop
vertex 12.19 0.03 -0.02
vertex 12.05 0.4 0.73
vertex 12.19 0.03 0.73
endloop
endfacet
facet normal 0.94 0.35 0
outer loop
vertex 12.19 0.03 -0.02
vertex 12.05 0.4 -0.02
vertex 12.05 0.4 0.73
endloop
endfacet
facet normal -0.94 -0.35 0
outer loop
vertex 12.05 0.4 -0.02
vertex 12.19 0.03 0.73
vertex 12.05 0.4 0.73
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 12.06 1.09 -0.02
vertex 12.06 2.93 0.73
vertex 12.06 1.09 0.73
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 12.06 1.09 -0.02
vertex 12.06 2.93 -0.02
vertex 12.06 2.93 0.73
endloop
endfacet
facet normal 1 -0.05 0
outer loop
vertex 12.06 3.63 -0.02
vertex 12.14 5.32 0.73
vertex 12.06 3.63 0.73
endloop
endfacet
facet normal 1 -0.05 0
outer loop
vertex 12.06 3.63 -0.02
vertex 12.14 5.32 -0.02
vertex 12.14 5.32 0.73
endloop
endfacet
facet normal -0.87 -0.49 0
outer loop
vertex 11.92 5.71 -0.02
vertex 12.14 5.32 -0.02
vertex 12.14 5.32 0.73
endloop
endfacet
facet normal 0.87 0.49 0
outer loop
vertex 12.14 5.32 -0.02
vertex 11.92 5.71 0.73
vertex 12.14 5.32 0.73
endloop
endfacet
facet normal 0.87 0.49 0
outer loop
vertex 12.14 5.32 -0.02
vertex 11.92 5.71 -0.02
vertex 11.92 5.71 0.73
endloop
endfacet
facet normal -0.87 -0.49 0
outer loop
vertex 11.92 5.71 -0.02
vertex 12.14 5.32 0.73
vertex 11.92 5.71 0.73
endloop
endfacet
facet normal 0.95 -0.32 0
outer loop
vertex 11.92 5.71 -0.02
vertex 12.11 6.28 0.73
vertex 11.92 5.71 0.73
endloop
endfacet
facet normal 0.95 -0.31 0
outer loop
vertex 11.92 5.71 -0.02
vertex 12.11 6.29 -0.02
vertex 12.11 6.28 0.73
endloop
endfacet
facet normal 1 0.03 0
outer loop
vertex 12.11 6.29 -0.02
vertex 12.06 8.01 0.73
vertex 12.11 6.28 0.73
endloop
endfacet
facet normal 1 0.03 0
outer loop
vertex 12.11 6.29 -0.02
vertex 12.06 8.01 -0.02
vertex 12.06 8.01 0.73
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 12.06 8.71 -0.02
vertex 12.06 10.55 0.73
vertex 12.06 8.71 0.73
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 12.06 8.71 -0.02
vertex 12.06 10.55 -0.02
vertex 12.06 10.55 0.73
endloop
endfacet
facet normal -0.79 0.61 0.01
outer loop
vertex 12.19 11.48 -0.02
vertex 11.98 11.21 -0.02
vertex 11.98 11.2 0.73
endloop
endfacet
facet normal 0.8 -0.6 -0.01
outer loop
vertex 11.98 11.21 -0.02
vertex 12.19 11.48 0.73
vertex 11.98 11.2 0.73
endloop
endfacet
facet normal 0.79 -0.61 0
outer loop
vertex 11.98 11.21 -0.02
vertex 12.19 11.48 -0.02
vertex 12.19 11.48 0.73
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.18 12.88 -0.02
vertex 12.19 11.48 -0.02
vertex 11.98 11.21 -0.02
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.18 12.88 -0.02
vertex 11.98 11.21 -0.02
vertex 11.97 13.14 -0.02
endloop
endfacet
facet normal -0.8 0.6 0
outer loop
vertex 12.19 11.48 -0.02
vertex 11.98 11.2 0.73
vertex 12.19 11.48 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 12.18 12.88 0.73
vertex 11.98 11.2 0.73
vertex 12.19 11.48 0.73
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 12.18 12.88 0.73
vertex 11.97 13.14 0.73
vertex 11.98 11.2 0.73
endloop
endfacet
facet normal 1 0.01 0
outer loop
vertex 12.19 11.48 -0.02
vertex 12.18 12.88 0.73
vertex 12.19 11.48 0.73
endloop
endfacet
facet normal 1 0.01 0
outer loop
vertex 12.19 11.48 -0.02
vertex 12.18 12.88 -0.02
vertex 12.18 12.88 0.73
endloop
endfacet
facet normal -0.78 -0.63 0
outer loop
vertex 11.97 13.14 -0.02
vertex 12.18 12.88 -0.02
vertex 12.18 12.88 0.73
endloop
endfacet
facet normal 0.78 0.63 0
outer loop
vertex 12.18 12.88 -0.02
vertex 11.97 13.14 0.73
vertex 12.18 12.88 0.73
endloop
endfacet
facet normal 0.78 0.63 0
outer loop
vertex 12.18 12.88 -0.02
vertex 11.97 13.14 -0.02
vertex 11.97 13.14 0.73
endloop
endfacet
facet normal -0.78 -0.63 0
outer loop
vertex 11.97 13.14 -0.02
vertex 12.18 12.88 0.73
vertex 11.97 13.14 0.73
endloop
endfacet
facet normal 0.96 -0.3 0
outer loop
vertex 12.06 13.81 -0.02
vertex 12.23 14.36 0.72
vertex 12.06 13.81 0.73
endloop
endfacet
facet normal 0.96 -0.3 0
outer loop
vertex 12.06 13.81 -0.02
vertex 12.23 14.36 -0.01
vertex 12.23 14.36 0.72
endloop
endfacet
facet normal 0.94 0.34 0
outer loop
vertex 12.23 14.36 -0.01
vertex 12.03 14.91 0.71
vertex 12.23 14.36 0.72
endloop
endfacet
facet normal 0.94 0.34 0
outer loop
vertex 12.23 14.36 -0.01
vertex 12.03 14.91 0
vertex 12.03 14.91 0.71
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.88 -14.45 0.84
vertex 6.58 -14.45 0.84
vertex 6.58 -9.29 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.88 -14.45 0.84
vertex 6.58 -9.29 0.84
vertex 6.88 -9.29 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.88 -9.29 0.84
vertex 6.58 -9.29 0.84
vertex 6.58 -9.05 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.88 -9.29 0.84
vertex 6.58 -9.05 0.84
vertex 6.88 -9.05 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.58 -14.45 0.84
vertex 6.57 -14.45 0.84
vertex 6.57 -9.34 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.58 -14.45 0.84
vertex 6.57 -9.34 0.84
vertex 6.58 -9.29 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.58 -9.29 0.84
vertex 6.57 -9.27 0.84
vertex 6.57 -9.05 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.58 -9.29 0.84
vertex 6.57 -9.05 0.84
vertex 6.58 -9.05 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.57 -14.45 0.84
vertex 6.55 -14.45 0.84
vertex 6.55 -9.39 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.57 -14.45 0.84
vertex 6.55 -9.39 0.84
vertex 6.57 -9.35 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.57 -9.25 0.84
vertex 6.55 -9.22 0.84
vertex 6.55 -9.05 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.57 -9.25 0.84
vertex 6.55 -9.05 0.84
vertex 6.57 -9.05 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.55 -14.45 0.84
vertex 6.54 -14.45 0.84
vertex 6.54 -9.4 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.55 -14.45 0.84
vertex 6.54 -9.4 0.84
vertex 6.55 -9.39 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.55 -9.22 0.84
vertex 6.54 -9.2 0.84
vertex 6.54 -9.05 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.55 -9.22 0.84
vertex 6.54 -9.05 0.84
vertex 6.55 -9.05 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.54 -14.45 0.84
vertex 6.52 -14.45 0.84
vertex 6.52 -9.42 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.54 -14.45 0.84
vertex 6.52 -9.42 0.84
vertex 6.54 -9.4 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.54 -9.2 0.84
vertex 6.52 -9.18 0.84
vertex 6.52 -9.05 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.54 -9.2 0.84
vertex 6.52 -9.05 0.84
vertex 6.54 -9.05 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.52 -14.45 0.84
vertex 6.51 -14.45 0.84
vertex 6.51 -9.43 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.52 -14.45 0.84
vertex 6.51 -9.43 0.84
vertex 6.52 -9.42 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.52 -9.18 0.84
vertex 6.51 -9.17 0.84
vertex 6.51 -9.05 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.52 -9.18 0.84
vertex 6.51 -9.05 0.84
vertex 6.52 -9.05 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.51 -14.45 0.84
vertex 6.5 -14.45 0.84
vertex 6.5 -9.43 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.51 -14.45 0.84
vertex 6.5 -9.43 0.84
vertex 6.51 -9.43 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.51 -9.17 0.84
vertex 6.5 -9.17 0.84
vertex 6.5 -9.05 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.51 -9.17 0.84
vertex 6.5 -9.05 0.84
vertex 6.51 -9.05 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.5 -14.45 0.84
vertex 6.49 -14.45 0.84
vertex 6.49 -9.44 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.5 -14.45 0.84
vertex 6.49 -9.44 0.84
vertex 6.5 -9.43 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.5 -9.17 0.84
vertex 6.49 -9.16 0.84
vertex 6.49 -9.05 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.5 -9.17 0.84
vertex 6.49 -9.05 0.84
vertex 6.5 -9.05 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.49 -14.45 0.84
vertex 6.46 -14.45 0.84
vertex 6.46 -9.45 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.49 -14.45 0.84
vertex 6.46 -9.45 0.84
vertex 6.49 -9.44 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.49 -9.16 0.84
vertex 6.46 -9.15 0.84
vertex 6.46 -9.05 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.49 -9.16 0.84
vertex 6.46 -9.05 0.84
vertex 6.49 -9.05 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.46 -14.45 0.84
vertex 6.44 -14.45 0.84
vertex 6.44 -9.45 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.46 -14.45 0.84
vertex 6.44 -9.45 0.84
vertex 6.46 -9.45 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.46 -9.15 0.84
vertex 6.44 -9.15 0.84
vertex 6.44 -9.05 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.46 -9.15 0.84
vertex 6.44 -9.05 0.84
vertex 6.46 -9.05 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.44 -14.45 0.84
vertex 6.41 -14.45 0.84
vertex 6.41 -9.44 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.44 -14.45 0.84
vertex 6.41 -9.44 0.84
vertex 6.44 -9.45 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.44 -9.15 0.84
vertex 6.41 -9.15 0.84
vertex 6.41 -9.05 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.44 -9.15 0.84
vertex 6.41 -9.05 0.84
vertex 6.44 -9.05 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.41 -14.45 0.84
vertex 6.39 -14.45 0.84
vertex 6.39 -9.44 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.41 -14.45 0.84
vertex 6.39 -9.44 0.84
vertex 6.41 -9.44 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.41 -9.15 0.84
vertex 6.39 -9.16 0.84
vertex 6.39 -9.05 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.41 -9.15 0.84
vertex 6.39 -9.05 0.84
vertex 6.41 -9.05 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.39 -14.45 0.84
vertex 6.36 -14.45 0.84
vertex 6.36 -9.43 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.39 -14.45 0.84
vertex 6.36 -9.43 0.84
vertex 6.39 -9.44 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.39 -9.16 0.84
vertex 6.36 -9.17 0.84
vertex 6.36 -9.05 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.39 -9.16 0.84
vertex 6.36 -9.05 0.84
vertex 6.39 -9.05 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.36 -14.45 0.84
vertex 6.34 -14.45 0.84
vertex 6.34 -9.42 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.36 -14.45 0.84
vertex 6.34 -9.42 0.84
vertex 6.36 -9.43 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.36 -9.17 0.84
vertex 6.34 -9.18 0.84
vertex 6.34 -9.05 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.36 -9.17 0.84
vertex 6.34 -9.05 0.84
vertex 6.36 -9.05 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.34 -14.45 0.84
vertex 6.31 -14.45 0.84
vertex 6.31 -9.39 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.34 -14.45 0.84
vertex 6.31 -9.39 0.84
vertex 6.34 -9.42 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.34 -9.18 0.84
vertex 6.31 -9.21 0.84
vertex 6.31 -9.05 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.34 -9.18 0.84
vertex 6.31 -9.05 0.84
vertex 6.34 -9.05 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.31 -14.45 0.84
vertex 6.29 -14.45 0.84
vertex 6.29 -9.36 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.31 -14.45 0.84
vertex 6.29 -9.36 0.84
vertex 6.31 -9.39 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.31 -9.22 0.84
vertex 6.29 -9.25 0.84
vertex 6.29 -9.05 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.31 -9.22 0.84
vertex 6.29 -9.05 0.84
vertex 6.31 -9.05 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.29 -14.45 0.84
vertex 6.28 -14.45 0.84
vertex 6.28 -9.31 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.29 -14.45 0.84
vertex 6.28 -9.31 0.84
vertex 6.29 -9.35 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.29 -9.26 0.84
vertex 6.28 -9.31 0.84
vertex 6.28 -9.05 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.29 -9.26 0.84
vertex 6.28 -9.05 0.84
vertex 6.29 -9.05 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.28 -14.45 0.84
vertex 5.98 -14.45 0.84
vertex 5.98 -9.05 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.28 -14.45 0.84
vertex 5.98 -9.05 0.84
vertex 6.28 -9.05 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 5.98 -14.45 0.84
vertex 4.58 -14.45 0.84
vertex 4.58 -13.95 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 5.98 -14.45 0.84
vertex 4.58 -13.95 0.84
vertex 5.98 -13.95 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 4.58 -14.45 0.84
vertex 4.08 -14.45 0.84
vertex 4.08 -9.05 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 4.58 -14.45 0.84
vertex 4.08 -9.05 0.84
vertex 4.58 -9.05 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 4.08 -14.45 0.84
vertex 2.38 -14.45 0.84
vertex 2.38 -13.95 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 4.08 -14.45 0.84
vertex 2.38 -13.95 0.84
vertex 4.08 -13.95 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 2.38 -14.45 0.84
vertex 1.88 -14.45 0.84
vertex 1.88 -11.31 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 2.38 -14.45 0.84
vertex 1.88 -11.31 0.84
vertex 2.38 -11.31 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 1.88 -11.81 0.84
vertex -0.12 -11.81 0.84
vertex -0.12 -11.31 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 1.88 -11.81 0.84
vertex -0.12 -11.31 0.84
vertex 1.88 -11.31 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -0.12 -14.45 0.84
vertex -0.62 -14.45 0.84
vertex -0.62 -11.31 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -0.12 -14.45 0.84
vertex -0.62 -11.31 0.84
vertex -0.12 -11.31 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -0.62 -14.45 0.84
vertex -2.32 -14.45 0.84
vertex -2.32 -13.95 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -0.62 -14.45 0.84
vertex -2.32 -13.95 0.84
vertex -0.62 -13.95 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -2.32 -14.45 0.84
vertex -2.82 -14.45 0.84
vertex -2.82 -11.31 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -2.32 -14.45 0.84
vertex -2.82 -11.31 0.84
vertex -2.32 -11.31 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -2.82 -11.81 0.84
vertex -4.82 -11.81 0.84
vertex -4.82 -11.31 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -2.82 -11.81 0.84
vertex -4.82 -11.31 0.84
vertex -2.82 -11.31 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -4.82 -14.45 0.84
vertex -5.32 -14.45 0.84
vertex -5.32 -11.31 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -4.82 -14.45 0.84
vertex -5.32 -11.31 0.84
vertex -4.82 -11.31 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -5.32 -14.45 0.84
vertex -7.02 -14.45 0.84
vertex -7.02 -13.95 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -5.32 -14.45 0.84
vertex -7.02 -13.95 0.84
vertex -5.32 -13.95 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -7.02 -14.45 0.84
vertex -7.52 -14.45 0.84
vertex -7.52 -10.01 0.84
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -7.02 -14.45 0.84
vertex -7.52 -10.01 0.84
vertex -7.02 -10.01 0.84
endloop
endfacet
endsolid F4
```

![Assembled board in KiCad](docs/F4.png)


## Opening the design in KiCad

Download or clone the full repository to include the project libraries and 3D models. Open the [MIFA-F4 project](esp32c3mini-MIFA-F4/esp32c3mini.kicad_pro) in **KiCad 10**. Select the `.kicad_sch` file to view the schematic or the `.kicad_pcb` file to inspect the board layout. In the PCB Editor, press **Alt+3** to open the 3D Viewer.

## Fabrication and assembly

Choose the files for either a single board or a six-board panel. Use all three files from the same row.

| Format | PCB fabrication | Assembly parts list | Component positions and rotations |
| --- | --- | --- | --- |
| Single board | [Gerber ZIP](esp32c3mini-MIFA-F4/esp32c3mini-Gerber.zip) | [BOM](esp32c3mini-MIFA-F4/esp32c3mini-BOM.csv) | [CPL](esp32c3mini-MIFA-F4/esp32c3mini-CPL.csv) |
| Six-board panel | [Panel Gerber ZIP](esp32c3mini-MIFA-F4/panel/esp32c3mini-panel-Gerber.zip) | [Panel BOM](esp32c3mini-MIFA-F4/panel/esp32c3mini-panel-BOM.csv) | [Panel CPL](esp32c3mini-MIFA-F4/panel/esp32c3mini-panel-CPL.csv) |

For JLCPCB, upload the Gerber ZIP when ordering the PCB, then upload the matching BOM and CPL during assembly setup. Five assembled panels yield 30 individual boards.

## Prototype status

The design passed KiCad connectivity and schematic parity checks. Before assembly, verify the regulator orientation in the manufacturer's placement preview. With the component side facing up and USB-C at the top, the regulator should have three leads toward USB-C and pin 1 at the upper right.

Hardware validation is pending for USB-C operation in both plug orientations, supply stability during Wi-Fi transmission, and antenna performance on a board separated from the panel. See the [F4 validation notes](esp32c3mini-MIFA-F4/00-HOLD.txt).

## Prototype status and known limitations

**This board has not been physically tested.** The MIFA-F4 layout passed KiCad connectivity and schematic parity checks. Boot reliability, USB-C operation, power stability, and RF performance still require measurements on assembled hardware. Build and test a small prototype batch before ordering a production run.

### Before assembly

- Confirm the **0.8 mm PCB thickness** with the manufacturer. The board edge forms the USB-C mating surface, so thickness and routing tolerances affect the fit.
- Check the regulator orientation in the assembly preview. With the component side facing up and USB-C at the top, **U2 should have three leads toward USB-C and pin 1 at the upper right**. On the panel, the corresponding references are U102 through U602.

### First-prototype checks

| Area | What to verify |
| --- | --- |
| Power and boot | Check for a short between 3.3 V and GND before applying power. Use a current-limited supply for the first power-up, measure the 3.3 V rail, and check for voltage dips or resets during Wi-Fi transmission. Repeat cold starts to check boot reliability. |
| USB-C | Test plug fit, power delivery, USB detection, and firmware flashing in both plug orientations. Check that the connection stays stable during normal cable movement. Contact durability over repeated insertions is unverified. |
| BOOT and RESET | Confirm that holding BOOT while pressing and releasing RESET enters download mode, and that pressing RESET alone restarts the application. |
| Wi-Fi and antenna | Test a board **after separating it from the panel**. Compare signal strength and packet loss against a known-good ESP32-C3 board at the same distance and orientation on low, middle, and high Wi-Fi channels. Measure antenna return loss (S11) with a calibrated vector network analyzer to check impedance matching. |
| Board headers | Verify the 5 V, 3.3 V, and ground pins before connecting peripherals. Check the exposed GPIOs against the schematic and confirm the mechanical fit in the intended breadboard or carrier. |

The antenna layout follows TI AN043. Its range and susceptibility to interference from the nearby 40 MHz crystal are unverified on this PCB. See the [F4 validation notes](esp32c3mini-MIFA-F4/00-HOLD.txt) for layout dimensions and additional test details.
