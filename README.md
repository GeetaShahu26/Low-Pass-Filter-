# 🎯 4th Order Low Pass Filter Design

## 📌 Overview
This project focuses on the design of a **4th order active low-pass filter** using operational amplifiers. The filter is implemented by cascading two 2nd-order stages to achieve better roll-off and frequency response.

---

## ⚙️ Specifications

- **Filter Type:** 4th Order Low Pass Filter  
- **Cutoff Frequency (fc):** 5 kHz  
- **Capacitor (C):** 0.1 µF  
- **Implementation:** Active (Op-Amp Based)

---

## 🧠 Basic Theory

A 4th order filter is formed by cascading two 2nd-order filters:

\[
H(s) = \frac{1}{(s^2 + a_1 s + 1)(s^2 + a_2 s + 1)}
\]

The cutoff frequency is given by:

\[
f_c = \frac{1}{2\pi RC}
\]

---

## 🔢 Final Component Values

| Component | Value |
|----------|------|
| R        | ~1.3 kΩ |
| C        | 0.1 µF |
| R1       | 10 kΩ |
| Rf       | 12 kΩ |
| R1'      | 12 kΩ |
| Rf'      | 1.8 kΩ |

---

## 🔌 Circuit Description

- Two cascaded op-amp based 2nd-order filters
- RC network defines cutoff frequency
- Gain controlled using feedback resistors

---

## 📘 Detailed Theory & Calculations

👉 For complete step-by-step derivation, refer to:  
[Theory Document](theory.md)

---

## 📈 Applications

- Audio signal processing  
- Noise filtering  
- Communication systems  
- Sensor signal conditioning  

---

## 🚀 Author
Electronics Engineering Student
