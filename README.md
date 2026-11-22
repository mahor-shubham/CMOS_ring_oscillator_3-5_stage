# CMOS Ring Oscillator Design and Performance Analysis

## 1. Project Overview

This project focuses on the design and performance analysis of 3-stage and 5-stage CMOS Ring Oscillators across different technology nodes: 90 nm, 45 nm, and 22 nm.

The oscillators are investigated at a constant supply voltage of 1 V to study the effects of technology scaling on oscillation frequency, propagation delay, and Power-Delay Product (PDP).

The project also explores the effect of supply voltage variation on a 5-stage CMOS Ring Oscillator implemented at the 90 nm technology node.

## 2. Project Objectives

- Design 3-stage and 5-stage CMOS Ring Oscillators.
- Analyze oscillator performance at 90 nm, 45 nm, and 22 nm technology nodes.
- Measure and compare oscillation frequencies.
- Analyze propagation delay with respect to channel length.
- Evaluate Power-Delay Product (PDP).
- Investigate the effect of supply voltage on propagation delay and power consumption.

## 3. Part A – Technology Scaling Analysis

### 3.1 Three-Stage CMOS Ring Oscillator

Design and analysis of a 3-stage CMOS Ring Oscillator at 90 nm, 45 nm, and 22 nm technology nodes with a constant supply voltage of 1 V.

# Circuit Diagram 

<img width="300" height="300" alt="image" src="https://github.com/user-attachments/assets/c9aa6e84-bd4a-4de5-97f8-dc6b2674803b" />

# Wave Form

<img width="975" height="441" alt="image" src="https://github.com/user-attachments/assets/ca0724bf-73d1-498d-a06e-19037a0d854f" />

**Parameters Analyzed:**
- Oscillation Frequency
- Propagation Delay
- Channel Length Variation
- Power-Delay Product (PDP)

### 3.2 Five-Stage CMOS Ring Oscillator

Design and analysis of a 5-stage CMOS Ring Oscillator using the same technology nodes and supply voltage.

<img width="500" height="300" alt="image" src="https://github.com/user-attachments/assets/666ee7d9-7afd-410a-9e12-68c6381235fb" />


**Parameters Analyzed:**
- Oscillation Frequency
- Propagation Delay
- Channel Length Variation
- Power-Delay Product (PDP)

### 3.3 Comparative Analysis

The analysis investigates:

- Performance comparison between 3-stage and 5-stage oscillators.
- Effect of technology scaling on oscillation frequency.
- Variation in propagation delay across different channel lengths.
- Power consumption and PDP comparison across technology nodes.

## 4. Part B – Supply Voltage Analysis at 90 nm

The 5-stage CMOS Ring Oscillator is further analyzed at different supply voltages to investigate the impact of supply voltage variation on circuit performance.

**Supply Voltage Values:**
- 1 V
- 1.5 V
- 2 V
- 2.5 V

**Parameters Analyzed:**
- Propagation Delay vs. Supply Voltage (VDD)
- Gate Power-Delay Product vs. Supply Voltage
- Oscillation Frequency Behaviour
- Power Consumption Variation

## 5. Design and Simulation Files

The project includes the following LTspice circuit schematics and documentation:

| File | Description |
|---|---|
| `Three stage CMOS Ring Oscillator.asc` | 3-stage CMOS Ring Oscillator |
| `Five stage CMOS Ring Oscillator.asc` | 5-stage CMOS Ring Oscillator |
| `PDF` | Detailed project documentation and analysis |

## 6. Tools and Technologies

- **LTspice** – Circuit design and simulation.
- **CMOS Technology** – 90 nm, 45 nm, and 22 nm.
- **Circuit Analysis** – Oscillation frequency, propagation delay, power consumption, and PDP.

## 7. Key Learning Outcomes

- Understanding the working principle of CMOS Ring Oscillators.
- Designing multi-stage inverter-based oscillators.
- Evaluating the impact of technology scaling on circuit performance.
- Analyzing oscillation frequency and propagation delay.
- Understanding power consumption and Power-Delay Product.
- Investigating supply voltage effects on CMOS circuit performance.
- Performing circuit simulations and waveform analysis using LTspice.

## 8. Conclusion

This project explores the relationship between inverter stages, technology scaling, and supply voltage in determining CMOS Ring Oscillator performance.

The comparative analysis of 3-stage and 5-stage configurations across different technology nodes provides insight into the trade-offs between oscillation frequency, propagation delay, and power consumption.

The supply voltage analysis further demonstrates how operating voltage influences the overall performance of CMOS oscillator circuits.

---

**Technologies:** CMOS | LTspice | Circuit Design | VLSI | Technology Scaling
