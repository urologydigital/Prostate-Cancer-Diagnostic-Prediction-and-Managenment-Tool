# Prostate Cancer Clinical Decision Support Tool

A comprehensive web-based clinical decision support tool for prostate cancer diagnosis, risk stratification, treatment planning, and follow-up management.

## Version 3.0

### Features

| Module | Description |
|--------|-------------|
| **Step 1: Assessment** | Initial patient assessment, PSA, DRE, risk factors, referral guidance |
| **Step 2: Investigations** | MRI PI-RADS, PSAD calculation, biopsy results |
| **Step 3: CPG Calculator** | Cambridge Prognostic Group calculation |
| **Step 4: Risk & Prognosis** | Comprehensive TNM staging, EAU risk groups, treatment recommendations, survival estimates |
| **Step 5: Treatment Options** | Detailed treatment information with pros, cons, risks, and BAUS patient leaflets |
| **Step 6: Follow-up** | Post-treatment surveillance protocols with scheduled dates and discharge criteria |
| **Step 7: Progression** | Biochemical recurrence management and salvage treatment options |
| **Step 8: Clinical Diagnosis** | Pathway for patients diagnosed clinically without biopsy |

### Clinical Guidelines

This tool is based on:
- **NICE NG131** - Prostate cancer: diagnosis and management (2019, updated 2021)
- **EAU-EANM-ESTRO-ESUR-ISUP-SIOG Guidelines** - Prostate Cancer (2024/2025)
- **GIRFT Urology** - Getting It Right First Time (April 2024)
- **BAUS** - British Association of Urological Surgeons patient information

### Treatment Modalities Covered

- Active Surveillance
- Watchful Waiting
- Radical Prostatectomy (Robotic/Laparoscopic)
- External Beam Radiotherapy (EBRT)
- Brachytherapy (LDR and HDR)
- SBRT/SABR (5-Fraction Hypofractionated RT)
- HIFU (High Intensity Focused Ultrasound)
- Cryotherapy
- Androgen Deprivation Therapy (ADT)
- Novel Hormonal Agents
- Chemotherapy (Docetaxel)

### Usage

1. Open `index.html` in any modern web browser
2. Navigate between modules using the step indicators
3. Each module works independently - no need to complete previous steps
4. Use "Reset This Module" to clear individual sections
5. Use "Reset All / New Patient" for a fresh start

### Technical Details

- **Single HTML file** - no server required, works offline
- **No data storage** - all calculations performed locally in browser
- **Mobile responsive** - works on desktop, tablet, and mobile
- **No patient data transmitted** - fully GDPR compliant

### Disclaimer

**FOR CLINICAL REFERENCE ONLY - NOT A MEDICAL DEVICE**

This tool is intended to support, not replace, clinical decision-making. All management decisions must be individualised based on patient circumstances, preferences, comorbidities, and local resources. All cancer diagnoses must be discussed at the Multidisciplinary Team (MDT) meeting.

### Author

Developed for NHS clinical practice.

### License

MIT License - See LICENSE file for details.
