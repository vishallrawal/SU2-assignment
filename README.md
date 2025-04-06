<<<<<<< HEAD
# Assignment 1 — Compile SU2 from Source

**Name**: Vishal  
**GSoC Org**: SU2  
**Task**: Successfully compile SU2 using Meson and Ninja

---

## ✅ System Info

- OS: Ubuntu (WSL)
- Python: 3.x
- Meson: 1.3.2
- Ninja: Installed via pip
- Compiler: GCC 13.3.0

---

## 🛠️ Steps to Compile

```bash
# Clone the repo
git clone https://github.com/su2code/SU2.git
cd SU2

# Run SU2's preconfiguration script
python3 preconfigure.py

# Setup build with Meson
meson setup build

# Compile SU2
meson compile -C build


output:
[810/810] Linking target SU2_DOT/src/SU2_DOT
=======
# SU2-assignment
>>>>>>> ac6960b4b83629a50081c8f2aa97ffccee08e19c
# SU2 Assignment

This repository contains:
- Compiled SU2 source
- Screenshot of successful compilation
- Setup steps for GSoC Qualification Task
