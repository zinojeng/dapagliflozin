# EMPAGLIFLOZIN vs DAPAGLIFLOZIN — Evidence Matrix

Maintainer: dapa-research-director (path `evidence/comparison/` is Director-owned; created for this
cross-agent question — specialist peers' paths untouched).
Method: 5-domain parallel research workflow + per-domain independent citation verification
(2026-08-28; 10 agents; 83 claims, 73 abstract/label-verified exactly, verifier corrections applied
inline below). Search end date 2026-08-28.
Binding rule (all files): a cross-trial contrast between the two development programs is NEVER a
proven between-drug difference; class-level pooled estimates are NEVER attributed to either agent.

---

## 1. The one-line answer

**No completed head-to-head randomized outcome trial exists (verified against ClinicalTrials.gov
2026-08-28).** The first — APPLE TREE (NCT06642272), Danish pragmatic EHR-embedded
cluster-randomized trial, empagliflozin 10 mg vs dapagliflozin 10 mg, n≈17,200, primary composite
死亡/HHF/MI/stroke/nephropathy over 24 months — started 2024-10-10, estimated primary completion
2028-12-31, status RECRUITING. Until then every between-agent claim is indirect (NMA) or
observational, and the best-designed of those are null.

## 2. Trial-architecture pairs (the classic evidence — different experiments, not head-to-head)

| Pair | Empagliflozin trial | Dapagliflozin trial | Key architectural difference |
|---|---|---|---|
| T2D CVOT | EMPA-REG OUTCOME (n=7,020; **100% established ASCVD**; eGFR ≥30; 3.1 y; 10/25 mg pooled). MACE HR 0.86 (95.02% CI 0.74–0.99, P=0.04); **CV death 3.7% vs 5.9%, HR 0.62 (0.49–0.77)**; all-cause death HR 0.68; MI/stroke individually NS. PMID 26378978 | DECLARE-TIMI 58 (n=17,160; **40.6% ASCVD / 59.4% MRF**; CrCl ≥60; 4.2 y). MACE HR 0.93 (0.84–1.03) NS; CV death/HHF HR 0.83 (0.73–0.95) driven by HHF 0.73; **CV death 0.98 (0.82–1.17)**. PMID 30415602 | Population risk: 100% vs 40.6% secondary prevention; placebo CV-death rate 5.9%/3.1 y vs far lower. The CV-death contrast (0.62 vs 0.98) tracks population, not molecule — Zelniker meta: MACE benefit confined to ASCVD stratum (0.86 vs 1.00; p-int 0.0501, borderline). [cross-trial-inference] |
| HFrEF | EMPEROR-Reduced (n=3,730; sicker cohort — mean LVEF 27.5%, median NT-proBNP ~1,900, **eGFR floor 20**; 16 mo). Primary HR 0.75 (0.65–0.86); CV death 0.92 (0.75–1.12) NS. PMID 32865377 | DAPA-HF (n=4,744; mean LVEF 31.1%, NT-proBNP ~1,440, eGFR floor 30; 18.2 mo). Primary HR 0.74 (0.65–0.85); **CV death 0.82 (0.69–0.98); all-cause 0.83 (0.71–0.97)** — nominal. PMID 31535829 | Near-identical primary HRs (0.74/0.75). Zannad prespecified meta (n=8,474): all-cause death 0.87 (0.77–0.98), CV death 0.86 (0.76–0.98), **no between-trial heterogeneity** — the strongest argument against a drug difference in HFrEF. PMID 32877652 [class-level] |
| HF EF>40% | EMPEROR-Preserved (n=5,988; 26.2 mo). Primary HR 0.79 (0.69–0.90), HHF-driven; CV death 0.91 (0.76–1.09) NS. PMID 34449189. **EMPEROR-Pooled post hoc: HHF attenuation at LVEF ≥65% (HR 1.05, 0.70–1.58)**. PMID 34878502 | DELIVER (n=6,263; 2.3 y; broader design — HFimpEF included, in/recent-hospital enrollment allowed). Primary HR 0.82 (0.73–0.92), worsening-HF-driven; CV death 0.88 (0.74–1.05) NS; consistent LVEF ≥60 vs <60. PMID 36027570. Jhund patient-level pooled (n=11,007): CV death 0.86, all-cause 0.90, **no EF modification**. PMID 36030328 | The EF≥65% attenuation signal (empa, post hoc, wide CI, n=865) vs dapagliflozin EF-consistency is a cross-trial signal confounded by different EF distributions and DELIVER's HFimpEF inclusion. Korean PS-matched cohort with real echo LVEF found NO agent difference in any EF stratum (interaction P=.32; PMID 41343213). |
| CKD | EMPA-KIDNEY (n=6,609; **eGFR 20–45 regardless of albuminuria** OR 45–90 with UACR ≥200; mean eGFR 37.3; **20% UACR <30**; 2.0 y). Primary HR 0.72 (0.64–0.82); **all-cause death 0.87 (0.70–1.08) NS**. PMID 36331190. Post-trial follow-up: combined HR 0.79 (0.72–0.87), post-trial-only 0.87 (0.76–0.99) — legacy effect. PMID 39453837 | DAPA-CKD (n=4,304; **UACR 200–5000 mandatory**; eGFR 25–75; mean 43.1; stopped early 2.4 y). Primary HR 0.61 (0.51–0.72), NNT 19; **all-cause death 0.69 (0.53–0.88)**. PMID 32970396 | Different populations by design: empagliflozin has randomized evidence in **non-albuminuric CKD and down to eGFR 20**; dapagliflozin's evidence is albuminuric-only, eGFR ≥25. The mortality contrast (significant vs NS) is cross-trial (lower-risk, partly normoalbuminuric EMPA-KIDNEY population, shorter follow-up, early stopping in DAPA-CKD). No dapagliflozin post-trial phase exists for durability comparison. |

## 3. Pharmacology (mechanistic tier — no demonstrated clinical consequence)

- SGLT2 IC50: dapagliflozin ~1.1–1.2 nM (more potent in absolute terms; Han 2008, PMID 18356408) vs empagliflozin 3.1 nM; SGLT2:SGLT1 selectivity ~1,200-fold (dapa, hSGLT1 ~1,390–1,400 nM) vs ~2,700-fold (empa, hSGLT1 ~8,300 nM) (Grempler 2012, PMID 21985634; review Azizogli 2023, PMID 38223846). Cross-assay variability caveat; the ~2-fold selectivity gap sits far above the SGLT1-effect threshold (canagliflozin ~650 nM; sotagliflozin ~36 nM) — **no clinical consequence demonstrated; must not be used to explain outcome differences**.
- Half-life essentially identical: empagliflozin 12.4 h (population PK, label §12.3) vs dapagliflozin ~12.9 h (label §12.3). Both once daily.
- Elimination differs: dapagliflozin predominantly renal via UGT1A9 (75% urine); empagliflozin multi-UGT (1A3/1A8/1A9/2B7), 54.4% urine / 41.2% feces. Neither label converts this into differential dosing.
- Dosing: empagliflozin 10 mg all indications, 25 mg glycemia-only up-titration (EMPA-REG pooled 10+25 mg; not powered for dose comparison); dapagliflozin 5→10 mg glycemia, 10 mg cardiorenal.
- Interactions: dapagliflozin AUC −22% with rifampin, +51% with mefenamic acid, neither clinically meaningful (PMID 23061428); empagliflozin UGT-induction effect NOT evaluated (absence of evaluation ≠ absence of interaction). Lithium: class-level label advice for both (Medsafe 2023 advisory covers both).
- Labels: Jardiance DailyMed setid faf3dd6a-9cd0-39c2-0d2e-232cb3f67565 (v31, effective 2026-01-30); Farxiga setid 72ad22ae-efe6-4cd6-a302-98aaee423d69 (v47, **effective 2026-06-03**, PI rev 06/2026).

## 4. Label differences (regulatory tier — the only durable differentiation)

| Item | Jardiance (empagliflozin) | Farxiga (dapagliflozin) |
|---|---|---|
| US T2D CV claim | "reduce the risk of **cardiovascular death** … established CV disease" (EMPA-REG; label attributes to CV death HR 0.62; MI 0.87 [0.70–1.09], stroke NS) | "reduce the risk of **hospitalization for heart failure** … established CV disease or multiple risk factors" (DECLARE; hHF 0.73; label: "no change in the risk of CV death"; §14.3 components CV death 0.98, MI 0.89 [0.77–1.01], stroke 1.01 [0.84–1.21]) |
| US HF indication | CV death + HHF (EF-unrestricted) | CV death + HHF + **urgent HF visit** (EF-unrestricted; endpoint-construction artefact, not differential efficacy) |
| US CKD indication | eGFR decline, ESKD, CV death, **all-cause hospitalization** | eGFR decline, ESKD, CV death, **HF hospitalization** |
| US CKD/HF eGFR floor | **No numeric initiation floor** on current PI (only glycemic <30 limit; §8.6 records trials enrolled to eGFR 20; note §8.6 also states trials did not enroll <20) | Initiation not recommended <25; **affirmative continuation clause below 25** (§2.3, rev 06/2026) |
| US glycemic floor | not recommended <30 → **labeled for glycemia in eGFR 30–44** | not recommended <45 |
| CKD limitations of use | PKD; IV immunosuppression or **>45 mg prednisone-equivalent** for kidney disease (quantified, mirrors EMPA-KIDNEY) | PKD; requiring/recent **any** immunosuppressive therapy for kidney disease (broader wording) |
| EU initiation floor | eGFR <20 not recommended; 25 mg requires eGFR ≥60 | eGFR <25 not recommended |
| Pediatric (≥10 y, T2D glycemia) | 10→25 mg (DINAMO) | 5→10 mg |
| T1D history (EU) | never indicated | 5 mg T1D-adjunct indication withdrawn 2021 (commercial, DHPC) |

## 5. Direct comparative evidence (all indirect or observational; best-designed = null)

| Study | Design | Result |
|---|---|---|
| Engström 2024 (PMID 38918063) | Scandinavian 3-nation registry, 141,065 empa vs 58,306 dapa new users | **Null co-primaries**: MACE HR 1.02 (0.97–1.08); HF 1.05 (0.97–1.14); serious renal 0.97 (0.87–1.07). Secondaries null (MI 1.00, stroke 1.03, CV death 1.01, DKA 1.12 [0.94–1.33]) except RRT 0.77 (0.60–0.99) — 1 of ~9 unadjusted secondaries, contradicted by null primary renal outcome |
| Bonnesen 2025 (PMID 39836391) | Danish TTE, kidney outcomes, 32,819 vs 17,464 | 6-y AKI RR 0.98; CKD G3–G5 RR 0.97; progression RR 0.94 (0.56–1.58). Median baseline eGFR 88 — kidney-healthy population |
| Bonnesen 2026 (PMID 41475615) | Danish TTE, HF, 2,860 empa vs 6,264 dapa | 1-y HF rehosp RR 0.81 (0.71–0.94) favoring empa but 5-y RR 0.92 (0.79–1.06) and **all mortality null**; authors "cannot exclude"; conflicts with Korean data |
| Bu 2025 (PMID 41343213) | Korean 8-center PS-matched, echo-phenotyped LVEF, 2,465/group | Primary CV death/HHF aHR 0.99 (0.83–1.19); **no EF-stratum heterogeneity (P-int .32)** |
| Lim 2023 (PMID 37496050) vs Riaz 2023 (PMID 37459069) | Korean NHIS (72,752/group) vs US MarketScan HFpEF (881 vs 1,628) | Directionally **opposite** (Korean favors dapa for HF events/CV death; MarketScan favors empa) — signature of residual confounding, not drug effect |
| Mortada 2026 (PMID 42034323; medRxiv preprint of same study PMID 41646698) | TriNetX HFmrEF PS-matched | Hospitalization HR 0.54 favoring empa — **biologically implausible magnitude (exceeds either drug's effect vs placebo); treated as confounding signal, not evidence** |
| Lin 2026 (PMID 42045736) | TriNetX TTE, T2D + CKD 3b–5, 4,361/group | MAKE 1.04 (0.94–1.16); MACE 1.02; isolated ESKD signal for dapa 1.28 (1.11–1.48) internally inconsistent with null MAKE — hypothesis-generating only |
| Zehra 2026 (PMID 42132163) | US TTE, moderate-CV-risk T2D, IPTW | Empa vs dapa MACE: **no difference**; only empa-vs-cana differed (0.92) |
| Bu F 2026 (PMID 41984016) | OHDSI 10-database multinational, negative-control-calibrated, 1.25M second-line initiators | Individual SGLT2i broadly similar within class for MACE — methodologically strongest observational rebuttal of single-database "differences" |
| Chen 2023 NMA (PMID 36702979); Kani 2024 NMA (PMID 38293914) | Placebo-anchored NMAs | Dapa vs empa: **no significant difference on any efficacy or safety endpoint** (CV death/HHF OR 1.00 [0.66–1.55]; mortality OR 0.92) |
| Miyake 2025 (PMID 40785825); Balleza Alejandri 2024 (PMID 38921682) | Only prospective head-to-head: nonrandomized open-label crossover n=25 (NT-proBNP) + small double-blind 3-arm RCT n=30 (FMD) | Both null/interchangeable — severely underpowered surrogate studies |

## 6. Safety differences (mostly: none demonstrated)

- **Central negative finding**: Qiu 2021 meta of large RCTs (PMID 33887983) — DKA RR 2.57, genital infection RR 3.75, volume depletion RR 1.14 vs placebo as a class, with **no molecule-level heterogeneity (all P-subgroup >0.05)**.
- DKA: CNODES molecule-specific HRs (vs DPP-4i) dapa 1.86 (1.11–3.10), empa 2.52 (1.23–5.14), cana 3.58 — overlapping CIs, authors conclude class effect (PMID 32716707). Shin 2025 US TTE (PMID 39836397): dapa vs empa DKA HR 0.78 (0.68–0.90) and genital infection HR 0.92 (0.89–0.95) — but documented channeling (empa initiators higher-risk at baseline); Scandinavian DKA 1.12 (0.94–1.33) null. **Net: no credible established difference.**
- Genital/UTI: the EMPA-REG 6.4% vs DECLARE 0.9% contrast is a **definition artefact** (any genital infection vs serious/discontinuation-only) — never compare. Ljungberg 2026 Danish TTE (PMID 42236297): UTI RR 0.98; genital infection RR 1.14 (1.04–1.25) and phimosis RR 1.23 with empa — absolute differences 0.2–0.3 pp, "broadly similar safety profiles".
- Amputation/fracture: canagliflozin-specific (Heyward 2020 cana RR 1.59 vs null for empa/dapa, PMID 32502190; Dicembrini 2019; Huang 2020; Li 2023 cohort meta fracture HR 0.99). DECLARE limb outcomes null (Bonaca 2020, PMID 32795086, exploratory). FAERS amputation/Fournier RORs (e.g. empa FG ROR 565) contradict randomized evidence — notoriety artefacts, not risk estimates.
- Volume depletion: class effect (older-adult NMA OR 1.18); **no empa-vs-dapa difference identified** (PMID 41892868).
- Discontinuation for AEs: similar to placebo for both programs; NMA empa serious-AE RR 0.87 (0.76–0.99) is indirect and borderline — not evidence of differential safety. (Verifier correction applied: DAPA-HF consistency claims limited to frailty classes and age strata as cited.)

## 7. Guidelines & Taiwan (⚠️TW items require re-verification at citation time)

- ESC 2021 + 2023 update: names exactly "dapagliflozin or empagliflozin", Class I LOE A, HFrEF/HFmrEF/HFpEF — an interchangeable pair, no preference (PMID 34447992; 37622666). AHA/ACC/HFSA 2022, KDIGO 2024, ADA SoC 2026: pure class-level "SGLT2i" wording (PMID 35363499; 38490803; DOI 10.2337/dc26-S010).
- Taiwan inserts reproduce the US claim split verbatim: Jardiance 「可降低心血管原因死亡的風險」 vs Forxiga 「可降低心衰竭住院的風險」. Jardiance licenses: 衛部藥輸字第026406號 (10 mg) / 第026405號 (25 mg) [verifier-corrected]; Forxiga 第026476號 (insert 2024-04-10). Jardiance TFDA HF-indication EF scope UNRESOLVED this session — verify before citing any EF-scope difference. ⚠️TW
- NHI 2.16 is a **single joint entry with identical criteria for both agents**: HFrEF LVEF ≤40% (dapa effective 111/5/1, empa 111/8/1); HFmrEF 41–49% added 114/3/1; **HFpEF not reimbursed for either** despite ESC Class I; CKD criteria identical (care-program enrollment, eGFR 25–60, uACR 200–5000, stop at eGFR <15). Functional interchangeability is near-total under NHI. ⚠️TW
- Cost trajectory: UK High Court 2025-04-28 invalidated dapagliflozin patent/SPCs (generics path); no comparable empagliflozin invalidation found; Taiwan generic status undocumented. ⚠️TW

## 8. Verifier flag register (applied above)

1. CVOT CV-death heterogeneity statement softened to cited primaries + Zelniker (per verifier).
2. Farxiga SPL v47 date corrected to effective 2026-06-03.
3. TriNetX "companion" identified as medRxiv preprint of same study.
4. Miyake crossover relabeled nonrandomized open-label; Balleza is the only randomized (n=30, FMD).
5. Grempler/Munir selectivity and t½ figures marked full-text-tier.
6. Jardiance TW licenses corrected to 026406/026405.
7. DAPA-HF discontinuation-consistency claim trimmed to cited strata.
8. Jardiance §8.6 "did not enroll <20" noted alongside "no numeric floor".
