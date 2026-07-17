# Documentation
# 📑 ThePrae Documentation & User Guide

Welcome to the official documentation directory for **The Persistent Reconstruction of Absorption Ensembles (ThePrae)**. This page provides an overview of the available guides, installation requirements, and testing workflows to help you get started with the software suite.

---

## 📘 Available Manuals
* **[User Manual (PDF)](https://github.com/SLRI-Tools/ThePrae/blob/main/docs/ThePrae%20User%20Manual.pdf)**: A comprehensive, step-by-step guide with graphical interface (UI) screenshots covering both **SLRI-Cal** (energy calibration) and **SLRI-LCF** (high-speed linear combination fitting) modules. *(Please ensure you have uploaded your PDF file named exactly 'ThePrae_User_Manual.pdf' into this docs folder).*

---

## 📥 Benchmarking & Test Dataset
To verify the software’s performance and reproduce the computational times mentioned in our paper (e.g., matching up to 50,000 synthetic mixtures in **5.23 seconds** on an Intel Core i5-14500 workstation), you can download our complete supplementary test data via the link below:

🔗  **[Download ThePrae Runtime Tests (ZIP)](https://github.com/SLRI-Tools/ThePrae/blob/main/ThePrae_runtime_tests.zip)**

### What is included in the test package:
1. **Sample XAS Spectra**: Raw and normalized experimental data for calibration testing.
2. **Standard Reference Library**: A collection of component spectra used for the Linear Combination Fitting (LCF) benchmarks.
3. **Pre-configured Benchmarks**: Simulated data sets containing thousands of mixed spectra to test the processing speed.

---

## 🛠️ System Requirements
* **Operating System**: Windows 10 / 11 (64-bit)
* **Hardware (Recommended)**: Intel Core i5 (12th Gen or higher) or AMD Ryzen 5 with at least 16 GB RAM for optimal high-throughput fitting performance.
* **Dependencies**: None. The distributed version is a standalone installer (`.exe`) that runs out-of-the-box.

---

## ✉️ Contact & Support
For academic inquiries, bug reports, or feature requests, please open an issue in the main repository or contact the lead developers:
* **Email**: anan@slri.or.th
* **Institution**: Synchrotron Light Research Institute (SLRI), Thailand
