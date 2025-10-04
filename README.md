<<<<<<< HEAD
# PID-101 📐

A hands-on series of Python simulations + explanations to understand PID (Proportional-Integral-Derivative) control. Ideal for engineering students, hobbyists, or anyone curious about control systems.

---

## 🔍 Table of Contents

1. [About](#about)  
2. [Structure](#structure)  
3. [What You’ll Learn](#what-youll-learn)  
4. [How to Use This Repo](#how-to-use-this-repo)  
5. [Experiments / Simulations](#experiments--simulations)  
6. [Play & Extend](#play--extend)  
7. [Prerequisites](#prerequisites)  
8. [Getting Started](#getting-started)  
9. [Contributing](#contributing)  
10. [License & Contact](#license--contact)

---

## ℹ️ About

This repository is a learning resource with code + commentary to help you understand PID control in various systems. Each simulation builds in complexity:

- Translating PID from theory → code  
- Simulating response, observing error, overshoot, steady-state behaviour  
- Comparing open vs closed loop systems  
- Moving from first-order systems to second-order, thermal, mechanical, etc.

---

## 🗂 Structure

PID-101/  
│  
├── Control/
│ ├── 1_first_order_dc_motor/  
│ ├── 2_thermal_systems/  
│ ├── 3_open_closed_loop/  
│ └── 4_spring_mass_damper/  
│  
├── README.md  
├── LICENSE  
└── assets/  


The experiment folder contains:

- `.py` and `.pynb` simulation code  
- A short write-up (markdown) explaining the model, the PID implementation, and what to observe.

---

## 🎯 What You’ll Learn

- How each term of PID (P, I, D) influences system behaviour.  
- Real effects like overshoot, settling time, oscillation, steady-state error  
- Differences between open-loop vs closed-loop feedback control  
- Modeling of first-order and second-order dynamics  
- How to tune PID gains in simulation to see what works (and what doesn’t)

---

## 🚀 How to Use This Repo

1. Pick an experiment file.  
2. Read the explanation (markdown) to understand the system model.  
3. Run the Python script to see the simulation.  
4. Change PID gains / system parameters. Observe how the response changes (plot, print, etc.). 
5. (Optional) Modify the system model or combine features from different examples.

---

## 🔬 Experiments / Simulations

| Experiment                      | Description                                                     |
| ------------------------------- | --------------------------------------------------------------- |
| **1. First-Order DC Motor**     | Simple model; see how P, I, D affect step response.             |
| **2. Thermal Systems**          | Heating/cooling dynamics; environmental losses; time constants. |
| **3. Open-Loop vs Closed-Loop** | Why feedback matters; compare both.                             |
| **4. Spring-Mass-Damper**       | Second-order dynamics; oscillations and damping.                |

---

## 🧰 Prerequisites

- Python 3.x  
- Libraries: `numpy`, `matplotlib` (or equivalent)  
- Basic knowledge: differential equations, basic control theory

---

## 🛠 Getting Started

```
bash
git clone https://github.com/mukul160/PID-.git
cd PID-
cd Experiments/1_first_order_dc_motor
python simulation.py
``````

---
## 🤝 Contributing

Want to add more systems or experiments (e.g. robotics, fluid dynamics)? Pull requests welcome! You can also help by:

- Improving documentation    
- Adding diagrams & plots
- Adding more “real world” examples

---

## 📜 License & Contact

This work is licensed under the MIT License.  
Questions, suggestions, or collaboration ideas? Contact: mukuly.2001@gmail.com
=======
# PID 101

This repository contains a series of Python simulations and accompanying explanations exploring **PID control** in a variety of systems. The goal is to help engineering students and enthusiasts understand how PID controllers work, and how to implement them in code.

The series progresses in complexity:

1. **First-Order Systems**  
   - Simple DC motor speed control  
   - Translating PID equations from theory to Python  
   - Observing the role of P, I, and D terms

2. **Thermal Systems**  
   - Temperature control with heating and cooling dynamics  
   - Modeling first-order thermal processes  
   - Introducing environmental losses and setpoint tracking

3. **Open-Loop vs Closed-Loop Comparison**  
   - Demonstrates why feedback is critical  
   - PID control vs fixed-input heating  
   - Observing overshoot, steady-state error, and system response

4. **Spring–Mass–Damper Systems**  
   - Simulating second-order dynamics  
   - State-space representation and discrete-time simulation  
   - Setting the stage for advanced control methods like LQR


## About
This repository is intended for learning and demonstration purposes. Each simulation is accompanied by code comments explaining the PID implementation and system dynamics.
Feel free to experiment with the parameters, try different PID gains, or extend the models to explore control systems further.
>>>>>>> refs/remotes/origin/master

---
