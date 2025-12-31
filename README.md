# Thermostat-Temperature-Control-System
A microcontroller-based thermostat system written in C, featuring temperature sensing, state machine control, and automatic heating/cooling management.
It reads temperature values from a sensor, compares them with a user-defined threshold, and controls heating/cooling devices accordingly.  

The project includes the full C source code, compiled firmware files, and documentation with design details such as the **state machine diagram** and project report.

---

## 📂 Project Structure
- **`project.c`** – Main C source code for the thermostat logic.
- **`project.cproj`, `project.atsln`, `.pdsprj`** – Project/solution files (Atmel Studio or similar).
- **`project.hex`, `project.rom`** – Compiled firmware for microcontroller programming.
- **`State machine.jpg`** – Diagram showing the system’s control logic.
- **`گزارش پروژه کنترل دما با ترموستات.pdf`** – Project report (in Persian).

---

## ⚙️ Features
- Reads real-time temperature values.
- Allows user-defined temperature threshold.
- Controls heating/cooling devices automatically.
- Implements a **state machine** for reliable control flow.

---

## 🛠 Requirements
- **Atmel Studio (or compatible IDE)** for compiling and programming.
- AVR-based microcontroller (e.g., ATmega series).
- Temperature sensor (e.g., LM35 or similar).
- Output devices (heater/cooler, fan, etc.).
- Programmer (e.g., USBasp, AVRISP mkII).

---

## 🚀 How to Use
1. Open the project in **Atmel Studio** using `project.cproj`.
2. Compile the code to generate a `.hex` file.
3. Upload the `.hex` file to the microcontroller using your programmer.
4. Connect the sensor and output devices according to the circuit.
5. Run the system and test temperature-based control.

---

## 📖 Documentation
- The PDF report (`گزارش پروژه کنترل دما با ترموستات.pdf`) explains the design, implementation, and testing.
- The **state machine diagram** illustrates the control logic.

---

## 📜 License


This project is licensed under the Creative Commons Attribution-NoDerivatives 4.0 International License. You are free to share the work, but you cannot modify it or create derivatives. Proper attribution must be given to the original author.
You can view the full license text here: [CC BY-ND 4.0 License](https://creativecommons.org/licenses/by-nd/4.0/legalcode)
![License: CC BY-ND 4.0](https://img.shields.io/badge/License-CC%20BY%20ND%204.0-lightgrey)




