# Simple Snake Game Simulation

A simple **hardware-based Snake Game** built entirely in **Logisim**, using digital logic components to simulate the classic retro gameplay.
The project demonstrates finite state machines, clock management, keyboard input interfaces, counters, collision detection, and VGA-style display logic.

## Features

* Fully digital-logic-based snake movement
* WASD keyboard control
* Food generation logic
* Win condition: collect **5 foods**
* Fail condition: snake touches itself
* Adjustable simulation tick rate
* Works on any system with **Logisim + JRE**

## Requirements

Before running the project, install:

* **Java Runtime Environment (JRE)**
* **Logisim** (Classic or Logisim-Evolution)
* The provided `.circ` circuit file

## ▶️ How to Run

1. **Download**

    * JRE
    * Logisim
    * The `.circ` file from this repository

2. **Open Logisim**

3. Click **File → Open** and select the `snake_game_final.circ` file.

4. Go to **Simulate** menu and ensure:

    * ✔ **Simulation Enabled** (`Ctrl+E`)
    * ✔ **Tick Enabled** (`Ctrl+K`)

5. Set **Tick Frequency** to **8 Hz**
   *(recommended for smooth gameplay)*

6. Click **Controls** and
   use your keyboard to move the snake:

    * **W** — Up
    * **A** — Left
    * **S** — Down
    * **D** — Right

7. **Game Rules**

    * Collect **5 food items** → 🎉 **You Win!**
    * Touch your own body → 💀 **Game Over**

## **Contributors**

| Name                      |
|---------------------------| 
| **Md. Samiul Islam Siam** |
| **Faiaz Ibne Iqbal**      |
| **Md. Sakhawat Hosen**    |    
