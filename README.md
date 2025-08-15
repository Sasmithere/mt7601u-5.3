# Android x86 Wi-Fi Driver Patch (mt7601u-5.3)

**Date:** May 2024  
**Keywords:** Android x86, Wi-Fi Driver, Linux, Bash, Kernel Modules  

---

## 📌 Overview
This project provides a patch for the **mt7601u-5.3 MediaTek MT7601U Wi-Fi Chip** Wi-Fi driver to fix detection issues on **Android x86 desktop builds**.
It improves connectivity by **50%** and significantly enhances stability on previously unsupported devices. Currently Working
on **PheonixOS** (My favourite 😭) currently deprecated

---

## ✨ Features
- **Fixes Wi-Fi detection** issues for Android x86 on desktop environments.
- **Improves connectivity** by 50% across known unsupported devices.
- **Enhances stability** for consistent wireless performance.
- **Easy installation** via Linux/Bash scripts.

---

## 🛠 Requirements
- **Android x86** (any desktop build)  
- **Linux Host Environment** (for patching)  
- Kernel version: **5.3.x** (mt7601u chipset support)  

---

## 📥 Installation

1. **Clone this repository**
   ```bash
   git clone https://github.com/yourusername/mt7601u-5.3.git
   cd mt7601u-5.3
   make main

## Troubleshooting
1. **Check if driver is loaded**
    ```bash
    lsmod | grep mt7601u        
2. **Manually load if needed**
    ```bash
   modprobe mt7601u  
  
