# Dapagliflozin 圍術期與生病日（Sick-Day）管理流程

> 檢索截止日 2026-08-27。本檔為臨床實作導向之整理；每項規則均標注權威來源與證據性質。
> 標示【verbatim】者為自原始文件逐字轉錄之關鍵句（英文保留原文）。
> 原始文件備份於 `evidence/safety/sources/`。
> 重要限制：各權威機構之停藥時程**彼此不一致**（美國 3–4 天 vs 英國「術前一日＋當日」vs
> 澳紐「共 3 天」）；且個案報告顯示停藥 5 天後仍可發生 euDKA（見
> `CASE_REPORT_FAILURE_MODES.md` #12–14）——停藥時程是風險降低手段，不是安全保證。

---

## 1. 擇期手術前停藥時程 — 各權威機構對照

| 權威來源 | 停藥規則 | 恢復用藥條件 | 出處（locator） |
|---|---|---|---|
| **US FDA 藥品仿單**（FARXIGA PI rev. 06/2026, §2.4） | 【verbatim】"Withhold FARXIGA for at least 3 days, if possible, prior to surgery or procedures associated with prolonged fasting."（至少 3 天） | 【verbatim】"Resume... when the patient is clinically stable and has resumed oral intake." | accessdata.fda.gov 202293s035lbl.pdf §2.4；本庫 sources/farxiga_s035.pdf |
| **US FDA 安全通報**（2020-03-19 更新版；注意：常被誤引為 3-15） | dapagliflozin／canagliflozin／empagliflozin 術前至少 3 天停藥；ertugliflozin 至少 4 天 | — | FDA DSC「3-19-2020 Update」（原頁已下架，經 Internet Archive 存證）；sources/fda_2020_dsc.txt |
| **EMA Forxiga SmPC** §4.4 | 未定天數。【verbatim】"Treatment should be interrupted in patients who are hospitalised for major surgical procedures or acute serious medical illnesses. Monitoring of ketones is recommended... Measurement of blood ketone levels is preferred to urine." | 【verbatim】"may be restarted when the ketone values are normal and the patient's condition has stabilised." | EMA Forxiga EPAR product information §4.4；sources/forxiga_smpc.pdf |
| **ADA Standards of Care 2026**（Section 16, Diabetes Care 2026;49(Suppl 1); DOI 10.2337/dc26-S016, PMID 41358892） | 【verbatim】"SGLT2 inhibitors should be held for 3–4 days before elective surgery."；擇期手術前 3 天（ertugliflozin 4 天）；非擇期手術者術後密切監測 euDKA | 住院中因心衰竭適應症可於恢復進食後重啟（§16, p. S346） | Diabetes Care 2026 §16 pp. S343, S346；sources/ada16.pdf |
| **英國 2025 多學會共識**（El-Boghdadly K et al. Anaesthesia 2025;80:412–424, DOI 10.1111/anae.16541；承 CPOC 2021/2023 路線） | 【verbatim】"omitted the day before and the day of a procedure"（術前一日＋手術當日，約 36–52 小時） | 【verbatim】"once eating and drinking normally and capillary ketones are < 0.6 mmol.l-1" | Anaesthesia 2025 全文（open access）；CPOC 原始 PDF 未能直接取得（Cloudflare 阻擋），另由 UKCPA Handbook 佐證 |
| **澳紐 ADS/ADEA/ANZCA/NZSSD Alert Update May 2023** | 【verbatim】"omit SGLT2i for at least 3 days (i.e. 2 days pre-procedure, and the day of procedure)"（住院手術與需腸道準備之大腸鏡）；日間手術（含胃鏡、無腸道準備）僅停手術當日 | 恢復正常進食（日間手術須完全恢復口服攝食）；【verbatim】"Consider delaying recommencement of SGLT2i for a further 24 hours." | diabetessociety.com.au Alert Update May 2023（全文已讀）；2022-11 ADS-ANZCA 指引 v2 同旨（sources/ads_anzca_2022.pdf） |
| **台灣 TFDA 核准仿單**（Forxiga 10 mg, 仿單版本 2024-04-10, §5.1.1） | 【verbatim】「預計接受非緊急、選擇性手術的病人，應考慮至少3天前暫時中斷Forxiga」 | 風險因子解除後恢復 | 衛部藥輸字第026476號仿單；sources/TFDA_Forxiga_10mg_insert_2024-04-10.pdf |
| **台灣 MOHW 病安通報系統 TPR 學習案例 No.186**（2024-12） | 重大手術：術前 72 小時（3 天）；小手術／局麻：24–48 小時；需禁食之內視鏡：24 小時；顯影劑檢查：通常 24–48 小時 | 正常進食、代謝穩定、無急性併發症、傷口癒合 | patientsafety.mohw.gov.tw No.186（全文已讀）；sources/MOHW_TPR_No186_periop_SGLT2i_2024-12.pdf。⚠️ 該文件中英文藥名與中文商品名配對有誤植，勿引用其品名對應 |
| **KDIGO 2024 CKD 指引** Practice Point 3.7.2 | 【verbatim】"It is reasonable to withhold SGLT2i during times of prolonged fasting, surgery, or critical medical illness (when people may be at greater risk for ketosis)."（未定天數） | — | Kidney Int 2024;105(4S), §3.7, p. S214–S217, DOI 10.1016/j.kint.2023.10.018；sources/kdigo2024.pdf |
| **AACE/ACE 2016 立場聲明**（Endocr Pract 2016;22:753–762, PMID 27082665）——**已被超越，僅供歷史脈絡** | 擇期手術前至少 24 小時停藥（早於 FDA 2020 標示變更；verbatim 未取得，出自新聞轉述） | — | DOI 10.4158/EP161292.PS；全文付費牆未驗證 |

**實務建議（本專案綜合，非任何單一指引原文）**：在台灣執業情境，dapagliflozin 擇期大手術以
**術前 3 天停藥**為準（TFDA 仿單 + FDA + ADA 一致）；日間小手術可參考澳紐規則（僅停當日）
但須向病人說明各國規則不一致；任何情境下，**術日晨測血酮**是比停藥天數更可靠的安全網。

---

## 2. 擇期手術流程（algorithm）

```
術前門診（排程時）
 ├─ 確認用藥清單含 SGLT2i（含複方：dapagliflozin/metformin=Xigduo XR、
 │   dapagliflozin/saxagliptin=Qtern）
 ├─ 開立停藥指示：大手術／需住院／需腸道準備 → 術前 3 天停
 │   （＝術前第 2、第 1 天與手術當日不服；台灣 TPR：72 小時）
 │   日間小手術（澳紐規則）→ 僅停手術當日
 ├─ 高風險註記：HbA1c >9%（ADS 2023：胰島素不足／DKA 風險標記）、
 │   低 C-peptide／LADA／胰臟炎或胰臟手術史（EMA SmPC 高風險群）、
 │   生酮/極低碳飲食、酗酒、併用 GLP-1 RA 且攝食不佳
 └─ 病人衛教：禁食期間勿自行恢復服藥；出現噁心嘔吐腹痛倦怠 → 提前就醫

手術當日（麻醉前）
 ├─ 測指尖血酮（β-hydroxybutyrate）——即使血糖正常也要測
 ├─ 【ADS/ANZCA May 2023 行動表，verbatim 依據】
 │   ・已停藥≥3天＋臨床良好＋血酮 <1.7 mmol/L → 進行手術
 │   ・未及時停藥：
 │       血酮 <1.0 且 BE >−5 → 可進行（日間手術），每小時監測血酮
 │       血酮 >1.0 且 BE >−5 → 酮症未酸中毒：諮詢內分泌，考慮在
 │         胰島素＋葡萄糖輸注下進行
 │       血酮 >1.0 且 BE <−5 → 推定 DKA（血糖 <14 mmol/L 即推定 euDKA）：
 │         非緊急手術延期；緊急手術在胰島素＋葡萄糖輸注下進行
 │   ・【verbatim】無血液氣體分析可用且血酮 >1.0 mmol/L → 不應進行手術
 └─ 麻醉紀錄與交班註記 SGLT2i 使用史（術後 DKA 監測 2–3 天，ADS-ANZCA 2022）

術後
 ├─ 未及時停藥或急症手術者：術後至少 2–3 天監測血酮（ADS-ANZCA 2022）
 ├─ 不明原因之陰離子間隙代謝性酸中毒（即使血糖正常、即使已有 AKI 或敗血症
 │   可解釋酸中毒）→ 測血酮再歸因（case signals：CASE_REPORT #6, #26, #27）
 └─ 重啟：恢復正常飲食＋臨床穩定（FDA）；英國標準加「血酮 <0.6 mmol/L」；
     澳紐建議考慮再延 24 小時；重啟後住院期間每日測血酮（UKCPA/CPOC 路線）
```

**急診手術（無法完成停藥期）**：不因未停藥而延誤救命手術；以胰島素＋葡萄糖輸注護航、
術中／術後密集血酮監測（ADS/ANZCA 行動表；術中 POC 血酮監測之可行性見個案 Takanami 2025,
PMID 41625909 — case-report signal）。

---

## 3. 生病日規則（Sick-Day Rules）

- **Diabetes Canada 2018 Appendix 8（SADMANS）**【verbatim 已核對】：病人生病無法維持足夠
  水分攝取、或急性腎功能下降（腸胃炎、脫水）時，應暫停：**S**ulfonylureas、**A**CE inhibitors、
  **D**iuretics/direct renin inhibitors、**M**etformin、**A**RBs、**N**SAIDs、**S**GLT2 inhibitors。
  （Can J Diabetes 2018;42(Suppl 1):S316, DOI 10.1016/j.jcjd.2017.10.045；sources/dc_appendix8.pdf）
- **ADA 2026 §16**【verbatim】："SGLT2 inhibitors should be avoided in cases of severe illness, in
  people with ketonemia or ketonuria, and during prolonged fasting and surgical procedures."
- **KDIGO 2024** PP 3.7.2：延長禁食、手術、重症期間暫停（見上表）。
- **EMA SmPC §4.4**：因重大手術或急性重症住院者中斷治療；期間監測**血**酮（優於尿酮）。
- **台灣 TPR No.186**：急性疾病、脫水風險、大量飲酒、極低碳飲食、延長禁食期間暫停。
- **暫停觸發情境（綜合上列來源）**：嘔吐／腹瀉／無法進食進水、發燒性急性感染、敗血症、
  急性心腎事件住院、延長禁食（含宗教性禁食與檢查前禁食）、腸道準備、大量飲酒、
  開始生酮／極低碳飲食（應勸阻——ADA 2026 rec 5.26/9.39 對高風險者「discourage a
  ketogenic eating pattern」；該條經 Guideline Central 轉錄，引用前宜核對原文頁）。
- **病人自我管理**：高風險病人給予血酮試紙／血酮機並教學（ADA 2026 rec 5.26/9.39）；
  症狀（噁心、嘔吐、腹痛、呼吸困難、異常倦怠）不論血糖高低都要驗酮體（EMA SmPC §4.4）。

---

## 4. euDKA 治療要點（供演講之「怎麼治」一頁）

- **JBDS-IP Guideline 02（rev. 2023-03）euglycaemic DKA**【verbatim】："1) Initiate glucose 10%
  straight away at 125 ml/hr because the glucose is <14 mmol/L 2) Begin with 0.1 units/kg/hr insulin
  rate 3) If glucose falling despite 10% glucose reduce to 0.05 units/kg/hr to avoid hypoglycaemia."
  （sources/jbds_dka.pdf）；DKA 發生於 SGLT2i 使用者 → 停藥、通報（英國 Yellow Card；台灣
  ADR 通報 02-2396-0100, adr.fda.gov.tw）、與糖尿病團隊討論是否重啟。
- **ADA 2026 §16 p. S348**【verbatim】："In euglycemic DKA (glucose <200 mg/dL and positive BOHB),
  5% or 10% dextrose needs to be started alongside 0.9% NaCl/crystalloid at the start of the insulin
  treatment."；診斷標準（Table 16.1）：BOHB ≥3.0 mmol/L＋pH <7.3 且/或 HCO₃⁻ <18 mmol/L，
  血糖 ≥200 mg/dL **或**已知糖尿病（容納 euDKA）。
- **勿單用碳酸氫鈉**：無法終止生酮，個案中反覆失敗並延誤診斷（case-report signals：
  CASE_REPORT #5, #6）。
- **無糖尿病者之 SGLT2i 酮酸中毒**：治療核心為**葡萄糖供給**（靜脈＋口服含糖液），
  僅需極少量或不需胰島素（case-report signals：Umapathysivam Diabetes Care 2024, PMID
  37988720；Miyazaki 2024, PMID 38985686；見 CASE_REPORT #8–10）。
- **鑑別**：酒精性酮酸中毒（AKA）——葡萄糖後低血糖、C-peptide 高、HbA1c 正常；治療不是
  胰島素（CASE_REPORT #31）。
- **T1D 輔助用藥情境之預防協定**：STICH（Garg SK et al. Diabetes Technol Ther 2018;20:571–575,
  DOI 10.1089/dia.2018.0246, PMID 30129772）——作者提出之委員會**評論性協定**，非官方指引；
  組成（Stop / Insulin / Carbohydrate ~30 g / Hydration）出自二手轉述，逐字內容未驗證。
  後續國際共識：Danne T et al. Diabetes Care 2019;42:1147–1154（"STOP DKA" protocol）。

---

## 5. 重啟（restart）準則整理

| 情境 | 準則 | 來源 |
|---|---|---|
| 術後／病後一般重啟 | 臨床穩定＋恢復口服攝食 | FDA PI §2.4/§5.1 |
| 加酮體條件（較嚴格，建議採用） | 正常進食進水＋毛細血酮 <0.6 mmol/L；重啟後住院期間每日血酮 | Anaesthesia 2025 共識【verbatim】；UKCPA/CPOC |
| EMA 版本 | 酮體正常＋病況穩定 | EMA SmPC §4.4 |
| 澳紐加註 | 考慮再延 24 小時才重啟 | ADS Alert May 2023【verbatim】 |
| **曾發生 DKA 者** | 【verbatim】"Restarting SGLT2 inhibitor treatment in patients experiencing a DKA while on SGLT2 inhibitor treatment is not recommended, unless another clear precipitating factor is identified and resolved." | EMA SmPC §4.4 |
| 個案警訊 | 術後 euDKA 治癒後出院時即重啟（Bazan 2025, PMID 40546578）——可行性個案層級；相對地，停藥後藥效可延長 5–11 天（#12–14），重啟時機無實證，宜個別化並確認誘因解除 | case-report signals |

---

## 6. 未解問題（供 synthesis / talk 引用）

1. 停藥 3–4 天是否足夠？——停藥 5 天仍發生 euDKA、停藥 11 天仍有糖尿之個案（case-report
   signal）vs FDA 標示「尿糖排泄於停藥後持續 3 天……上市後報告有超過 6 天、最長 2 週」
   （FARXIGA PI §5.1）。無前瞻性研究界定最適停藥期（ADA 2026 §16 自承 "until further
   prospective studies are conducted, as an abundance of caution"）。
2. 英美規則差距（36–52 小時 vs ≥72 小時）未有頭對頭證據。
3. DKA 後重啟之安全性：EMA 原則上不建議（除非誘因明確且已解除）；個案報告有成功重啟者；
   無系統性證據。
4. 非糖尿病 HF/CKD 病人之術前血酮篩檢是否必要——指引未及，個案警訊存在。
5. 住院中（急性心衰）起始之安全性屬試驗證據範疇——見 SAFETY_EVIDENCE_MATRIX.md
   （DICTATE-AHF、DAPA ACT HF-TIMI 68）。
