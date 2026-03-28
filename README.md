# Maple-math-conventions
A collection of Maple codes related to conventions of projective surface in the compact case and projective curve in the logarithmic case.

# Maple Code for Genericity Assumptions Verification

This repository contains two Maple files designed to verify specific genericity assumptions (Conventions) regarding the smoothness and transversality of intersections for projective surfaces and curves.

The files correspond to the following mathematical contexts:

### 📂 File 1: `convention_cpt.mw` (see also .pdf)
**Context:** Verification for a **Surface** $X$ in the projective space of dimension $3$ defined by $\widehat{R} = 0$ .

This script checks the following assumptions to ensure the surface and its associated divisors are in general position:

1.  **Smoothness:** The surface $X$ is smooth.
2.  **General Position:** The five divisors defined by the homogeneous polynomial $\widehat{R}$ and its partial derivatives ($\widehat{R}_X, \widehat{R}_Y, \widehat{R}_Z, \widehat{R}_T$) intersect transversely (i.e., any intersection has the expected codimension).
3.  **Transversality with Hyperplanes:** The coordinate hyperplanes $\{Z=0\}$ and $\{T=0\}$ intersect the surface $X$ transversely.

---

### 📂 File 2: `convention_log.mw` (see also .pdf)
**Context:** Verification for a **Curve** $\mathcal{C}$ in the projective space of dimension $2$ defined by $\widehat{R} = 0$.

This script checks the following assumptions to ensure the curve and its associated divisors are in general position:

1.  **Smoothness:** The curve $\mathcal{C}$ is smooth.
2.  **General Position:** The divisors defined by $\widehat{R}$ and its partial derivatives ($\widehat{R}_T, \widehat{R}_X, \widehat{R}_Y$) are in general position (i.e., any intersection has the expected codimension).
3.  **Transversality with Lines:** The coordinate lines $\{Y = 0\}$ and $\{T=0\}$ intersect the curve $\mathcal{C}$ transversely.
