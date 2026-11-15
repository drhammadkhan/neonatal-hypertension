# Neonatal hypertension – BP percentile check

Single-file, offline web app (`index.html`) that compares a neonatal blood pressure
(SBP, DBP, MAP) with percentiles by postconceptional age (26–44 weeks).

Reference: Dionne JM et al. Pediatr Nephrol 2012;27:17–32 (Erratum: 27:159–60).

Notes
- Thresholds between the tabulated 2-week PMA steps are linearly interpolated.
- The 36-week 99th-percentile MAP is printed as 71 in the source table used (below the 95th, 72);
  the app uses 77 (consistent with SBP 92 / DBP 70). Verify against the original paper/erratum.
- Decision support only; not a substitute for clinical judgement.
