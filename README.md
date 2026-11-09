```markdown
# UR3e Robotic Manipulator Kinematics GUI

A MATLAB App Designer application for forward kinematics, homogeneous transformation analysis, and matrix inversion for the Universal Robots UR3e 6-DOF industrial collaborative robot.

---

## 🚀 Key Features

* **Modified DH Formulation:** Computes homogeneous transformation matrices ($T_{0}^{6}$) using Standard/Modified Denavit-Hartenberg (DH) parameters across all 6 revolute joints.
* **Matrix Analysis Suite:** Real-time computation of transformation transpose, matrix rank, determinant, and matrix inversion ($T_{6}^{0}$).
* **Transformation Validation:** Automatic verification of mathematical consistency ($T \times T^{-1} \approx I$).
* **Standalone Executable Deployment:** Packaged and compiled into a standalone Windows executable (`.exe`) via MATLAB Compiler Runtime (MCR).

---

## 🛠️ Tech Stack

* **Platform:** MATLAB R2021b
* **Tools:** MATLAB App Designer, MATLAB Compiler Runtime (MCR)
* **Core Concepts:** Robotics Kinematics, Denavit-Hartenberg Parameters, Matrix Transformations

---

## 📁 Repository Structure

```text
UR3e-Kinematics-App/
├── matrixURe3.mlapp          # Interactive MATLAB App Designer file
├── matrixURe3_exported.m     # Exported MATLAB class code
├── UR3e.prj                  # Deployment and compilation project
└── README.md

```

---

## ⚙️ How to Run

1. Open MATLAB (R2021b or newer).
2. Run the exported script in the MATLAB Command Window:
```matlab
app = matrixURe3_exported;

```


Or double-click `matrixURe3.mlapp` in MATLAB to inspect the UI design.

---

## 👨‍💻 Author

**Ali Molaei**

M.Sc. in Mechatronics Engineering

* Email: [molaeiali24@gmail.com](https://www.google.com/search?q=mailto%3Amolaeiali24%40gmail.com)
* Telegram: [@AliMoj4z](https://www.google.com/search?q=https://t.me/AliMoj4z)
