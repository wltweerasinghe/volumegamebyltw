# Legendary Volume Game v2.0 — Official Documentation & Governance

Welcome to the public documentation and repository governance directory for **Legendary Volume Game by LTW v2.0**.

> **IMPORTANT NOTICE REGARDING SOURCE CODE:**  
> This public repository contains **strictly documentation, legal frameworks, and configuration metadata**. The underlying production application source code, execution binaries, and proprietary implementation scripts are maintained in a separate private repository and are **NOT** published, hosted, or accessible within this public project.

---

## Executive Summary

**Legendary Volume Game by LTW v2.0** is an interactive, browser-based educational mathematics laboratory designed for students (specifically demonstrated at President's College, Kotte) to practice 3D volume calculations. Built using HTML5, CSS3, and native JavaScript with a dynamic Canvas confetti system and Web Audio API synthesis, the application renders interactive geometric solids—including Cubes, Cuboids, Cylinders, Prisms, Cones, Spheres, and Pyramids[cite: 1]. Features include a 30-second Countdown Timer, integrated Hint system, LocalStorage Leaderboard tracking, real-time attempt logging, and dynamic feedback visuals[cite: 1].

---

## Architectural & Technical Highlights

- **Dynamic Visual Geometry Representation:** Utilizes CSS visual styling and dynamic HTML canvas renderings to present tailored geometry graphics for each solid type[cite: 1].
- **Client-Side Math & Precision Engine:** Handles local evaluation of mathematical volumes (using standard values such as $\pi = \frac{22}{7}$ or $3.14$) with integer rounding checks without backend latency[cite: 1].
- **Web Audio Sound Synthesis:** Employs the native Browser Web Audio API (`AudioContext`) to synthesize custom sound effects for correct and incorrect answer submissions on the fly[cite: 1].
- **Backend Analytics & Remote Logging:** Integrates with Google Apps Script web endpoints to track individual student attempts, accuracy, and overall round scores asynchronously[cite: 1].
- **Offline & Progressive Capabilities:** Embedded Service Worker implementation allowing instant caching and offline capability during active browser sessions[cite: 1].

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
└── VERSION                        # Current major version tag (v2.0)
```

---

## Rights & Licensing Summary

All files published within this repository are governed by the Strict Source-Available & Proprietary License.

**Permitted:** Viewing and inspecting documentation in a browser for educational, technical review, or portfolio assessment purposes.
**Prohibited:** Any copying, redistribution, public mirroring, commercial monetization, reverse engineering, or utilization for artificial intelligence / machine learning training.

For comprehensive details, please refer to the complete [LICENSE](LICENSE.md) file.

**Contact & Enterprise Enquiries**
For inquiries regarding commercial licensing, enterprise deployment permissions, or direct code audits, please reach out directly to [W L T Weerasinghe](mailto:wltweerasinghe@gmail.com).

---

## Copyright Notice

**Copyright (c) 2026 W Lithira Thulnith Weerasinghe / LTW. All Rights Reserved.**

W Lithira Thulnith Weerasinghe™, W L T Weerasinghe™ and LTW™ are trademarks of W Lithira Thulnith Weerasinghe.