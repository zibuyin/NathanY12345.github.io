# Automatic Pill Dispenser

### Disigned By: Nathan Yin on Feb 11 2025

---

## Background

Most existing pill dispensers lack the ability to automatically count pills, requiring users to manually count pills each time. This process can be inconvenient and prone to errors, especially for individuals managing multiple medications or those with disabilities. There is a clear need for a more efficient, user-friendly solution that automates both pill counting and dose reminders.

## **Design Concepts:**

For the initial designs, I chose to use CAD (Computer-Aided Design) software. This method allows for faster and more precise visualization of the components compared to hand-drawn sketches. I can also test if the concept works on computer to minimize wasting 3D printing filament.

### **Roller and Funnel Mechanism(V1.0)**

Our initial design is based on a “Roller and Funnel” system. The funnel serves as a storage container for the pills before they are dispensed. The roller, functioning as a conveyor belt, moves the pills from the funnel towards a dispensing mechanism. Pills settle into evenly spaced slots on the roller, which then carries them down into a tunnel.

Inside the tunnel, an infrared (IR) sensor detects the number of pills being dispensed. Once the desired quantity is reached, the sensor signals the roller to stop, ensuring precise dispensing. This design combines simplicity and accuracy, making it ideal for pill distribution.
<img src="https://github.com/NathanY12345/NathanY12345.github.io/blob/main/Screenshot%202025-02-11%20at%2022.52.52.png" alt="drawing" width="200"/>
### CHANGE ME: ADD ADVANTAGES
![w](https://github.com/NathanY12345/NathanY12345.github.io/blob/main/Screenshot%202025-02-11%20at%2022.52.52.png)

While the “Roller and Funnel” design has its advantages, it also presents several significant disadvantages

1.	**Adaptability to Different Pill Sizes and Shapes**

•	Pills of varying sizes and shapes require rollers with customized slot dimensions to ensure only one pill fits per slot. Smaller pills may result in multiple pills being dispensed at once, while larger pills may not fit at all.

•	This necessitates frequent manual adjustments or replacements of the roller, which contradicts our original goal of creating a user-friendly design.

2.	**Complexity and Size**

•	The entire mechanism is bulky and complex, increasing the likelihood of mechanical failures.

•	The larger size not only makes manufacturing more expensive but also reduces convenience for users who may struggle to find space for the device in their homes.

3.	**Dependence on a Stepper Motor**

•	To precisely rotate the roller, the design relies on a stepper motor, which adds complexity to the circuit and raises production costs.

•	This further complicates the design and detracts from its intended simplicity and affordability.
