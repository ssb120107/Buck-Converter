
# Buck Converter Project

## Project Title

**Design and Implementation of a DC–DC Buck Converter**

---

## Project Overview:

This project focuses on the design, simulation, and implementation of a **DC–DC Buck Converter**, which is used to step down a higher DC input voltage to a lower DC output voltage efficiently.
The converter operates using a high-frequency switching device and passive components such as an **inductor**, **capacitor**, and **diode** to regulate the output voltage.
This project demonstrates the working principle, performance analysis, and efficiency evaluation of a buck converter under different load conditions.

---

## Objectives:

* To design a **step-down DC–DC converter (Buck Converter)**
* To understand the working of **switching converters**
* To simulate the converter using software tools
* To analyze output voltage ripple and efficiency
* To verify theoretical and simulated results

---

## Components Used:

| Component       | Description                           |
| --------------- | ------------------------------------- |
| MOSFET / Switch | Used for high-frequency switching     |
| Diode           | Provides current path during OFF time |
| Inductor (L)    | Stores and releases energy            |
| Capacitor (C)   | Filters output voltage ripple         |
| DC Power Supply | Input voltage source                  |
| Load Resistor   | Represents output load                |
| PWM Generator   | Controls duty cycle                   |

---

## Working Principle:

A buck converter works by rapidly switching the input voltage ON and OFF using a MOSFET.

* When the switch is **ON**, energy is stored in the inductor.
* When the switch is **OFF**, the inductor releases energy through the diode to the load.
* The output voltage is controlled by adjusting the **duty cycle (D)** of the switching signal.

The ideal output voltage is given by:

**Vout = D × Vin**

Where:

* **Vout** = Output Voltage
* **Vin** = Input Voltage
* **D** = Duty Cycle (0 to 1)

## Design Specifications

(Modify these based on your project)

| Parameter             | Value  |
| --------------------- | ------ |
| Input Voltage (Vin)   | 25 V   |
| Output Voltage (Vout) | 17.5 V |
| Switching Frequency   | 15 kHz |
| Inductor Value        | 1mH    |
| Capacitor Value       | 470 µF |
| Load Resistance       |Varaible|


## Simulation

The circuit was simulated using:

* MATLAB Simulink 
* PWM signal used for switching control
* Output voltage and current waveforms were analyzed

## Hardware Implementation:
The converter circuit was assembled on:

* Breadboard 
* MOSFET driven using PWM
* Output measured using multimeter / oscilloscope


## Results and Observations

* Output voltage remained stable at the desired level
* Ripple voltage reduced using capacitor filter
* Efficiency increased compared to linear regulators
* Converter operated successfully under varying load

---

## Challenges Faced

* Selecting proper inductor value
* Managing switching noise
* Reducing output voltage ripple
* Ensuring stable PWM control
* adjusting Load values for keeping the converter in ccm (continous conduction mode)


## Applications

Buck converters are widely used in:

* Power supplies
* Battery chargers
* Laptop power systems
* Solar charge controllers
* Embedded systems
* Electric vehicles

---
