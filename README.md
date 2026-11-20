# 🧱 Breakout — Bruce / LilyGO T-Embed CC1101

<p align="center">🇺🇸 <b>English</b> · 🇫🇷 <a href="README.fr.md">Français</a></p>

[![Bruce firmware](https://img.shields.io/badge/firmware-Bruce-8A2BE2?logo=github)](https://github.com/BruceDevices/firmware) [![Device](https://img.shields.io/badge/device-LilyGO%20T--Embed%20CC1101-1E90FF)](https://github.com/BruceDevices/firmware) [![Language](https://img.shields.io/badge/script-JavaScript%20(BJS)-F7DF1E)](https://github.com/BruceDevices/firmware) [![License: MIT](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)

A colorful **brick-breaker** for the Bruce JS interpreter, built around the rotary encoder. Changing level layouts, power-ups that drop from bricks, tough bricks, and a persistent top-5 high score table.

![Breakout gameplay](docs/hero.jpg)

## 🎮 Controls

**Rotate = move the paddle**, **click = launch the ball** (the bounce angle depends on where it hits the paddle), **ESC = menu**.

## ✨ Features

- 🧱 **Levels** — layouts cycle (full / checker / pyramid / stripes), colors per row, ball speeds up, and **tough 2-hit bricks** appear from level 3. "LEVEL n" flash.
- 🎁 **Power-ups** drop from bricks — catch them with the paddle:
  - **E** wider paddle · **M** multi-ball (up to 3) · **S** slow ball (8 s) · **L** extra life
- ❤️ **3 lives**, HUD with score / level / best / lives.
- 🏆 **Persistent top-5 high scores** (`/breakout_scores.json`) with **3-initials** entry on a record.
- 🖥️ Flicker-free incremental rendering, picto menu decorated with a brick row.

| Menu | Level 2 | Game over |
|---|---|---|
| ![menu](docs/menu.jpg) | ![level 2](docs/level2.jpg) | ![game over](docs/gameover.jpg) |

## 🚀 Install

1. Copy **`Breakout.js`** onto the SD card (e.g. `/scripts` or `/BruceJS`).
2. On the device: **JS Interpreter → select `Breakout.js`** (or add it to your favorites with [bruce-launcher](https://github.com/koua29/bruce-launcher)).
3. High scores are stored in `/breakout_scores.json` on the SD.

## 🛒 Hardware

*Amazon affiliate links: if you buy through these links, the project earns a small commission at no extra cost to you.*

<table>
<tr>
<td align="center" width="33%">
  <a href="https://www.amazon.com/dp/B0D45MSMJR?linkCode=ll2&amp;tag=koua29bbreakout-20&amp;ref_=as_li_ss_tl"><img src="docs/amazon-B0D45MSMJR.jpg" width="200" alt="Anker 545 power bank (10,000 mAh)"></a><br>
  <b><a href="https://www.amazon.com/dp/B0D45MSMJR?linkCode=ll2&amp;tag=koua29bbreakout-20&amp;ref_=as_li_ss_tl">Anker 545 power bank (10,000 mAh)</a></b><br><sub>Keeps the T-Embed running away from an outlet</sub>
</td>
<td align="center" width="33%">
  <a href="https://www.amazon.com/dp/B0C1FCZM94?linkCode=ll2&amp;tag=koua29bbreakout-20&amp;ref_=as_li_ss_tl"><img src="docs/amazon-B0C1FCZM94.jpg" width="200" alt="433 MHz SMA antenna (2-pack)"></a><br>
  <b><a href="https://www.amazon.com/dp/B0C1FCZM94?linkCode=ll2&amp;tag=koua29bbreakout-20&amp;ref_=as_li_ss_tl">433 MHz SMA antenna (2-pack)</a></b><br><sub>Sub-GHz antenna for the CC1101 radio</sub>
</td>
<td align="center" width="33%">
  <a href="https://www.amazon.com/dp/B0B7NVMBPL?linkCode=ll2&amp;tag=koua29bbreakout-20&amp;ref_=as_li_ss_tl"><img src="docs/amazon-B0B7NVMBPL.jpg" width="200" alt="SanDisk 64 GB microSD (2-pack)"></a><br>
  <b><a href="https://www.amazon.com/dp/B0B7NVMBPL?linkCode=ll2&amp;tag=koua29bbreakout-20&amp;ref_=as_li_ss_tl">SanDisk 64 GB microSD (2-pack)</a></b><br><sub>For Bruce themes, scripts and captures</sub>
</td>
</tr>
</table>

<sub>As an Amazon Associate I earn from qualifying purchases.</sub>

## 🙏 Credits & License

- Script: **koua29**. Runs on the excellent **[Bruce firmware](https://github.com/BruceDevices/firmware)**.
- Released under the **MIT License** — see [LICENSE](LICENSE).

## ☕ Buy me a coffee

<img src="docs/paypal-qr.png" width="170" alt="PayPal" />
