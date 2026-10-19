# SaharaFlex Pro DRC v3.0 🇩🇿
### Advanced High-Speed PCB Design Rule Checker

**Designer:** Sifi Boukhari - Khenchela, Algeria  
**Email:** ssifi1972@gmail.com  
**GitHub:** ssifi1972-ux/SaharaFlex-Pro-DRC

## 🏆 Altium Competition Submission - $500 Prize

Custom Python tool built for flexible PCB for harsh Sahara environments.

### Results: 7 Violations Detected
- **2 CRITICAL:**
    - DiffPair_Length USB1: 0.5mm > 0.1mm tolerance
    - DiffPair_Gap USB1: 0.18mm != 0.15mm required
- **5 HIGH:**
    - Impedance 90Ω violations
    - High-Speed 50mm constraints

### 12 Design Rules Checked
Clearance 0.2mm, Trace Width 0.15mm, Via Drill 0.3mm, Impedance 90Ω, HighSpeed 50mm, Matched Length, Diff Pair Gap/Width/Length

### How to Run
```bash
python naza.py
