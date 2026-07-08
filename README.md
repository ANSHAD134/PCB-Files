# PCB-Files

![KiCad](https://img.shields.io/badge/Made%20with-KiCad-314CB0?style=for-the-badge&logo=kicad&logoColor=white)
![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

A collection of my personal **KiCad PCB design projects**, custom symbol/footprint libraries, and 3D models used across different electronics builds.

---

## 📂 Repository Structure

```
PCB-Files/
├── 3D Models/                     # STEP files for 3D-printed / mechanical parts (motors, etc.)
├── KiCad Tools/
│   └── Symbol Libaries/           # Custom KiCad symbol libraries
├── Water Alarm/                   # Water level alarm PCB project (schematic + layout)
│   ├── Water Alarm.kicad_pro
│   ├── Water Alarm.kicad_sch
│   ├── Water Alarm.kicad_pcb
│   ├── FoodPrint Libraries/       # Custom footprints used in the project
│   ├── Graber/                    # Gerber export files
│   └── Water Alarm-backups/       # Auto-generated project backups
└── amplifier/                     # Audio amplifier PCB project
```

---

## 🔧 Projects

### 💧 Water Alarm
A KiCad project for a **water level detection alarm circuit** — includes schematic, PCB layout, custom footprints, and Gerber files ready for fabrication.

### 🔊 Amplifier
A KiCad-based **audio amplifier** PCB design.

### 🧩 3D Models
STEP (`.stp`) files for components (e.g. gear motors) used to preview real-world fit inside KiCad's 3D viewer.

### 📚 KiCad Tools / Symbol Libraries
Custom schematic symbol libraries reused across multiple projects for easier and consistent design work.

---

## 🖼️ Preview

> Add PCB / schematic screenshots here so visitors can see the boards without opening KiCad.
> Tip: In KiCad, use **File → Plot** or take a screenshot of the 3D viewer, then drop the image into an `images/` folder and reference it like below:

```markdown
![Water Alarm PCB](images/water-alarm-pcb.png)
![Water Alarm Schematic](images/water-alarm-schematic.png)
![Amplifier PCB](images/amplifier-pcb.png)
```

---

## 🛠️ Getting Started

1. Install **[KiCad](https://www.kicad.org/download/)** (v7 or later recommended).
2. Clone this repository:
   ```bash
   git clone https://github.com/ANSHAD134/PCB-Files.git
   ```
3. Open any project's `.kicad_pro` file in KiCad to view/edit the schematic and PCB layout.
4. Gerber files (inside `Graber/` folders) can be sent directly to a PCB fab (JLCPCB, PCBWay, etc.) for manufacturing.

---

## 📄 License

This project is open for personal and educational use. Feel free to fork and modify for your own builds. Add a `LICENSE` file (e.g. MIT) if you'd like to make the terms official.

---

## 🙋 Author

**ANSHAD134** — [GitHub Profile](https://github.com/ANSHAD134)
