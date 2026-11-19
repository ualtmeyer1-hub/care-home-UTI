# Care Home UTI Symptom & Urine Sampling Guide

A lightweight, offline-capable Progressive Web App (PWA) designed to support frontline care home staff in assessing residents for suspected urinary tract infection (UTI) and determining when a urine specimen is clinically indicated[cite: 1].

## Purpose & Clinical Scope
* **Curbs Inappropriate Urine Dipsticking:** Reinforces national guidance against urine dipstick testing in older adults (65+) and catheterised residents due to high rates of asymptomatic bacteriuria[cite: 1].
* **Structured Symptom Triage:** Separates catheterised and non-catheterised resident pathways, screening first for urgent sepsis/upper UTI red flags (RESTORE2 / NEWS2) before evaluating localised urinary symptoms versus non-specific behavioural changes[cite: 1].
* **Alternative Cause Screening (`PINCH ME`):** Prompts staff to assess hydration, constipation, pain, medication, and environmental factors when residents present with isolated confusion or dark/malodorous urine[cite: 1].
* **Pre-Analytical Specimen Quality:** Provides step-by-step collection guidance (clean-catch MSU vs. aseptic needleless catheter sampling port aspiration, catheter replacement >7 days, and filling Red-Top Boric Acid tubes to the 10 mL line)[cite: 1].
* **SBAR Handover Generator:** Produces a structured SBAR summary ready to copy or share with primary care, ANPs, or out-of-hours services[cite: 1].

## Guideline Alignment
* **UKHSA** Diagnostic Decision Tools for Older Adults (65+) and Catheter-Associated UTI[cite: 1]
* **SIGN 160** Management of suspected bacterial lower urinary tract infection in adult women[cite: 1]
* **NICE QS90 & NG113** Urinary tract infections in adults / Catheter-associated UTI[cite: 1]
* **UK SMI B 41** Investigation of urine (Issue 8.8)[cite: 1]

## Technical Notes
* Self-contained HTML/CSS/JS with zero external runtime dependencies[cite: 1].
* Uses a Web App Manifest (`manifest.json`) and Service Worker (`sw.js`) so care staff can save the tool to a smartphone home screen and run it offline[cite: 1].
* No patient-identifiable data is stored, logged, or transmitted.

## Disclaimer
This tool is a clinical decision support aid for care home staff and does not replace clinical judgement. Always escalate acutely deteriorating residents immediately via local RESTORE2, NHS 24, or 999 protocols[cite: 1].