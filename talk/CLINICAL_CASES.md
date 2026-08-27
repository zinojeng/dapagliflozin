# 聽眾投票病例（4 例）— Dapagliflozin 心腎證據 40 分鐘演講

> 維護：dapa-research-director（case-writing subagent）。資料日期 2026-08-27。
> 上游：`synthesis/MASTER_SYNTHESIS.md`、`synthesis/CLAIMS_LEDGER.md`、`synthesis/CONTROVERSIES.md`、
> `synthesis/EVIDENCE_GAPS.md`、`evidence/safety/PERIOPERATIVE_SICK_DAY_ALGORITHM.md`、
> `evidence/safety/CASE_REPORT_FAILURE_MODES.md`、`evidence/safety/IMPLEMENTATION_CHECKLIST.md`。
> **本檔所有數值與措辭以 CLAIMS_LEDGER 的 ✅/❌ 規則為準；未在上游檔案出現的數字一律未寫入。**
>
> 使用方式：每例 ≤2 分鐘（病例 20 秒 → 投票 30 秒 → 講解 60 秒 → take-home 10 秒）。
> 建議插入位置：CASE-1 於「T2D 雙軌」段、CASE-2 於「何時起始／DAPA ACT 爭議」段、
> CASE-3 於「eGFR 邊界與 evidence cliff」段、CASE-4 於「安全性收尾」段。

**證據層級標記（投影片右下角固定圖例）**

| 標記 | 意義 |
|---|---|
| `[RCT 主要終點]` | 隨機試驗預先指定之主要終點 |
| `[RCT 次級終點]` | 隨機試驗次級終點 |
| `[預先設定次族群]` | prespecified subgroup（非交互作用證明） |
| `[事後分析]` | post hoc / 探索性 |
| `[病人層級合併分析]` | prespecified patient-level pooled |
| `[類別層級統合]` | SGLT2i 類別，**不得冠名 dapagliflozin** |
| `[指引／仿單]` | 指引建議等級或法規文件 |
| `[個案報告訊號]` | case-report signal——**教學警訊，不得作為發生率或療效證據** |

---

## CASE-1 ── 「HbA1c 已達標，還要不要加藥？」

### 病例敘述

58 歲男性，第二型糖尿病 12 年。目前 metformin 1000 mg BID 單方，**HbA1c 6.7%（已達個人化目標）**。
最近兩次相隔三個月的 **UACR 分別為 470 與 450 mg/g**，**eGFR 55 mL/min/1.73 m²**（近一年穩定）。
血壓 132/78，已使用最大耐受劑量 ARB 並穩定超過 4 週。
**無心肌梗塞／中風／周邊動脈疾病病史，無心衰竭病史，LVEF 正常。** 無低血糖事件。

### 投票（單選最佳）

- **A.** HbA1c 已達標，不需再加藥；3 個月後追蹤 UACR 與 eGFR
- **B.** 加上 dapagliflozin 10 mg QD，適應症是**腎臟／心衰竭保護**，不是降血糖
- **C.** 把 ARB 加到超過核准最大劑量、或再加一個 ACEI，先把蛋白尿壓下來
- **D.** eGFR 已 55、降糖效益開始減弱，改用其他降糖藥觀察

### 正確傾向：B

<!-- src: synthesis/CLAIMS_LEDGER.md §C1,C2,C3,A1,A2,A3,F1 ; MASTER_SYNTHESIS.md §2.4 ; 原始PDF/ADA_SOC_2026_S11.md ; 原始PDF/KDIGO_2024_CKD_Guideline_ExecSummary.md ; evidence/safety/IMPLEMENTATION_CHECKLIST.md §A1,A6 -->

**1. 這位病人幾乎是 DAPA-CKD 的納入條件本身。**
DAPA-CKD 納入 4,304 人，**eGFR 25–75、UACR 200–5000**，67.5% 為 T2D。
主要複合終點 **9.2% vs 14.5%，HR 0.61（95% CI 0.51–0.72），NNT 19（15–27）**，中位追蹤 2.4 年（試驗提前中止）
`[RCT 主要終點]`（Heerspink NEJM 2020, PMID 32970396）。
全因死亡 **4.7% vs 6.8%，HR 0.69（0.53–0.88），p=0.004** `[RCT 次級終點]`。
本例 UACR 450、eGFR 55 → **落在試驗族群內，不需外推**。

**2. 器官保護與降血糖脫鉤。**
DAPA-CKD 預先設定分層：T2D 層 HR 0.64（0.52–0.79）、非 T2D 層 HR 0.50（0.35–0.72），
**p-interaction 0.24** `[預先設定次族群]`（Wheeler, PMID 33338413）。
可講「未見糖尿病狀態修飾療效」；**不可講**「非糖尿病者獲益更大」——點估計差異不是交互作用證據。
ADA 2026 §11 原文亦明言 SGLT2i 的腎臟作用機轉
【verbatim】"independent of glycemia"。

**3. 指引已把門檻寫成 UACR／eGFR，不是 HbA1c。**
ADA 2026 Recommendation **11.7a（Grade A）**【verbatim】："For people with type 2 diabetes and CKD,
use of a sodium–glucose cotransporter 2 (SGLT2) inhibitor with demonstrated benefit to reduce CKD
progression and cardiovascular events is recommended. SGLT2 inhibitors should be initiated in
individuals with eGFR ≥20 mL/min/1.73 m² but can safely continue until kidney failure." `[指引／仿單]`
KDIGO 2024 **Recommendation 3.7.2（1A）**【verbatim】適用於 "eGFR ≥20 ml/min per 1.73 m² with urine
ACR ≥200 mg/g (≥20 mg/mmol), or heart failure, irrespective of level of albuminuria." `[指引／仿單]`

**4. 但要對聽眾誠實說明「這位病人買到的是哪一軌」——DECLARE 的雙軌教學。**
DECLARE-TIMI 58（17,160 人 T2D，40.6% 有 ASCVD、59.4% 僅多重危險因子，CrCl ≥60，中位追蹤 4.2 年）：

| 終點 | 結果 | 層級 |
|---|---|---|
| MACE（CV death/MI/缺血性中風） | 8.8% vs 9.4%，**HR 0.93（0.84–1.03），p=0.17——未達顯著**（非劣性達成） | `[RCT 主要終點]` |
| CV death 或心衰住院 | 4.9% vs 5.8%，HR 0.83（0.73–0.95），p=0.005 | `[RCT 主要終點]` |
| 　└ 心衰住院 | HR 0.73（0.61–0.88）**← 驅動者** | 分項 |
| 　└ CV death | HR 0.98（0.82–1.17）**中性** | 分項 |
| 腎臟複合（≥40% eGFR 下降至 <60／ESRD／renal or CV death） | 4.3% vs 5.6%，HR 0.76（0.67–0.87）；renal-specific HR 0.53（0.43–0.66） | `[RCT 次級終點]` |

（Wiviott NEJM 2019, PMID 30415602；Mosenzon Lancet D&E 2019, PMID 31196815）
本例**無 ASCVD**：類別層級統合顯示 MACE 效益侷限於已有 ASCVD 者——ASCVD 層 HR 0.86（0.80–0.93）
vs 無 ASCVD 層 HR 1.00（0.87–1.16），p-interaction 0.0501 `[類別層級統合]`（Zelniker 2019）。
→ **對這位病人的正確說法是「保腎、少住院」，不是「預防心肌梗塞或中風」。**

**5. 實作三件事**（`IMPLEMENTATION_CHECKLIST.md` A1–A6、B）
① 器官保護適應症一律 10 mg QD（不需從 5 mg 起始）；
② 未併用胰島素或磺醯脲類 → 不需預防性減量，低血糖風險低；
③ 起始時同步衛教生病日規則（SADMANS）與預期性 eGFR 下降。
⚠️TW：台灣健保 §2.16（114/3/1 版）CKD 給付需**同時**滿足「初期 CKD 照護整合方案或 Pre-ESRD 計畫收案 ＋
最大耐受 ACEI/ARB 穩定 ≥4 週 ＋ 起始 eGFR 25–60 ＋ uACR 200–5000」——本例數值符合，
但**須確認收案身分**；給付規定隨時修訂，引用時點須再查證。

### 常見錯誤選項為何錯

- **A（觀察就好）**：把「血糖達標」當成「治療完成」。這位病人的風險寫在 UACR 450 上，而不是 HbA1c 6.7% 上。
  DAPA-CKD 的 NNT 19 是在 2.4 年內達成的——延後 3 個月不是無成本的決定。
- **C（強化 RAS 阻斷）**：ADA 2026 §11 引用之兩個試驗顯示 **ACEI 與 ARB 併用對 CVD 或 CKD 均無益處，
  且高血鉀／AKI 不良事件較多** `[指引／仿單]`。RAS 阻斷已最大耐受時，下一步是加**不同機轉**的藥。
- **D（因 eGFR 55 而放棄）**：混淆兩個門檻。**降血糖效果**在 eGFR <45 明顯減弱
  （FDA 仿單用語 "likely to be ineffective"；EMA 建議 GFR <45 需考慮加其他降糖藥）；
  但**器官保護**在試驗下限 eGFR 25 仍成立，KDIGO 的類別證據甚至下探到 20。
  教學句：**Glycemic efficacy declines before cardiorenal efficacy disappears.**

### Take-home

> **決定要不要開 dapagliflozin 的數字是 UACR 和 eGFR，不是 HbA1c。**

---

## CASE-2 ── 「急性心衰住院第 3 天，今天就開嗎？」

### 病例敘述

74 歲男性，缺血性心肌病變 HFrEF，**LVEF 30%**，因急性肺水腫入院，現為**住院第 3 天**。
利尿後體重下降 3 kg，**IV furosemide 40 mg q12h 已 24 小時未再調升**，未使用 IV 血管擴張劑或強心劑，
但下肢仍有水腫、頸靜脈壓稍高。
**BP 98/62**、HR 78 規則、RR 18、SpO₂ 96%（室內空氣）。
**eGFR 28**（入院時 34），K 4.4，NT-proBNP 5,200 pg/mL。
目前用藥：sacubitril/valsartan 低劑量、bisoprolol 2.5 mg、spironolactone 25 mg。

### 投票（單選最佳）

- **A.** 今天就開始 dapagliflozin 10 mg，同時下修 loop diuretic 並排定腎功能與血壓追蹤
- **B.** 等 IV 利尿劑停掉、改口服後，出院當天再開
- **C.** 出院後心臟科門診 4 週回診時再評估
- **D.** eGFR 28 加上 BP 98/62，這個病人不適合 SGLT2i

### 正確傾向：A（**附帶條件**，見下）

<!-- src: synthesis/CLAIMS_LEDGER.md §B1,D1,D2 ; synthesis/CONTROVERSIES.md §C1 ; evidence/frontier/RECENT_TRIAL_MATRIX.md §2,§5 ; 原始PDF/europepmc_PMID_40884036.pdf ; evidence/safety/IMPLEMENTATION_CHECKLIST.md §A1,A2,C -->

**這一題必須把兩句話分開講（CONTROVERSIES C1 裁定措辭）：**
> **「住院內起始『安全、可行』有專屬 RCT 支持；『早期硬結局效益』目前是類別層級統合的主張。」**

**1. 專屬 RCT：DAPA ACT HF-TIMI 68 主要終點未達。**
2,401 名急性心衰住院病人（任何 LVEF；71.5% LVEF ≤40%；44.7% 為 de novo HF），
雙盲、住院中隨機、盲性治療 2 個月。
主要終點（CV death 或心衰惡化，2 個月內）：**10.9% vs 12.7%，HR 0.86（95% CI 0.68–1.08），P=0.20——未達統計顯著**
`[RCT 主要終點]`（Berg Circulation 2025, PMID 40884036）。
全因死亡 3.0% vs 4.5%，**HR 0.66（0.43–1.00）** `[RCT 次級終點]`——**邊緣、僅可作為假說生成，不得宣稱效益**。
❌ 禁用措辭：「DAPA ACT 證明住院起始降低早期死亡」。

**2. 那為什麼還是今天開？因為試驗建立的是「可行性與安全性」。**
DAPA ACT 的**穩定條件**【verbatim】："no intensification in the dose of intravenous diuretics during the
12 hours prior to randomization and no use of intravenous vasodilators or inotropes during the 24 hours
prior to randomization."
→ **注意：條件是「劑量未再調升」，不是「已停用 IV 利尿劑」。** 本例完全符合。
隨機時間：入院至隨機**中位 3.6 天（IQR 2.1–5.4 天）**；隨機至出院中位 2 天。本例第 3 天正是試驗的操作時點。
安全性：症狀性低血壓 3.6% vs 2.2%；腎功能惡化 5.9% vs 4.7%；**無任何 DKA 個案**。
DICTATE-AHF 更進一步：在**協定化 IV 利尿劑滴定**下於就診 24 小時內給藥，主要終點（利尿效率）
**OR 0.65（0.41–1.02），P=0.06 未達顯著** `[RCT 主要終點]`，但次級 decongestion surrogates 正向
（累積 loop diuretic 劑量 560 vs 800 mg, P=0.006；24 小時排鈉與尿量較高）`[RCT 次級終點][surrogate]`，
且未見糖尿病、腎臟或心血管安全事件增加（Cox JACC 2024, PMID 38569758）。
❌ 不可把 DICTATE-AHF 當作臨床結局證據。

**3. 早期效益的主張只能標「類別層級」。**
DAPA ACT 論文內嵌之預先設定統合（住院起始之 SGLT2i，n≈3,527）：CV death/心衰惡化
**HR 0.71（0.54–0.93）**；全因死亡 HR 0.57（0.41–0.80）`[類別層級統合]`。
J Card Fail 2026 TSA 統合（8 RCT，n=4,096，含 dapagliflozin／empagliflozin／sotagliflozin，
加權中位追蹤 60 天）：全因死亡 **RR 0.61（0.47–0.81）**，TSA 判定為 firm；心衰惡化 RR 0.67（0.48–0.94）；
**心衰再住院 RR 0.87（0.70–1.09）未達顯著** `[類別層級統合]`（PMID 42067122）。
❌ 這些數字**不得冠名 dapagliflozin**。

**4. 長期效益才是真正的處方理由。**
DAPA-HF（4,744 名門診慢性 HFrEF）：主要複合 16.3% vs 21.2%，**HR 0.74（0.65–0.85）**；
心衰惡化 HR 0.70（0.59–0.83）；**CV death HR 0.82（0.69–0.98）**；全因死亡 HR 0.83（0.71–0.97）
`[RCT 主要終點＋次級]`（McMurray NEJM 2019, PMID 31535829）。
這是四大 landmark 中**唯一單一試驗即同時證明「少惡化」與「少死亡」**者。
住院起始的真正論證是**避免治療惰性**：出院時沒開，門診常常就永遠沒開。

**5. 但這位病人在族群邊緣——要講出來。**
DAPA ACT 隨機時**中位 SBP 119 mmHg（IQR 108–133）、中位 eGFR 63（IQR 48–82）**；
DAPA-HF 則**排除 SBP <95 與 eGFR <30** ⚠️（納入排除細節待全文核）。
本例 SBP 98、eGFR 28 → **在仿單允許範圍內（FDA/EMA/TFDA：eGFR <25 不建議起始；28 可起始），
但比試驗族群更脆弱**。TSOC 2023 心衰共識之實務門檻為 SBP ≥95、eGFR ≥20（該條經 AI 摘要取得，
逐字引用前宜核對原文）。
→ 所以正確答案不是「無條件今天開」，而是 **今天開 ＋ 三個配套**：
① 起始同時下修 loop diuretic 或暫停其他降壓藥（本例已 euvolemic 傾向、SBP 98）——
  ESC 2021 §5.3.5【verbatim 依據】述及 SGLT2i 之利尿／利鈉特性「可能允許減少 loop diuretic 需求」
  （**機轉推論性敘述**；DAPA-HF 中多數病人利尿劑劑量未變，兩組平均劑量無差異，Jackson Circulation 2020,
  PMID 32673497 `[次要分析]`）；
② 48–72 小時內複驗腎功能與電解質，量姿位性血壓；
③ **出院醫囑寫死劑量與回診日**，避免「住院開了、門診停了」。

### 常見錯誤選項為何錯

- **B（等停 IV 利尿劑）**：沒有任何證據要求先停 IV 利尿劑。DAPA ACT 的門檻是「12 小時內未調升劑量」，
  DICTATE-AHF 甚至是在 IV 利尿劑滴定協定中**同時**給藥。把時點推到出院當天，實務上就是常常忘記開。
- **C（門診再說）**：治療惰性的標準路徑。而且沒有證據顯示延後起始比較安全——DAPA ACT 的安全數據
  正是在住院中收集的。
- **D（永不使用）**：兩個誤讀。其一，把仿單的**起始**門檻（eGFR <25 不建議起始）套到 eGFR 28 的病人身上；
  其二，把 DAPA ACT 的陰性主要終點讀成「所以不該住院起始」——CLAIMS_LEDGER D1 明列
  ❌ 禁用措辭：**「陰性故應放棄住院起始」**。陰性的是「2 個月硬結局優勢」，不是「安全性」，
  更不是「HFrEF 的長期適應症」。

### Take-home

> **住院內起始的證據是「安全、可行」；「早期救命」還只是類別層級的統合主張——這兩句話要分開講。**

---

## CASE-3 ── 「起始兩週 eGFR 掉到 24，停不停？」

### 病例敘述

68 歲女性，糖尿病腎病變，UACR 800 mg/g。
過去半年 **eGFR 由 32 緩慢下滑至 27**（本來就在下降）。在 eGFR 27 時起始 **dapagliflozin 10 mg QD**。
**兩週後回診：eGFR 24**，K 4.6，BP 118/70（起始前 126/74），體重下降 0.8 kg，無姿位性頭暈、無新症狀。
併用：furosemide 40 mg QD、最大耐受劑量 ARB。近期無 NSAID、無顯影劑檢查。

### 投票（單選最佳）

- **A.** eGFR 已 <25，立刻停 dapagliflozin
- **B.** 繼續用——視為預期性血行動力學 dip；同時檢視容積狀態與併用藥，2–4 週複驗
- **C.** 繼續用，但把 ARB 停掉以保住 eGFR
- **D.** 繼續用，數字在預期範圍內，不需額外評估

### 正確傾向：B

<!-- src: synthesis/CLAIMS_LEDGER.md §C5,C4 ; synthesis/CONTROVERSIES.md §C2 ; synthesis/EVIDENCE_GAPS.md G1 ; 原始PDF/KDIGO_2024_CKD_Guideline_ExecSummary.md ; evidence/safety/IMPLEMENTATION_CHECKLIST.md §B,§C ; evidence/safety/CASE_REPORT_FAILURE_MODES.md #30 -->

**1. 幅度落在預期範圍。**
27 → 24 為 **−3 mL/min/1.73 m²（約 −11%）**。
DAPA-CKD 起始後 2 週 eGFR 變化：**T2D 層 −2.61、非 T2D 層 −2.01** `[預先設定分析]`（Heerspink 2021）；
DAPA-HF 事後分析：**dapagliflozin −4.2 vs placebo −1.1** `[事後分析]`（Adamson Circulation 2022, PMID 35442064）。
衛教用整數：**起始後 2 週 eGFR 平均多降約 3–4 mL/min/1.73 m²，可逆。**

**2. Dip 不預示較差結局。**
DAPA-CKD 之次要分析中，早期 eGFR 下降 **>10% 者結局不劣（HR 0.73, 0.59–0.91）**
（Jongs JASN 2022, PMID 35977807 ⚠️**分析屬性（prespecified vs post hoc）待方法學稽核核定**）；
且早期下降 >10% 者不伴隨較多嚴重不良事件。長期 eGFR slope 為 **+0.95 mL/min/1.73 m²/年**（相對安慰劑）。

**3. 指引直接寫了「不必因此停藥」。**
KDIGO 2024 **Practice Point 3.7.3**【verbatim】："SGLT2i initiation or use does not necessitate alteration
of frequency of CKD monitoring and the reversible decrease in eGFR on initiation is generally not an
indication to discontinue therapy." `[指引／仿單]`
→ 連**追蹤頻率都不必因為起始 SGLT2i 而改變**。

**4. 「起始門檻」與「續用門檻」是兩件事——這是本例最重要的分辨。**
本例是**在 eGFR 27 起始、之後掉到 24**，不是「在 eGFR 24 起始」。

| 情境 | FDA / EMA / TFDA 仿單 | KDIGO 2024 |
|---|---|---|
| **起始** | eGFR ≥25 可起始；**<25 不建議起始**（EMA：<25 經驗有限、<15 禁用） | **≥20 可起始**（Rec 3.7.1／3.7.2, **1A**） |
| **續用** | 治療中降至 <25 **可續用**（FDA §2.2/§2.3） | 【verbatim】"Once an SGLT2i is initiated, it is reasonable to continue an SGLT2i even if the eGFR falls below 20 ml/min per 1.73 m², unless it is not tolerated or KRT is initiated." |

⚠️ **20–25 這個地帶要誠實講（CONTROVERSIES C2／EVIDENCE_GAPS G1）**：
KDIGO ≥20 建議的**證據主體是 EMPA-KIDNEY，屬類別層級**；**dapagliflozin 在 eGFR 20–25 沒有隨機起始資料**。
DAPA-CKD 的 stage 4（eGFR <30）次族群為 **RRR 27%（95% CI −2 至 47），p-interaction 0.22**
`[預先設定次族群]`（Chertow JASN 2021, PMID 34272327）——
✅ 可講「與整體一致、無交互作用證據」；❌ **不可講「已證明 eGFR <30 有效」**。
⚠️TW：台灣健保 §2.16 規定**治療中 eGFR <15 停止給付**（114/3/1 版，引用時點須再查證）。

**5. 但「不停藥」不等於「不評估」——B 之所以勝過 D。**
CLAIMS_LEDGER C5 的界線是：**持續下降或 >30% 下降須找其他原因**。
本例應主動做的三件事：
① **容積評估**：體重降 0.8 kg、BP 由 126/74 降至 118/70、併用 loop diuretic ——
  若已 euvolemic，可考慮下修 furosemide（實務原則：euvolemic 且血壓偏低者起始時可考慮減利尿劑；
  充血未解者不減）；
② **併用藥回顧**：NSAID、顯影劑、其他腎毒性藥物；
③ **2–4 週複驗**確認是「一次性 dip 後打平」而非持續下滑。
`[個案報告訊號]` 提醒：曾有長期 empagliflozin 使用者於**腹瀉脫水**後發生少尿型 AKI（Cr 13 mg/dL，需血液透析），
腎切片為**滲透性腎病變**，停藥＋透析 2 週後腎功能恢復（PMID 41691209）——
這是 case-report signal，**不是發生率**；教學點是：**不是每個下降都是良性 dip，所以要評估**。

### 常見錯誤選項為何錯

- **A（立刻停藥）**：兩個錯誤疊在一起。其一，把可逆的血行動力學 dip 當成腎損傷——
  CLAIMS_LEDGER C5 ❌ 禁用措辭：「eGFR 下降代表腎損傷、應停藥」。
  其二，把 **<25 這個「起始」門檻誤當成「停藥」門檻**；FDA 與 KDIGO 都明文允許續用。
  停掉的代價是失去 HR 0.61 的腎臟保護（DAPA-CKD `[RCT 主要終點]`）。
- **C（停 ARB）**：為了保住一個數字，放棄另一個有硬終點證據的治療。RAS 阻斷是 CKD 的基礎用藥，
  也是 KDIGO 與健保給付的前提條件（最大耐受 ACEI/ARB 穩定 ≥4 週）。
  如果真的判定是容積相關，**先動的是利尿劑，不是 ARB**。
- **D（不評估）**：漏掉真正的 AKI。本例同時具備 loop diuretic、體重下降、血壓下降三個容積訊號；
  KDIGO 說的是「不必改變**監測頻率**」，不是「不必臨床評估」。

### Take-home

> **eGFR 的 dip 是血行動力學，不是腎損傷；「不停藥」也不等於「不評估容積」。**

---

## CASE-4 ── 「非糖尿病、血糖 112，為什麼酸中毒？」

### 病例敘述

72 歲男性，**非糖尿病**，缺血性心肌病變 HFrEF（LVEF 30%），因心衰竭適應症使用 **dapagliflozin 10 mg QD 已 8 個月**。
**急性腸胃炎第 2 天**：嘔吐數次、幾乎未進食，但**所有慢性病藥物照常服用**。
急診：BP 104/64、HR 104、**RR 24**、體溫 37.2°C、意識清楚但明顯倦怠。
**血糖 112 mg/dL**、Na 138、Cl 100、**HCO₃⁻ 13 mmol/L**、K 4.0、Cr 較基礎值略升、乳酸 1.6 mmol/L。
（**陰離子間隙 = 138 −（100 + 13）= 25**）

### 投票（單選最佳）

- **A.** 血糖正常又沒有糖尿病，先當脫水性 AKI／腸胃炎處理，輸液後再觀察
- **B.** 立即驗**血中 β-hydroxybutyrate**＋血氣分析，並計算陰離子間隙
- **C.** 驗尿酮就夠了
- **D.** 驗乳酸與敗血症篩檢，低灌流才是主因

### 正確傾向：B

<!-- src: synthesis/CLAIMS_LEDGER.md §E2 ; synthesis/EVIDENCE_GAPS.md G10,G11 ; evidence/safety/PERIOPERATIVE_SICK_DAY_ALGORITHM.md §3,§4,§5 ; evidence/safety/CASE_REPORT_FAILURE_MODES.md #8,#9,#10,#11,#27,#30 ; evidence/safety/IMPLEMENTATION_CHECKLIST.md §B -->

**1. 血糖正常不排除酮酸中毒——這是本例唯一要記住的事。**
FDA 仿單 §5.1 明載酮酸中毒可發生於血糖 <250 mg/dL；EMA SmPC §4.4 要求症狀（噁心、嘔吐、腹痛、
異常倦怠、呼吸困難）**不論血糖高低都要驗酮體** `[指引／仿單]`。
CLAIMS_LEDGER E2 ❌ 禁用措辭：**「非糖尿病不會發生酮酸中毒」**。

**2. 非糖尿病族群的證據長什麼樣子——要把兩層講清楚。**
- `[RCT]` DAPA-CKD 非糖尿病層 **0 例 DKA**（Persson，已核全文）；DAPA-HF 非糖尿病層 **0 例**（Petrie）。
  DAPA ACT 住院族群亦**無任何 DKA 個案**。
- `[個案報告訊號]` 但上市後個案已確認可以發生：
  - Umapathysivam Diabetes Care 2024（PMID 37988720）：HFrEF 起始 SGLT2i 後**首兩例發表之非糖尿病嚴重酮酸中毒**，
    **均由進食減少誘發**；以靜脈葡萄糖＋口服含糖液體＋極少量胰島素緩解。
  - Miyazaki 2024（PMID 38985686）：83 歲女性、無糖尿病、HF（EF ~30%），跌倒骨折後厭食 2 週仍續用——
    **血糖 124 mg/dL、HbA1c 5.9%、pH 7.329、HCO₃⁻ 14.3 mmol/L、BHB 5,150 µmol/L、C-peptide 正常**；
    **僅以葡萄糖治療緩解，未用胰島素**。
  - Prasad 2025（PMID 41625235）：58 歲男性缺血性心肌病變（LVEF 35%）＋CKD 2 期、非糖尿病，
    起始 dapagliflozin 2 週後噁心嘔吐倦怠——**pH 7.21、HCO₃⁻ 12 mmol/L、AG 23、BHB 5.4 mmol/L、血糖 108 mg/dL**；
    48 小時內緩解。

✅ 正確措辭：「試驗中未見，上市後個案已見——**機率低但表現容易被忽略**。」
❌ 禁用：以個案報告估算發生率。

**3. 為什麼一定要驗「血」酮而不是尿酮。**
EMA SmPC §4.4【verbatim】："Monitoring of ketones is recommended... Measurement of blood ketone levels
is preferred to urine." `[指引／仿單]`
ADA 2026 §16 亦建議對高風險者提供**血中 β-hydroxybutyrate** 監測工具。

**4. 順帶教一個診斷標準的陷阱（EVIDENCE_GAPS G11）。**
ADA 2026 Table 16.1 之 DKA 定義：**BOHB ≥3.0 mmol/L ＋ pH <7.3 且／或 HCO₃⁻ <18 mmol/L，
且血糖 ≥200 mg/dL 或已知糖尿病**。
本例**血糖 112 且無糖尿病**——**兩個條件都不符**，形式上不落入 ADA 的 DKA 定義框架。
這正是現有指引的缺口：**非糖尿病 SGLT2i 使用者的酮體篩檢策略，指引尚未分化**。
臨床上要記的是操作規則：**SGLT2i 使用者 ＋ 不明原因陰離子間隙代謝性酸中毒 → 先驗血酮再歸因**。

**5. 驗完之後怎麼治（一頁講完）。**
- ADA 2026 §16 p. S348【verbatim】："In euglycemic DKA (glucose <200 mg/dL and positive BOHB),
  5% or 10% dextrose needs to be started alongside 0.9% NaCl/crystalloid at the start of the insulin
  treatment." `[指引／仿單]`
- JBDS-IP Guideline 02（rev. 2023-03）【verbatim】："1) Initiate glucose 10% straight away at 125 ml/hr
  because the glucose is <14 mmol/L 2) Begin with 0.1 units/kg/hr insulin rate 3) If glucose falling
  despite 10% glucose reduce to 0.05 units/kg/hr to avoid hypoglycaemia." `[指引／仿單]`
- **非糖尿病者的治療核心是「給糖」**——靜脈葡萄糖＋口服含糖液體，僅需極少量或不需胰島素
  `[個案報告訊號]`（#8–10）。
- **勿單用碳酸氫鈉**：無法終止生酮，個案中反覆失敗並延誤診斷 `[個案報告訊號]`（#5、#6）。
- **停藥＋通報 ADR**（台灣 02-2396-0100, adr.fda.gov.tw；英國 Yellow Card）。
- **重啟**：EMA §4.4【verbatim】："Restarting SGLT2 inhibitor treatment in patients experiencing a DKA
  while on SGLT2 inhibitor treatment is not recommended, unless another clear precipitating factor is
  identified and resolved." 本例誘因（腸胃炎致攝食下降）明確且可解除 → 屬個別化決策；
  ⚠️ 但**無系統性證據界定重啟時機**（EVIDENCE_GAPS G10），且停藥後藥效可延長
  （FDA §5.1：尿糖持續 3 天，上市後報告 >6 天甚至 2 週）。

**6. 真正的預防點：這位病人在家就該停藥。**
**SADMANS**（Diabetes Canada 2018 Appendix 8, DOI 10.1016/j.jcjd.2017.10.045【verbatim 已核對】）——
生病無法維持足夠水分攝取或急性腎功能下降時應暫停：
**S**ulfonylureas、**A**CE inhibitors、**D**iuretics、**M**etformin、**A**RBs、**N**SAIDs、**S**GLT2 inhibitors。
ADA 2026 §16【verbatim】："SGLT2 inhibitors should be avoided in cases of severe illness, in people with
ketonemia or ketonuria, and during prolonged fasting and surgical procedures."
→ **「照常服藥」四個字就是本例的失效點。**非糖尿病的心衰竭病人常常沒有拿到過生病日衛教——
因為他不覺得自己在吃「糖尿病藥」。

### 常見錯誤選項為何錯

- **A（先當脫水性 AKI）**：這是**最常見的診斷遮蔽路徑**。
  `[個案報告訊號]` 一組 3 例 ICU 敗血症＋AKI＋euDKA 病人，**每一例的酸中毒最初都被歸因於 AKI**，
  血酮檢測才是決定性檢查，且 euDKA 的治療優先於腎臟替代療法（PMID 40502910）。
  教學句：**未驗酮體前，不要把陰離子間隙酸中毒歸因於腎衰竭。**
- **C（尿酮就夠）**：尿酮主要偵測 acetoacetate，而 SGLT2i 相關酮酸中毒以 **β-hydroxybutyrate** 為主；
  EMA 明文指出**血酮優於尿酮**。用尿酮做排除會漏診。
- **D（只驗乳酸／敗血症）**：本例乳酸 1.6 mmol/L，**不足以解釋 AG 25**。
  且「有共存感染」正是 euDKA 最典型的遮蔽情境之一——曾有 90 歲缺血性心肌病變病人因併存 UTI
  而使 euDKA 悶燒未被發現 `[個案報告訊號]`（PMID 39246944）。**找到一個診斷不等於排除第二個。**

### Take-home

> **血糖正常不排除酮酸中毒；SGLT2i 使用者只要有陰離子間隙酸中毒，先驗血酮再歸因。**

---

## 講者備忘（不投影）

1. 四例的隱藏主線是同一句話：**dapagliflozin 的門檻、風險與證據等級，都不是由「血糖」定義的。**
   CASE-1 是門檻（UACR/eGFR ≠ HbA1c）、CASE-2 是證據等級（RCT vs 類別統合）、
   CASE-3 是可逆生理 vs 損傷、CASE-4 是血糖正常不排除酮症。
2. 全部個案報告一律以 `[個案報告訊號]` 開場，並在該張投影片重複一次
   「case reports are safety signals, not incidence or efficacy evidence」。
3. ⚠️TW 標記之健保條文（CASE-1 給付條件、CASE-3 eGFR <15 停付）在演講前須再查證現行版本。
4. ⚠️ 待方法學稽核（`appraisal/`）確認後可能需修訂之處：
   DAPA-HF 納入排除細節（SBP<95、eGFR<30）、Jongs JASN 2022 之分析屬性、
   DECLARE 安全性表格數值之來源鏈（CONTROVERSIES C9）。
5. 投票工具建議用單選、不顯示即時分佈直到收票，避免從眾；
   CASE-2 與 CASE-3 預期會出現明顯分歧，這兩題留給討論的時間值得多 15 秒。
