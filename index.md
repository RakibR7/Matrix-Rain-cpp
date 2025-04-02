---
layout: default
title: Matrix Rain Animation in Modern C++
---

# Matrix Digital Rain Animation

<img src="https://raw.githubusercontent.com/RakibR7/Matrix-Rain-cpp/main/docs/assets/images/main_part_3.png" alt="Matrix Animation" style="max-width: 100%;">

## Introduction

Hello, my name is Rakib Rana. I've created a console-based Matrix Digital Rain animation using Modern C++ and Windows console APIs. This project simulates the iconic cascading green characters effect from "The Matrix" film series, bringing the cyberpunk aesthetic to your console window.

## Demo

<video width="100%" controls autoplay loop muted>
  <source src="https://raw.githubusercontent.com/RakibR7/Matrix-Rain-cpp/main/docs/assets/images/CPLUSGIF.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>
<p><em>Live demonstration of the Matrix Digital Rain animation running in a Windows console.</em></p>

## Project Overview

<div style="margin-bottom: 30px;">
  <img src="https://raw.githubusercontent.com/RakibR7/Matrix-Rain-cpp/main/docs/assets/images/Rainfall_header_part_4.png" alt="Header Structure" style="max-width: 100%;">
  <p><em>Header file defining the Rainfall class with its core functions.</em></p>
</div>

<div style="margin-bottom: 30px;">
  <img src="https://raw.githubusercontent.com/RakibR7/Matrix-Rain-cpp/main/docs/assets/images/main_part_3.png" alt="Main Function" style="max-width: 100%;">
  <p><em>Main function showing initialization and execution of the Matrix rain effect.</em></p>
</div>

<div style="margin-bottom: 30px;">
  <img src="https://raw.githubusercontent.com/RakibR7/Matrix-Rain-cpp/main/docs/assets/images/part_1.png" alt="GotoXY Implementation" style="max-width: 100%;">
  <p><em>Implementation of GotoXY function for cursor positioning.</em></p>
</div>

<div style="margin-bottom: 30px;">
  <img src="https://raw.githubusercontent.com/RakibR7/Matrix-Rain-cpp/main/docs/assets/images/part_2.png" alt="Animation Implementation" style="max-width: 100%;">
  <p><em>Core animation logic in PrintRainfall method.</em></p>
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
