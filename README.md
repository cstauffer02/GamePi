# 🎮 GamePi

A portable handheld retro gaming console powered by a **Raspberry Pi Zero W**. The **GamePi** is designed as a low‑cost, DIY‑friendly device capable of running classic game console emulators with full physical controls, a compact display, and portable power.

![GamePi](media/GamePi.jpg)

🎥 [Watch the GamePi demo video](https://vimeo.com/1106315738?fl=pl&fe=sh)

---

## 🎯 Project Goals

1. **Design a portable handheld retro gaming console** that supports targeted retro console emulators with a complete control interface:
   - NES
   - Sega Genesis
   - SNES
   - Game Boy, Game Boy Color, Game Boy Advance
2. **Include all essential controls:**
   - Directional pad (D‑Pad)
   - A, B, X, Y buttons
   - R/L bumpers
   - Start & Select buttons
   - Mono audio with volume control
3. **Reuse already‑owned components from college program** where possible to keep costs low.
4. Keep the design **affordable** and **iterative** — the current revision is a working prototype, to be refined over time.

---

## 🛠 Design & Features

- **3.5‑inch LCD screen** for retro game visuals
- **Display settings interface** via 3 front‑mounted buttons
- **Mono audio** output with adjustable volume wheel
- **Portable** — powered by onboard AA batteries or external micro‑USB
- **Removable Raspberry Pi Zero W**
- **Accessible ports** — micro‑USB (power), USB (devices), and mini‑HDMI
- **Removable battery compartment cover**
- **Removable Pi cover** with convenient port cutouts

---

## 🧩 Hardware Overview

- **Main Processor:** Raspberry Pi Zero W
- **PCB:** Designed in Altium
- **Enclosure & Buttons:** Designed in Fusion 360
- **Display:** 3.5" LCD
- **Audio:** Mono speaker with volume control
- **Power:**
  - AA battery pack (portable mode)
  - External micro‑USB (bench power mode)

---

## 🖼 Enclosure & Assembly

The enclosure is designed for both ease of access and durability:
- Rear **battery cover** allows quick battery changes
- Rear **Raspberry Pi cover** enables Pi removal for other projects
- Pi connects to PCB via **female header rail** for tool‑free removal
- Port access slots in the Pi cover for power, USB devices, and HDMI

---

## 📜 Design Philosophy

This prototype intentionally uses **mixed component types** (axial + SMD resistors, etc.) for the sake of **component availability**:
> _Some unintuitive design choices may be noticed in the PCB files. For example, the use of both axial and SMD resistors. This stems from goal #3 — “Reuse already‑owned components from college program.” Some SMD components were not available during development, so axial/radial parts were substituted._

---

## 📂 Repository Structure

    GamePi/
    ├── Enclosure/          # Fusion 360 CAD models for case & buttons
    ├── PCB/                # Altium PCB design files
    ├── media/              # Images and demonstration video
    └── README.md 
---

## 🚀 Future Improvements

- Refine PCB layout for cleaner component selection
- Improve enclosure ergonomics
- Integrate rechargeable lithium battery + charging circuit
- Implement conductive silicon button pads for quieter buttons
- Add stereo audio support
- Explore Pi 4 CM for improved performance

---

## 👤 Author

**Cameron Stauffer**  
Electrical Project Engineer | Hardware & Embedded Systems Enthusiast  
[LinkedIn](www.linkedin.com/in/cameronstauffer)
