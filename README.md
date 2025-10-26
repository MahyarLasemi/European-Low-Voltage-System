# **LV_Grid_Simulation**
[![License](https://img.shields.io/badge/License-Apache_2.0-red.svg)](https://opensource.org/licenses/Apache-2.0)  
[![Python](https://img.shields.io/badge/Python-3.11-blue)](https://www.python.org/downloads/release/python-3110/)  
[![Contributions Welcome](https://img.shields.io/badge/Contributions-Welcome-brightgreen)](#contributors)  
[![GitHub repo](https://img.shields.io/badge/GitHub-Repository-black.svg?logo=github)](https://github.com/V2X-Hub/LV_Grid_Simulation)  

---

## 📖 **Table of Contents**  
- [📌 Overview](#-overview)
- [🔹 Key Features](#-key-features)
- [⚡ Installation](#-installation)
  - [🔹 Prerequisites](#-prerequisites)
  - [🔹 Setup Guide](#-setup-guide)
- [🚀 Getting Started](#-getting-started)
- [📜 License](#-license)
- [🙏 Acknowledgment & Attribution](#-acknowledgment--attribution)
- [👥 Contributors](#-contributors)

---

## **📌 Overview**
**LV_Grid_Simulation** is an easy to....

This repository investigates the impact of electric vehicles (EVs) on a typical Low Voltage (LV) Grid using OpenDSS.
The purpose of this repository to give a step-by-step guide for the simulation of a typical LV Grid.

The test network model is based on the IEEE 13-node and also European Low Voltage Test Feeder (IEEE-906) [https://cmte.ieee.org/pes-testfeeders/resources/] and includes 906 nodes, 905 line segments, 55 load buses, and a base operation voltage of 416 V (stepped down from 11 kV by an 800 kVA transformer).

---

## **🔹 Key Features**  
  - ✅ **TBC** 
  - ✅ **TBC**.  
  - ✅ **TBC**.  


---

## **⚡ Installation**  
### **🔹 Prerequisites**  
Ensure **Git** is installed and added to the system `PATH`.  

### **🔹 Setup Guide**  
1️⃣ **Create a Conda virtual environment**  
```bash
conda create --name <name_env> python=3.11
conda activate <name_env>
```
2️⃣ **Install LVGS and its dependencies**  
```bash
pip install git+https://github.com/V2X-Hub/LV_Grid_Simulation.git
```

---

## **🚀 Getting Started**  
### Run tests
```bash
pip install pytest
pytest --doctest-modules examples/*.py
```

### Explore
The easiest way to explore **LVGS** is by running:  
📂 **`tbc.ipynb`** – A step-by-step guide demonstrating a simple case study.  

📂 **Advanced Case Studies** (located in the examples directory):  
-  **13-bus:** `???.ipynb`  
-  **EU-LV-Grid:** `???.ipynb`  

---

## **📜 License**  
This project is released under the **Apache License 2.0**. For academic and professional use, please provide attribution to **LVGS**.  

---

## **🙏 Acknowledgment & Attribution**  
This project uses [OpenDSS](Link) (Licence Text???).  

---

## **👥 Contributors**  
👨‍💻 **This repository is developed by:**  
- [Vahid Vahidinasab](https://github.com/vahidinasab), Full Professor and Chair in Sustainability, The University of Salford, Manchester, UK
- [Mahyar Lasemi](https://github.com/MahyarLasemi), Graduate Researcher, Smart Energy Systems Lab., SBU, Tehran, Iran

🙌 **Contributions are welcome!** See our [Contribution Guidelines](CONTRIBUTING.md).
