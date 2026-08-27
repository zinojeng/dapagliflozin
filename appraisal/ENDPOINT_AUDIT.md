# ENDPOINT AUDIT — 端點與方法學稽核

維護者：dapa-methods-auditor（獨立稽核，未參與撰寫任何 evidence/ 檔案）
稽核日：2026-08-27；稽核對象：main @ b7322d4 之全部 12 個 evidence/ 檔案。
獨立驗證方法：本稽核於 2026-08-27 以 Europe PMC REST（摘要層級）與
ClinicalTrials.gov API v2 對重點數字與註冊資料做**第二次獨立**核對（與 landmark
peer 的第一次核對互相獨立）；驗證紀錄見文末附錄 A。
判定標籤：**PASS**（無異議）／**PASS-with-note**（正確但須補限定）／
**FLAG**（須修正或降級措辭）／**PENDING-FT**（結論保留至全文核對）。

---

## 1. 端點定義稽核（endpoint definitions）

| 試驗 | 主要端點 | 端點性質 | 判定 |
|---|---|---|---|
| DECLARE-TIMI 58 | 雙共同主要：(a) MACE；(b) CV death/HHF；另設 MACE 非劣性安全主要 | 硬臨床複合 ×2 | PASS |
| DAPA-HF | worsening HF（住院或需靜脈治療之緊急就診）或 CV death | 硬臨床複合 | PASS |
| DELIVER | worsening HF（非計畫住院或緊急就診）或 CV death | 硬臨床複合 | PASS |
| DAPA-CKD | 持續 ≥50% eGFR 下降、ESKD、renal/CV death | 硬臨床複合（含 surrogate 衍生成分 ≥50% eGFR 下降——已裁定、持續性，慣例視為硬終點） | PASS |
| DapaTAVI | 1 年 all-cause death 或 worsening HF | 硬臨床複合 | PASS |
| DAPA ACT HF-TIMI 68 | 2 個月 CV death 或 worsening HF | 硬臨床複合（超短觀察窗） | PASS-with-note：任何引用都須帶「2 個月」時窗 |
| DAPA-MI | 階層式 win-ratio 複合（death→HHF→MI→AF→新發 T2DM→NYHA→體重−5%） | 混合階層（硬＋代謝／症狀成分） | FLAG：見 §4 |
| DICTATE-AHF | 利尿效率（體重變化/loop 劑量） | surrogate | PASS |
| DARE-ESKD-2 | NT-proBNP 變化 | surrogate | PASS |
| INFINITI | 坐姿收縮壓 | surrogate | PASS |
| Uchiyama ADPKD | eGFR slope（月 1–6） | surrogate | PASS |

worsening HF 的操作型定義在 DAPA-HF（需靜脈治療）與 DELIVER/DapaTAVI/DAPA ACT
（住院或緊急就診）之間不完全同義——跨試驗比較事件率時不得直接並排當同一端點
（比較 HR 可，比較絕對率須註明定義差異）。

## 2. 複合端點驅動成分（composite drivers）

逐一覆核 LANDMARK_TRIAL_MATRIX §7 與 COMPOSITE_ENDPOINT_DECOMPOSITION.md
之分解表，並與本稽核之獨立摘要驗證比對：

| 複合 | 檔案宣稱之驅動 | 稽核判定 |
|---|---|---|
| DECLARE CVD/HHF | HHF（0.73）；CV death 中性（0.98） | PASS（摘要已核） |
| DAPA-HF | 兩成分皆顯著（0.70／0.82） | PASS |
| DELIVER | worsening HF（0.79）；CV death 單獨 NS（0.88） | PASS |
| DAPA-CKD | 腎特異成分（0.56） | PASS |
| DapaTAVI | worsening HF subHR 0.63；死亡 0.87 NS | PASS（摘要已核：91/620 分位 15.0% vs 124 20.1%） |
| DAPA-MI WR | 新發 T2DM＋體重（非硬終點成分） | PASS |
| DAPA ACT | 主要中性；無驅動可言 | PASS |

兩個 evidence 檔之複合分解紀律整體 **PASS**——未發現任何一處把陽性複合寫成
全成分獲益。

## 3. 首次事件 vs 反覆事件（first vs recurrent events）

- 各 landmark 主要端點均為 time-to-first-event（HR）；Jhund 2022 pooled 之
  「total HF admissions RR 0.71」為**反覆事件 rate ratio**——兩者不可互換。
  引用規則：寫「總住院次數減少 29%」須標明為 recurrent-event 分析（pooled、
  prespecified）；不得寫成「住院風險 HR 0.71」。
- DELIVER 主論文另有 total-events 分析（檔案僅寫「total events lower」未給數字）
  ——synthesis 若引用須補確切 rate ratio 與 CI（PENDING-FT）。

## 4. 階層端點與 win ratio 稽核

**DAPA-MI（FLAG——引用紀律最高風險試驗）**
- 主要分析法於試驗中期因事件數不足而**變更**（傳統 time-to-event → win ratio
  ＋加入代謝成分）。此為正式的 prespecified amendment，但任何引用 WR 1.34
  (1.20–1.50) 都必須同句帶出：(a) 驅動者為新發 T2DM 與體重（非硬終點）；
  (b) CV death/HHF HR 0.95 (0.64–1.40) 顯示硬終點無效益；(c) 分析法中途變更。
- Win ratio 不是相對風險：1.34 不可換算成「事件減少 34%」；WR 亦受成分排序與
  比對平局率影響，絕對效益不可自 WR 推得。
- 判定：frontier 檔案處理**正確**；本條為給 synthesis/talk 的強制措辭規則。

**DapaTAVI win-ratio 再分析（post hoc）**
- WR 1.36 (1.03–1.78)；加入 KCCQ 後移向無效（1.10, 0.94–1.30）——顯示其臨床
  事件效益對「端點階層的選擇」敏感。與 prespecified KCCQ 陰性結果（12 個月
  OR 1.03, 0.83–1.27）一致。演講中可用作「win ratio 對成分選擇敏感」的教學例。
- 判定：PASS；引用時標 post hoc。

## 5. 優越性／非劣性／中性結果之分類稽核

| 結果 | 正確歸類 | 判定 |
|---|---|---|
| DECLARE MACE | 安全性非劣性成立（上界 <1.3, p<0.001）；優越性**未**成立（p=0.17） | PASS——兩句必須分開講，不得只講其一 |
| DAPA ACT 主要 | 中性（0.86, 0.68–1.08, P=0.20） | PASS |
| DICTATE-AHF 主要 | 未達顯著（P=0.06）——不是「趨勢證明有效」 | PASS |
| DARE-ESKD-2 主要 | 中性（見 §11 之 CI/P 分歧裁定） | 裁定見 CONTRADICTIONS §1.1 |
| INFINITI 主要 | 中性（SBP 未降） | PASS-with-note：摘要另載 MAP 第 1 週 −3.9 (−7.5 至 −0.2) 名義上顯著——frontier 檔未收；如引用血壓資料須並陳，且標 secondary |

## 6. 次族群 vs 正式交互作用

一致性宣稱（p-interaction 不顯著，允許「未見效果修飾證據」）：
Petrie 糖尿病狀態（0.80）、Wheeler 糖尿病（0.24）與病因（0.53）、Chertow
stage 4 vs 2/3（0.22）、Peikert 年齡（0.95）、Butt 衰弱之臨床事件（0.40）、
Mc Causland eGFR 分層（0.16）、Jackson 利尿劑劑量（0.61）、Erlinge LVEF（0.76）
——各檔案措辭紀律 PASS。

**FLAG 之三處顯著／邊際交互作用（引用時須全句限定）：**
1. **Zelniker MACE × ASCVD，p-int 0.0501**：嚴格而言**未達** 0.05。
   允許：「MACE 效益見於已確立 ASCVD 之次族群（0.86, 0.80–0.93），多重危險
   因子組未見效果（1.00, 0.87–1.16），交互作用檢定為邊際（p=0.0501）」。
   禁止：「已證明 MACE 效益僅限次級預防」（as proven interaction）。
   landmark 檔案兩處引用此結果時未帶 p-int 邊際性質之限定——synthesis 須補。
2. **Butt KCCQ × 衰弱，p-int 0.021**：顯著交互作用但端點為 KCCQ（PRO/
   surrogate），臨床事件之 p-int 為 0.40。允許：「衰弱越重者 KCCQ 改善越大
   （prespecified，p-int 0.021）」；禁止：「衰弱者臨床效益更大」。
3. **Heerspink 慢性 slope × T2D，p-int 0.0049**：surrogate 上的顯著交互作用；
   硬終點之糖尿病交互作用為 0.24（無修飾證據）。兩者不得混引。
   另 Storey（DAPA-MI）NYHA 症狀 p-int 0.009 為 post hoc——僅 hypothesis-generating。

## 7. 多重比較（multiplicity）

1. **DECLARE 階層檢定（PENDING-FT，本稽核最重要之未決方法學項目）**：
   DECLARE 為雙共同主要＋階層式次要檢定設計。MACE 優越性未達顯著後，
   次要端點（腎複合、all-cause death）依 SAP 是否仍具正式（confirmatory）
   顯著性、或僅為名義顯著——**須以 NEJM 全文／SAP 確認檢定順序**。
   在確認前，synthesis 引用 DECLARE 腎複合 0.76 (0.67–0.87) 時一律標
   「prespecified secondary；正式檢定地位待全文確認，暫以名義顯著對待」。
2. **DAPA ACT all-cause death 0.66 (0.43–1.00)**：主要端點未達顯著之試驗中的
   次要端點，且 CI 上界觸 1.00——僅 hypothesis-generating。frontier 檔已正確
   標注；此為不可退讓之紅線。
3. **Jhund pooled MACE 0.90 (0.81–1.00), p=0.045**：邊際；pooled 分析之
   非主要端點。允許引用但須帶 CI 全寬，不得寫成穩健 MACE 效益。
4. 大量 prespecified/post hoc 次分析（Mosenzon、Oyama、Adamson、Jongs 等）
   均未經多重比較校正——引用一律標分析層級（各檔已做到；synthesis 沿用）。

## 8. 絕對 vs 相對效益

各檔案除 DAPA-CKD（NNT 19）外多僅報相對效益。以下 ARR/NNT 由**已驗證**事件率
計算（本稽核計算，供 talk 使用，須標「由試驗事件率推算」）：

| 試驗（追蹤期） | 主要端點 ARR | NNT（追蹤期內） |
|---|---|---|
| DAPA-HF（18.2 月） | 21.2−16.3 = 4.9% | ≈21 |
| DELIVER（2.3 年） | 19.5−16.4 = 3.1% | ≈33 |
| DAPA-CKD（2.4 年） | 14.5−9.2 = 5.3% | 19（95% CI 15–27，論文原載） |
| DECLARE CVD/HHF（4.2 年） | 5.8−4.9 = 0.9% | ≈111 |
| DapaTAVI（1 年） | 20.1−15.0 = 5.1% | ≈20 |

紀律：低風險族群（DECLARE 型 T2D 初級預防）相對效益聽起來大、絕對效益小；
演講須兩者並陳。安全端亦同：DKA HR 2.18 之絕對超額僅 0.2%/4.2 年。

## 9. 追蹤時長之可比性

2 個月（DAPA ACT）、5 天（DICTATE）、12 週（INFINITI）、24 週（DARE-ESKD-2）、
6 個月（Uchiyama）、1 年（DapaTAVI/DAPA-MI）、18.2 月–4.2 年（landmark）。
規則：不同時窗之事件率與 NNT 不可直接並列比較；DAPA ACT 的中性結果只回答
「2 個月內」的問題，不推翻慢性期效益，也不被慢性期證據拯救。

## 10. 競爭風險（competing risks）

- DapaTAVI worsening HF 以 **subhazard ratio**（Fine-Gray，死亡為競爭風險）
  報告——frontier 檔正確保留 subHR 字樣。引用時不得改寫為 HR。判定 PASS。
- 高齡（DapaTAVI 中位 82 歲級）與透析族群死亡競爭風險高：DAPA-CKD 透析起始
  post hoc（n=167）之 all-cause 效益由**非 CV 死亡**驅動（0.27）而 CV 死亡
  中性（1.33, 0.40–4.40）——機轉不明、post-randomization 子集，frontier 已
  標 observational-grade。判定 PASS；此結果**不得**進入任何效益主張。

## 11. Surrogate vs 硬終點

各檔案標注紀律 PASS。彙總不可跨越之線：
- eGFR slope（DELIVER、DAPA-CKD、Uchiyama、NCT06982079）、NT-proBNP
  （DARE-ESKD-2）、TKV、利尿效率、尿鈉、KCCQ、LV mass/strain（Renal Lifecycle
  substudies）均為 surrogate——只允許「支持」語言，不允許「證明臨床效益」。
- DELIVER 腎複合 HR 1.08 (0.79–1.49)：HFpEF 族群**不得**宣稱腎硬終點保護，
  slope 改善不改變此結論（landmark 檔已明載，PASS）。

## 12. 外部效度（applicability）

各試驗排除條件之邊界宣告均正確（DECLARE CrCl≥60；DAPA-HF eGFR≥30/SBP≥95
⚠️FT；DELIVER eGFR≥25；DAPA-CKD 蛋白尿 CKD、排除 ADPKD/免疫腎炎 ⚠️FT）。
補充稽核意見：
- DapaTAVI 為西班牙單一國家、open-label（endpoint 裁定盲）、高 HF 風險選樣
  ——不可外推 all-comer TAVI；frontier 已載，PASS。
- DAPA ACT 排除 cardiogenic shock／重症——「住院起始安全」不含此族群。
- 台灣族群外推：全區塊依 ⚠️TW 規範另行查證，安全檔紀律 PASS。

## 13. 藥物特異 vs 類別證據（indirectness）

引用階梯（landmark INTERPRETATION §4 之三層規則）稽核 PASS。強制執行點：
1. KDIGO eGFR ≥20 起始（1A）之低於 25 區間依據為 **EMPA-KIDNEY 類別證據**，
   非 dapagliflozin RCT——任何 dapagliflozin 演講寫到 eGFR 20–25 起始都須標
   「類別外推＋與美國仿單（≥25）不一致」。
2. 急性 HF 早期起始效益：**類別層級**（embedded meta 0.71；Ahmed TSA meta
   0.61）；dapagliflozin 專屬試驗中性。二者並陳、標籤不可互換。
3. Vaduganathan／SMART-C／Zelniker 均為 class-level；不得將其效應值冠於
   dapagliflozin 單藥。
4. 本稽核獨立檢索確認：**不存在** dapagliflozin 專屬之急性＋慢性
   「full care-spectrum」pooled 分析（截至 2026-08-27）——詳
   CONTRADICTIONS §1.2。

## 14. 證據斷崖（evidence cliffs）

FRONTIER_AND_EVIDENCE_CLIFFS.md 之五級排序經覆核**維持原判**。
本稽核補強兩項註冊資料（原 ONGOING_TRIALS 標記待查證者，今已獨立核實）：
- **NCT05321706 = DAPARHT**（心臟移植受贈者腎保護；Oslo University Hospital；
  n≈430；dapagliflozin 10 mg vs placebo，雙盲；主要端點 eGFR slope 2 週–12 月
  ——**surrogate**；active, not recruiting；primary completion 2028-09-30；
  registry 最後更新 2026-07-01）。ClinicalTrials.gov API 已核。
- **NCT06982079**（Ain Shams University；**dapagliflozin** 10 mg；n≈60 單中心；
  eGFR <20 未透析；主要端點 eGFR slope 1 年＋至 RRT 時間；recruiting；
  估計完成 2026-11）。小型、surrogate 主軸——即使發表亦不足以填補
  「eGFR <20 起始」斷崖；Renal Lifecycle 仍為唯一事件驅動之出口。

---

## 附錄 A — 本稽核之獨立驗證紀錄（2026-08-27）

| 項目 | 方法 | 結果 |
|---|---|---|
| DARE-ESKD-2（PMID 41970273） | Europe PMC 摘要 | 標題／期刊／DOI／−155 (−327 至 −33), P=0.065／KCCQ +7 (P=0.073／0.094)／6MWT −0.9 m／n=80 全部相符 |
| INFINITI（PMID 41385300） | Europe PMC 摘要 | CJASN，2026（線上 2025-12）；52 納入 51 完成；SBP 未降；mGFR −4.2／−3.49 相符；另載 MAP −3.9 (−7.5 至 −0.2)（frontier 未收，見 §5）；無 UTI/GU 感染 |
| DAPA ACT（PMID 40884036） | Europe PMC 摘要 | N=2401（1218/1183）；10.9 vs 12.7%，0.86 (0.68–1.08) P=0.20；成分 0.91/0.78/0.66 (0.43–1.00)；低血壓 3.6 vs 2.2%；WKF 5.9 vs 4.7%；meta 0.71 (0.54–0.93)／0.57 (0.41–0.80) 全相符 |
| DapaTAVI（PMID 40162639） | Europe PMC 摘要 | 620/637 隨機、1222 主分析；91 (15.0%) vs 124 (20.1%)，0.72 (0.55–0.95) P=0.02；death 47 (7.8%) vs 55 (8.9%)，0.87 (0.59–1.28)；worsening HF subHR 0.63 (0.45–0.88) 相符；惟分母標記見 CONTRADICTIONS §2.3 |
| Ahmed TSA meta（PMID 42067122） | Europe PMC 摘要 | J Card Fail 2026；8 RCTs n=4096；RR 0.61 (0.47–0.81)／0.67 (0.48–0.94)／0.68 (0.47–0.99)／0.87 (0.70–1.09)；TSA 敘述相符 |
| DECLARE（PMID 30415602） | PubMed efetch 摘要 | DKA 0.3 vs 0.1% P=0.02；genital 0.9 vs 0.1% P<0.001；renal 4.3 vs 5.6%，0.76 (0.67–0.87)；death 0.93 (0.82–1.04) 相符；**摘要不含 AKI／骨折／截肢數字** |
| PMC6683461（DECLARE 安全表轉載源） | Europe PMC fullTextXML | 轉載忠實性核對，詳 CONTRADICTIONS §2.1 |
| NCT05321706／NCT06982079 | ClinicalTrials.gov API v2 | 如 §14 |
| care-spectrum meta 檢索 | Europe PMC 2025-01-01–2026-08-27 | 25 筆候選逐一排除，詳 CONTRADICTIONS §1.2 |
