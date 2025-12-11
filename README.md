# ♟️ PhantomChess

[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)
![Status](https://img.shields.io/badge/Status-Development-blue)

## 📖 Overview

This repository contains the complete engineering lifecycle of an **Automated Chess Board** capable of moving pieces physically. 

The project is structured to demonstrate the progression from high-level software abstraction to low-level hardware integration. It covers three key stages:
1.  **Logic Prototyping** 
2.  **Resource Optimization**
3.  **Hardware Implementation** 

---

## Project Structure & Roadmap

Each folder in this repository represents a distinct stage in the development cycle. Please refer to the specific `README.md` inside each folder for detailed documentation.

### 1. [Desktop Version](./Desktop/README.md)
**Focus:** *Game Logic & Architecture*
* Written in **C++**.
* Developed to design and test the core chess engine, move validation, and game state management in a high-level environment.
* Serves as the "Logic Laboratory" before porting code to constrained hardware.

### 2. [Embedded Version](./Embedded/README.md)
**Focus:** *Optimization & Networking*
* Written in **C++** (for Microcontrollers).
* Hosts a **local Game Server** allowing users to play chess via a network interface.
* Demonstrates memory optimization techniques and adaptation of the chess engine for embedded systems (limited RAM/Flash).

### 3. [Final Version](./PhantomChess/README.md)
**Focus:** *Mechatronics & Product Finalization*
* **The Final Product Code.**
* Combines the optimized logic with hardware control drivers.
* Controls **Stepper Motors**, **Electromagnets**, and sensors to physically move pieces on the board automatically.

---

## Technology Stack

* **Languages:** C++
* **Hardware (Target):** TBD
* **Mechanics:** TBD
* **Protocols:** TBD

---

## AI Usage Transparency

To ensure engineering integrity, I declare the following regarding the use of Artificial Intelligence in this project:

* **Source Code:** All software logic, algorithms, and drivers were designed and written **manually by humans**. No AI code generation tools were used for the development of the core project.
* **Documentation:** AI assistance was used **strictly for formatting and styling** the repository documentation (README files) to ensure a professional visual presentation.

---

## ⚖️ License

This project is licensed under the **Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0)**.

You are free to:
* **Share** — copy and redistribute the material in any medium or format.
* **Adapt** — remix, transform, and build upon the material.

**Under the following terms:**
* **Attribution** — You must give appropriate credit.
* **NonCommercial** — You may **NOT** use the material for commercial purposes (selling, paid services, etc.).

See the [LICENSE](./LICENSE) file for details.
