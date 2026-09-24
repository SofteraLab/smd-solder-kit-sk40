<p align="center">
  <a href="https://www.softeralab.com/">
    <img src="docs/assets/images/en/logo.png" alt="Softera Lab" width="96">
  </a>
</p>

<h1 align="center">SMD Solder Kit · SK-40</h1>

<p align="center"><strong>Softera Lab training board for SMD soldering practice</strong></p>

<p align="center">
  <a href="README.uk.md"><img alt="UA" src="https://img.shields.io/badge/UA-README.uk.md-F97316?style=flat-square"></a>
  <a href="https://www.softeralab.com/"><img alt="Website" src="https://img.shields.io/badge/softeralab.com-09090B?style=flat-square&labelColor=18181B"></a>
  <a href="https://www.instagram.com/softeralab/"><img alt="Instagram" src="https://img.shields.io/badge/Instagram-09090B?style=flat-square&labelColor=18181B"></a>
  <a href="https://www.youtube.com/@SofteraLab"><img alt="YouTube" src="https://img.shields.io/badge/YouTube-09090B?style=flat-square&labelColor=18181B"></a>
  <img alt="USB Type-C 5V" src="https://img.shields.io/badge/USB--C-5V-09090B?style=flat-square&labelColor=F97316">
</p>

<p align="center"><strong>Languages:</strong> English (this page) · <a href="README.uk.md">Українська</a></p>

<p align="center">
  <img src="docs/assets/images/en/banner.png" alt="SMD Solder Kit" width="720">
</p>

Softera Lab kit for practicing SMD soldering. This repository is a **product page and assembly guide** for people who want to buy the kit or join the [soldering course](https://www.softeralab.com/course-basic-soldering/).

This is **not an open-source hardware project**. Schematics source, Gerbers, and manufacturing files are not published.

> © Softera Lab. All rights reserved. Copying the board, schematic, or manufacturing files without written permission is prohibited.

## How it works

Video of ready to work KIT: [YouTube Short](https://www.youtube.com/shorts/_bBBfhrwp9k)

## About the kit

[SMD Solder Kit SK-40](https://www.softeralab.com/course-basic-soldering/) is a practice board from [Softera Lab](https://www.softeralab.com/). It has three resistor + LED sections in **1206**, **0805**, and **0603**, plus USB Type-C at **5 V**.

There is **no microcontroller**. Timing comes from a **555** timer (U1, SOIC-8). LED stepping is handled by two **4017** counters (U2 and U3, SOIC-16).

The other side of the board is a package reference: Metric/Inch sizes, SOT footprints, and a Speed section.

Step-by-step assembly lives in [`docs/`](docs/) (Ukrainian guide for the course).

<p align="center">
  <img src="docs/assets/images/en/how-it-works.png" alt="How the kit works" width="720">
</p>

## Specifications

| Parameter | Value |
| --- | --- |
| Product | SMD Solder Kit · SK-40 |
| Input | USB Type-C, 5 V |
| Indicators | Section LED lights when that section is soldered correctly |
| LED sections | 1206 (R11–R15), 0805 (R6–R10), 0603 (R1–R5) |
| Logic | 555 timer (U1, SOIC-8) and two 4017 (U2, U3, SOIC-16). No MCU |
| Support parts | C1–C3, R18 |
| Reference side | Metric/Inch table, SOT-23 / SOT-25 / SOT-26 / SOT-89, Speed section |
| Check | Connect USB and watch the LEDs |

<p align="center">
  <img src="docs/assets/images/en/board-overview.png" alt="Board overview" width="720">
</p>

## What's in the box

<p align="center">
  <img src="docs/assets/images/en/kit-contents.png" alt="Kit contents" width="720">
</p>

1. SMD Solder Kit board
2. Resistors 0603, 0805, 1206
3. LEDs 0603, 0805, 1206
4. 555 timer (SOIC-8) and two 4017 ICs (SOIC-16)
5. Support components for the ICs
6. USB Type-C connector
7. Consumables: flux, solder, board cleaner

## Assembly (short)

Full order and tools: [getting started](docs/02-getting-started.md).

1. Solder USB Type-C
2. 1206 section: resistors R11–R15 + LED
3. 0805 section: resistors R6–R10 + LED
4. 0603 section: resistors R1–R5 + LED
5. IC support parts: C1–C3, R18
6. U1 — 555, SOIC-8
7. U2 and U3 — 4017, SOIC-16
8. Connect USB and check LEDs

<p align="center">
  <img src="docs/assets/images/en/assembly-order.png" alt="Assembly order" width="720">
</p>

## Links

| Item | Where |
| --- | --- |
| Ukrainian README | [README.uk.md](README.uk.md) |
| Board overview | [docs/01-hardware-overview.md](docs/01-hardware-overview.md) |
| Tools & assembly | [docs/02-getting-started.md](docs/02-getting-started.md) |
| Soldering technique | [docs/03-soldering.md](docs/03-soldering.md) |
| Troubleshooting | [docs/04-troubleshooting.md](docs/04-troubleshooting.md) |
| Buy / course | [Soldering course](https://www.softeralab.com/course-basic-soldering/) |
| Website | [softeralab.com](https://www.softeralab.com/) |
| Contact | [Contacts](https://www.softeralab.com/our-contacts/) · support@softeralab.com |
| Instagram | [instagram.com/softeralab](https://www.instagram.com/softeralab/) |
| YouTube channel | [youtube.com/@SofteraLab](https://www.youtube.com/@SofteraLab) |
| Demo video | [YouTube Short](https://www.youtube.com/shorts/_bBBfhrwp9k) |

## Copyright

© Softera Lab. All rights reserved.

Public materials may be viewed. You may not copy, manufacture, redistribute, or commercially use the board design without written permission from Softera Lab.
