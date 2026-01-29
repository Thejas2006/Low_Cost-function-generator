
# 🔧 Digital Function Generator (Op-Amp Based)

A low-cost, digital function generator designed and built using op-amps and discrete components to produce **sine, square, and triangular waveforms** with adjustable frequency and amplitude. This project demonstrates practical waveform generation using classical analog design techniques.

---

## 📌 Overview

This function generator is built around an **XR-2206 waveform generator IC** and **741 op-amps** to create stable and tunable output signals for electronics testing and experimentation.

It supports:

* **Sine Wave**
* **Square Wave**
* **Triangular Wave**
* **Low and High Frequency Ranges**
* **External Amplitude Control for Square Wave**

Designed as a hands-on learning platform for understanding:

* Oscillator design
* Integrators and comparators
* Signal shaping
* Op-amp gain control
* Frequency control using RC networks

---

## ⚙️ Features

* Dual frequency range (Hz to kHz scale)
* Adjustable amplitude control
* Stable waveform shaping using analog filters
* External op-amp stage for square wave scaling
* Split power supply operation for symmetric waveforms

---

## 🧠 System Architecture

### Core Blocks:

* **XR-2206 IC** – Generates base sine, square, and triangular signals
* **RC Timing Network** – Controls output frequency
* **Op-Amp Stage (741)** – Used for square wave amplitude control
* **Dual Power Supply (±15V)** – Ensures clean and symmetric output

---

## 🔬 Experimental Results (Proof of Work)


> 📷 *Waveform captures are included in the "results" pdf for verification.*

---

## 🛠 Hardware Used

* XR-2206 Function Generator IC
* 741 Op-Amps
* Resistors & Potentiometers (1kΩ – 100kΩ range)
* Capacitors (0.001µF – 2000µF)
* Dual Power Supply (±15V)
* Digital Storage Oscilloscope (DSO)
* Breadboard / PCB Setup

