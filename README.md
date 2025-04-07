# 🚀 SSTO Monobloc – Compact Orbital Vehicle with 13 km Mid-Air Refueling

## 📌 Objective

Design a **single-stage-to-orbit (SSTO)** vehicle capable of:
- Taking off horizontally from Earth
- Using **lightweight airbreathing engines** up to 13 km altitude
- Performing a **LOX/LH2 full refueling at 13 km**, using a **hybrid tank conversion system** that transforms kerosene tank volume into LOX/LH2 storage
- Switching to **cryogenic rocket engines** to reach low Earth orbit (~7.8 km/s)
- No detachable stages, no external infrastructure

---

## 💡 General Characteristics

| Feature                   | Specification                  |
|---------------------------|----------------------------------|
| **Type**                  | Single-stage-to-orbit (SSTO)     |
| **Total Length**          | ~42 m                           |
| **Wingspan**              | ~24 m                           |
| **Height**                | ~7 m                            |
| **Dry Mass**              | 23,000 kg                       |
| **Takeoff Mass**          | ~155,000 kg (after full LOX/LH2) |
| **Internal Volume**       | ~850 m³                         |

---

## 💎 Propulsion

### ✈️ Airbreathing Engines (0 → 13 km)

| Engine            | Based on        | Type         | Thrust per Unit | Role                         |
|-------------------|------------------|--------------|------------------|-------------------------------|
| **SRX-mini**      | F124 / custom     | Turbofan      | ~35–50 kN        | Takeoff + low-altitude climb  |

> Two engines mounted low on the fuselage, used only up to 13 km.

---

### 🚀 Rocket Engines (13 km → Orbit)

| Engine         | Based on     | Type         | Thrust per Unit | Isp   | Dimensions (H × ⌀) |
|----------------|--------------|--------------|------------------|-------|--------------------|
| **BE-3**       | Blue Origin  | LOX/LH2 cryo | ~490 kN          | ~450 s| ~2.0 m × ~1.0 m     |

> **Four BE-3 engines** mounted at the rear of the fuselage, activated after LOX/LH2 refueling. Designed for reuse and regenerative cooling.

---

## 🛢️ Tanks & Storage

| Content       | Location        | Estimated Volume | Details                                                                 |
|---------------|------------------|------------------|-------------------------------------------------------------------------|
| **LH2**       | Front section    | ~430 m³          | Lightweight, longitudinal layout                                        |
| **LOX**       | Rear section     | ~220 m³          | Denser, located close to engines                                        |
| **Kerosene**  | Lower fuselage   | ~200 m³          | Used during takeoff, then **80% converted** into LOX/LH2 tank volume    |

> After takeoff, a hybrid system transforms up to **80% of the kerosene tank volume** into a LOX/LH2 fillable tank, which transfers propellant to the main tanks.

---

## 🌐 Flight Profile

### ✈️ Phase 1: Horizontal Takeoff
- Uses **SRX-mini airbreathing engines**
- Climbs to **13 km / ~250 m/s**
- Burns ~60% of kerosene reserves

### 💡 Phase 2: LOX/LH2 Refueling at 13 km
- Mid-air refueling via hybrid tank conversion
- LOX/LH2 transferred to main tanks
- Air intakes closed; air engines deactivated

### 🚀 Phase 3: Rocket Propulsion
- **4 × BE-3** engines activated (total thrust: 1.96 MN)
- Gravity turn: 60° → 10°
- Horizontal velocity: **~7.3 km/s**
- Final altitude: **~162.5 km**
- ✅ **Orbital status: achieved**

---

## 🔄 Key Advantages
- ✅ Horizontal takeoff from conventional runway
- ✅ Smooth transition between atmospheric and orbital propulsion
- ✅ 13 km refueling via hybrid system optimizes mass and performance
- ✅ Full SSTO capability without staging

---

## 🌟 Next Steps
- Thermal shield design for reentry
- Powered or gliding atmospheric landing
- Orbital refueling or ISRU for Mars-based missions
