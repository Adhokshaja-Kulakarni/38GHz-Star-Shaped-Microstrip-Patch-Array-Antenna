# 38 GHz Eight-Point Star-Shaped Microstrip Antenna Array

### Design, Simulation and Performance Analysis Using CST Studio Suite

## 1. Project Overview

This project presents the design and electromagnetic simulation of a **38 GHz, 2×1 eight-point star-shaped microstrip antenna array**, intended for potential short-range radar applications.

The antenna consists of two star-shaped radiating elements connected through a symmetrical microstrip feeding network. The design was developed and evaluated using **CST Studio Suite**.

The project focuses on antenna geometry development, impedance matching, return loss, voltage standing wave ratio (VSWR), radiation characteristics, gain, and efficiency.

**Project type:** Electromagnetic simulation and antenna design  
**Operating frequency:** 38 GHz  
**Simulation software:** CST Studio Suite  
**Application:** Short-range radar (proposed)

---

## 2. Design Specifications

| Parameter | Value |
|---|---|
| Operating frequency | 38 GHz |
| Antenna configuration | 2×1 microstrip array |
| Radiating element geometry | Eight-point star |
| Substrate material | Rogers RT/duroid 5880 |
| Relative dielectric constant | 2.2 |
| Substrate thickness | 0.254 mm |
| Copper thickness | 0.035 mm |
| Substrate dimensions | 10.5 × 6.5 mm |
| Element spacing | 3.947 mm |
| Initial outer star radius | 1.707 mm |
| Initial inner star radius | 1.229 mm |
| Approximate feed width | 0.70 mm |

The initial antenna dimensions were calculated using conventional microstrip antenna design equations and subsequently refined through electromagnetic simulation. Initial calculated dimensions should not be interpreted as independently verified final optimized dimensions.

---

## 3. Antenna Geometry and Feeding Structure

The proposed antenna comprises two eight-point star-shaped radiating patches arranged side by side on a rectangular dielectric substrate.

A symmetrical microstrip feeding structure connects the two radiating elements to a common central feed point.

The star-shaped geometry was selected as an alternative to a conventional rectangular microstrip patch for investigating its resonant and radiation characteristics at millimeter-wave frequencies.

The original antenna model is available in the repository as `38Ghz_8point_new.cst`.

---

## 4. Simulation Results

The following results were obtained from the CST Studio Suite electromagnetic simulation.

| Performance parameter | Simulated result |
|---|---|
| Resonant frequency | 38 GHz |
| S11 / Return loss | −29.464 dB |
| VSWR | 1.0705 |
| Approximate −10 dB impedance bandwidth | 1.016 GHz |
| Peak reported 3D gain | 6.481 dBi |
| Radiation efficiency | 89.36% |
| Total efficiency | 89.26% |
| Main lobe direction (2D cut) | 0° |
| 3 dB angular width (2D cut) | 48.3° |
| Side lobe level (2D cut) | −19.3 dB |

### 4.1 Return Loss (S11)

The simulated S11 reaches **−29.464 dB at 38 GHz**, indicating strong impedance matching and low reflected power at the operating frequency.

The approximately −10 dB crossing frequencies are:

- Lower frequency: 37.504 GHz
- Upper frequency: 38.520 GHz

Therefore, the estimated impedance bandwidth is:

**Bandwidth = 38.520 − 37.504 = 1.016 GHz**

### 4.2 Voltage Standing Wave Ratio

The simulated VSWR is **1.0705 near 38 GHz**.

This value is close to the ideal VSWR of 1, indicating effective impedance matching at the operating frequency.

### 4.3 Reference Impedance

The CST reference impedance plot indicates approximately:

- Real component: 50.388 Ω
- Imaginary component: 0 Ω
- Marker frequency: 38.006 GHz

This plot represents the reported **reference impedance**, and should not be interpreted as a direct antenna input-impedance measurement without further verification.

### 4.4 Three-Dimensional Radiation Pattern

The simulated three-dimensional far-field pattern at 38 GHz exhibits a directional radiation characteristic.

The CST results report:

- Gain: 6.481 dBi
- Radiation efficiency: 89.36%
- Total efficiency: 89.26%

These results characterize the simulated antenna's radiation performance.

### 4.5 Two-Dimensional Radiation Pattern

The two-dimensional far-field gain plot at 38 GHz and φ = 0° reports:

- Main lobe magnitude: 6.42 dBi
- Main lobe direction: 0°
- 3 dB angular width: 48.3°
- Side lobe level: −19.3 dB

The 2D radiation pattern provides additional information about the directional characteristics and beamwidth of the antenna.

---

## 5. Design Methodology

1. Selected a target operating frequency of 38 GHz.
2. Selected the dielectric substrate and conductor parameters.
3. Calculated initial microstrip patch and feed dimensions using antenna design equations.
4. Developed the eight-point star-shaped radiating geometry.
5. Arranged two radiating elements in a 2×1 array.
6. Constructed a shared microstrip feeding network.
7. Created the electromagnetic simulation model in CST Studio Suite.
8. Evaluated S11, VSWR, and far-field radiation characteristics.
9. Refined the simulated design to obtain the reported final results.

---

## 6. Project Files

The repository contains:

- `38Ghz_8point_new.cst` — Original CST antenna design file.
- `38GHz_8Point_2x1_Antenna_Formula_Sheet.pdf` — Antenna design calculations and parameter documentation.
- Six CST simulation screenshots showing:
  - Antenna geometry
  - S11 / return loss
  - VSWR
  - Reference impedance
  - 3D radiation pattern
  - 2D radiation pattern

The simulation screenshots are currently stored using their original uploaded filenames.

---

## 7. Tools and Technical Concepts

**Software:** CST Studio Suite

**Technical concepts:**

- Millimeter-wave antenna design
- Microstrip patch antennas
- Eight-point star-shaped radiating structures
- 2×1 antenna arrays
- Microstrip feeding networks
- Electromagnetic simulation
- S-parameter analysis
- Impedance matching and VSWR
- Radiation patterns, gain and efficiency

---

## 8. Conclusion

A 38 GHz, 2×1 eight-point star-shaped microstrip antenna array was modeled and simulated using CST Studio Suite.

The final simulation demonstrated an S11 of **−29.464 dB**, VSWR of **1.0705**, reported gain of **6.481 dBi**, and total efficiency of **89.26%**.

These results demonstrate promising simulated impedance-matching and radiation characteristics for further investigation in millimeter-wave and short-range radar antenna applications.

The project represents a simulation-based design study. Physical fabrication, experimental measurement, and practical radar-system validation have not been demonstrated.

---

## Author

**Adhokshaja Kulakarni**  
Electronics & Telecommunication Engineering  
Bangalore Institute of Technology, Bengaluru

**GitHub:** https://github.com/Adhokshaja-Kulakarni  
**LinkedIn:** https://www.linkedin.com/in/adhokshaja-kulakarni-3950002a9
