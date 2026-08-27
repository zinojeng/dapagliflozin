# TALK OUTLINE — Dapagliflozin in 2026：成熟的器官保護與證據停止的地方

> 演講長度：40 分鐘（含 4 個聽眾投票病例插入點）
> 結構：Director 選定之 **T1（總論）**，內嵌 T2 開場張力、T3 爭議核心、T5+T6 收尾
> 資料來源：`synthesis/CLAIMS_LEDGER.md`（數值與措辭之唯一權威）、`synthesis/CONTROVERSIES.md`、
> `synthesis/EVIDENCE_GAPS.md`、`synthesis/DECISION_LOG.md`；補充數值來自
> `evidence/landmark/LANDMARK_TRIAL_MATRIX.md`、`evidence/frontier/RECENT_TRIAL_MATRIX.md`、
> `evidence/safety/SAFETY_EVIDENCE_MATRIX.md`、`evidence/safety/PERIOPERATIVE_SICK_DAY_ALGORITHM.md`、
> `evidence/guidelines-labels/GUIDELINE_LABEL_MATRIX.md`。
> 每條數值後之 `[ledger:X#]` 為 CLAIMS_LEDGER 條目編號，供稽核 grep 回驗；
> `[LM§]`／`[FR§]`／`[SF§]`／`[GL§]` 分別指 landmark／frontier／safety／guideline 矩陣章節。
>
> **全稿三條紅線**
> 1. 每個統合分析數字必須標 **class-level（SGLT2i 類別）** 或 **dapagliflozin 專屬**——不得互換。
> 2. 每個陽性複合終點必須說出**誰在驅動**；陽性複合 ≠ 各分項均獲益。
> 3. 任何台灣給付／法規內容一律加 **⚠️TW**（須於引用時點再獨立查證，DECISION_LOG D3）。

---

## 分鐘預算總表

| # | 段落 | 分鐘 | 累計 | 投影片 | 證據層級 |
|---|---|---|---|---|---|
| 1 | 開場張力：MACE-neutral 為何仍改變治療 | 5 | 0–5 | S1–S3 | 成熟 |
| 2 | 成熟證據：DAPA-HF → DELIVER → pooled → DAPA-CKD | 10 | 5–15 | S4–S9 | 成熟 |
| 3 | 爭議核心：急性心衰住院內起始 | 8 | 15–23 | S10–S13 | 演進中 |
| 4 | 新族群與過度外推：DapaTAVI、DAPA-MI | 7 | 23–30 | S14–S17 | 演進中／探索性 |
| 5 | 證據懸崖：eGFR <20–25、透析、移植、ADPKD | 5 | 30–35 | S18–S20 | 探索性 |
| 6 | 安全性：euDKA、圍術期、eGFR dip vs AKI | 4 | 35–39 | S21–S23 | 安全原則 |
| 7 | 收尾＋必備 NOT-proven slide | 1 | 39–40 | S24–S25 | — |

**病例插入點（病例本文由另一 agent 撰於 `talk/CLINICAL_CASES.md`）**

| 插入點 | 時間 | 位置 | 投票問題主旨 |
|---|---|---|---|
| `[CASE-1 → talk/CLINICAL_CASES.md]` | 第 4 分鐘（S3 後） | 開場張力結尾 | T2D、多重危險因子但無 ASCVD——你開 dapagliflozin 的理由是哪一軌？ |
| `[CASE-2 → talk/CLINICAL_CASES.md]` | 第 14 分鐘（S9 後） | 成熟證據結尾 | LVEF 55% 的 HFpEF 病人問「這個藥能讓我活久一點嗎？」你怎麼答？ |
| `[CASE-3 → talk/CLINICAL_CASES.md]` | 第 22 分鐘（S13 後） | 爭議核心結尾 | 急性心衰住院第 2 天、已脫離 IV inotrope——現在起始還是出院前起始？ |
| `[CASE-4 → talk/CLINICAL_CASES.md]` | 第 34 分鐘（S20 後） | 證據懸崖結尾 | eGFR 22、UACR 800 的病人——起始、續用、還是停藥？ |

---

# 段落 1｜開場張力：MACE-neutral 為何仍改變治療（0–5 分鐘，5 min）

### S1｜一句話開場：這是一個「主要終點沒達標卻改寫指引」的藥 ⟨成熟⟩ [0:00–0:45]
- DECLARE-TIMI 58：**MACE 未顯著下降**——8.8% vs 9.4%，HR 0.93（95% CI 0.84–1.03），p=0.17；n=17,160 T2D，中位追蹤 4.2 年 `[ledger:A1]`
- 同一試驗的另一個共同主要終點卻是陽性：CV death/HHF 4.9% vs 5.8%，HR 0.83（0.73–0.95），p=0.005 `[ledger:A2]`
- 今天要回答的問題：這個落差不是統計意外，而是**藥理作用的定位**——以及它在哪裡停止
- 🎤 講者提示：先讓聽眾記住「一個試驗、兩個主要終點、兩種命運」，整場演講都掛在這個張力上。

### S2｜兩條風險軌：動脈粥狀硬化軌 vs 心衰／腎臟軌 ⟨成熟⟩ [0:45–2:30]
- **不動的那一軌**：MACE HR 0.93（0.84–1.03）；全因死亡 6.2% vs 6.6%，HR 0.93（0.82–1.04）——中性 `[ledger:A1]`[LM§2]
- **會動的那一軌**：複合終點的驅動者是 **HHF，HR 0.73（0.61–0.88）**；CV death 單獨為中性 HR 0.98（0.82–1.17）`[ledger:A2]`
- **腎臟軌同向**：預先設定之次級 cardiorenal 複合 4.3% vs 5.6%，HR 0.76（0.67–0.87）；renal-specific HR 0.53（0.43–0.66）`[ledger:A3]`
- 措辭紀律：可以說「降低心衰住院」，**不可以說「預防心肌梗塞／中風」，也不可以在 DECLARE 層級說「降低心血管死亡」** `[ledger:A1,A2]`
- 🎤 講者提示：這張投影片是全場的骨架——後面每一個族群都在問「你治療的是哪一軌」。

### S3｜這不是 dapagliflozin 獨有：類別層級的同一個訊號 ⟨成熟⟩ [2:30–4:00]
- **class-level（SGLT2i 類別）**：Zelniker 2019 三試驗統合（EMPA-REG OUTCOME + CANVAS + DECLARE，n=34,322）——MACE 效益侷限已建立 ASCVD 層 HR 0.86（0.80–0.93）vs 無 ASCVD 者 HR 1.00（0.87–1.16），p-interaction 0.0501 `[ledger:F1]`[LM§6.5]
- **class-level**：同一統合中 CV death/HHF HR 0.77（0.71–0.84）不論有無 ASCVD 或 HF 病史 [LM§6.5]
- 教學句：**MACE 只在次級預防族群出現；心衰與腎臟效益到處都在**——這是「兩條軌」的類別層級佐證
- ⚠️ 這是 class-level 數字，**不得冠名 dapagliflozin** `[ledger:F 前言]`
- 🎤 講者提示：p-interaction 0.0501 要念出來——它剛好在門檻上，是「訊號」不是「證明」。

`[CASE-1 → talk/CLINICAL_CASES.md]` **第 4 分鐘 · 聽眾投票（~1 min）**

---

# 段落 2｜成熟證據：從 HFrEF 到 CKD（5–15 分鐘，10 min）

### S4｜DAPA-HF：四大 landmark 中唯一單試驗雙分項皆顯著 ⟨成熟⟩ [5:00–6:45]
- 族群：4,744 名慢性 HFrEF（NYHA II–IV、LVEF ≤40%、NT-proBNP 升高）；**排除 eGFR <30、SBP <95**；中位追蹤 18.2 月 `[ledger:B1]`
- 主要複合（心衰惡化或 CV death）：16.3% vs 21.2%，**HR 0.74（0.65–0.85）** `[ledger:B1]`
- **複合驅動者：兩者皆動**——心衰惡化 HR 0.70（0.59–0.83）**且** CV death HR 0.82（0.69–0.98）；全因死亡 HR 0.83（0.71–0.97）`[ledger:B1]`
- 措辭紀律：這是 landmark 中**唯一**能在單試驗層級同時主張兩個分項的；**不可據此說「所有心衰患者均證明死亡下降」** `[ledger:B1]`
- 🎤 講者提示：把「兩者皆動」講成例外而不是常態——後面三個試驗都不是這樣。

### S5｜DAPA-HF 的第二個訊息：器官保護與血糖脫鉤 ⟨成熟⟩ [6:45–7:45]
- 55% 受試者**沒有糖尿病**（2,605/4,744）[LM§3]
- 無糖尿病者 HR 0.73（0.60–0.88）vs 有糖尿病者 HR 0.75（0.63–0.90），p-interaction 0.80 `[ledger:B2]`
- 原文標註為 **exploratory analysis**；正確講法是「**未見糖尿病狀態之效果修飾證據**」，**不是「證明兩者等效」** `[ledger:B2]`
- 🎤 講者提示：這一句的措辭差別，就是「一致性」與「等效性」的差別，值得停三秒。

### S6｜DELIVER：LVEF >40% 的真實價值主張 ⟨成熟⟩ [7:45–9:30]
- 族群：6,263 名 HF、LVEF >40%（HFmrEF/HFpEF），**eGFR ≥25**；中位追蹤 2.3 年 `[ledger:B3]`
- 主要複合：16.4% vs 19.5%，**HR 0.82（0.73–0.92）** `[ledger:B3]`
- **複合驅動者：worsening HF，HR 0.79（0.69–0.91）**；CV death 單獨 HR 0.88（0.74–1.05）——**單獨不顯著** `[ledger:B3]`
- 措辭紀律：可以說「減少心衰惡化事件」；**不可以說「DELIVER 證明 HFpEF 死亡率下降」** `[ledger:B3]`
- 🎤 講者提示：這是全場第二個「陽性複合 ≠ 各分項獲益」的實例，語氣要與 DECLARE 那張呼應。

### S7｜那死亡率呢？——引 pooled，不引 DELIVER ⟨成熟⟩ [9:30–10:45]
- **dapagliflozin 專屬**（非 class-level）：Jhund 2022 病人層級**預先規劃**合併分析，DAPA-HF + DELIVER，n=11,007 `[ledger:B4]`
- CV death **HR 0.86（0.76–0.97）**；全因死亡 **HR 0.90（0.82–0.99）**；總心衰住院次數 RR 0.71（0.65–0.78）`[ledger:B4]`
- 規則（DECISION_LOG D11）：跨 EF 的**死亡率主張一律引此篇**，不引 DELIVER 單獨；反之，class-level 統合（Vaduganathan、SMART-C）的數字**不得冠名 dapagliflozin** `[ledger:B4]`
- 對照參考 **class-level（SGLT2i 類別）**：五試驗統合 CV death/HHF HR 0.77（0.72–0.82）`[ledger:F3]`
- 🎤 講者提示：這張是「引用紀律」的示範——同一個臨床問題，答案取決於你引哪一層證據。

### S8｜衰弱不是不給藥的理由 ⟨成熟⟩ [10:45–11:45]
- DELIVER 預先設定之衰弱分析（Rockwood frailty index）：最衰弱層 HR 0.74（0.61–0.91），p-interaction 0.40——**相對療效跨衰弱層一致** `[ledger:B5]`
- KCCQ 改善幅度隨衰弱程度加大，p-interaction 0.021 `[ledger:B5]`
- 措辭紀律：**不可說「衰弱患者證明獲益更大」**（絕對獲益推論 ≠ 交互作用證明）；衰弱者整體 AE 與停藥率較高，但**在各衰弱層內並未多於 placebo** `[ledger:B5]`[LM§4]
- 實務結論：處方難度是**耐受性管理問題**，不是年齡或衰弱的排除條件
- 🎤 講者提示：這是全場最容易被聽眾帶回門診用的一句話，可以放慢。

### S9｜DAPA-CKD：效應量最大的一個，也是邊界最清楚的一個 ⟨成熟⟩ [11:45–14:00]
- 族群：4,304 名 CKD，**eGFR 25–75、UACR 200–5000 mg/g**，67.5% 為 T2D；中位 2.4 年，**因療效提前中止** `[ledger:C1]`
- 主要複合（持續 ≥50% eGFR 下降／ESKD／腎或 CV 死亡）：9.2% vs 14.5%，**HR 0.61（0.51–0.72）**；**NNT 19（15–27）** `[ledger:C1]`
- **複合驅動者：腎臟事件**——kidney-specific 複合 HR 0.56（0.45–0.68）；同時 CV death/HHF HR 0.71（0.55–0.92）亦下降 [LM§5]
- 次級終點：**全因死亡 4.7% vs 6.8%，HR 0.69（0.53–0.88），p=0.004** `[ledger:C2]`
- 與血糖脫鉤：T2D 層 HR 0.64（0.52–0.79）vs 非 T2D 層 HR 0.50（0.35–0.72），p-interaction 0.24——講「一致」，**不講「非糖尿病獲益更大」** `[ledger:C3]`
- ❌ 不可外推之處（下半場會逐一處理）：UACR <200、eGFR <25 起始、透析、移植、ADPKD、lupus/ANCA `[ledger:C1]`
- 🎤 講者提示：NNT 19 是全場最有說服力的數字，但緊接著必須念出排除條件——這正是下半場的入口。

`[CASE-2 → talk/CLINICAL_CASES.md]` **第 14 分鐘 · 聽眾投票（~1 min）**

---

# 段落 3｜爭議核心：急性心衰住院內起始（15–23 分鐘，8 min）

> 本段全程採用 **CONTROVERSIES C1 裁定措辭**：
> 「住院內起始『安全、可行』有專屬 RCT 支持；『早期硬結局效益』目前是類別層級統合的主張——兩句話分開講。」

### S10｜問題設定：出院時沒開，之後多半就不會開了 ⟨演進中⟩ [15:00–16:00]
- 臨床動機：住院是打破 therapeutic inertia 的時間窗（出院處方率論證）；但動機不等於證據 [CONTROVERSIES C1]
- 兩層證據將給出**方向一致、強度不同**的答案——今天要學的是如何同時持有這兩層
- 指引現況：ADA 2026 Rec 16.11（grade A）——住院中若有 HF 適應症且無禁忌，可續用／起始 [SF§3–4]
- 🎤 講者提示：先講清楚「這一段沒有乾淨答案」，聽眾才會願意跟著看兩造。

### S11｜DAPA ACT HF-TIMI 68：專屬試驗，主要終點未達 ⟨演進中⟩ [16:00–18:00]
- 族群：2,401 名急性心衰住院者（71.5% LVEF ≤40%），住院 24 小時–14 天內隨機分派，雙盲 2 個月 `[ledger:D1]`[FR§2]
- 主要終點（CV death 或心衰惡化，2 個月）：10.9% vs 12.7%，**HR 0.86（0.68–1.08），P=0.20——未達統計顯著** `[ledger:D1]`
- 次級：全因死亡 3.0% vs 4.5%，**HR 0.66（0.43–1.00）**——**次級終點、僅供產生假說**（DECISION_LOG D6）`[ledger:D1]`[FR§2]
- 安全性（可引用之安全證據）：症狀性低血壓 3.6% vs 2.2%；腎功能惡化 5.9% vs 4.7%；**DKA 0 vs 0** [SF§3–4]
- 措辭紀律：**不可說「DAPA ACT 證明早期死亡效益」**；**也不可說「陰性所以應放棄住院起始」** `[ledger:D1]`
- 🎤 講者提示：HR 0.66 的上限剛好觸到 1.00——把這個細節講出來，聽眾才懂為什麼它只能是假說。

### S12｜同類統合卻是陽性——同一篇論文裡的兩層證據 ⟨演進中⟩ [18:00–20:00]
- **class-level（SGLT2i 類別）**：DAPA ACT 論文內嵌之**預先設定**住院起始統合（試驗層級，n≈3,527）——CV death/心衰惡化 **HR 0.71（0.54–0.93），P=0.012**；全因死亡 **HR 0.57（0.41–0.80），P=0.001** `[ledger:F4]`[FR§2]
- **class-level（SGLT2i 類別）**：J Card Fail 2026 TSA 統合（8 個 RCT，n=4,096，含 dapagliflozin／empagliflozin／sotagliflozin，加權中位追蹤 60 天）——全因死亡 **RR 0.61（0.47–0.81）**；心衰惡化 RR 0.67（0.48–0.94）；CV death RR 0.68（0.47–0.99）；**心衰再住院 RR 0.87（0.70–1.09）不顯著**；TSA 判定死亡率下降為 firm `[ledger:F4]`[FR§3]
- ⚠️ 兩組數字**都是 class-level，都不得冠名 dapagliflozin**；統合含開放標籤小試驗，追蹤 ≤2 個月 [CONTROVERSIES C1]
- 文獻識別註記：dapagliflozin 專屬之 care-spectrum 病人層級合併分析**已存在但尚不可引數字**——Berg 等，JACC Heart Fail 2026;14(8):103232（PMID 42547169，2026-08-01 刊出，摘要與結果尚未可取得）；目前可引數字的仍只有上述兩篇 class-level 文獻（DECISION_LOG D4 修訂版）
- 🎤 講者提示：強調「陽性統合的最大單一試驗，就是那個中性的試驗本身」——這是統合分析閱讀的核心陷阱。

### S13｜DICTATE-AHF 與本段裁定 ⟨演進中／安全原則⟩ [20:00–22:00]
- DICTATE-AHF（n=240，開放標籤）：主要終點利尿效率 **OR 0.65（0.41–1.02），P=0.06——未達顯著** `[ledger:D2]`
- 次級（surrogate）：累積 loop diuretic 劑量 560 vs 800 mg，P=0.006；24 小時尿鈉 P=0.03 [SF§7]
- 措辭紀律：支持**早期使用之安全性與利尿增益（surrogate）**；**不可當作臨床結局證據** `[ledger:D2]`
- **本段裁定（C1）**：
  1. 「住院內起始安全、可行」——**有 dapagliflozin 專屬 RCT 支持**
  2. 「住院內起始降低早期硬結局」——**目前是 class-level 統合的主張**
  3. 啟動門檻（血壓、停用 inotrope、容積狀態）沿用試驗納入條件；**不得宣稱有 RCT 界定的最低穩定標準** [CONTROVERSIES C1]
- 🎤 講者提示：這三句話請照唸——它們是本段唯一不能自由發揮的措辭。

`[CASE-3 → talk/CLINICAL_CASES.md]` **第 22 分鐘 · 聽眾投票（~1 min）**

---

# 段落 4｜新族群與過度外推：trial literacy 兩堂課（23–30 分鐘，7 min）

### S14｜DapaTAVI：複合陽性、驅動者單一 ⟨演進中⟩ [23:00–24:45]
- 族群：1,222 名 TAVI 後**高心衰風險**者（曾因心衰住院＋至少一項：eGFR 25–75、糖尿病、或 LVEF ≤40%）；西班牙多中心、**開放標籤（PROBE）** `[ledger:D3]`[FR§1]
- 主要複合（1 年全因死亡或心衰惡化）：15.0% vs 20.1%，**HR 0.72（0.55–0.95），P=0.02** `[ledger:D3]`
- **複合驅動者：心衰惡化**——9.4% vs 14.4%，subhazard ratio **0.63（0.45–0.88）**；全因死亡 7.8% vs 8.9%，**HR 0.87（0.59–1.28）——單獨不顯著** `[ledger:D3]`[FR§1]
- 措辭紀律：**不可說「降低 TAVI 後死亡率」** `[ledger:D3]`
- 🎤 講者提示：這是本場第三個「誰在驅動」的案例——到這裡聽眾應該可以自己搶答了。

### S15｜DapaTAVI 的兩個補充證據，方向相反 ⟨演進中⟩ [24:45–26:15]
- **預先設定**之 KCCQ 健康狀態分析：TAVI 本身之外**無額外 KCCQ 增益**——12 個月改善 OR 1.03（0.83–1.27），P=0.819 [FR§1]
- **事後**方法學再分析（win ratio）：原主要終點 WR 1.36（1.03–1.78），P=.028；**把 KCCQ 加進階層後估計值移向無效** WR 1.10（0.94–1.30）[FR§1]
- 安全性：生殖器感染與低血壓顯著較多 `[ledger:D3]`
- **裁定措辭（C5）**：支持「**符合 DapaTAVI 入選條件的高風險 TAVI 後病人**」起始；**不支持全體 TAVI 常規**。介入已解除瓣膜阻塞，殘餘心衰風險（纖維化、HFpEF 生理、AF、CKD）才是治療標的 [CONTROVERSIES C5]
- ⚠️ 不外推至全體 TAVI 或未處理之重度 AS（EVIDENCE_GAPS G7）
- 🎤 講者提示：82–85 歲族群 NNT 與 NNH 並存——這是共享決策的實例，不是常規醫囑。

### S16｜DAPA-MI：統計陽性 ≠ 臨床陽性 ⟨探索性⟩ [26:15–28:15]
- 族群：4,017 名急性 MI（左心室功能受損或 Q 波 MI）、**無糖尿病病史、無慢性心衰**；registry-based RCT `[ledger:D4]`[FR§4]
- 主要終點為階層複合（win ratio）：**WR 1.34（1.20–1.50）**，P<0.001 `[ledger:D4]`
- **驅動者是低階層的 cardiometabolic 分項**（新發 T2DM、體重）；**分析方法因事件累積過低而於試驗中期修改** `[ledger:D4]`[FR§4]
- **硬終點無效**：CV death 或 HHF 2.5%（50/2019）vs 2.6%（52/1998），**HR 0.95（0.64–1.40）** `[ledger:D4]`
- 事後分析：糖尿病前期層新發 T2DM 10.1% vs 13.1%，HR 0.74（0.55–0.99）——**post hoc** [FR§4]
- 措辭紀律：可說「改善 cardiometabolic 結果（防新發糖尿病、減重）；未降低 CV death/HHF」；**不可說「DAPA-MI 顯示心血管保護」** `[ledger:D4]`
- 🎤 講者提示：把「死亡」和「≥5% 減重」放進同一個階層終點——這一句講出來，全場會安靜。

### S17｜這兩堂課的共同結論：先問終點是怎麼組起來的 ⟨演進中／探索性⟩ [28:15–30:00]
- **裁定措辭（C4）**：Statistically positive ≠ hard-outcome positive。DAPA-MI 支持的是 post-MI 病人的**代謝風險管理**，不是心血管二級預防適應症 [CONTROVERSIES C4]
- 三問清單（可直接帶回 journal club）：
  1. 主要終點是**哪一類複合**（時間至事件／階層 win ratio）？
  2. **哪一個分項在驅動**？分項單獨顯著嗎？
  3. 分析計畫**有沒有在試驗進行中修改**？
- EVIDENCE_GAPS G6 提醒：post-MI 硬終點是 **negative-evidence floor（已測未證）**，不是 data gap——**不得宣稱效益**
- 🎤 講者提示：這是全場最可攜帶的一張投影片，建議留在螢幕上多停幾秒讓人拍照。

---

# 段落 5｜證據懸崖：eGFR <20–25、透析、移植、ADPKD（30–35 分鐘，5 min）

### S18｜eGFR 20–25 起始地帶：三個權威、三種答案 ⟨探索性／規則衝突⟩ [30:00–31:45]
- **KDIGO 2024** Rec 3.7.1：eGFR ≥20 建議起始（**Grade 1A**）；另 eGFR 20–45 且 UACR <200 為 Grade 2B [GL§2.1]
- **US FDA 仿單**：非降糖適應症 **eGFR <25 不建議起始** [GL§1.1]
- **EMA SmPC**：**eGFR <15 不建議起始**；<25 屬「limited experience」 [GL§1.2]
- **關鍵事實**：KDIGO ≥20 的證據主體是 **EMPA-KIDNEY（class-level）**；**dapagliflozin 沒有 eGFR 20–25 的隨機起始資料**；DAPA-CKD stage 4 次族群主要終點降低 27%（95% CI **−2 至 47**），**CI 跨越無效線**，p-interaction 0.22 `[ledger:C4]`[CONTROVERSIES C2]
- **裁定措辭（C2）**：「eGFR 22 的病人是 **shared-decision 地帶**」——並且必須區分「**起始**」與「**續用**」：續用 <25 已有 US 仿單 rev 06/2026 §2.3 **肯定性條款**支持；<20 續用至透析或移植為 KDIGO practice point [GL§2.1]（DECISION_LOG D16）
- ⚠️TW 台灣給付面：NHI CKD 適應症條件為 **eGFR 25–60＋uACR 200–5000＋整合照護方案收案；eGFR <15 停止給付**（114/3/1 版本）——**給付 ≠ 適應症 ≠ 實證邊界，三層必須分開講**；引用時點須再獨立查證 [SF§13]（DECISION_LOG D3；EVIDENCE_GAPS G13）
- 🎤 講者提示：這張要慢——大部分聽眾以為「指引說可以就是仿單說可以」。

### S19｜懸崖底下：透析、移植、ADPKD ⟨探索性⟩ [31:45–33:30]
- **透析**：DARE-ESKD-2（n=80，24 週，開放標籤盲評）——主要終點 NT-proBNP 校正後組間差 **−155 pg/ml（95% CI −327 至 −33）但 P=0.065，未達顯著**；KCCQ／6 分鐘走路／心超皆中性；安全性無差異 `[ledger:D5]`[FR§7]
  - ⚠️ CI 與 P 值不一致須同時註記（DECISION_LOG D9）；措辭：**「安全但未證實 surrogate 改善」**，不可說「已證明透析無效」`[ledger:D5]`
  - 反向的觀察級訊號：DAPA-CKD 試驗中開始透析者之事後分析（n=167）全因死亡 aHR 0.47（0.23–0.98），**由非 CV 死亡驅動——觀察性等級，僅供產生假說**（DECISION_LOG D10）[FR§6]
- **腎移植**：INFINITI（n=52，12 週，雙盲）——主要終點坐姿收縮壓**未達顯著**，第 12 週 −2.9 mmHg（−8.9 至 3.1），P=0.33；GFR dip 現象保留；12 週安全性乾淨 `[ledger:D6]`[FR§8]
  - 措辭：**機轉與短期安全資料；無臨床結局證據**。52 人 12 週不能排除感染風險，更不能證明保護 graft（EVIDENCE_GAPS G3）
- **ADPKD**：唯一 RCT 為 Uchiyama 交叉試驗（n=27，tolvaptan 使用者，開放標籤，6 個月交叉）——eGFR slope **+2.57 vs −5.65 mL/min/1.73 m²/年，P=0.002**；TKV **−0.44% vs +5.04%，P=0.01** `[ledger:D7]`[FR§9]
  - **裁定措辭（C8）**：生物學合理、訊號早期、方向曾不一致（既往 TKV 增加之個案訊號與 vasopressin 機轉疑慮必須並陳）——**非已證實之 ADPKD 治療**（DECISION_LOG D17）
- 🎤 講者提示：三個族群、三種「不知道」——中性 surrogate、機轉資料、方向衝突的小試驗，性質不同不能混講。

### S20｜懸崖上的那一個試驗：Renal Lifecycle ⟨探索性／待讀出⟩ [33:30–35:00]
- NCT05374291：實用型、國際、研究者發起、**雙盲**、事件驅動（468 個首次主要事件；80% power 偵測 25% RRR）[FR§6]
- 納入三個族群於同一試驗：**eGFR ≤25**、**透析中（HD/PD）**、**腎移植且 eGFR ≤45**；計畫約 1,500 人 [FR§6]
- 主要複合終點：心衰住院、全因死亡、或（非透析者之）腎衰竭 [FR§6]
- **截至 2026-08-27 尚無主要結果發表或完整結果presentation**；其心臟影像子研究設計論文仍將此族群之心血管保護描述為「to be established」（DECISION_LOG D15）[FR§6]
- 它同時回答 EVIDENCE_GAPS 的 **G1（eGFR <20–25 起始）、G2（透析硬結局）、G3（腎移植硬結局）**——是 Director watch-list 第一順位
- 🎤 講者提示：告訴聽眾「今天這一段的答案，兩年內會改寫」——這是誠實，也是最好的收束。

`[CASE-4 → talk/CLINICAL_CASES.md]` **第 34 分鐘 · 聽眾投票（~1 min）**

---

# 段落 6｜安全性：三個必須帶走的原則（35–39 分鐘，4 min）

### S21｜euDKA：包含非糖尿病使用者 ⟨安全原則⟩ [35:00–36:20]
- **T2D 長期使用**：DECLARE-TIMI 58 裁定事件 DKA **0.3% vs 0.1%（27 vs 12 例）**，HR 2.18（1.10–4.30）⚠️（HR/CI 取自開放取用轉載，全文核對中）——**風險約增一倍，但 4.2 年絕對風險 <0.5%** `[ledger:A4]`（DECISION_LOG D13）
- **觀察性一致（class-level 與分子別並陳）**：CNODES 世代 vs DPP-4i——**SGLT2i 類別** HR 2.85（1.99–4.08）；**dapagliflozin 分子別** HR 1.86（1.11–3.10）[SF§1]
- **非糖尿病使用者**：DAPA-CKD 非糖尿病層（1,398 人）**0 例**；DAPA-HF 非糖尿病層（2,605 人）**0 例**——但上市後**個案報告已證實可發生**，共同誘因為**攝食下降**，治療核心為**葡萄糖供給**（幾乎不需胰島素）`[ledger:E2]`[SF§2]
- 措辭紀律：**「試驗中未見，上市後個案已見——機率低但表現易被忽略」**；**不可說「非糖尿病不會發生酮酸中毒」**，也不可用個案估算發生率 `[ledger:E2]`（DECISION_LOG D14）
- 診斷陷阱：**血糖 <250 mg/dL 不排除 DKA**；不明原因陰離子間隙代謝性酸中毒即使已有 AKI 或敗血症可解釋，仍應測血酮再歸因 [SF§1]
- 🎤 講者提示：這一句要對麻醉科與急診同仁講——他們是最常第一個看到 euDKA 的人。

### S22｜圍術期：各國規則不一致，血酮才是安全網 ⟨安全原則⟩ [36:20–37:50]

| 權威 | 擇期手術停藥規則 | 性質 |
|---|---|---|
| US FDA 仿單 §2.4 | 「at least 3 days」（至少 3 天） | label |
| ADA Standards of Care 2026 §16 | 「held for **3–4 days**」（ertugliflozin 4 天） | 指引 |
| 英國多學會共識（Anaesthesia 2025） | 「omitted **the day before and the day of** a procedure」（約 36–52 小時） | 共識 |
| 澳紐 ADS/ADEA/ANZCA/NZSSD（2023-05） | 「at least 3 days（術前 2 天＋當日）」；日間手術僅停當日 | 共識 |
| ⚠️TW 台灣 TFDA 仿單（2024-04-10 版） | 「至少3天前暫時中斷」 | label |
| ⚠️TW 台灣 MOHW TPR No.186（2024-12） | 大手術 72 小時；小手術／局麻 24–48 小時；需禁食內視鏡 24 小時 | 病安通報系統建議 |

- **無任何比較性研究界定最適停藥天數**（ADA 2026 自承）；**停藥期是風險降低手段，不是安全保證** `[ledger:E3]`（EVIDENCE_GAPS G9）
- 反例：仿單載明停藥後**尿糖持續 3 天、上市後報告超過 6 天、最長 2 週**；個案顯示**停藥 5 天後仍發生術後 euDKA**、**停藥第 8 天復發** `[ledger:E3]`[SF§5]
- **可操作的安全網**：術日晨測指尖血酮（β-hydroxybutyrate）——即使血糖正常也要測；ADS/ANZCA 行動閾值 **1.0 / 1.7 mmol/L**（血酮 >1.0 且 BE <−5 推定 DKA；無血氣可用且血酮 >1.0 則不應進行手術）[SF§ 圍術期流程 §2]
- 措辭紀律：**不可把 3 天描述為經證實之安全界線** `[ledger:E3]`
- ⚠️TW 台灣兩列須於引用時點再獨立查證（DECISION_LOG D3）
- 🎤 講者提示：表格不要逐列唸——直接說「五個權威、三種天數、零個比較性試驗」，然後跳到血酮。

### S23｜起始後的 eGFR dip 不是 AKI ⟨安全原則⟩ [37:50–39:00]
- **預期幅度**：DAPA-HF 起始後 2 週 eGFR 變化 **−4.2（95% CI −4.6 至 −3.9）vs placebo −1.1**；DAPA-CKD 急性 dip **2.61（T2D）／2.01（非 T2D）mL/min/1.73 m²** `[ledger:C5]`[SF§8]
- **dip 不預示較差結局**：DAPA-HF 中 >10% dip 者主要結局 **HR 0.73（0.59–0.91）**——效益保留；DAPA-CKD 總 eGFR slope 差 **+0.95（0.63–1.27）mL/min/1.73 m²/年** 有利 dapagliflozin `[ledger:C5]`
- **AKI 不增加、反而較少**：DECLARE HR 0.69（0.55–0.87）⚠️（轉載值待核）；**class-level（SGLT2i 類別）** SMART-C 統合 AKI **RR 0.77（0.70–0.84）** `[ledger:E4]`[LM§6.4]
- **KDIGO 2024 practice point**：可逆性 dip 是預期現象，**一般不是停藥指徵**；起始後**不需增加監測頻率** [GL§2.1]
- 何時該查：**>30% 下降或持續下降**——找容積狀態、併用藥物、其他病因；例外警訊為脫水下之滲透性腎病變（個案層級） `[ledger:C5,E4]`
- 措辭紀律：**不可說「eGFR 下降代表腎損傷、應停藥」** `[ledger:C5]`
- 🎤 講者提示：這是門診端最常見的錯誤停藥原因，值得用最後 20 秒重複一次。

---

# 段落 7｜收尾（39–40 分鐘，1 min）

### S24｜What dapagliflozin has NOT yet proven ⟨必備投影片｜標題不得更動⟩ [39:00–39:45]

| 未證實的主張 | 現有最佳證據 | 缺口性質 |
|---|---|---|
| **MACE reduction** | DECLARE MACE HR 0.93（0.84–1.03），p=0.17（非劣性達成）`[ledger:A1]` | 已測未證 |
| **Mortality in HFpEF alone（單一試驗層級）** | DELIVER CV death HR 0.88（0.74–1.05），單獨不顯著；死亡率主張須引 Jhund pooled（CV death 0.86, 0.76–0.97）`[ledger:B3,B4]` | 已測未證（單試驗） |
| **Post-MI hard outcomes** | DAPA-MI CV death/HHF HR 0.95（0.64–1.40）`[ledger:D4]` | 已測未證（negative-evidence floor，G6） |
| **Dialysis / transplant / ADPKD efficacy** | DARE-ESKD-2 中性 surrogate（P=0.065）；INFINITI 12 週機轉；Uchiyama n=27 surrogate `[ledger:D5,D6,D7]` | 僅 surrogate／未測（G2–G4） |
| **Initiation below eGFR 25（dapagliflozin 專屬）** | 無隨機起始資料；DAPA-CKD stage 4 次族群 27%（CI −2 至 47）；KDIGO ≥20 之證據主體為 class-level `[ledger:C4]` | 未測（agent-specific，G1） |
| **In-hospital-initiation hard benefit（agent-specific）** | DAPA ACT 主要終點 HR 0.86（0.68–1.08），P=0.20；早期效益為 class-level 統合主張（HR 0.71；TSA RR 0.61）`[ledger:D1,F4]` | 已測未證＋僅類別（G5） |

- 🎤 講者提示：這張是全場的良心——逐列唸完，不要跳過任何一列。

### S25｜三句話結束 [39:45–40:00]
1. Dapagliflozin 治療的是**心衰／腎臟軌**，不是動脈粥狀硬化軌——**MACE-neutral 從來不是失敗**
2. 每個陽性複合終點都要問**「誰在驅動」**；每個統合數字都要問**「這是 class 還是 agent」**
3. 藥的邊界不是模糊地帶，而是**可以指名道姓的六件事**——它們寫在上一張投影片上
- 🎤 講者提示：不做「未來展望」——最後停在 Renal Lifecycle 已經給過的那句「兩年內會改寫」。

---

## 附錄：講者自查清單（上台前 5 分鐘）

- [ ] 每個統合分析數字都念出了 **class-level** 或 **dapagliflozin 專屬**？（S3、S7、S12、S21、S23）
- [ ] 每個陽性複合終點都說了**驅動分項**？（S2、S4、S6、S9、S14、S16）
- [ ] 所有台灣給付／法規內容都標了 **⚠️TW** 並說明「須於引用時點再查證」？（S18、S22）
- [ ] 沒有把 subgroup 估計講成已證實之交互作用？（S5、S8、S9、S18）
- [ ] 沒有把 surrogate 改善講成臨床結局獲益？（S13、S19、S23）
- [ ] 沒有把 case report 講成發生率或比較性安全證據？（S21、S22）
- [ ] `What dapagliflozin has NOT yet proven` 這張**沒有被時間壓縮掉**？

## 附錄：本大綱之待決項（隨 auditor 裁定同步修訂）

| 影響投影片 | 項目 | 狀態 |
|---|---|---|
| S21、S23 | DECLARE 安全表 HR（DKA 2.18、AKI 0.69）取自 PMC6683461 轉載 | OPEN — DECISION_LOG D13／CONTROVERSIES C9 |
| S19 | DARE-ESKD-2 之 CI 與 P 值不一致 | CLOSED — auditor 證實分歧存在於原文摘要（不同統計程序）；以作者 P 值結論（中性）為準，引用時兩者並陳（DECISION_LOG D9） |
| S22 | FDA 仿單版次（06/2026 vs DailyMed 10/2024） | OPEN — DECISION_LOG D16（引用章節而非版次） |
| S23 | Jongs JASN 2022 之 prespecified／post hoc 屬性 | OPEN — auditor |
