# bandgap-ota-opamp-design
Analog IC design and simulation in LTspice: OTA, two-stage op-amp, and bandgap reference with wide-swing cascode current mirror, focusing on high output resistance, supply independence, and stable biasing.e with wide-swing cascode current mirror. Covers gain, phase margin, slew rate, ICMR, output swing, and bias stability.
# 🔬 Analog IC Design (LTspice)

This repository contains analog integrated circuit design projects implemented and simulated in LTspice. The focus is on high-performance analog building blocks including amplifiers and reference circuits.

---

## 📁 Projects

### 🔹 1. Two-Stage Amplifier (BJT & MOSFET)

* Designed and simulated two-stage amplifier circuits
* Compared BJT and MOSFET implementations

**Key Results:**

* BJT Gain ≈ 2981
* MOSFET Gain ≈ 28.1
* Frequency response and impedance analyzed

---

### 🔹 2. Two-Stage Unbuffered Op-Amp

* Miller compensated two-stage op-amp design

**Key Results:**

* Gain ≈ 7000 V/V (~76 dB)
* Phase Margin ≈ 60°
* Slew Rate ≈ 7.75 V/µs
* Power Dissipation ≈ 0.94 mW

---

### 🔹 3. OTA (Operational Transconductance Amplifier)

* MOSFET differential pair with current mirror load

**Key Results:**

* High voltage gain (~100 dB at low frequency)
* Slew Rate ≈ 30 V/µs
* MHz-level bandwidth
* ICMR and output swing analyzed

---

### 🔹 4. Bandgap Reference + Wide-Swing Cascode Current Mirror

* Designed temperature-independent reference current source
* Integrated with wide-swing cascode current mirror

**Key Features:**

* High output resistance (≈ gm·ro² behavior)
* Reduced dependency on supply voltage (VDD)
* Output current stable across wide Vout range
* µA-level reference current (~10 µA)

---

## ⚙️ Analyses Performed

* DC Operating Point (.op)
* AC Analysis (Bode Plot)
* Transient Analysis (Slew Rate)
* Input Common-Mode Range (ICMR)
* Output Swing Analysis
* Supply Dependency (VDD sweep)
* Output Dependency (Vout sweep)

---

## 📊 Key Engineering Insights

* Cascode structures significantly improve output resistance
* Wide-swing cascode reduces minimum output voltage requirement
* Slew rate is limited by bias current and load capacitance
* MOSFET amplifiers provide higher input impedance
* Bandgap references ensure supply and temperature stability

---

## 🛠️ Tools Used

* LTspice
* Analog Circuit Design Techniques

---

## 📎 Reports

Detailed reports are available in the `/report` folder:

* Bandgap Reference & WS Cascode Analysis
* OTA Design
* Two-Stage Op-Amp Design

---

## 👨‍💻 Author

**Murat Emre Demirci**
Electrical & Electronics Engineering Student

---
