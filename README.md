# RISCV-Assembly-Assignments
Collection of RISC-V Assembly projects including Bitmap Graphics (Mini CAD) and Math Graphing

# RISC-V Assembly Assignments

This repository contains my advanced assignments for the Computer Architecture course. The projects are written entirely in **RISC-V Assembly** and executed using the **RARS (RISC-V Assembler and Runtime Simulator)** environment.

## Projects Overview

### 1. Mini CAD (Project 20)
A command-line based drawing application that parses user input to render geometric shapes on the RARS Bitmap Display.
* **String Parsing:** Extracts drawing commands and coordinates from raw string input.
* **Graphics Algorithms:** * Bresenham's Line Algorithm for drawing straight lines.
  * Midpoint Circle Algorithm for rendering circles.
* **Memory Management:** Direct pixel manipulation via Bitmap Display MMIO.

### 2. Math Graphing (Project 6)
A mathematical visualization tool that plots quadratic functions ($y = ax^2 + bx + c$) on a Cartesian coordinate system.
* **Coordinate Transformation:** Maps standard mathematical coordinates to Bitmap physical pixels.
* **Continuous Plotting:** Interpolates points to draw smooth parabolic curves.

---

## How to Run

1. Download and install [RARS 1.6](https://github.com/TheThirdOne/rars).
2. Open the desired `.asm` file in RARS.
3. Open the required tools via the `Tools` menu:
   * **Bitmap Display:** Set Unit Width/Height to `1x1` and Display Width/Height to `512x512`. Set Base Address to `0x10010000 (global data)`.
   * **Keyboard and Display MMIO:** To input commands and view parsing results.
4. Assemble (`F3`) and Run (`F5`).

---

## Author
**Dương Tuấn Phi** Hanoi University of Science and Technology (HUST)

> ** Disclaimer for Students:** > This repository is strictly for personal portfolio and educational reference. If you are currently taking the Computer Architecture course, please do not copy the source code for your assignments to avoid academic integrity violations.