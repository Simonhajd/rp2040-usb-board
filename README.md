# RP2040 USB Board (12×38mm)

A minimal RP2040 USB device board designed to fit within a 12mm × 38mm footprint, which is roughly the size of a small USB drive.

This project started from an RP2040 reference design and was stripped down to only the systems required for the USB device operation. I changed the flash and power components and entirely redesigned the layout to meet the width constraint, which matches the width of a standard USB port.

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
