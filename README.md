# Half-Bridge DC-DC Converter Using MATLAB/Simulink

## 📌 Project Overview

This project presents the **design and simulation of a transformer-isolated Half-Bridge DC-DC Converter** using **MATLAB/Simulink and Simscape Electrical**.

The converter uses MOSFET-based high-frequency switching to convert DC input power into a high-frequency AC waveform. A high-frequency transformer provides electrical isolation and voltage transformation, while a diode rectifier and RLC filter convert the transformer output back into a smooth DC output.

The project demonstrates the fundamental principles of **power electronics, switching converters, transformer isolation, rectification, and output filtering**.

## 🎯 Objectives

* Design a Half-Bridge DC-DC converter in MATLAB/Simulink.
* Implement MOSFET-based high-frequency switching.
* Generate appropriate gate-pulse signals for the switches.
* Model transformer-based electrical isolation and voltage conversion.
* Implement secondary-side diode rectification.
* Use an RLC filter to reduce output ripple.
* Measure and analyze converter voltage and current waveforms.
* Study the overall switching and power-conversion behavior.

## ⚙️ System Block Diagram

```text
          DC Input
             │
             ▼
     ┌─────────────────┐
     │ Half-Bridge     │
     │ MOSFET Switches │
     └────────┬────────┘
              │
              │ High-Frequency AC
              ▼
     ┌─────────────────┐
     │ High-Frequency  │
     │   Transformer   │
     └────────┬────────┘
              │
              ▼
     ┌─────────────────┐
     │ Diode Rectifier │
     └────────┬────────┘
              │
              ▼
     ┌─────────────────┐
     │   RLC Filter    │
     └────────┬────────┘
              │
              ▼
          DC Output
```

## 🔧 Main Components

| Component           | Function                                      |
| ------------------- | --------------------------------------------- |
| DC Voltage Source   | Provides input DC power                       |
| MOSFETs             | Perform high-frequency switching              |
| Pulse Generator     | Generates MOSFET gate-control signals         |
| Transformer         | Provides isolation and voltage transformation |
| Diodes              | Rectify the secondary-side waveform           |
| RLC Filter          | Smooths the rectified output                  |
| Voltage Measurement | Measures voltage across the circuit           |
| Current Measurement | Measures circuit current                      |
| Scope               | Displays voltage/current waveforms            |
| powergui            | Supports electrical power-system simulation   |

## 🔄 Working Principle

The converter operates by switching the MOSFET devices at high frequency.

1. A DC voltage is supplied to the half-bridge circuit.
2. Gate pulses control the MOSFET switching sequence.
3. The switching devices generate a high-frequency alternating voltage.
4. The high-frequency voltage is applied to the transformer.
5. The transformer provides **galvanic isolation** and changes the voltage level according to its turns ratio.
6. The secondary-side diodes rectify the high-frequency waveform.
7. The RLC filter reduces voltage/current ripple.
8. The resulting signal provides the required DC output.
9. Voltage and current measurement blocks are used to evaluate converter performance.

## 🛠️ Software Used

* **MATLAB**
* **Simulink**
* **Simscape Electrical**
* **Power Electronics Simulation Tools**

## 📂 Project Structure

```text
Half-Bridge-DC-DC-Converter/
│
├── halfbridgedcdcconverter.slx
└── README.md
```

## 📊 Simulation Analysis

The simulation can be used to analyze:

* MOSFET switching behavior
* Gate-pulse signals
* Transformer primary and secondary waveforms
* Rectified output voltage
* Output current
* Voltage ripple
* Current ripple
* Overall DC-DC conversion behavior

## 🚀 Applications

Half-bridge DC-DC converters are commonly used in:

* Isolated DC power supplies
* Battery charging systems
* Renewable-energy power converters
* Electric vehicle power electronics
* Telecom power supplies
* Industrial power supplies
* DC bus voltage conversion

## 💡 Key Learning Outcomes

Through this project, I gained practical understanding of:

* Power semiconductor switching
* MOSFET gate control
* DC-DC converter topology
* Transformer-isolated power conversion
* Diode rectification
* RLC filtering
* MATLAB/Simulink modeling
* Simscape Electrical simulation
* Voltage and current waveform analysis

## 👨‍💻 Author

Rohit Kumar

Electrical / Electronics Engineering
Interested in **Power Electronics, MATLAB/Simulink, Control Systems, and Power Conversion**

## ⭐ Keywords

`MATLAB` `Simulink` `Simscape Electrical` `Power Electronics` `DC-DC Converter` `Half-Bridge Converter` `MOSFET` `Transformer` `Rectifier` `RLC Filter` `Power Conversion`
