# Minimal Computational Eloquence (MCE)
**Bounding Language Efficiency Debt to Prevent Signal Collapse**

**Author:** J. C. Brocius ([ORCID: 0009-0005-1466-0282](https://orcid.org/0009-0005-1466-0282))  
**Affiliation:** Nascent Labs & Technologies, LLC — North Las Vegas, NV  
**Live Paper & Simulator:** [https://jessebrocius-boop.github.io/minimal-computational-eloquence/](https://jessebrocius-boop.github.io/minimal-computational-eloquence/)

---

## Overview
Unbounded verbosity in generative systems accumulates **Language Efficiency Debt**—a structural overhead that degrades effective Signal-to-Noise Ratio ($\text{SNR}_{\text{eff}}$) and accelerates **Signal Collapse** across multi-turn context windows.

This repository contains the self-contained academic paper, the interactive browser-based **Token-to-Meaning Index (TMI)** and **Effective SNR** simulator, and the zero-dependency Python verification script.

## Repository Structure
* `index.html` — Single-file HTML paper and interactive TMI / $\text{SNR}_{\text{eff}}$ simulator (zero external dependencies).
* `mce_notebook.py` — Zero-dependency Python verification script for reproducing the analytical curves and boundary conditions.
* `CITATION.cff` — Native GitHub citation metadata.
* `LICENSE` — Dual license (MIT for code, CC-BY-4.0 for paper text).

## Usage
* **Live Demo:** Open the GitHub Pages link above, or open `index.html` directly in any modern browser.
* **Local Verification:**
  ```bash
  python mce_notebook.py
