# CONTRADICTIONS AND OVERCLAIMS — 矛盾裁定與過度宣稱登錄

維護者：dapa-methods-auditor；稽核日 2026-08-27；對象 main @ b7322d4。
本檔為裁定文件：每項爭議給出【已驗證證據】【裁定】【允許/禁止措辭】。
措辭細則另見 CLAIMS_LEDGER.md（L-xx 交叉編號）。

---

## 1. Director 指定優先事項之裁定

### 1.1 DARE-ESKD-2 之 CI/P 分歧（frontier 檔標記）

【已驗證證據】本稽核 2026-08-27 自 Europe PMC 摘要逐字核對（PMID 41970273）：
"The intergroup difference in NT-proBNP change was not statistically significant
after adjustment by baseline values (median [95% CI] difference: −155 [−327 to
−33] pg/ml; P = 0.065)."——分歧**存在於論文摘要本身**，非 frontier 轉錄錯誤。
注意原文為 **median** difference：區間估計（可能為分位數迴歸或 bootstrap）與
校正後檢定 P 值來自不同統計程序，CI 排除 0 與 P=0.065 可並存。
【裁定】採作者結論：**中性試驗**。frontier 檔之處理（引 P 值結論）正確。
【允許】「調整基線後組間差異未達統計顯著（P=0.065）；報告之中位數差異區間
為 −155（−327 至 −33）pg/ml——區間與 P 值方法學上不同源，以作者檢定結論為準」。
【禁止】「NT-proBNP 顯著下降（CI 不含 0）」；亦禁止只引 CI 不引 P。
【限定】全文方法章節可進一步釐清兩者統計程序（P-FT，非攔截性）。

### 1.2 「2026 care-spectrum 統合分析」身分（frontier 檔懸案）

【已驗證證據】本稽核獨立於 frontier peer 重跑檢索（Europe PMC，
2025-01-01–2026-08-27，dapagliflozin×(DAPA-HF/DELIVER)×(acute/hospitalized/
DAPA ACT)×(pooled/patient-level)，25 筆候選逐一檢視）：**未發現任何
dapagliflozin 專屬之急性＋慢性（care-spectrum）pooled 分析**。既有實體僅：
(a) DAPA ACT HF-TIMI 68 論文內嵌之住院 HF 類別 meta（HR 0.71/0.57）；
(b) Ahmed 2026 J Card Fail TSA meta（PMID 42067122，類別，8 RCT n=4096，
本稽核已核其全部效應值）。
【裁定】懸案**結案**：Director 簡報所稱之「2026 care-spectrum meta-analysis」
應視為不存在之引用；synthesis 僅得引用上述 (a)(b) 並標**類別層級**。
若 Director 另有具體文獻，須提供 PMID 重審。

### 1.3 INFINITI 引用錨定

【已驗證證據】PMID 41385300 = Sridhar et al., CJASN，期刊年 **2026**
（線上 2025-12-12）；52 納入/51 完成；SBP 主要端點中性；mGFR dip −4.2/−3.49
——與 frontier 檔一致。Europe PMC 載 DOI 10.2215/cjn.0000000951，格式異常
（CJASN 新式 DOI 尾碼位數存疑）。
【裁定】引用以 **PMID 41385300 為錨**；DOI 於全文落地時再確認；引用年份
統一為 2026（線上先行 2025-12-12）。另：摘要載 MAP 第 1 週 −3.9
（−7.5 至 −0.2）名義下降，frontier 檔未收——引用血壓資料時須並陳並標 secondary
（見 ENDPOINT_AUDIT §5）。

### 1.4 ONGOING_TRIALS 第 5–6 項註冊再查證（原標記待查）

【已驗證證據】ClinicalTrials.gov API v2（2026-08-27）：
- **NCT05321706 = DAPARHT**：心臟移植受贈者、dapagliflozin 10 mg vs placebo
  雙盲、Oslo University Hospital、n≈430、主要端點 eGFR slope（2 週–12 月，
  **surrogate**）、active not recruiting、primary completion 2028-09-30。
- **NCT06982079**：**dapagliflozin** 10 mg、Ain Shams University、n≈60 單中心、
  eGFR <20 未透析、主要端點 eGFR slope＋至 RRT 時間、recruiting、估計完成
  2026-11。
【裁定】查證義務**已結**；ONGOING_TRIALS 可據此更新（frontier peer 所有）。
兩者均 surrogate 主軸——即使發表也不改變「advanced CKD 斷崖以 Renal
Lifecycle 為唯一事件驅動出口」之判斷。

### 1.5 DECLARE 安全表 HR 來源（safety 檔最優先複核請求）

【已驗證證據】本稽核取得 PMC6683461 全文 XML，逐格核對 safety 檔轉載值：
DKA 2.18 (1.10–4.30)、genital 8.36 (4.19–16.68)、UTI 0.93 (0.73–1.18)、
major hypo 0.68 (0.49–0.95)、amputation 1.09 (0.84–1.40)、fracture 1.04
(0.91–1.18)、SAE 0.91 (0.87–0.96)、discontinuation 1.15 (1.03–1.28)、
AKI 0.69 (0.55–0.87)——**轉載全部忠實**（safety 檔無抄錄錯誤）。
另自 NEJM 摘要（PubMed efetch）二次確認：DKA 0.3 vs 0.1% (P=0.02)、
genital 0.9 vs 0.1% (P<0.001)；**摘要不含 AKI/骨折/截肢/低血糖數字**。
【裁定】問題性質從「轉錄正確性」收斂為「來源層級」：HR/CI 仍係二手轉載，
NEJM Table 3 核對維持 P-FT（待 原始PDF/）。其中 **AKI 列有內部矛盾**：
PMC6683461 印 125 (1.5%) vs 113 (1.3%)——placebo 件數低於 dapagliflozin
卻配 HR 0.69 favoring dapagliflozin，顯係該回顧排版錯誤（safety 檔原疑慮
證實）。
【允許】引用 HR 值時標「取自開放取用轉載（PMC6683461），NEJM 原表待核」。
【禁止】引用 PMC6683461 之 AKI 件數/百分比；在未核全文前把任何轉載 HR
當 verbatim NEJM 數字。

## 2. 本稽核新發現之跨檔數字問題

### 2.1 【FLAG-必修】SAFETY_EVIDENCE_MATRIX 基本盤表：DAPA-HF「45% 無糖尿病」

safety 檔試驗基本盤表寫「DAPA-HF……**45% 無糖尿病**」；landmark 檔（Petrie
2020，PMID 32219386，摘要已核）為 **2,605（55%）無糖尿病**（即 45% *有*
糖尿病）。安全檔將比例反置。
【裁定】safety 檔須改為「55% 無糖尿病」或「45% 有 T2D」。字段屬 safety peer
所有——由 Director 轉交修正，本稽核不代改。
（同表 DAPA-CKD「32.5% 無 T2D」與 landmark 67.5% T2D 相符，PASS。）

### 2.2 【FLAG-待議】RECENT_TRIAL_MATRIX：DapaTAVI 死亡成分分母

frontier 檔寫「All-cause death: 7.8% vs 8.9%, **(47/620)**/(55/637)」。摘要
（已核）給 47 (7.8%) vs 55 (8.9%)，但 47/620=7.6%、55/637=8.6%——摘要百分比
之分母應為主分析人口（1,222，約 604/618），非隨機分派人數。
【裁定】數字本身正確；**分母標注錯誤**。引用時寫「47 (7.8%) vs 55 (8.9%)」
不附「/620、/637」。frontier peer 修正（低優先）。

### 2.3 【維持既有 FLAG】Renal Lifecycle 樣本數 ≈1500 vs ≈1750

兩數字並存於 frontier 檔（主設計論文 vs 影像子研究論文）——peer 已如實並陳。
【裁定】維持並陳；synthesis 寫「約 1,500–1,750（不同方案文件）」。

### 2.4 微項（毋須修檔，synthesis 留意）

- PMC6683461 genital infection 印 p=0.001；NEJM 摘要為 p<0.001——引 NEJM 摘要值。
- DELIVER DKA「裁定 2 vs 0 vs registry 3 vs 3」：兩套裁定口徑不同，safety 檔
  已正確標注（PASS）；引用時擇一口徑並標明。
- INFINITI 引用年份 2025/2026 混用（frontier 檔 vs Europe PMC）——統一 2026。
- Prasad 個案（PMID 41625235）出版年 2025/首發 2026-01-16——safety 檔已標，
  synthesis 引用時統一。

## 3. 跨權威矛盾之裁定（講課措辭）

### 3.1 起始 eGFR 下限：FDA ≥25 vs EMA <15 禁（<25 有限經驗）vs KDIGO ≥20

【裁定】非證據矛盾，是**證據外推幅度**差異：dapagliflozin RCT 下限 25
（DAPA-CKD/DELIVER）；KDIGO ≥20 靠 EMPA-KIDNEY 類別證據；EMA 用「有限經驗」
語言。講課以「一張表、三轄區、各標依據」呈現（L-12）。eGFR 22 病例：
KDIGO 可起始、美國仿單外、EU 有限經驗、台灣 NHI 給付外（起始窗 25–60）。
【禁止】「指引與仿單衝突所以擇一即可」——須顯式標注採用之權威與轄區。

### 3.2 續用至透析：KDIGO practice point vs 仿單沉默

【裁定】KDIGO「eGFR <20 續用至透析/移植」為 practice point（非分級建議），
仿單僅載「試驗中未要求停藥」。允許：「續用有指引 practice-point 支持與試驗
內操作先例；並非仿單指示」。台灣情境加註：NHI **eGFR <15 停付**——臨床續用
與給付規則將分流（⚠️TW）。

### 3.3 HFpEF 推薦級：ESC 2023 Class I vs AHA/ACC/HFSA 2022 2a

【裁定】年代差（AHA 定稿早於 DELIVER 發表）非證據衝突。講課標注各指引
出版年；引 ESC verbatim 前須完成 ⚠️FT 核對（目前僅二手摘要層級）。

### 3.4 圍術期停藥時程：美/台 ≥3 天 vs 英 前一日＋當日 vs 澳紐 共 3 天

【裁定】無頭對頭證據之共識分歧；safety 檔之調和（台灣實務以 3 天為準＋
術日血酮）為合理之作者綜合，**必須**標「本專案綜合建議，非任一指引原文」
（safety 檔已標，PASS）。禁止把任何時程講成「實證最適值」；個案顯示停藥
5–11 天仍可發病（case-signal；L-25）。

### 3.5 KDIGO 2B（eGFR 20–45＋ACR<200）vs DAPA-CKD 納入條件

【裁定】此建議之族群**不在** DAPA-CKD 內；引用時依據寫 EMPA-KIDNEY／pooled
類別證據＋2B 弱建議。禁止以 DAPA-CKD 佐證非蛋白尿 CKD（L-30）。

## 4. 過度宣稱紅線清單（synthesis/talk 逐條對照）

| # | 過度宣稱（禁止形式） | 裁定依據 | Ledger |
|---|---|---|---|
| O-1 | 「dapagliflozin 預防 MI/中風」 | MACE 陰性 | L-01 |
| O-2 | 「DECLARE 顯示降低 CV 死亡」 | CV death 0.98 | L-02 |
| O-3 | 「DELIVER 證明 HFpEF 延長壽命」 | CV death NS；死亡主張限 pooled | L-06/07 |
| O-4 | 「已證明 MACE 效益僅限次級預防」 | p-int 0.0501 邊際＋類別間接 | L-04 |
| O-5 | 「eGFR<30 已證實有效」 | 次族群 CI 跨 null | L-11 |
| O-6 | 「dapagliflozin 實證支持 eGFR 20（–25）起始」 | 類別外推 | L-12 |
| O-7 | 「住院起始證明降低死亡」 | 主要中性；死亡為 secondary、CI 觸 1.00 | L-15 |
| O-8 | 「類別統合＝dapagliflozin 證據」（任何場合） | 間接性 | L-14/16 |
| O-9 | 「DAPA-MI 顯示 MI 後心血管保護」 | 硬終點 0.95；WR 由代謝成分驅動 | L-19 |
| O-10 | 「TAVI 後降低死亡／改善生活品質」 | 成分 NS；KCCQ 陰性 | L-18 |
| O-11 | 「透析／移植／ADPKD 有效」 | 無結局證據（各為 surrogate/機轉/n=27） | L-20–22 |
| O-12 | 「透析起始子集 aHR 0.47＝續用可救命」 | post hoc、非 CV 死亡驅動 | L-20 |
| O-13 | 「HFpEF 有腎保護」 | DELIVER 腎複合 1.08 | L-06 |
| O-14 | 「停藥 3 天即安全」／引用 0.17%/1.1% 圍術期發生率 | 無比較證據；一手未核 | L-25 |
| O-15 | 「非糖尿病者不會 DKA」 | RCT 零事件≠零風險；個案已見 | L-24 |
| O-16 | 以 FAERS 計 Fournier「發生率」 | 無分母 | L-26 |
| O-17 | 「衰弱者臨床效益更大」 | 事件 p-int 0.40；KCCQ 交互限 PRO | L-09 |
| O-18 | 用個案報告支持任何效益或發生率 | case=訊號 | 全域 |
| O-19 | 「slope／NT-proBNP／TKV 改善＝臨床效益」 | surrogate 紅線 | 全域 |
| O-20 | 未標年代並列 ESC I 與 AHA 2a 製造「指引矛盾」敘事 | 年代差 | L-30 |

## 5. 未決事項總登錄（銷帳條件）

| # | 事項 | 狀態 | 銷帳條件 |
|---|---|---|---|
| P-1 | DECLARE NEJM Table 3 全部安全 HR（含 AKI 正確件數、骨折、Fournier、volume depletion） | P-FT | 原始PDF/ NEJM 全文核對（本稽核員執行） |
| P-2 | DECLARE 階層檢定順序（腎複合/死亡之 confirmatory 地位） | P-FT | NEJM 全文＋SAP/appendix |
| P-3 | landmark ⚠️FT 五項設計事實（DECLARE HF 盛行率/安全表；DAPA-HF 排除條件；DAPA-CKD 背景治療與排除；KDIGO 2B verbatim；ESC 2023 verbatim） | P-FT | 對應全文/指引 PDF |
| P-4 | DELIVER 全試驗安全表印刷值（現為分層加總）＋ total-events rate ratio | P-FT | DELIVER 全文＋附錄 |
| P-5 | DAPA-MI 全試驗安全表與確切中位追蹤 | P-FT | 全文 |
| P-6 | safety 未核實清單 #7–#10（Jongs presp 屬性、Jabbour 數值、ADA rec 5.26/9.39 原文、TSOC/DAROC 原文等） | P-FT | 各原文 |
| P-7 | INFINITI 正式 DOI | P-FT | 全文/CrossRef |
| P-8 | SAFETY 基本盤表 DAPA-HF 糖尿病比例修正（§2.1） | FLAG-必修 | safety peer 修檔後本稽核複驗 |
| P-9 | DapaTAVI 死亡分母標注（§2.2） | FLAG-低 | frontier peer 修檔 |
| P-10 | ⚠️TW 全區塊引用時點再查證 | 常設 | talk 定稿前 |

截至本稽核提交時，原始PDF/ 尚未落地 main（git fetch @ 稽核當日）；P-1–P-7
待 Director 通知全文到位後啟動第二輪銷帳。
