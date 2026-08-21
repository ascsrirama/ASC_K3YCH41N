<div align="center">

# ⚡ ASC_K3YCH41N

**A little PCB that lights up, and also opens my car.**

![PCB](https://img.shields.io/badge/PCB-Altium-1a936f?style=flat-square)
![Status](https://img.shields.io/badge/status-v1.0-orange?style=flat-square)
![License](https://img.shields.io/badge/license-personal--use-lightgrey?style=flat-square)

</div>

---

After getting my first car, I wanted to have a custom keychain. I also wanted to work on a small PCB design just for fun, and the idea came to me: why not make a PCB for a keychain!

A simple, beginner PCB project built around a basic LED circuit, all laid out on a small board shaped to double as a keychain.

The Gerber files are included so you can order and build your own (if you like it).

## 🖼️ Images

<div align="center">

| Front | Back |
|:---:|:---:|
| ![Front of board](https://i.imgur.com/gJxc6bu.png) | ![Back of board](https://i.imgur.com/uulafRo.png) |

</div>

## 🔌 How it works

- **Power** — A coin cell battery mounted directly on the PCB via a battery holder.
- **Switch** — A slide or tactile switch breaks/completes the circuit, so the LED only lights up on demand (saves battery when it's on your keys).
- **Current-limiting resistor** — Sized to protect the LED and keep current draw reasonable for coin cell life.
- **LED** — The main output. Circuit path: battery (+) → switch → resistor → LED → battery (–).
- **Board outline** — The PCB itself is shaped as a functional keychain, with a mounting hole for a keyring, rather than a plain rectangle.

## Features

-  Hanuman silkscreen art
-  LinkedIn QR code *(yes, a recruiter did scan it and it worked)*

## 🧩 Components

| Part | Qty |
|---|---|
| Switch | x1 |
| LED | x6 |
| Resistor | x6 |
| Coin Cell Battery | x1 |
| Battery Holder | x1 |

## 🎯 Why this project

- Practice basic PCB layout (traces, footprints, board outline shaping)
- Design for a non-rectangular, functional board shape
- Get hands-on experience ordering and assembling a small-batch PCB
- End up with something practical and personal — a keychain that's actually mine

## 🕓 Revision

Current revision: **Feb 2026**

## 🐛 Issues

- **Incorrect switching** — the switch in the schematic was wired incorrectly, resulting in a small fix with the wire
- **Silkscreen misalignment** — bottom layer QR code is off center
