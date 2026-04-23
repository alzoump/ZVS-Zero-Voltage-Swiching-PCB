# ⚡ ZVS – Zero Voltage Switching PCB

> A high-efficiency Zero Voltage Switching (ZVS) driver PCB for high-frequency power conversion applications.

---

## 📖 What is ZVS?

**Zero Voltage Switching (ZVS)** is a technique where a switch turns on only when the voltage across it is **zero**.  
This results in:

- 🔥 **Reduced power loss & heat**
- 📉 **Lower electrical noise**
- ⚙️ **Improved efficiency**
- 🔋 **Extended component lifespan**

Especially effective in **high-frequency power converters**.

---

## 🧰 Bill of Materials (BOM)

| Component | Value / Part | Qty |
|---|---|---|
| MOSFETs | IRF260N | 2× |
| Resistors | 100 Ω, 5 W | 2× |
| Resistors | 4.7 kΩ | 2× |
| Zener Diodes | 12 V | 2× |
| Schottky Diodes | 1N5818 | 2× |
| Fast Diodes | UF600J | 2× |
| Capacitors | 1 nF polyester | 4× |
| Inductor | 10 µH (or short) | 1× |

---

## 📊 Frequency vs. Capacitance Reference

### General Capacitance Table

| Capacitance | Frequency | Inductance |
|---|---|---|
| 10 nF | ~500 kHz | ~10 µH |
| 22 nF | ~300 kHz | ~13 µH |
| 47 nF | ~200 kHz | ~13 µH |

### This Build (250 pF total)

| Frequency | Required Inductance |
|---|---|
| 500 kHz | ~405 µH |
| 1 MHz | ~101 µH |
| 2 MHz | ~25 µH |
| **3 MHz** ⭐ | **~11 µH** |
| 5 MHz | ~4 µH |

> ⭐ Default configuration targets **3 MHz** output under ideal conditions.

---

## 🔄 Compatible MOSFET Alternatives

If the **IRF260N** is unavailable, the following drop-in alternatives are compatible:

| Manufacturer | Part Numbers |
|---|---|
| Infineon / IR | IRF240, IRFB3206PBF, IRF2807 |
| Infineon / IR | IRFP260NPBF, IRFP260M, IRFP260MPBF, IRFP260 |
| Infineon / IR | IRFP250N, IRFP254, IRFP264 |
| Infineon / IR | IRFP4127, IRFP4227, IRFP4232, IRFP4668 |
| ST Micro | STW40N20, STW38NB20 |
| Motorola | MTW32N20E |



## ⚠️ Safety Notice

This circuit operates at **high frequencies and voltages**. Always:
- Use appropriate insulation and enclosures
- Verify component ratings before substitution
- Do not operate without proper knowledge of power electronics

---
