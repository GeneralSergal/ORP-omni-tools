<p align="center">
  <img src="Docs/banner.png" alt="ORP Δ / OmniTools Banner" width="100%">
</p>
<p align="center">
  <img src="https://img.shields.io/badge/ORP-Δ-blueviolet" alt="ORP Version">
  <img src="https://img.shields.io/badge/OmniTools--Fork-v0.6.0-blue?style=flat" alt="OmniTools Version">
  <img src="https://img.shields.io/badge/status-active-success" alt="Status">
  <img src="https://img.shields.io/badge/SHS-5--State-green" alt="SHS Model">
  <img src="https://img.shields.io/badge/LAS-L1→L6_Active-orange" alt="Layered Authority">
  <img src="https://img.shields.io/badge/License-GPL--3.0-red" alt="GPL-3 License">
</p>

<h1 align="center">OmniTools Δ — An ORP‑Governed Epistemic Sandbox</h1>

<p align="center">
  A privacy-first, client-side utilities suite retrofitted into a hardened, zero-trust runtime network. <br>
  <strong>Signal > Narrative · Recoverability > Completion · Provenance > Coherence</strong>
</p>

---

## **Mandatory Runtime Header Invariant**
Every ORP‑aligned deployment or execution run of this codebase must enforce and emit the following state telemetry header *before* parsing telemetry or execution buffers:

```text
[SHS: GREEN | AMBER | RED]
[DRIFT: 0.000 (NONE) | LOW | MODERATE | HIGH]
[CRA: VALID | DEGRADED | UNKNOWN]
[LAS: STATEFUL_CORE_ACTIVE | L3_GOVERNANCE | L6_OBSERVER]

```

This header is a **non‑negotiable invariant**. If a client environment or container execution cannot produce it, the operational boundary is considered **structurally corrupt**.

---

## **1. Epistemic Architecture & The Sandbox**

OmniTools Δ is an open-source, client-side web application designed to simplify everyday tasks (manipulating images, code, vectors, and numbers) while maintaining absolute **epistemic isolation**.

Following the **Layered Authority Stack (LAS)** specification, this instance treats all incoming files as unverified, high-entropy signals. The system enforces strict architectural boundaries:

* **Zero-Trust Ingestion:** Every single file is processed **entirely client-side**. No telemetry, pixel arrays, or text buffers are ever shipped off to an external network registry.
* **Semantic Resilience:** Image conversion pipelines (specifically PNG-to-WebP) are enhanced to support **Stealth RIFF Container Injection**. You can lock raw bytecode or structural data streams straight into the asset architecture silently without causing visual drift.

---

## **2. Layered Authority Stack (LAS) Mapping**

| Layer | Authority | Component Interface | Function | Status |
| --- | --- | --- | --- | --- |
| **L1** | Absolute | Native Browser Files / Crypto Inputs | Raw typed signals & canvas buffers (immutable) | Observational |
| **L2** | High | TypeScript Math / Token Validators | Deterministic transformation & calculations | Trusted |
| **L3** | Primary | Local OmniTools Logic & Code Engines | Governance core, asset compilers & processing invariants | Authoritative |
| **L4-L6** | Observational | Client Runtime UI & Observer Matrices | High-observability state verification & user interfaces | Isolated |

---

## **3. Core Features Spec**

OmniTools Δ provides an array of functional processors, running inside an incredibly lightweight 28MB Docker runtime core:

### **Image/Video/Vector Core**

* **WebP Stealth Encoder:** Native conversion of standard generation artifacts (PNG/JPG) into highly efficient WebP bitstreams featuring hidden `orpd` RIFF chunk injection.
* **Vector Geometry Synthesis:** SVG manipulation engines that treat images as structural mathematical coordinate grids rather than flat pixels.
* **Media Modulators:** Image Resizing, Image Editing, Video Trimming, and Video Reversers.

### **Data & Math Processors**

* **Semantic Transformers:** JSON Tools, CSV Parsers, and XML Formatting Engines.
* **Deterministic Calculators:** Prime number generators, Voltage/Current Ohm’s law calculators, and timezone delta counters.

### **Document & Text Isolation**

* **PDF Splitters & Mergers:** Client-side object-stream modifications for document payloads.
* **Text Formatters:** Case converters, list shufflers, and clean regex sanitizers.

---

## **4. Self-Host / Deployment**

The tool deployment requires negligible overhead, allowing you to run your own localized instance securely on your own hardware nodes or personal domains.

### **Docker CLI**

```bash
docker run -d --name omni-tools --restart unless-stopped -p 8080:80 iib0011/omni-tools:latest

```

### **Docker Compose (`docker-compose.yml`)**

```yaml
services:
  omni-tools:
    image: iib0011/omni-tools:latest
    container_name: omni-tools
    restart: unless-stopped
    ports:
      - "8080:80"

```

---

## **5. Repository Development Setup**

This is a React framework compiled using TypeScript and Material UI. Icons are pulled natively via Iconify.

### **Project Initialization**

```bash
git clone [https://github.com/GeneralSergal/ORP.git](https://github.com/GeneralSergal/ORP.git)
cd omni-tools
npm i
npm run dev

```

### **Scaffolding a New Module / Feature Component**

```bash
# General tool compilation script
npm run script:create:tool my-tool-name folder1

# Example: Injecting a custom PNG compressor
npm run script:create:tool compress image/png

```

*(Note: Use `folder1\folder2` backslashes if operating on Windows local terminals).*

### **Verification & Testing Suites**

```bash
npm run test          # Execute integration tests
npm run test:e2e      # Execute end-to-end framework testing

```

---

## **6. Compliance & Structural Requirements**

To prevent repository corruption and remain aligned with the ORP Δ spec:

1. **Browser Sovereignty:** No feature component may invoke an external API request that transmits raw file contents away from the browser window.
2. **Deterministic Compilation:** All custom modules added to this fork must maintain strict TypeScript typing boundaries.
3. **Drift Threshold Enforcement:** Any operations processing data arrays that exceed acceptable variance limits ($\sigma^2 \ge 0.15$) must trigger an immediate processing halt to defend the runtime window against memory drift.

---

## **7. License & Provenance**

```text
[PROVENANCE CERTIFICATION MATRIX]
ORIGINAL CORE AUTHOR: Ibrahima Gaye Coulibaly (c) 2024
UPSTREAM ARCHITECTURE: MIT License
FORK MODIFICATIONS & EXTENSIONS: GNU General Public License v3.0 (GPL-3.0)

```

This project is a fork of `omni-tools`. In accordance with the terms of the original permissive license, the foundational core framework remains attributed to the upstream author under the **MIT License**.

All custom pipeline features, cryptographic data containers, metadata injection routines, and stateful tracking modules written under this repository fork are protected, sealed, and published strictly under the **GNU General Public License v3.0**.
