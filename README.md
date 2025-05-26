# Möbius Strip Modeling in Python 🌀

This project models a 3D Möbius strip using parametric equations and computes key geometric properties like surface area and edge length. It also visualizes the strip using `matplotlib`.

## 📌 Features

- Generates a 3D mesh of the Möbius strip
- Computes surface area using numerical integration
- Calculates the total length of the boundary edges
- Visualizes the strip with 3D plotting

## 🧮 Parametric Equations Used

x(u,v) = (R + v * cos(u/2)) * cos(u)
y(u,v) = (R + v * cos(u/2)) * sin(u)
z(u,v) = v * sin(u/2)

markdown
Copy
Edit

Where:
- `u ∈ [0, 2π]`
- `v ∈ [-w/2, w/2]`

## 🚀 How to Run

1. Install dependencies:
   ```bash
   pip install numpy matplotlib scipy
Run the script:

```bash
python mobius_strip.py
```
📷 Output
Prints surface area and edge length

Displays an interactive 3D plot
