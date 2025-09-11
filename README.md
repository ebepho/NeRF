# NeRF: Neural Radiance Fields  

> A modern implementation of Neural Radiance Fields with practical enhancements  

---

## 📖 Project Overview  
This project was completed as part of the **APS360 course at the University of Toronto**. The goal was to recreate and extend **Neural Radiance Fields (NeRF)** for generating 3D reconstructions from 2D images.  

Our motivation was to **democratize interior design** by enabling users to take a set of photos or a short video of an object and generate a 3D model viewable in modeling software such as **SketchUp** or **Revit**.  

We leveraged the **Realistic Synthetic 360 dataset**, implemented a **baseline MLP model**, and optimized NeRF with techniques such as **ray casting**, **positional encoding**, and **background removal**.  

---

## 📁 Project Structure  

```
nerf/
├── README.md          # This file
├── data/              # Sample scenes and datasets
├── configs/           # Training configurations
├── nerf/              # Core NeRF implementation
│   ├── models/        # Neural field models
│   ├── train.py       # Training script
│   ├── eval.py        # Evaluation script
│   └── vis.py         # Visualization tools
├── scripts/           # Utility scripts
└── results/           # Experimental results
```
---

## 📌 Disclaimer  
This repository contains only documentation, results, and visuals.  
All code was developed as part of a University of Toronto class project and remains under academic ownership.  

It is provided for **educational and informational purposes only**. If you are a student, please do not use this work to complete your own assignments or projects, as this may violate your institution’s academic integrity policies. By using the contents of this repository, you agree to do so responsibly and ethically.  
