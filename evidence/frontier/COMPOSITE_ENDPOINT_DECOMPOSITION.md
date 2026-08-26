# Composite endpoint decomposition — recent dapagliflozin trials

Maintained by: dapa-frontier-evidence
Purpose: for every positive (or near-positive) composite, identify exactly which components drove the result, so no composite is misdescribed as uniform benefit across components.

---

## DapaTAVI (NEJM 2025; DOI 10.1056/NEJMoa2500366; PMID 40162639)

Primary composite (1 yr): all-cause death OR worsening HF (hospitalization or urgent visit).
Result: 15.0% vs 20.1%; HR 0.72 (95% CI 0.55–0.95), P=0.02 — **positive**.

| Component | Dapagliflozin | Standard care | Effect estimate | Drives composite? |
|---|---|---|---|---|
| All-cause death | 7.8% (47/620) | 8.9% (55/637) | HR 0.87 (0.59–1.28) | **No** — CI crosses 1 |
| Worsening HF (hosp. or urgent visit) | 9.4% | 14.4% | subHR 0.63 (0.45–0.88) | **Yes — sole significant driver** |

Correct claim: "Dapagliflozin after TAVI reduced the composite of death or worsening HF, driven by worsening-HF events; no significant effect on mortality alone was shown."
Incorrect claim: "Dapagliflozin reduces mortality after TAVI."

Robustness (post hoc, Rev Esp Cardiol 2026; DOI 10.1016/j.rec.2025.08.003; PMID 40976500): win ratio of original hierarchy 1.36 (1.03–1.78); adding NYHA class tightened precision (WR 1.31, 1.09–1.56); **adding KCCQ moved the estimate to null** (WR 1.10, 0.94–1.30) — consistent with the prespecified KCCQ analysis (JACC 2025; DOI 10.1016/j.jacc.2025.07.051; PMID 41062227) showing no incremental health-status benefit (12-mo OR 1.03, 0.83–1.27). The clinical-event benefit and the health-status neutrality are separate findings; do not blend them.

---

## DAPA ACT HF-TIMI 68 (Circulation 2025; DOI 10.1161/CIRCULATIONAHA.125.076575; PMID 40884036)

Primary composite (2 mo): CV death OR worsening HF.
Result: 10.9% vs 12.7%; HR 0.86 (0.68–1.08), P=0.20 — **negative/neutral on the primary**.

| Component / secondary | Dapagliflozin | Placebo | Effect estimate | Note |
|---|---|---|---|---|
| Worsening HF | 9.4% (115) | 10.3% (122) | HR 0.91 (0.71–1.18) | Neutral; numerically dominant component |
| CV death | 2.5% (30) | 3.1% (37) | HR 0.78 (0.48–1.27) | Neutral |
| All-cause death | 3.0% (36) | 4.5% (53) | HR 0.66 (0.43–1.00) | **Secondary endpoint in a trial that missed its primary — hypothesis-generating, not a mortality claim** |

Correct claim: "In-hospital initiation of dapagliflozin did not significantly reduce CV death or worsening HF at 2 months; a nominal all-cause-mortality signal and the class-level meta-analysis (CV death/worsening HF HR 0.71, 0.54–0.93; all-cause death HR 0.57, 0.41–0.80) support safety and possible early benefit of in-hospital initiation as a class."
Incorrect claims: "DAPA ACT proved early mortality benefit"; "dapagliflozin failed in acute HF, so in-hospital initiation should be abandoned" (the trial confirms safety/feasibility of in-hospital initiation; guideline momentum rests on the class-level totality).

Meta-analysis component note (embedded prespecified meta, same paper): the pooled early benefit is **class-level** (dapagliflozin + empagliflozin + sotagliflozin trials); DAPA ACT HF-TIMI 68 is the largest single contributor and was itself neutral on the primary.

---

## DAPA-MI (NEJM Evid 2024; DOI 10.1056/EVIDoa2300286; PMID 38320489)

Primary: hierarchical win-ratio composite — death → HHF → nonfatal MI → AF/flutter → new-onset T2DM → NYHA class at last visit → ≥5% weight loss.
Result: win ratio 1.34 (1.20–1.50), P<0.001 — **positive**.

Decomposition:
- Hard clinical components (death, HHF, nonfatal MI, AF/flutter): event rates low; CV death or HHF 2.5% vs 2.6%, HR 0.95 (0.64–1.40) — **no contribution**.
- **Drivers: cardiometabolic components added mid-trial — new-onset T2DM and body-weight reduction** (trial itself states the win ratio "was mainly driven by the added cardiometabolic outcomes"; analysis plan changed during the trial because of low event accrual).
- Subanalyses quantify the drivers: new-onset T2DM in prediabetes 10.1% vs 13.1% (HR 0.74, 0.55–0.99; JAHA 2025, DOI 10.1161/JAHA.124.040327, PMID 40728174); consistent WR across LVEF strata with no CV-death/HHF effect in either (ESC Heart Fail 2025, DOI 10.1002/ehf2.15420, PMID 40958495).

Correct claim: "After MI in patients without diabetes or HF, dapagliflozin improved cardiometabolic outcomes (chiefly prevention of new-onset diabetes and weight reduction) but did not reduce CV death or HF hospitalization."
Incorrect claim: "DAPA-MI showed cardiovascular benefit post-MI."

---

## DICTATE-AHF (JACC 2024; DOI 10.1016/j.jacc.2024.02.009; PMID 38569758)

Primary: diuretic efficiency (weight change per loop-diuretic dose) — a single surrogate, not a composite: OR 0.65 (0.41–1.02), P=0.06 — **missed**.
Positive secondaries are all surrogates of decongestion (lower cumulative loop dose 560 vs 800 mg P=0.006; natriuresis P=0.03; urine output P=0.005).
Correct claim: "DICTATE-AHF supports safety and enhanced diuresis of early in-hospital dapagliflozin; its primary efficiency endpoint was not met, and it was not powered for clinical outcomes."

---

## DARE-ESKD-2 (Kidney Int Rep 2026; DOI 10.1016/j.ekir.2026.106355; PMID 41970273)

Primary: NT-proBNP change (surrogate): between-group difference −155 pg/ml (−327 to −33) with adjusted **P=0.065 — not significant**; all secondaries (KCCQ, 6MWT, echo) neutral.
Note the CI/P discordance as reported in the abstract (CI excludes 0 while adjusted P=0.065): flag for methods auditor — likely reflects the adjustment model; cite the P-value-based conclusion (neutral) as the authors do.
Correct claim: "In 80 dialysis patients over 24 weeks, dapagliflozin was safe but did not improve HF surrogate markers."
Do NOT infer either hard-outcome benefit or futility; Renal Lifecycle remains the outcome test in this population.

---

## DAPA-CKD dialysis-initiation post hoc (Clin Kidney J 2026; DOI 10.1093/ckj/sfag170)

Not a composite decomposition but a mortality decomposition worth recording: all-cause mortality aHR 0.47 (0.23–0.98) was **driven by non-CV mortality** (aHR 0.27, 0.10–0.73), with CV mortality neutral/uninterpretable (aHR 1.33, 0.40–4.40; n=167). Post-randomization subset → observational grade. An effect concentrated in non-CV death lacks an obvious mechanism and should be flagged as possibly chance/selection.

---

## Cross-cutting rules applied

1. A positive composite ≠ uniform component benefit (DapaTAVI: HF-driven; DAPA-MI: metabolic-component-driven).
2. A neutral primary + positive secondary mortality ≠ mortality benefit (DAPA ACT HF-TIMI 68).
3. Surrogate movement (NT-proBNP, natriuresis, eGFR slope, TKV) ≠ clinical outcome benefit (DARE-ESKD-2, DICTATE-AHF, Uchiyama ADPKD crossover).
4. Class-level meta-analytic benefit ≠ agent-level proof (Circulation 2025 embedded meta; J Card Fail 2026 TSA meta).
