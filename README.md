# BetterBoard

BetterBoard is a custom PCB I designed in KiCad. This repo contains the PCB design, schematics, and manufacturing files.

Betterboard is designed to operate efficiently on battery power and includes several debug LEDs. I created it because many of my projects rely on batteries, and troubleshooting them is often a major pain.

## USB Data Line Problem

One problem I ran into was routing the USB D+ and D- data lines. The connections crossed, which made it tricky to route the traces without interfering with each other.

![Crossed USB data lines](Images/Screenshot%202026-11-06%20172912.png)

## Finished PCB Design

After working through the routing issues, I finished the PCB layout. Here's the final design in KiCad.

![Finished PCB layout](Images/Screenshot%202026-11-08%20131323.png)
