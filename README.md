# 🌌 Linear Algebra Visual Engine Series
### *Simulation Architect Path: Phase 1*

> *"I like building from first principles: prove the idea in code, then make it visual enough to teach."*

Welcome to the **Linear Algebra Visual Engine** series. This is a collection of 5 distinct physics/math engines built from scratch using **Python, NumPy, and the Blender `bpy` API**. 

Instead of relying on textbooks or black-box libraries, I built these engines to prove the core concepts of Linear Algebra geometrically and procedurally.

---

## 🏗️ The Engines

### 1. [LA-Visual-Engine](https://github.com/divyanshailani/LA-Visual-Engine)
**Proof of Concept:** Vectors aren't just lists of numbers; they are spatial directions that can be manipulated and scaled.
*First Principles:* A foundational engine establishing the isometric continuous 3D coordinate space, drawing vectors and basic transformations dynamically.
![LA-Visual-Engine](https://raw.githubusercontent.com/divyanshailani/LA-Visual-Engine/main/docs/assets/renders/placeholder.gif)

### 2. [LA-Visual-Engine-3D](https://github.com/divyanshailani/LA-Visual-Engine-3D)
**Proof of Concept:** A matrix is a linear transformation of space, uniquely determined by where it sends the basis vectors î, ĵ, and k̂.
*First Principles:* Animates a full 3D space lattice morphing under any $3 \times 3$ transformation matrix, proving linearity visually.
![LA-Visual-Engine-3D](https://raw.githubusercontent.com/divyanshailani/LA-Visual-Engine-3D/main/docs/assets/renders/placeholder.gif)

### 3. [Basis-Translator-3D](https://github.com/divyanshailani/Basis-Translator-3D)
**Proof of Concept:** The same physical vector has different coordinates depending on your chosen coordinate system (basis).
*First Principles:* Overlaps two entire coordinate spaces. Proves that $A \cdot x = \text{new basis coordinates}$ while the physical "anchor" vector never actually moves.
![Basis-Translator-3D](https://raw.githubusercontent.com/divyanshailani/Basis-Translator-3D/main/docs/assets/renders/placeholder.gif)

### 4. [Cramers-Rule-3D](https://github.com/divyanshailani/Cramers-Rule-3D)
**Proof of Concept:** Solving a linear system is finding the ratio of transformed volumes.
*First Principles:* Visually proves Cramer's Rule by calculating the determinant as the volume of a parallelepiped, showing how swapping columns alters the 3D volume proportionally.
![Cramers-Rule-3D](https://raw.githubusercontent.com/divyanshailani/Cramers-Rule-3D/main/docs/assets/renders/Project_04_Cramers_Rule.gif)

### 5. [Eigenvector-Explorer-3D](https://github.com/divyanshailani/Eigenvector-Explorer-3D)
**Proof of Concept:** Eigenvectors are the specific axes of space that remain completely stable during a transformation, with eigenvalues being their stretch factor.
*First Principles:* Scans a transformation, identifies real eigenvectors, and visualizes them as glowing axes that only scale along their own line while the rest of space morphs around them.
![Eigenvector-Explorer-3D](https://raw.githubusercontent.com/divyanshailani/Eigenvector-Explorer-3D/main/docs/assets/renders/Project_05_symmetric.gif)

---

## 🛠️ The Tech Stack
- **Python 3.11+**: The logic brain.
- **NumPy**: The math engine (matrix operations, determinants, eigenvalues).
- **Blender 5.0+ (`bpy`)**: The rendering engine.
- **Methodology**: 2-Phase architecture (Phase 1: Math/Logic Verification → Phase 2: Blender Scene Generation).

## 🚀 Next Phase
Moving from pure mathematics to physics: **Project 6A — Solar System Simulator** (N-body gravity, Velocity Verlet integration, NASA JPL datasets).