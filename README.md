# Legendary Volume Game v3.0 — Official Documentation & Governance

Welcome to the public documentation and repository governance directory for **Legendary Volume Game by LTW v3.0**.

> **IMPORTANT NOTICE REGARDING SOURCE CODE:**  
> This public repository contains **strictly documentation, legal frameworks, and configuration metadata**. The underlying production application source code, execution binaries, and proprietary implementation scripts are maintained in a separate private repository and are **NOT** published, hosted, or accessible within this public project.

---

## Executive Summary

**Legendary Volume Game by LTW v3.0** is an interactive, browser-based educational mathematics laboratory designed for students (specifically demonstrated at President's College, Kotte) to practice 3D volume calculations. Built using HTML5, CSS3, and native JavaScript with a dynamic Canvas confetti engine and Web Audio API synthesis, the application renders interactive geometric solids—including Cubes, Cuboids, Cylinders, Prisms, Cones, Spheres, and Pyramids. Features include a 30-second Countdown Timer per question, an integrated Hint system (2 hints per attempt), LocalStorage Leaderboard tracking, real-time attempt logging via Google Apps Script web endpoints, dynamic feedback visuals, and integrated anti-tamper protection overlays.

---

## Architectural & Technical Highlights

- **Dynamic Visual Geometry Representation:** Utilizes tailored CSS shape mechanics and dynamic HTML canvas renderings to present geometric solids (e.g., custom border geometry for Cones and Prisms, rounded profiles for Cylinders and Spheres).
- **Client-Side Math & Precision Engine:** Evaluates 3D geometric volumes locally using exact fractional formulas and integer rounding checks without backend latency.
- **Web Audio Sound Synthesis:** Employs the native Browser Web Audio API (`AudioContext`) to generate custom synthesized tones for correct ($880\text{ Hz} \rightarrow 440\text{ Hz}$) and incorrect ($180\text{ Hz}$ sawtooth) answer submissions on the fly.
- **Backend Analytics & Remote Logging:** Asynchronously posts student attempts, correctness, individual dimension variables, and total score results directly to a Google Apps Script spreadsheet endpoint.
- **Client Integrity & Anti-Tamper System:** Features active keyboard shortcut blocking (`Ctrl+U`, `Ctrl+S`, `Ctrl+P`, `F12`), context menu prevention, and runtime DevTools detection overlays.
- **Offline & Progressive Capabilities:** Embedded Service Worker implementation enabling instant caching and offline execution during active browser sessions.

---

## Public Repository Architecture

This public repository contains only governance and metadata assets structured as follows:

```text
.
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── bug_report.md          # Structured template for reporting documentation issues
│   └── PULL_REQUEST_TEMPLATE.md   # Guidelines for documentation contribution review
├── .editorconfig                  # Code style and formatting standards across editors
├── .gitignore                     # Repository file exclusion parameters
├── CHANGELOG.md                   # Comprehensive release notes and documentation history
├── CITATION.cff                    # Machine-readable academic and professional citation format
├── CODE_OF_CONDUCT.md             # Public engagement and community interaction guidelines
├── CONTRIBUTING.md                # Policies regarding contributions and repository limits
├── LICENSE                        # Strict Source-Available & Proprietary License
├── README.md                      # Primary project overview and governance document
├── SECURITY.md                    # Vulnerability reporting protocols and security posture
├── SUPPORT.md                     # Official support channels and inquiry procedures
└── VERSION                        # Current major version tag (v3.0)
```

---

## Rights & Licensing Summary

All files published within this repository are governed by the Strict Source-Available & Proprietary License.

**Permitted:** Viewing and inspecting documentation in a browser for educational, technical review, or portfolio assessment purposes.  
**Prohibited:** Any copying, redistribution, public mirroring, commercial monetization, reverse engineering, or utilization for artificial intelligence / machine learning training.

For comprehensive details, please refer to the complete [LICENSE](LICENSE.md) file.

**Contact & Enterprise Enquiries**  
For inquiries regarding commercial licensing, enterprise deployment permissions, or direct code audits, please reach out directly to **W L T Weerasinghe** at [wltweerasinghe@gmail.com](mailto:wltweerasinghe@gmail.com) or via phone at **+94 76 021 0025**.

---

## Copyright Notice

**Copyright (c) 2026 W Lithira Thulnith Weerasinghe / LTW. All Rights Reserved.**

W Lithira Thulnith Weerasinghe™, W L T Weerasinghe™, and LTW™ are trademarks of W Lithira Thulnith Weerasinghe.