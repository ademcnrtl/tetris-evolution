# Tetris: A Digital Tribute (1984 - 1989)

### *An Analytical and Aesthetic Exploration of the Origins of Tetris*

This repository houses a meticulously developed recreation of **Tetris**, dedicated to its original creator, **Alexey Pajitnov**. The project serves as a digital museum, documenting the formal and technical evolution of the world’s most significant puzzle game from its inception in the Soviet Union to its global dominance on handheld platforms.

## Project Objective

The primary objective of this project is to preserve the historical integrity of Tetris’s early iterations. By implementing era-specific hardware limitations, visual filters, and auditory landscapes, this software allows users to experience the game exactly as it appeared on the **Elektronika 60**, **MS-DOS**, and **Nintendo GameBoy**.

## Historical Interpretations

This implementation features three distinct execution modes, each governed by unique architectural constraints:

### I. The Foundation: Elektronika 60 (1984)
* **Technical Specification:** Character-based ASCII rendering.
* **Visual Fidelity:** Integrated **GLSL CRT Emulation** simulating phosphor persistence, scanlines, and the characteristic spherical distortion of 1980s Soviet monitors.
* **Historical Note:** A recreation of the original environment where Pajitnov first conceived the "falling blocks" mechanic.

### II. The Expansion: MS-DOS Version (1986)
* **Technical Specification:** 16-color CGA/EGA palette simulation.
* **Aesthetics:** Representation of the first commercial era, featuring the iconic boxed UI and standardized PC input latency.

### III. The Phenomenon: GameBoy Edition (1989)
* **Technical Specification:** 4-shade monochromatic green palette.
* **Acoustics:** High-fidelity 8-bit chiptune synthesis of the **"Korobeiniki"** (Theme A), utilizing frequency-limited channels to mimic the LR35902 sound chip.
* **Impact:** A tribute to the version that established Tetris as a cultural icon.

## Technical Implementation

* **Rendering Pipeline:** Custom shader-based post-processing to simulate analog video signals.
* **Logic Engine:** Precise adherence to the original rotation systems (pre-SRS) and gravity calculations found in the 1980s source code.
* **User Interface:** Minimalist design intended to minimize distraction and maximize historical immersion.

## Deployment

### Accessing the Simulation
The project is hosted via **GitHub Pages**. To execute the simulation locally:

1.  Clone the repository:
    git clone https://github.com/ademcnrtl/tetris-evolution.git
    
3.  Open `index.html` in any modern, standards-compliant web browser.

## Dedication & Disclaimer

This work is dedicated to **Alexey Pajitnov**. His contribution to software engineering and computer science continues to inspire developers worldwide.

**Legal Disclaimer:** This is a non-commercial, educational project. **Tetris®** is a registered trademark of **The Tetris Company**. This project is an independent tribute and is not affiliated with, authorized, or endorsed by The Tetris Company.

*Developed by Adem Can Certel - March 2026*
