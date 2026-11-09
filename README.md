# OvaSense AI — MVP (MED-PCKPZB)

Interactive prototype of **OvaSense AI**: a wearable concept for managing PMOS (formerly PCOS) *after* a doctor's diagnosis (it does not diagnose). Team code MED-PCKPZB, Medathon 2026, track 3.

**Live demo:** open the GitHub Pages link of this repository (`index.html`, a single self-contained file that also works offline by double-clicking).

## What it shows
- Patient dashboard: interstitial glucose, time in range, next dose, "do I need a blood test?"
- Measurements, personalised diet, **meal ideas from the ingredients you have** (matched to your daily plan), symptoms and bleeding (PBAC) analysis
- Cycle and fertility estimates (calendar method with uncertainty; not contraception)
- Digital twin ("what if?") with a **3D body twin** built from your measurements, a **timeline** (days/weeks/months) of projected shape and measurements, and a **privacy-preserving body scan** (X-ray-style outline processed on-device; the photo is never shown or stored); rule-based local assistant
- Doctor panel with ECDSA-signed plans/commands, device simulator with fault injection, security lab (11 attacks rejected)

## Important
- All data is **synthetic**; this is an educational simulation, not a medical device.
- The assistant is rule-based (no LLM, no network calls).
- Full source (modular JS, 52 unit tests, 22 browser tests): `OvaSense-MVP-source.zip`.
