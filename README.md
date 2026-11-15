# Neonatal hypertension – BP percentile check

Single-file, offline web app (`index.html`) that compares a neonatal blood pressure
(SBP, DBP, MAP) with percentiles by corrected gestational age (CGA) (26–44 weeks).

Reference: Dionne JM et al. Pediatr Nephrol 2012;27:17–32 (Erratum: 27:159–60).

Notes
- Values are Table 2 as corrected in the erratum (all 10 age rows checked).
- Thresholds between the tabulated 2-week CGA steps are linearly interpolated.
- Decision support only; not a substitute for clinical judgement.
