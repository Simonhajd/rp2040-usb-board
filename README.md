# RP2040 USB Board (12×38mm)

A minimal RP2040 USB device board designed to fit within a 12mm × 38mm footprint, which is roughly the size of a small USB drive.

This project started from an RP2040 reference design and was stripped down to only the systems required for the USB device operation. I changed the flash and power components and entirely redesigned the layout to meet the width constraint, which matches the width of a standard USB port.

<img width="220" alt="Screenshot 2026-02-16 at 4 19 01 PM" src="https://github.com/user-attachments/assets/5e1096af-4c91-473a-8912-445760701eb7" />

<img width="220" alt="Screenshot 2026-02-16 at 4 18 46 PM" src="https://github.com/user-attachments/assets/872ec61c-cf78-4c3d-8219-2ed321ef4473" />
<img width="220" alt="Screenshot 2026-02-16 at 4 23 13 PM" src="https://github.com/user-attachments/assets/efa38517-1422-4e12-bb1f-67b342546125" />

---

## What’s On It

* RP2040 (QFN)
* External QSPI flash
* 3.3V regulator
* Native USB interface
* Single status LED
* 2-layer PCB


There's no GPIO breakout since I intended to make a compact reliable RP2040 rather than a development board.

---

## Why

I wanted to see how small a functional RP2040 implementation could reasonably be made while still following the datasheet requirements.

The goal wasn’t to create a dev board, but a compact usb device.

---

## Status

Rev A boards are currently in fabrication and will be tested upon arrival.
