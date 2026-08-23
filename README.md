# 43-B: 1D Stochastic Z-Axis Physically Unclonable Functions

> **Part of [Project 43 — Labrador](https://github.com/aaronukgarcia): Exploring commercial and scientific applications of synthetic labradorescence**

## Overview

Proposes a new class of physical unclonable function (PUF) that encodes cryptographic entropy in the depth dimension of a one-dimensional dielectric multilayer stack. Sub-nanometre thermodynamic fluctuations during BCP self-assembly may create unique spectral barcodes.

## Status

| Item | Status |
|------|--------|
| Stage | Scientific / Conceptual |
| Spectral fingerprint stability | **Unknown** |
| Prototype | None |
| Seeking | PUF hardware security, BCP chemistry, spectral measurement, adversarial ML |

## Key Idea

Each BCP multilayer tag has a stochastic depth profile producing a unique spectral transmission signature. If stable under environmental ageing, this could serve as an optical PUF for anti-counterfeiting. The approach exploits the inherent randomness of block copolymer self-assembly rather than treating it as a defect to be eliminated.

**Prior art context:** optical PUFs are an established field — plasmonic nanoparticle PUFs (Smith et al., *Adv. Funct. Mater.* 2016), fluorescent quantum-dot labels (Liu et al., *Nat. Commun.* 2019), colloidal-crystal crack PUFs (*Nanoscale*, 2022) — but these encode entropy in the x–y plane. The z-axis (through-thickness) encoding proposed here is the untested addition.

## Target Applications (Conditional)

- Pharmaceutical anti-counterfeiting
- Luxury goods authentication
- Supply chain integrity

## Version history

| Version | Date | Change |
|---|---|---|
| 1.0a | 2026-08-23 | Reference list corrected: seven placeholder citations ("[Representative citation; exact reference to be verified]") replaced with fully verified sources; body attributions updated to match; a GAN-attribution overstatement softened to "machine-learning techniques" |

## Document

:page_facing_up: **[43-B_Stochastic_PUF_Formatted.docx](43-B_Stochastic_PUF_Formatted.docx)** — Full collaboration whitepaper
:bookmark_tabs: **[43-B_Stochastic_PUF_Formatted.pdf](43-B_Stochastic_PUF_Formatted.pdf)** — PDF export

## Author

**Aaron Garcia** · Independent Researcher · [aaron@garcia.ltd](mailto:aaron@garcia.ltd)

## Licence

This work is released under the [MIT Licence](LICENSE).
