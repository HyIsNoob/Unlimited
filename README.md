# UNLIMITED

An Augmented Reality web experiment simulating Gojo Satoru's techniques. This project uses Computer Vision and WebGL to create interactive energy fields controlled by your hands.

## Overview

This application is a single-file WebAR tool. It runs directly in your web browser without installation. It uses MediaPipe Hands to track your movements and Three.js to render thousands of physics-based particles.

You can control the Limitless techniques (Red, Blue, and Purple) using specific hand gestures.

## Features

* Real-time tracking for left and right hands.
* Interactive particle system with attraction and repulsion physics.
* Post-processing effects using UnrealBloomPass for neon glow.
* Gesture recognition for Fists, Open Hands, and Snaps.
* Adaptive UI that responds to your actions.

## Controls

The system detects three main phases based on hand distance and gestures.

| Technique | Hand | Gesture | Effect |
| :--- | :--- | :--- | :--- |
| **Red (Reversal)** | Right | Fist | Particles pull inward to the palm center. |
| **Blue (Lapse)** | Left | Fist | Particles push outward from the palm center. |
| **Purple (Hollow)** | Both | Hands Close | Merges Red and Blue into a purple energy sphere. |
| **Attack** | Both | Snap | Explodes the purple sphere with a shockwave. |

## Tech Stack

* **HTML5 & JavaScript** for core logic.
* **Three.js** for 3D rendering and particle systems.
* **MediaPipe Hands** for computer vision and hand tracking.
* **WebGL Shaders** for visual effects.

## How to Run

1.  Clone this repository.
    ```bash
    git clone [https://github.com/HyIsNoob/Domain-Expansion-AR.git](https://github.com/HyIsNoob/Domain-Expansion-AR.git)
    ```
2.  Open the project folder.
3.  Run the `index.html` file using a local server. You can use the "Live Server" extension in VS Code.
4.  Allow camera access when prompted by the browser.

## Author

**HyIsNoob**
* Student at University of Information Technology (UIT).
* Windows User: khang (HYISNOOB).
