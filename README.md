# StellarMesh ☄️ | Synthetic Asteroid Rendering Pipeline & Dataset

![StellarMesh Preview]([https://github.com/StellarMesh-Labs/StellarMesh-Asteroid-Dataset-Pipeline/blob/main/3000%20gumroad%20cover.png])

A fully headless Python-Blender rendering architecture designed to procedurally generate physically accurate, multi-modal synthetic datasets for aerospace computer vision, OpNav (Optical Navigation), and 3D shape reconstruction research.

## 🚀 Get the Data & Code

We offer a free 600-mesh sample for independent researchers, as well as the complete 3,000+ mesh dataset and the underlying Python/Blender pipeline toolkit for commercial and enterprise applications.

* **[Free 600-Mesh Sample Dataset (Kaggle) ➔]([https://www.kaggle.com/datasets/hassaanfazal/astrovision-3d-asteroid-and-photometry-dataset])**
* **[Get the Full 3,000+ Mesh Dataset (Gumroad) ➔]([https://stellarmeshlabs.gumroad.com/l/asteroid_dataset])**
* **[Download the Rendering Pipeline & Toolkit (Gumroad) ➔]([https://stellarmeshlabs.gumroad.com/l/rendering_pipeline])**

## ⚙️ Pipeline Features

The StellarMesh architecture automates the extraction of radiometrically accurate data using Blender's Cycles engine and Python automation.

* **Multi-Pass EXR Rendering:** Automatically outputs RGB, precise Z-Depth, and camera-space Surface Normals.
* **Photometric Lightcurves:** Generates time-series CSV data tracking `total_flux`, `projected_area`, `mean_depth`, and Sun/Observer coordinate vectors per rotational step.
* **Procedural Regolith Materials:** Built-in node setups for both Uniform and Variable Albedo surface configurations.
* **Headless Automation:** Generate massive datasets via command-line without ever opening the Blender GUI.

## 📊 Dataset Schema
Each lightcurve CSV logs the following metrics:
- `total_flux`: Absolute sum of pixel brightness (linear scale).
- `normalized_flux`: Total flux normalized by projected pixel area.
- `projected_area`: Total count of non-transparent silhouette pixels.
- `mean_depth` & `mean_normal_z`: Average Z-buffer distance and camera-facing Z-vector.
- `sun_x/y/z` & `obs_x/y/z`: The 3D coordinate frame vectors relative to the asteroid body.

## 🤝 Consulting & Custom Integration
If your research lab or aerospace startup requires customized Python scripts, advanced shader development, or specific modifications to the rendering architecture for a proprietary machine learning workflow, custom consulting is available. Please reach out via the contact information provided in the Gumroad toolkit receipt.

---
*Tags: Computer Vision, Machine Learning, Optical Navigation, OpNav, Synthetic Data, Asteroids, Photometry, Blender 3D, Python, Deep Learning*
