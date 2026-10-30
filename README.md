# More Modes Than You Think: Cantilever Beam Modal Analysis

**Course:** AE 264 – Vibrations  
**Semester:** Spring 2026  
**Authors:** Nirmit Bhanderi, Amal M S

## Overview

This project investigates the vibrational characteristics of an idealised aircraft wing modelled as a cantilever beam. Analytical predictions using Euler–Bernoulli beam theory are compared with three-dimensional finite element modal analysis.

The study examines natural frequencies, mode shapes, and the effects of cross-sectional geometry on bending and torsional behaviour.

## Methodology

1. **Analytical analysis:** Derived natural frequencies using Euler–Bernoulli beam theory.
2. **Finite element analysis:** Performed modal analysis on rectangular and L-shaped beam geometries.
3. **Comparison:** Compared analytical predictions with numerical results and investigated discrepancies between the two approaches.

## Results

The rectangular beam showed good agreement between analytical and finite element predictions for its first few modes.

| Mode | FEA frequency | Analytical frequency | Difference |
|---|---:|---:|---:|
| Vertical bending (1) | 62.326 Hz | 61.69 Hz | 1.02% |
| Lateral bending (1) | 409.33 Hz | 411.26 Hz | 0.47% |
| Torsion | 1151.8 Hz | 1157.78 Hz | 0.52% |
| Axial | 6379.2 Hz | 6364.69 Hz | 0.23% |

The analysis also investigates bending–torsion coupling in the asymmetric L-shaped cross-section, in contrast to the more independent modes observed in the symmetric rectangular beam.

## Mode Shapes and Animations

### Rectangular Beam

| Mode | Mode shape | Animation |
|---|---|---|
| 1 | [View](figures/mode1.jpg) | [Watch](videos/mode_01.mp4) |
| 2 | [View](figures/mode2.jpg) | [Watch](videos/mode_02.mp4) |
| 3 | [View](figures/mode3.jpg) | [Watch](videos/mode_03.mp4) |
| 4 | [View](figures/mode4.jpg) | [Watch](videos/mode_04.mp4) |
| 5 | [View](figures/mode5.jpg) | [Watch](videos/mode_05.mp4) |
| 6 | [View](figures/mode6.jpg) | [Watch](videos/mode_06.mp4) |
| 7 | [View](figures/mode7.jpg) | [Watch](videos/mode_07.mp4) |
| 8 | [View](figures/mode8.jpg) | [Watch](videos/mode_08.mp4) |
| 9 | [View](figures/mode9.jpg) | [Watch](videos/mode_09.mp4) |
| 10 | [View](figures/mode10.jpg) | [Watch](videos/mode_10.mp4) |

### L-Shaped Beam

![L-shaped beam mode shape](figures/L-shaped%20mode.png)

[Watch mode animation](videos/L-shaped_beam_mode.mp4)

## Report

[Read the complete project report](report/Project_Report.pdf)

## Tools

- ANSYS – Finite element modal analysis
- MATLAB – Analytical calculations and numerical analysis
