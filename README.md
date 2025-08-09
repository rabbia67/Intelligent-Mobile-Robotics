# 🤖 Intelligent Mobile Robotics

A MATLAB-based collection of **mobile robotics algorithms** and simulations, including **Bug Algorithms**, **Potential Field Methods**, and **Wheeled Mobile Robot Kinematics with RRT & Kalman Filtering**.

---

## 📂 Repository Structure

```plaintext
Intelligent-Mobile-Robotics/
│
├── BugAlgorithms/
│   ├── Bug1.m
│   ├── Bug2.m
│   ├── TangentBug.m
│   ├── MyBug.m
│   └── Documentation.pdf
│
├── PotentialFieldMethods/
│   ├── StandardPotentialField.m
│   ├── MyPotentialField.m
│   ├── NavigationFunction.m
│   └── Documentation.docx
│
├── Kinematics_RRT_Kalman/
│   ├── TricycleTrailer_Kinematics.m
│   ├── RRT_PathPlanning.m
│   ├── KalmanFilter_Implementation.m
│   └── Documentation.pdf
│
└── README.md
```

---

## 🧭 Module Overview

### **🚦 Module 1 — Bug Algorithms**
![Bug Algorithm Simulation](images/bug_algo.gif)

Includes:
- **Bug 1**
- **Bug 2**
- **Tangent Bug**
- **MyBug** (Custom hybrid algorithm)

**Highlights of MyBug:**
- 📌 Segment-based obstacle boundary division
- 🔄 Dynamic segment switching & skipping
- 🗂 Memory-based obstacle geometry storage
- 🏎 More efficient paths than standard Bug methods

---

### **🛰 Module 2 — Potential Field Methods**
![Potential Field Simulation](images/potential_field.gif)

Implements:
- **Standard Potential Field**
- **MyPotential Algorithm**
- **Navigation Function Approach**

**MyPotential Advantages:**
- Hybrid attractive potential (quadratic near goal, exponential far away)
- Gaussian repulsive potential for smooth avoidance
- Reduced local minima issues
- Smoother & more direct paths

---

### **🚗 Module 3 — Kinematics, RRT, and Kalman Filter**
![RRT Path Planning](images/rrt_demo.gif)

Covers:
- Kinematic modeling of a **tricycle robot with trailer**
- RRT for path planning
- Kalman Filter for noise correction

**Key Features:**
- Models non-holonomic wheeled robots
- Generates collision-free paths in complex environments
- Corrects noisy trajectories with Kalman filtering

---

## 🛠️ Technologies
- **MATLAB** — Simulation and implementation
- **Path Planning** — Bug, Potential Field, RRT
- **State Estimation** — Kalman Filter
- **Robotics Models** — Tricycle with trailer

---

## 🚀 How to Run
```bash
git clone https://github.com/rabbia67/Intelligent-Mobile-Robotics.git
```
1. Open MATLAB.
2. Navigate to the relevant module folder.
3. Run the main `.m` script.
4. Adjust parameters inside the code to explore different scenarios.

---

## 📊 Results Summary
| Module | Main Improvement |
|--------|------------------|
| Bug Algorithms | Shorter paths via dynamic segment switching |
| Potential Fields | Reduced local minima, smoother navigation |
| Kinematics & Planning | Kalman filter improves accuracy |

---

## 📄 License
For educational & research purposes. Please cite if using in projects or publications.

