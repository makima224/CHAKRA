# Description

**CHAKRA** is a jutsu visualizer based on the legendary series, *Naruto Shippuden*. It leverages the **MediaPipe** framework and **Three.js** to manifest elemental chakra techniques in real-time through hand-tracking. Powered by **Gemini 3**.

![rasengan](https://github.com/user-attachments/assets/054cd56b-77a0-42e9-a238-df41e746d2b7)

# Features

This project utilizes particles to render volume-based elemental techniques:

* **Wind Style: Rasen-Shuriken**
    * **Visuals:** A high-velocity Archimedean spiral with 6 curved blades and a dense rotating core.
    * **Trigger:** Index finger pointing up, thumb tucked.
* **Water Style: suiton**
    * **Visuals:** A massive liquid tsunami featuring real-time sine-wave vertex displacement and rhythmic ripples.
    * **Trigger:** Index + Middle fingers up
* **Rasengan**
    * **Visuals:** A chaotic Fibonacci sphere of swirling blue chakra with internal turbulence and vibration.
    * **Trigger:** Index finger up with thumb spread wide.
* **Wood Style: mokuuton**
    * **Visuals:** Geometric structural growth representing the birth of a forest.
    * **Trigger:** Two-hand detection.
* **Lightning Style: Chidori**
    * **Visuals:** Erratically jumping particles simulating high-voltage electrical discharge.
    * **Trigger:** Closed fist.

# Getting Started

### Prerequisites
You need a modern web browser (Chrome, Edge, Firefox) and a webcam.

### Installation

1. **Clone the repo**
   ```bash
   git clone [https://github.com/makima224/CHAKRA.git](https://github.com/makima224/CHAKRA.git)
   cd CHAKRA
