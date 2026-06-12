# OpenRocket Flight Simulation Project 🚀

This repository contains the `.ork` design and simulation file for a high-power rocket built in **OpenRocket**. The objective of this project is to analyze the vehicle's flight physics, predict aerodynamic behavior under thrust, and evaluate stability parameters using a mid-power composite motor.

## 📐 Rocket Specifications & Dimensions
* **Total Length:** 25.88 in
* **Maximum Diameter:** 1.969 in
* **Mass (Without Motor):** 9.61 oz
* **Mass (With Motor):** 14.7 oz
* **Selected Motor:** AeroTech G80-5 (Composite)

---

## 🔬 Flight Stability Profile
To ensure a safe, predictable flight path off the launch rail, the center of pressure ($CP$) must remain safely behind the center of gravity ($CG$).

* **Center of Gravity (CG):** 15.528 in (from nose tip)
* **Center of Pressure (CP):** 17.693 in (from nose tip at $M = 0.300$)
* **Static Stability Margin:** 1.1 cal (8.4 %)

---

## 📊 Simulated Flight Performance
Based on the OpenRocket computational physics engine running the **G80-5** flight configuration, the vehicle achieves the following performance parameters:

* **Predicted Apogee:** 2008 ft
* **Maximum Velocity:** 656 ft/s (Mach 0.589)
* **Peak Acceleration:** 823 ft/s²

---

## 📂 How to Run the Simulation
1. Download the latest version of [OpenRocket](https://openrocket.info/).
2. Download the `High power Rocket.ork` file from this repository.
3. Open the file in OpenRocket to view the components (Nose cone mass components, shock cord, parachute, freeform fin set) and run the flight profiles.
