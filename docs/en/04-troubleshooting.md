---
id: troubleshooting
title: If an LED stays dark
sidebar_position: 4
description: Dark section, SOIC bridges, power polarity, and overheated SMD LEDs on the SMD Solder Kit.
---

<p className="brand-kicker">Diagnostics</p>

# If an LED stays dark

The kit card has one rule: when soldering is correct, the section LED lights. Work from power down to the specific section.

![Check — the LED should light](../assets/images/en/how-it-works.png)

## Dark section

| Check | What should be true |
| --- | --- |
| USB | Cable and port supply 5 V. USB Type-C sits on all contacts, no solder ball inside the shield |
| Neighbor sections | If none light — check power and ICs first. If one is dark — its resistors and LED |
| Section resistor | R1–R5 for 0603, R6–R10 for 0805, R11–R15 for 1206. Both ends wetted, part not tombstoned |
| LED | Both pads soldered, package not overheated during assembly |
| 555 and 4017 | U1 — 555 in SOIC-8. U2 and U3 — 4017 in SOIC-16. Package key matches silkscreen, no bridged pins |

On the assembled sample, 0603 and 0805 are green; 1206 is red. Another section’s color does not indicate a fault: each section has its own LED.

## ICs

:::caution Package key
SOIC-8 (555) and SOIC-16 (4017) have a pin-1 mark. A reversed package leaves the chain dark and may heat after 5 V is applied. Remove power before reworking that IC.
:::

| Symptom | What to do |
| --- | --- |
| Two adjacent pins shine as one blob | Flux and remove excess solder until there is a gap between pins again |
| Package shifted by half a pitch | Undo the diagonal tacks and reseat to the mark |
| 555 and 4017 swapped | U1 is the 8-pin 555. U2 and U3 are 16-pin 4017. They do not fit each other’s footprints |

## Power

Pads on the reference side are marked “+” and “−”. Plus goes to “+”. USB Type-C on the assembled board is already the normal 5 V input — do not add a separate supply on those pads for the first check.

A board that heats immediately after the cable is plugged in comes off the port. Then inspect bridges on U1–U3 and solder balls near the connector.

## Overheat and flux

An LED heated too long with the tip can stay dark even with a good-looking joint. Replace that LED.

Sticky flux between pins gives unstable contact. After assembly, clean with IPA and dry before checking again.

## What to include if a section stays dark

- which section: 1206, 0805, or 0603;
- whether neighbor sections light or the board is fully dark;
- whether the 555 (U1) and both 4017 (U2, U3) keys match the silkscreen;
- a daylight photo of the section showing pins and resistor ends.

Course where this board is soldered with a mentor: [Basic electronics soldering course](https://www.softeralab.com/course-basic-soldering/).
