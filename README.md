# NodalAnalysis

# Nodal Analysis for a Gas Well

This project demonstrates **Nodal Analysis** for a gas well using Python.  
It plots the **Inflow Performance Relationship (IPR)** and **Tubing Performance Relationship (TPR)** curves for different tubing sizes to determine the optimum production conditions.

---

## What is Nodal Analysis?
Nodal Analysis is a technique in petroleum engineering used to evaluate the performance of a well by analyzing the pressure and flow relationships between the **reservoir (inflow)** and the **wellbore/tubing (outflow)**.  
By plotting IPR and TPR curves, the intersection point indicates the expected **operating point (flow rate & bottom-hole pressure)** of the well.

---

##  Code Overview
The notebook includes:
- Importing libraries: `numpy`, `pandas`, `matplotlib`
- Defining IPR data (sourced from **PetroWiki**)
- Defining TPR data for different tubing sizes (`1.90"`, `2.375"`, `2.875"`)
- Plotting IPR and TPR curves
- Visualizing the operating point graphically

---

##  Output
The result is a plot showing:
- **IPR curve** (reservoir inflow capacity)  
- **TPR curves** for different tubing diameters  
- Intersection points that indicate the feasible production rate and pressure  
---
