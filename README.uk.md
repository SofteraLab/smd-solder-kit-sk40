<p align="center">
  <a href="https://www.softeralab.com/">
    <img src="docs/assets/images/logo.png" alt="Softera Lab" width="96">
  </a>
</p>

<h1 align="center">SMD Solder Kit · SK-40</h1>

<p align="center"><strong>Навчальна плата Softera Lab для пайки SMD</strong></p>

<p align="center">
  <a href="README.md"><img alt="EN" src="https://img.shields.io/badge/EN-README.md-F97316?style=flat-square"></a>
  <a href="https://www.softeralab.com/"><img alt="Сайт" src="https://img.shields.io/badge/softeralab.com-09090B?style=flat-square&labelColor=18181B"></a>
  <a href="https://www.softeralab.com/course-basic-soldering/"><img alt="Курс пайки" src="https://img.shields.io/badge/Курс%20пайки-09090B?style=flat-square&labelColor=18181B"></a>
  <img alt="USB Type-C 5V" src="https://img.shields.io/badge/USB--C-5V-09090B?style=flat-square&labelColor=F97316">
  <img alt="0603 0805 1206" src="https://img.shields.io/badge/0603%20·%200805%20·%201206-09090B?style=flat-square&labelColor=18181B">
</p>

<p align="center"><strong>Мови:</strong> <a href="README.md">English</a> · Українська (ця сторінка)</p>

![SMD Solder Kit](docs/assets/images/banner.jpg)

Набір Softera Lab для тренування пайки SMD. Ця сторінка — опис і інструкція для тих, кому цікаво купити набір або пройти [курс пайки](https://www.softeralab.com/course-basic-soldering/).

Це **не open-source проєкт**: схема, Gerber і виробничі файли публічно не викладаються.

> © Softera Lab. All rights reserved. Копіювання плати, схеми та виробничих файлів без письмового дозволу заборонене.

## Як працює

[![Демо SMD Solder Kit SK-40](docs/assets/images/banner.jpg)](https://www.youtube.com/shorts/_bBBfhrwp9k)

Відео: [YouTube Short](https://www.youtube.com/shorts/_bBBfhrwp9k)

## Про набір

[SMD Solder Kit SK-40](https://www.softeralab.com/course-basic-soldering/) — практична плата [Softera Lab](https://www.softeralab.com/). На ній три секції «резистор + LED» у корпусах **1206**, **0805** і **0603** та роз’єм USB Type-C на **5 В**.

Мікроконтролера немає: такт задає таймер **555** (U1, SOIC-8), кроки по світлодіодах рахують дві мікросхеми **4017** (U2 і U3, SOIC-16).

Окремий бік плати — довідник корпусів: Metric/Inch, площадки SOT і секція Speed.

Покроковий монтаж: [`docs/`](docs/).

![Як працює набір](docs/assets/images/how-it-works.jpg)

## Характеристики

| Параметр | Значення |
| --- | --- |
| Product | SMD Solder Kit · SK-40 |
| Input | USB Type-C, 5 V |
| Indicators | LED секції світиться, якщо пайка цієї секції правильна |
| LED sections | 1206 (R11–R15), 0805 (R6–R10), 0603 (R1–R5) |
| Logic | Таймер 555 (U1) і дві 4017 (U2, U3). Без МК |
| Support parts | C1–C3, R18 |
| Reference side | Metric/Inch, SOT-23 / 25 / 26 / 89, Speed |
| Check | Підключити USB і подивитись на LED |

![Огляд плати](docs/assets/images/board-overview.jpg)

## Що в коробці

![Комплектація](docs/assets/images/kit-contents.jpg)

1. Плата SMD Solder Kit
2. Резистори 0603, 0805, 1206
3. Світлодіоди 0603, 0805, 1206
4. Таймер 555 (SOIC-8) і дві 4017 (SOIC-16)
5. Обв’язка мікросхем
6. Роз’єм USB Type-C
7. Флюс, припій, змивка

## Збірка коротко

Повний порядок: [перший запуск](docs/02-getting-started.md).

1. Припаяй USB Type-C
2. Секція 1206: R11–R15 + LED
3. Секція 0805: R6–R10 + LED
4. Секція 0603: R1–R5 + LED
5. Обв’язка: C1–C3, R18
6. U1 — 555, SOIC-8
7. U2 і U3 — 4017, SOIC-16
8. Підключи USB і перевір LED

![Порядок збірки](docs/assets/images/assembly-order.jpg)

## Посилання

| Матеріал | Де |
| --- | --- |
| English README | [README.md](README.md) |
| Огляд плати | [docs/01-hardware-overview.md](docs/01-hardware-overview.md) |
| Інструменти і збірка | [docs/02-getting-started.md](docs/02-getting-started.md) |
| Техніка пайки | [docs/03-soldering.md](docs/03-soldering.md) |
| Якщо LED не світиться | [docs/04-troubleshooting.md](docs/04-troubleshooting.md) |
| Купити / курс | [Курс пайки](https://www.softeralab.com/course-basic-soldering/) |
| Контакти | [Контакти](https://www.softeralab.com/our-contacts/) · support@softeralab.com · +38 (096) 22-67-529 |
| Демо | [YouTube Short](https://www.youtube.com/shorts/_bBBfhrwp9k) |

## Авторське право

© Softera Lab. All rights reserved.

Публічні матеріали можна переглядати. Копіювати, виготовляти чи комерційно використовувати дизайн плати без письмового дозволу Softera Lab заборонено.
