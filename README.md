# Image Compression Visualizer

An interactive browser-based tool to visualize image compression using **DCT** (Discrete Cosine Transform) and **Haar Wavelet Transform** — built with vanilla HTML, CSS, and JavaScript.

## What it does
- Upload any image (or use the built-in demo)
- Choose between **DCT** (JPEG-style) or **Wavelet** compression
- Drag a slider to control compression level (1% → 100%)
- See 4 live panels: Original · Reconstructed · Coefficient Map · Loss Map
- Metrics: Compression Ratio, MSE, and PSNR updated in real time

## Concepts Covered
| Topic | Detail |
|---|---|
| DCT | Block-based frequency transform (8×8, 16×16, 32×32) |
| Haar Wavelet | Multi-resolution global decomposition |
| Compression | Retain top-K coefficients, zero out the rest |
| Quality Metrics | MSE, PSNR, Compression Ratio |

## How to Run
Just open `index.html` in any browser. No installation needed.

## Tech Stack
Pure HTML · CSS · JavaScript — no libraries, no frameworks, no build step.

---
Made for academic demonstration of lossy image compression techniques.
