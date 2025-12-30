# C++: Bresenham Drawing Tool
**Independent Technical Exploration | University Year 1**

A computer graphics prototype developed in C++ to explore low-level rendering logic. This tool implements Bresenham's line algorithm to facilitate real-time, grid-based drawing using the SFML library.

## 🕹️ Project Overview
This project originated from independent research into computer graphics fundamentals. Following a recommendation to explore line-drawing algorithms, I developed this tool to bridge the gap between continuous mouse-coordinate input and discrete grid-based rendering.

It utilises the same foundational framework as my [C++ Game of Life simulation](https://github.com/MylesColeman/CPP-Game-of-Life), demonstrating architectural flexibility by repurposing a cellular automata engine into an interactive technical tool.

## 🛠️ Key Technical Features

### Algorithm Implementation
* **Bresenham’s Line Algorithm:** Researched and implemented the algorithm to determine the most efficient path of grid cells between two arbitrary mouse coordinates.
* **Integer-Only Logic:** The implementation avoids floating-point arithmetic for coordinate calculations, mirroring low-level hardware rendering techniques for maximum efficiency.
* **Coordinate-to-Grid Mapping:** Developed a system that translates real-time SFML mouse events into 2D array coordinates, allowing users to "paint" onto the simulation grid dynamically.

### Engineering Initiative
* **Framework Adaptation:** Demonstrated code modularity by adapting a custom SFML-based framework originally designed for automated simulations into a user-input-driven utility.
* **Input Validation:** Managed real-time event polling to ensure drawing logic only triggers within valid grid boundaries, preventing array out-of-bounds errors during high-speed mouse movement.

## 💻 Technical Specs
* **Language:** C++
* **Library:** SFML (Simple and Fast Multimedia Library)
* **Compiler:** Visual Studio
* **Key Algorithm:** Bresenham's Line Algorithm
