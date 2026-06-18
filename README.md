# Passive-Herringbone-Micromixer-CFD
Performance evaluation of a passive staggered herringbone micromixer using ANSYS Fluent and Fusion 360.
# Performance Evaluation of Passive Herringbone Micromixer

An engineering study investigating the fluid mixing efficiency of a passive Staggered Herringbone Micromixer (SHM) using Computational Fluid Dynamics (CFD). This project was completed for the course **ME 224 - Fundamentals of Microscale Flows** at IIT Indore.

## 📌 Project Overview
Microfluidic systems operate at extremely low Reynolds numbers, resulting in strictly laminar flow where fluid mixing relies entirely on slow molecular diffusion. This project evaluates how complex, asymmetric channel geometries (45° slanted grooves) induce chaotic advection to exponentially accelerate fluid homogenization without external energy sources.

## 🛠️ Tech Stack & Tools
* **CAD Modeling:** Fusion 360
* **CFD Simulation:** ANSYS (Navier-Stokes & Species Transport Modeling)
* **Data Analysis:** Microsoft Excel / Origin Lab

## 📐 Geometric Configurations Evaluated
1. **3-Inlet Flow-Focusing Geometry:** Sandwiches the solute stream to double the initial interfacial area.
2. **2-Inlet Y-Shaped Geometry:** Standard baseline mixing channel.
3. **Plain Microchannel:** Used as a geometric control group (no grooves).

## 📊 Key Findings & Results
* **Velocity vs. Mixing Index:** Confirmed a powerful inverse relationship. Lower velocities increase fluid "residence time," allowing molecular diffusion to completely homogenize the layers stretched by the herringbone structures.
* **Peak Performance:** Achieved a near-perfect Mixing Index (MI) of **0.9947** at an ultra-low inlet velocity of 0.000085 m/s.
* **Geometric Superiority:** The 3-inlet herringbone geometry vastly out-performed the plain channel, achieving a ~0.98 MI compared to a linear, sluggish 0.56 MI in the smooth control channel.

## 📁 Repository Structure
* `/CAD-Models` — Contains `.step` files for all 3 configurations.
* `/Simulation-Data` — Contains tabulated data points, mesh details, and raw mixing metrics.
* `ME 224 Report.pdf` — The comprehensive final project report document.

## 👥 Authors (Group 1)
* Akash Kumar Gupta
* Aadarsh S 
* Abhinav Jain 
* Anand Vivek
* **Course Coordinator:** Dr. Vijai Laxmi (Assistant Professor, ME, IIT Indore)
