4-1_MUX_USING_CMOS# 🔀 4:1 Multiplexer (MUX) Using CMOS - LTspice Simulation

This project implements a **4:1 multiplexer (MUX)** using **CMOS logic gates**, designed and simulated using **LTspice**. A multiplexer is a key combinational circuit widely used in digital systems for data selection.

---

## 📌 Project Objective

Design and simulate a **4-to-1 Multiplexer using CMOS logic gates** with:
- Minimized transistor count
- Realistic timing and voltage behavior
- Verified logic functionality using LTspice

---

## 🛠️ Tools Used

- **LTspice XVII** – Circuit design and simulation
- **CMOS Logic** – Based on PMOS and NMOS transistors
- **Windows/Linux OS** – LTspice compatible platform

---

## ⚙️ Circuit Overview

### 4:1 Multiplexer Function

A 4:1 MUX selects one of 4 input signals based on 2 selection inputs:
Inputs: A, B, C, D
Select: S1, S0
Output: Y = A·S1'·S0' + B·S1'·S0 + C·S1·S0' + D·S1·S0

### CMOS Design Method:

- Implemented using **pass-transistor logic** or **gate-level CMOS** (AND/OR/NOT using PMOS and NMOS)
- Selection logic and output buffering handled with complementary transistor pairs


---

## ✅ Simulation Results

- Output waveform confirms selection logic matches truth table
- Propagation delays and voltage levels observed
- CMOS gates function correctly under typical 5V VDD

> 📷 *See `waveforms/mux_output_waveform.png`*

---

## 📊 Truth Table

| S1 | S0 | Output Y |
|----|----|----------|
| 0  | 0  | I0       |
| 0  | 1  | I1       |
| 1  | 0  | I2       |
| 1  | 1  | I3       |


## 🚀 How to Simulate

1. Open `mux_4to1_cmos.asc` in LTspice
2. Click **Run (Simulate)** button
3. Probe the output node (`Y`)
4. Observe waveform transitions based on `S1` and `S0` inputs

---

## 🧠 Learning Outcomes

- CMOS implementation of combinational logic circuits
- Use of LTspice for custom logic gate simulations
- Understanding of transistor-level logic optimization


---

## 📜 License

This project is open-source and available under the MIT License.

---


