# Fongwah Desktop UHF RFID Reader SDK (C#)

![UHF Reader Image][(https://fongwahrfid.net/wp-content/uploads/2025/09/U6-CU-91-768x768.jpg)or (https://fongwahrfid.net/wp-content/uploads/2026/01/UHF-RFID-Reader-Desktop-U1-CU-71.png)]

## Overview
Official C# SDK and sample application for **Fongwah Desktop UHF RFID Readers**. 
This project provides a complete Visual Studio solution to help developers integrate RFID functionalities into Windows applications.

## Compatible Hardware
* **U6-CU-91** (Desktop Writer/Reader)
* **U1-CU-71** (Portable Mini Reader)

## Features
* ✅ **Inventory Mode**: Small number bulk tag reading (Anti-collision).
* ✅ **Read/Write**: Support EPC, TID, and User memory banks.
* ✅ **Tag Lock/Kill**: Security operations for Gen2 tags.
* ✅ **Plug & Play**: USB Virtual Serial (COM) or HID mode support.

## 🚀 Quick Start
1.  **Clone the Repo**: Download this repository or `git clone`.
2.  **Open Solution**: Double-click `UHFtest.sln` in Visual Studio.
3.  **⚠️ Important**: Ensure `E7umf.dll` is in the execution folder (`/bin/Debug` or `/bin/Release`).
4.  **Select Port**: Open the software, select the correct COM port, and click "Open".

## Troubleshooting
* **DLL Not Found?** Make sure you are building for **x86 (32-bit)** platform, as the underlying DLL is 32-bit.
* **Cannot Open Port?** Check Device Manager to ensure the USB driver is installed (CP210x or CH340).

## Support
For full datasheets and protocols, visit [Fongwah Tech](https://fongwahrfid.net).
