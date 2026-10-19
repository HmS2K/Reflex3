# Reflex v3.0 - 2D Acoustic Simulation Software

**Free 2D acoustic simulation software featuring real-time hybrid ray tracing, a stochastic Monte Carlo engine, and dynamic heatmaps. Includes 30-band spectral analysis and seamless DXF CAD integration for precise room acoustics and noise control engineering.**

---

## 🎯 About the Project

Reflex v3.0 is a specialized acoustic prediction tool developed for acousticians, audio engineers, and architects. It is released completely **free of charge** to the community. 

This release aims to test its real-world utility and study how professionals interact with it. Your workflow experience, bug reports, and feature requests will directly shape the development of the next major version.

## 🔍 Scope & Limitations: Why 2D?

Reflex v3.0 is **strictly a 2D simulation environment**. 

While the industry often leans toward complex 3D modeling, Reflex is purposely built in 2D to fill a crucial gap in the acoustic design workflow. 3D modeling can be computationally heavy and time-consuming. Reflex is optimized instead for:
*   **Ultra-fast iterations:** Make geometric and material adjustments on architectural floor plans and sections on the fly.
*   **Real-time attenuation calculations:** See the immediate acoustic impact of moving a wall, screen, or noise source without waiting for long renders.
*   **Instant Proof-of-Concept:** Test acoustic ideas, barrier effectiveness, and spatial layouts in seconds before committing to a heavy 3D software workflow.

## ✨ Key Features

*   **Hybrid Ray Tracing Engine:** Combines specular reflection pathways with a stochastic Monte Carlo engine for late reverberation and Lambertian radiosity.
*   **Dynamic Gridmaps (Heatmaps):** Real-time Sound Pressure Level (SPL) mapping with adaptive resolution (from Ultra 2x2 px to Low 24x24 px).
*   **30-Band Spectral Analysis:** Independent evaluation of Absorption ($\alpha$), Sound Reduction Index (Rw), Scattering, and Diffusion for every surface.
*   **Smart DXF CAD Integration:** 
    *   *Import:* Reads specific layers (`wall`, `screen`, `source`, `receiver`, `reference`) and extracts dB(A) text values.
    *   *Export:* Sends the full model back to CAD, rendering the noise map as solid polygonal hatches and isolines ready for architectural printing.
*   **PDF Material Extraction:** Automatically extracts acoustic curves by importing PDF reports from Zorba ($\alpha$) and Insul (Rw).
*   **Real-Time Interaction:** Fluid geometric editing with keyboard modifiers, axis-locking, magnetic grid snapping, and live updates on isolated microphones (Receivers).

## 🚀 Getting Started

1. Download the latest installer from the [Releases](../../releases) page.
2. Run the installer and follow the setup wizard.
3. Check the "Help" menu or press `F1` inside the app for a quick start guide.

## 🤝 Call for Feedback

Reflex v3.0 is a tool built for the community, and its future depends on your input. Since this software is completely free, the only "payment" requested is your professional feedback!

Please use the [Issues](../../issues) and [Discussions](../../discussions) tabs to share:
*   **Bug Reports:** Did the software crash? Did a DXF fail to import properly? Let me know.
*   **Feature Requests:** What crucial acoustic metric or tool is missing from your daily workflow?
*   **Use Cases:** How are you using Reflex? Share your screenshots and projects!

## 📜 License & Disclaimer

Freeware - Free for commercial and non-commercial use. Software is provided "as is" without warranty.

---
*Developed with focus on acoustics, math, and practical engineering.*
