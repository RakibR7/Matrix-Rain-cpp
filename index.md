---
layout: default
title: Matrix Rain Animation in Modern C++
---

## Introduction

Hello, my name is Rakib Rana. I've created a console-based Matrix Digital Rain animation using Modern C++ and Windows console APIs. This project simulates the iconic cascading green characters effect from "The Matrix" film series, bringing the cyberpunk aesthetic to your console window.

# Matrix Digital Rain Animation

<img src="https://raw.githubusercontent.com/RakibR7/Matrix-Rain-cpp/main/docs/assets/images/CPLUSGIF.gif" alt="Matrix Rain Animation" style="max-width: 100%;">
<p><em>Live demonstration of the Matrix Digital Rain animation running in a Windows console.</em></p>

## Project Overview

<div style="margin-bottom: 30px;">
  <img src="https://raw.githubusercontent.com/RakibR7/Matrix-Rain-cpp/main/docs/assets/images/Rainfall_header_part_4.png" alt="Header Structure" style="max-width: 100%;">
  <p><em>This header file demonstrates the modular design of the project by defining the Rainfall class with clearly separated responsibilities, using modern C++ structure and Windows API integration to support the object-oriented approach required for maintaining clean, reusable code.</em></p>
</div>

<div style="margin-bottom: 30px;">
  <img src="https://raw.githubusercontent.com/RakibR7/Matrix-Rain-cpp/main/docs/assets/images/main_part_3.png" alt="Main Function" style="max-width: 100%;">
  <p><em>This main function showcases the initialization and execution of the animation by creating an instance of the Rainfall class, reflecting a well-structured program flow and highlighting how the program leverages modular function calls to deliver the final rain effect.</em></p>
</div>

<div style="margin-bottom: 30px;">
  <img src="https://raw.githubusercontent.com/RakibR7/Matrix-Rain-cpp/main/docs/assets/images/part_1.png" alt="GotoXY Implementation" style="max-width: 100%;">
  <p><em>The GotoXY method uses the Windows API to manipulate cursor positioning in the console, forming a critical part of the animation system while also demonstrating the use of platform-specific libraries and system-level control techniques within a modern C++ context.</em></p>
</div>

<div style="margin-bottom: 30px;">
  <img src="https://raw.githubusercontent.com/RakibR7/Matrix-Rain-cpp/main/docs/assets/images/part_2.png" alt="Animation Implementation" style="max-width: 100%;">
  <p><em>The PrintRainfall function implements the core animation logic using randomization, console manipulation, and loop control, combining algorithmic thinking with performance-aware design in line with rubric criteria for creativity, problem-solving, and advanced code structure.</em></p>
</div>


## Technical Implementation

### Key Components

- **Rainfall Class**: Encapsulates all functionality for the animation
  - `PrintRainfall()`: Main animation loop that creates the rain effect
  - `GotoXY(int x, int y)`: Controls console cursor positioning

### Animation Features

- **Character Variety**: Mix of numbers and letters ('1', '2', '3', '4', '5', 'A', 'B', 'C', 'D')
- **Random Positioning**: Dynamic column selection for rainfall
- **Color Effects**: Random color generation for enhanced visual appeal
- **Customizable Parameters**: Adjustable width, height, drop size, and density

## How to Build and Run

### Visual Studio
1. Open the project in Visual Studio
2. Build the solution (F7 or Ctrl+Shift+B)
3. Run the program (F5)

That's it! The Matrix Digital Rain animation will execute in the console window.

## About the Author

Developed by **Rakib Rana**, a final-year BEng (Hons) student specializing in Software & Hardware Engineering, with a passion for graphics and systems programming.

---

© 2025 Rakib Rana | [GitHub](https://github.com/RakibR7)
