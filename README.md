# ESPHome Step Monitor – Cheap Yellow Display (ESP32-2432S028 / JC2432W328C)

A fun and functional step tracker that displays your daily step count on a 2.8" “Cheap Yellow Display” ESP32 board. Reads steps from your mobile phone or smartwatch using Home Assistant.

This repository contains:
- YAML files for ESPHome, sensors, and automations
- A printable label template for the enclosure
- Link to the 3D-printed case on Thingiverse

---

## 📺 YouTube Build Guide

- **Part 1: ESPHome Setup + Step Count Workaround**  
  https://youtu.be/X_7EBsNffCY

- **Part 2: 3D Printing and Assembly**  
  https://youtu.be/-Jx554oW4lc

---

## 🖨️ STL Files for the Enclosure

Download the 3D printable enclosure here:  
**Thingiverse:** https://www.thingiverse.com/thing:7041744

---

## 📦 Files in This Repository

- `esphome_step_monitor.yaml` – Main ESPHome config
- `automation_step_count_at_midnight.yaml` – Automation to store steps at midnight
- `input_number_steps_at_midnight.yaml` – Input number helper
- `template_mobile_daily_steps_sensor.yaml` – Template sensor for daily steps
- `Step_Monitor_Cover_Template_A4.pdf` – Printable label (A4 size)
- `Step_Monitor_Cover_Template_Letter.pdf` – Printable label (US Letter)

🔧 Files are also provided in "split" formats for those using separate YAML packages.

---

## 💬 Questions or Help?

Join the discussion or ask questions on the **Lazy Tech Geek Discord**:  
https://discord.gg/jEaremqDJd
