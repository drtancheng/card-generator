# 🏷️ TC OpenSCAD Card Script Generator

[![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-ffdd00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black)](https://ko-fi.com/drtancheng)
[![Live Landing Page](https://img.shields.io/badge/Landing_Page-39fdc0?style=for-the-badge&logo=github&logoColor=black)](https://drtancheng.github.io/tc-card-generator/)
[![Python](https://img.shields.io/badge/Python-3.9+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)

An interactive desktop designer for printable cards, asset tags, and lanyard badges optimized for dual-colour 3D printing (Bambu Lab P2S / AMS, 256 × 256 mm bed).

Generates production-ready OpenSCAD scripts with flush two-colour inlays, auto-fitted text metrics, zip-tie lanyard slots, and camera-scannable QR codes.

<p align="center">
  <img src="Interface.jpg" alt="TC OpenSCAD Card Script Generator Preview" width="800" style="border-radius: 8px;">
</p>

## ✨ Key Features

* **Flush Inlay Architecture:** Text and QR code form the first layer (0.20 mm) printed face-down on the build plate in Colour A; the structural card body forms Colour B.
* **Nozzle-Aware Verification:** Automatically evaluates stroke widths and clearances against a standard 0.4 mm nozzle to prevent unprintable text or unreadable QR modules.
* **Simulated Optical Scanner:** Integrated CV model verifies whether your printed QR code will decode reliably under real-world camera conditions.
* **True-Type Font Layout:** Automatic line-wrapping, font metrics calculations, and per-glyph stroke emboldening.
* **One-Click Multi-STL Export:** Connects directly with the OpenSCAD CLI to export aligned `_1_inlay.stl` and `_2_plate.stl` dual-part files ready for Bambu Studio.

  
### Note for Malaysian supporters 🇲🇾

For supporters in Malaysia: Should you wish to support our initiative through a local funds transfer, the DuitNow QR code below is available for your convenience.

<p align="left">
  <img src="QR.jpg" alt="DuitNow QR Support" width="220" style="border-radius: 8px;">
</p>
