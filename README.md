# Visible-Light-Communication-for-Indoor-Positioning
This project documents a system that uses visible light (LEDs) to determine the position of objects in a large indoor setting.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 📌 Project Overview
*(Answers: Why is it relevant? & What did I do?)*
Briefly explain the limitations of indoor RF positioning and how this project utilizes Visible Light Communication (VLC) via ceiling-mounted LEDs and photodiode receivers to achieve accurate indoor localization based on Received Signal Strength (RSS).

## ⚙️ System Architecture 
*(Answers: How did I do it?)*
- **Transmitter Design:** Modulated ceiling-mounted LED infrastructure.
- **Receiver Design:** Photodiode system with custom feedback capacitor design and ADC interfacing.
- **Signal Processing:** FFT-based signal detection pipeline to separate frequencies and extract RSS.
- **Positioning Engine:** Trilateration based on a calibrated RSS-to-distance model.

## 🛠️ Hardware & Software Stack
* **Hardware:** [Insert Microcontroller/ADC], [Insert Photodiode model], [Insert LEDs]
* **Software:** [Insert Languages, e.g., Python, MATLAB, C++]
* **Libraries:** [e.g., NumPy, SciPy for FFT]

## 📊 Key Results
*(Answers: What results did I get?)*
* Summarize the calibration results.
* State the final positioning accuracy (MAE and RMSE).
* *(Add a screenshot of your RSS-Position Curve here)*

## 🚧 Challenges Faced
*(Answers: What challenges did I face?)*
* **Challenge 1:** [e.g., Bandwidth limitations] -> **Solution:** [How you fixed it]
* **Challenge 2:** [e.g., Ambient noise] -> **Solution:** [How you fixed it]

## 🚀 Future Work
*(Answers: What are future areas for improvement?)*
- [ ] Implement dynamic user tracking.
- [ ] Integrate IMU sensor fusion.
- [ ] Optimize the LED identification circuit for higher frequencies.

## 📂 Repository Structure
```text
├── data/               # Raw ADC and voltage readings
├── src/                # Signal processing and trilateration scripts
├── hardware/           # Circuit schematics and PCB designs
└── docs/               # Full thesis and supplementary documentation
