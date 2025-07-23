# 🔧 Advanced Digital Design Projects – ENCS3310

This repository contains two Verilog-based digital logic design projects completed for the **Advanced Digital Design** course. Each project demonstrates the design, simulation, and testing of digital systems using structural and behavioral modeling techniques.




---

## ✅ Project 1: FSM Sequence Detector (`1011`)

This project implements a **Finite State Machine (FSM)** to detect the binary sequence `1011` using both structural and behavioral modeling.

### 🔍 Key Features:
- Moore FSM design
- T-Flip-Flop based implementation
- Sequence detection output logic
- Simulation and waveform validation
- Comparison between structural and behavioral outputs

### 📌 Output:
The FSM activates the output signal when the sequence `1011` is detected in a serial input stream. Testbench waveforms confirm correct state transitions.

---

## ✅ Course Project: 2x4 Decoder + Mux Circuit

This project combines a **2-to-4 Decoder** with **2x1 Multiplexers (MUX)** to realize complex logic expressions (`f1`, `f2`) from a defined truth table.

### 🔍 Key Features:
- 2-to-4 decoder with enable input
- MUX selection-based output control
- Logic design using Verilog modules
- Simulation using testbench with waveform analysis

### 📌 Output Functions:
- `f1 = (~decoderout[2] & I0) | (decoderout[2] & I1)`
- `f2 = ~(decoderout2[2] & decoderout2[3])`

The design is verified using waveform simulations where all input combinations are tested.

---

## ▶️ How to Run

1. Use any Verilog simulator like **ModelSim**, **Vivado**, or **Icarus Verilog**
2. Compile all modules (`.v` files saved from `.txt`)
3. Run the testbench
4. Open waveform viewer to validate the behavior

---

## 📎 Notes

- All Verilog files are provided in `.txt` format for easy inspection
- Simulation results are documented in PDF and DOCX files
- These projects demonstrate both combinational and sequential design

---

## 📘 Course

- Course: **ENCS3310 – Advanced Digital Design**
- Topic: FSM, MUX, Decoder, Structural/Behavioral modeling
