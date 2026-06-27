# ⚡ Transformerless Power Supply PCB

![KiCad](https://img.shields.io/badge/Design-KiCad-314CB0?style=flat-square&logo=kicad&logoColor=white)
![PCB](https://img.shields.io/badge/Type-PCB%20Hardware-2b7489?style=flat-square)
![Output](https://img.shields.io/badge/Output-5V%20DC-e10600?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-3da639?style=flat-square)

## 📌 Overview  
This is a **PCB design** for a **Transformerless Power Supply**, created using **KiCad**. This circuit provides a **regulated 5V DC output** using an **LM7805 voltage regulator**. The design eliminates the need for bulky transformers, making it compact and efficient.

> ⚠️ **Safety:** a transformerless supply is **not mains-isolated** — the low-voltage side is electrically live with respect to the AC mains. Do not handle it while powered, and do not connect it to anything that a person can touch.

## 🛠️ Specifications  
- **Input Voltage**: AC Mains (220V AC)
- **Output Voltage**: 5V DC (regulated)
- **Voltage Regulator**: LM7805

## 🧾 Bill of Materials
| Component | Value / Part | Qty |
|-----------|--------------|:---:|
| Rectifier diodes | 1N4007 | 4 |
| Zener diodes | (voltage regulation) | 2 |
| Voltage regulator | LM7805 | 1 |
| Film capacitors | 2.2 µF, 0.1 µF | 2 |
| Electrolytic capacitors | 1000 µF, 470 µF | 2 |
| Resistors | 1 MΩ, 20 kΩ, 20 kΩ, 2.2 kΩ | 4 |
| Indicator LED + series resistor | — | 1 + 1 |
| Screw terminals (AC in / DC out) | 2-pin | 2 |

> Derived from the design specifications.

## 📂 What's in this repo
- **`Images/`** — rendered schematic, PCB layout, and 3D views
- **`Schematics/`**, **`PCB_Design/`** — exported PNG views of the schematic and layout
- **`Gerber_Files/`** — ready-to-manufacture Gerbers (`Gerber files.zip`)

> Note: this repo ships the rendered **images** and the manufacturing **Gerbers**. The editable KiCad project files (`.kicad_pro` / `.kicad_sch` / `.kicad_pcb`) are not included.

## 🖼️ Preview Images  
| Schematic | PCB Layout | 3D Render |
|-----------|------------|------------|
| ![Schematic](Images/Schematic.png) | ![PCB](Images/pcb_layout.png) | ![3D](Images/3d_render.png) |

## 🔧 How to Use  
1️⃣ **Review the design** from the schematic and PCB images in `Images/`.  
2️⃣ **Order the board** by sending `Gerber_Files/Gerber files.zip` to any PCB manufacturer.  
3️⃣ **Assemble** using the Bill of Materials above — and mind the safety note.

## 🔗 Links  
- 🚀 **Connect on LinkedIn**: [Ramu Roy](https://www.linkedin.com/in/ramu-roy-b780382b7)  
- 📺 **Ampnics Tutorial**: [YouTube Playlist](https://youtube.com/playlist?list=PLxgq6Jtu7shQPHqYjKUVa28CmktTzHDLp&si=2TdaJywcDumlzVk_) 

## 📜 License  
This project is licensed under the **MIT License** – feel free to use and modify it!
