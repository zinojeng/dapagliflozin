# CLAIMS LEDGER — dapagliflozin 核心論斷帳冊（Director 版）

維護：dapa-research-director。狀態：pending methods audit（appraisal/ 完成後逐條對齊）。
每條欄位：Claim｜Population｜Intervention/Comparator｜Endpoint｜Absolute｜Relative (95% CI)｜
Follow-up｜Design｜Source｜Certainty（高/中/低/極低）｜Applicability｜Key caveat｜
✅ Permitted wording｜❌ Prohibited wording。
數值上游：evidence/landmark/、evidence/frontier/、evidence/safety/（均經 PubMed 摘要層級核驗；
⚠️ 註記者見 DECISION_LOG D13/D16）。

---

## A. 第二型糖尿病（DECLARE-TIMI 58）

### A1. MACE 中性
- Claim：dapagliflozin 未顯著降低 T2D 患者之 MACE。
- Population：17,160 T2D（40.6% ASCVD；59.4% 多重危險因子）；CrCl ≥60。
- I/C：dapagliflozin 10 mg od vs placebo。Endpoint：MACE（CV death/MI/缺血性中風）。
- Absolute：8.8% vs 9.4%。Relative：HR 0.93（0.84–1.03）, p=0.17。Follow-up：中位 4.2 年。
- Design：RCT 共同主要終點（優越性未達；非劣性達成）。Source：Wiviott NEJM 2019, PMID 30415602。
- Certainty：高（陰性結果之確定性）。Applicability：腎功能大致正常之 T2D。
- Caveat：非劣性達成常被忽略；class-level 統合（Zelniker）顯示 MACE 效益侷限 ASCVD 層。
- ✅「DECLARE 中 MACE 未顯著下降（HR 0.93, 0.84–1.03）」
- ❌「dapagliflozin 預防心肌梗塞／中風」

### A2. CV death/HHF 下降（HHF 驅動）
- Absolute：4.9% vs 5.8%。Relative：HR 0.83（0.73–0.95）, p=0.005；HHF HR 0.73（0.61–0.88）；CV death HR 0.98（0.82–1.17）。
- 其餘同 A1。Certainty：高。
- Caveat：完全由 HHF 驅動；CV death 中性。
- ✅「顯著降低 CV death/HHF 複合，效果由心衰住院驅動」
- ❌「降低心血管死亡」（DECLARE 層級）

### A3. 腎臟次級終點下降
- Endpoint：cardiorenal 複合（≥40% eGFR 下降至 <60、ESRD、renal/CV death）。
- Absolute：4.3% vs 5.6%。Relative：HR 0.76（0.67–0.87）；renal-specific HR 0.53（0.43–0.66）；ESRD/renal death 11 vs 27 事件, HR 0.41（0.20–0.82）。
- Design：prespecified secondary（Mosenzon Lancet D&E 2019, PMID 31196815）。Certainty：中-高（次級終點；ESRD 事件數極少）。
- ✅「次級分析顯示腎臟複合終點下降」
- ❌ 把 DECLARE 腎臟結果當作與 DAPA-CKD 同級之硬終點確證。

### A4. DKA 風險倍增（絕對風險極低）
- Absolute：0.3% vs 0.1%（27 vs 12 例）。Relative：HR 2.18（1.10–4.30）⚠️（HR/CI 取自 PMC6683461 轉載，待全文核）。
- Design：RCT 裁定安全性端點＋obs 一致（CNODES HR 2.85 class；dapa 1.86）。Certainty：高（方向）；HR 精確值待核。
- ✅「長期使用使 DKA 風險約增一倍，但 4.2 年絕對風險 <0.5%」
- ❌ 忽略絕對風險、或以 RCT 值推估非糖尿病族群。

## B. 心衰竭（DAPA-HF、DELIVER、pooled）

### B1. HFrEF 主要複合下降（兩分項皆顯著）
- Population：4,744 HFrEF（NYHA II–IV, LVEF ≤40%, NT-proBNP 升高；45% T2D）；排除 eGFR<30、SBP<95 ⚠️FT。
- Absolute：16.3% vs 21.2%。Relative：HR 0.74（0.65–0.85）；worsening HF 0.70（0.59–0.83）；CV death 0.82（0.69–0.98）；all-cause death 0.83（0.71–0.97）。Follow-up：18.2 月。
- Source：McMurray NEJM 2019, PMID 31535829。Certainty：高。
- Applicability：門診慢性 HFrEF；不含急性失代償、hypotensive、eGFR<30。
- ✅「HFrEF 中同時降低心衰惡化與死亡——四大 landmark 中唯一單試驗層級雙分項顯著者」
- ❌「所有心衰患者均證明死亡下降」

### B2. 糖尿病狀態不修飾療效（exploratory）
- Relative：無 DM HR 0.73（0.60–0.88）；有 DM 0.75（0.63–0.90）；p-int 0.80（Petrie JAMA 2020, PMID 32219386，原文標 exploratory）。Certainty：中。
- ✅「未見糖尿病狀態之效果修飾證據」
- ❌「證明糖尿病與非糖尿病患者等效」

### B3. HFmrEF/HFpEF 主要複合下降（worsening HF 驅動）
- Population：6,263, LVEF >40%, eGFR ≥25。Absolute：16.4% vs 19.5%。
- Relative：HR 0.82（0.73–0.92）；worsening HF 0.79（0.69–0.91）；CV death 0.88（0.74–1.05，單獨 NS）。Follow-up：2.3 年。
- Source：Solomon NEJM 2022, PMID 36027570。Certainty：高。
- ✅「LVEF >40% 中減少心衰惡化事件；單一試驗未證明 CV 死亡下降」
- ❌「DELIVER 證明 HFpEF 死亡率下降」

### B4. 跨 EF 死亡率下降（pooled，dapagliflozin 專屬）
- Design：prespecified patient-level pooled（DAPA-HF+DELIVER, n=11,007）。
- Relative：CV death HR 0.86（0.76–0.97）；all-cause 0.90（0.82–0.99）；total HF admissions RR 0.71（0.65–0.78）。
- Source：Jhund Nat Med 2022, PMID 36030328。Certainty：中-高（pooled）。
- ✅「病人層級預先規劃合併分析顯示跨 EF 死亡率下降」——死亡率主張一律引此，不引 DELIVER 單獨。
- ❌ 把 class-level（Vaduganathan/SMART-C）數字冠名 dapagliflozin。

### B5. Frailty：相對療效一致；KCCQ 改善之交互作用僅限 PRO（O-17：事件端 p-int 0.40，禁稱「衰弱者臨床效益更大」）
- Relative：FI class 3 HR 0.74（0.61–0.91）；p-int 0.40；KCCQ p-int 0.021（Butt Circulation 2022, PMID 36029465, prespec）。Certainty：中。
- Caveat：衰弱者 AE 與停藥整體較多（非藥物特異）——處方難度是實務問題。
- ✅「衰弱不是不給藥的理由；耐受性管理是重點」
- ❌「衰弱患者證明獲益更大」（絕對獲益推論而非交互作用證明）

### B6. DELIVER 腎臟複合未下降
- Relative：HR 1.08（0.79–1.49）；事件率 1.1/100 py；eGFR slope 改善（surrogate）。Source：Mc Causland JAMA Cardiol 2023, PMID 36326604（prespec+post hoc 複合）。
- ✅「HFpEF 族群未證明腎臟硬終點保護」
- ❌ 以 slope 改善宣稱腎保護。

## C. 慢性腎臟病（DAPA-CKD）

### C1. 主要複合下降
- Population：4,304；eGFR 25–75；UACR 200–5000；67.5% T2D；排除 T1D、PKD、lupus、ANCA ⚠️FT。
- Absolute：9.2% vs 14.5%；NNT 19（15–27）。Relative：HR 0.61（0.51–0.72）。Follow-up：2.4 年（提前中止）。
- Source：Heerspink NEJM 2020, PMID 32970396。Certainty：高。
- ✅「蛋白尿 CKD（含非糖尿病）之腎臟／心血管複合顯著下降，NNT 19」
- ❌ 外推至非蛋白尿 CKD、eGFR<25、透析、移植、ADPKD。

### C2. 全因死亡下降
- Absolute：4.7% vs 6.8%。Relative：HR 0.69（0.53–0.88）, p=0.004。Certainty：高（次級）。
- ✅「全因死亡顯著下降（次級終點）」

### C3. 無糖尿病層一致
- Relative：T2D 0.64（0.52–0.79）；非 T2D 0.50（0.35–0.72）；p-int 0.24（Wheeler, PMID 33338413, prespec）。Certainty：中-高。
- ✅「器官保護與降血糖脫鉤」
- ❌「非糖尿病獲益更大」（點估計差異非交互作用證據）

### C4. Stage 4（eGFR<30）次族群
- Relative：27%（95% CI −2 至 47）；p-int 0.22（Chertow JASN 2021, PMID 34272327, prespec subgroup）。Certainty：低（該層單獨）。
- ✅「與整體一致、無交互作用證據」
- ❌「已證明 eGFR <30 有效」

### C5. 起始 eGFR dip 為血行動力學現象
- 數值：2 週 dip −2.61（T2D）/−2.01（非 T2D）；DAPA-HF −4.2 vs −1.1；>10% dip 者結局不劣（HR 0.73, 0.59–0.91）；總 slope +0.95/年。
- Design：prespec（Heerspink 2021）＋post hoc（Adamson 2022, PMID 35442064；Jongs 2022, PMID 35977807 ⚠️屬性待核）。Certainty：中-高。
- ✅「預期性 dip 非停藥指徵（KDIGO practice point）；持續或 >30% 下降須找其他原因」
- ❌「eGFR 下降代表腎損傷、應停藥」

## D. 急性與新族群（frontier）

### D1. 住院內起始（DAPA ACT HF-TIMI 68）主要終點未達
- Population：2,401 急性 HF 住院（71.5% LVEF≤40%）。Absolute：10.9% vs 12.7%（2 月）。
- Relative：HR 0.86（0.68–1.08）, P=0.20；all-cause death 0.66（0.43–1.00，secondary）；symptomatic hypotension 3.6% vs 2.2%。
- Source：Berg Circulation 2025, PMID 40884036。Certainty：高（陰性主要終點）；早期死亡訊號＝低。
- ✅「單一試驗主要終點未達；安全性與可行性確立；早期效益主張屬 class-level 統合（HR 0.71；J Card Fail 2026 TSA all-cause RR 0.61）」
- ❌「DAPA ACT 證明早期死亡效益」；「陰性故應放棄住院起始」

### D2. DICTATE-AHF 主要利尿效率未達
- Relative：OR 0.65（0.41–1.02）, P=0.06；次級 decongestion surrogates 正向。Source：Cox JACC 2024, PMID 38569758。Certainty：中（安全/機轉）；效益＝未證明。
- ✅「支持早期使用之安全性與利尿增益（surrogate）」
- ❌ 當作臨床結局證據。

### D3. DapaTAVI 複合正向（worsening HF 驅動）
- Population：1,222 高 HF 風險 TAVI 後（西班牙、open-label）。Absolute：15.0% vs 20.1%（1 年）。
- Relative：HR 0.72（0.55–0.95）；worsening HF subHR 0.63（0.45–0.88）；all-cause death 0.87（0.59–1.28）；KCCQ 無增益；genital infection 與 hypotension 較多。
- Source：Raposeiras-Roubín NEJM 2025, PMID 40162639。Certainty：中-高（開放標籤、單一國家）。
- ✅「高風險 TAVI 後降低死亡或心衰惡化複合，由心衰惡化驅動」
- ❌「降低 TAVI 後死亡率」；外推至全體 TAVI 或未處理之重度 AS。

### D4. DAPA-MI：cardiometabolic 終點驅動
- Population：4,017 急性 MI、無糖尿病無慢性 HF。Relative：win ratio 1.34（1.20–1.50）；CV death/HHF HR 0.95（0.64–1.40）；新發 T2D（prediabetes 層）HR 0.74（0.55–0.99, post hoc）。
- Source：James NEJM Evid 2024, PMID 38320489。Certainty：高（硬終點無效之確定性）；cardiometabolic 獲益＝中。
- ✅「改善 cardiometabolic 結果（防新發糖尿病、減重）；未降低 CV death/HHF」
- ❌「DAPA-MI 顯示心血管保護」

### D5. 透析（DARE-ESKD-2）中性
- Population：80 慢性透析、24 週。NT-proBNP 差 −155 pg/ml（−327 至 −33）但調整後 P=0.065；KCCQ/6MWT/echo 均中性；安全。
- Source：Barreto KI Rep 2026, PMID 41970273。Certainty：低（小樣本 surrogate）。
- ✅「安全但未證實 surrogate 改善；硬終點待 Renal Lifecycle」
- ❌「已證明透析無效」或「DAPA-CKD 延伸至透析」。CI/P 不一致須註記（D9）。

### D6. 腎移植（INFINITI）機轉性
- Population：52 穩定 KTR、12 週。SBP 主要終點未達（wk12 −2.9, −8.9 至 3.1）；GFR dip 保留；12 週安全乾淨。
- Source：Sridhar CJASN 2025, PMID 41385300。Certainty：極低（臨床結局）。
- ✅「機轉與短期安全資料；無臨床結局證據」

### D7. ADPKD（Uchiyama crossover）
- Population：27 位 tolvaptan 使用者、6 月交叉。eGFR slope +2.57 vs −5.65（P=0.002）；TKV −0.44% vs +5.04%（P=0.01）。
- Source：Uchiyama KI Rep 2025, PMID 40303212。Certainty：極低-低（小、開放、surrogate、曾有 TKV 增加個案訊號）。
- ✅「生物學合理性與早期訊號；非已證實之 ADPKD 治療」

## E. 安全性核心

### E1. 生殖器黴菌感染增加；嚴重 UTI 不增加
- 數值：label pool 女 8.4% vs 1.5%、男 2.8% vs 0.3%；DECLARE 嚴重/致停藥 0.9% vs 0.1%；嚴重 UTI 1.5% vs 1.6%⚠️；Dave obs HR 0.98（vs DPP-4i）。
- Certainty：高。✅ 兩句並陳。❌ 以 GU 感染混稱 UTI 風險。

### E2. 非糖尿病者 DKA：RCT 零事件、個案已證實可發生
- RCT：DAPA-CKD 非 DM 0 例（Persson 已核全文）；DAPA-HF 非 DM 0 例（Petrie）。個案：Umapathysivam 2024 等（攝食下降誘發；治療核心為給糖）。
- Certainty：「極低風險」高確定；「零風險」錯誤。
- ✅「試驗中未見，上市後個案已見——機率低但表現易被忽略」
- ❌「非糖尿病不會發生酮酸中毒」；以個案估發生率。

### E3. 術前停藥 ≥3 天（label/共識，無 RCT）
- FDA/ADA/TFDA ≥3 天 vs 英國「術前一日＋當日」vs 澳紐「共 3 天」；停藥後糖尿可持續 3 天、上市後報告至 2 週；個案顯示停藥 5 天後仍 euDKA。
- Certainty：規則＝label/共識級；最適天數無比較證據。
- ✅「停藥期是風險降低而非保證；術日晨血酮是更可靠的安全網」
- ❌ 將 3 天描述為經證實之安全界線。

### E4. AKI 不增加、反而較少
- DECLARE HR 0.69（0.55–0.87）⚠️轉載；SMART-C class RR 0.77（0.70–0.84）；KDIGO：dip 非停藥指徵。Certainty：高（class）；dapa 專屬 HR 待核。
- ✅「大型試驗未見 AKI 增加；class 統合顯示 AKI 較少」＋例外個案（滲透性腎病變, teaching signal）。

## F. Class-level（引用時必稱「SGLT2i 類別」）

- F1. MACE 效益集中於 ASCVD 層（O-4 紅線：p-interaction 0.0501 屬**邊際**、且為類別間接證據——禁稱「已證明僅限次級預防」）：Zelniker 2019——ASCVD HR 0.86（0.80–0.93）vs 無 ASCVD 1.00（0.87–1.16）。
- F2. 腎病進展 RR 0.63（0.58–0.69）；CV death RR 0.86：SMART-C 2022（13 trials, n=90,409）。
- F3. HF 五試驗：CV death/HHF 0.77（0.72–0.82）：Vaduganathan 2022。
- F4. 住院 HF 起始早期效益：embedded meta HR 0.71（0.54–0.93）；J Card Fail 2026 TSA all-cause RR 0.61（0.47–0.81）。
- ✅ 一律標示 class-level。❌ 冠名 dapagliflozin。
