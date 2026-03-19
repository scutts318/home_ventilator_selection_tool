# Home Ventilator Selection Tool
**Clinical decision support tool for home ventilator selection | Royal Brompton Hospital, GSTT**

A web-based clinical decision support tool designed to guide clinicians through the selection of appropriate home ventilators for patients with chronic respiratory failure. Built by a specialist home ventilation team with 17+ years of NIV and home ventilation experience.

---

## Clinical Background

Selecting the right home ventilator is a complex clinical decision involving diagnosis, ventilation interface, dependency level, portability requirements, pressure mode, and mouthpiece ventilation needs. This tool standardises that decision-making process across a busy tertiary outreach service covering a wide geographical footprint across South East England.

---

## What It Does

The tool guides clinicians through a **6-step decision pathway**:

1. **Primary diagnosis** — COPD, neuromuscular disease (MND/Duchenne/SMA), obesity hypoventilation syndrome, chest wall disorder (kyphoscoliosis), or spinal cord injury
2. **Ventilation interface** — non-invasive (NIV) vs invasive (tracheostomy)
3. **Ventilation dependency** — nocturnal only, extended/part-day, high dependency (>16hrs), or near-continuous/24-hour
4. **Portability & battery** — ambulatory, wheelchair-dependent, or mains-only
5. **Pressure mode** — fixed S/T or PC vs AVAPs/iVAPS (volume-assured pressure support)
6. **Mouthpiece ventilation (MPV)** — daytime mouthpiece ventilation requirement for NMD or high SCI patients unable to tolerate daytime mask

It then produces **ranked device recommendations** with:
- Primary and alternative device options in departmental preference order
- Battery life comparisons (internal, external, total)
- Backup ventilator and escalation guidance for high-dependency patients
- Mode and settings guidance (recommended vs alternative) by diagnosis
- Remote monitoring platform availability (AirView, prismaTS, BreasConnect)
- Phase-out warnings for devices being withdrawn from use
- Clinical alerts for complex or high-risk configurations

---

## Devices Covered

Includes devices across the full departmental formulary:

| Manufacturer | Devices |
|---|---|
| ResMed | Lumis 100, Lumis 150 |
| Löwenstein | Prisma 40, Prisma 50-C, Luisa |
| Breas (NIPPY) | NIPPY 4, NIPPY 4+ |
| Philips | Trilogy EVO (phasing out) |

---

## How to Use

Open `ventilator_selection_tool.html` directly in any modern web browser — no installation, server, or internet connection required. Designed for desktop and tablet use at the point of clinical decision-making. Includes a printable one-page reference card.

---

## Clinical Disclaimer

This tool is designed to **support**, not replace, clinical judgement. Device selection should always be confirmed by a qualified respiratory clinician with knowledge of the individual patient's clinical context. Settings, backup provision, and escalation plans must comply with local clinical governance frameworks and current BTS/ERS guidelines.

---

## Built With

- HTML5, CSS3, Vanilla JavaScript
- No external dependencies — fully self-contained single file

---

## Author

**Steve Cutts** — Senior Respiratory Physiotherapist, Band 8a Team Lead  
Outreach Complex Home Ventilation & Tracheostomy Care Team  
Royal Brompton Hospital, GSTT | [LinkedIn](https://www.linkedin.com/in/steve-cutts-147475)
