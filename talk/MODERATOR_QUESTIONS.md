# MODERATOR QUESTIONS — 演講後 Panel 討論十問

維護：dapa-research-director（drafting subagent）。
上游：`synthesis/CLAIMS_LEDGER.md`、`synthesis/CONTROVERSIES.md`、`synthesis/EVIDENCE_GAPS.md`、
`synthesis/MASTER_SYNTHESIS.md`、`dapa Q 202608.md` §三。
規則：本檔所有數字與措辭均取自 CLAIMS_LEDGER / CONTROVERSIES，行內以
`<!-- src:synthesis/{檔名}#{條目} -->` 標註可回溯位置；未在上游帳冊出現的數字一律不得出現於此檔。

設計意圖：每題都是「證據層級辨識題」——迫使與談人在回答中主動說出
「這是主要終點／次級終點／預先規劃次族群／post hoc／surrogate／觀察性／類別層級」。
主持人不需要自己判對錯，只需追問「這是哪一層的證據？」

---

## Q1. DECLARE 的 MACE 中性，該怎麼稱呼這個藥？

**問題本文**
DECLARE-TIMI 58 的 MACE 是 HR 0.93（0.84–1.03）、p=0.17，也就是優越性未達而非劣性達成；
在這個前提下，您在門診跟病人、跟同事介紹 dapagliflozin 時，還會不會用「心血管保護藥」這五個字，
如果會，您保護的是哪一條軌？ <!-- src:synthesis/CLAIMS_LEDGER.md#A1 -->

**主持人追問**
1. 如果一位 T2D 病人問「這個藥可以防我中風嗎」，您的第一句話怎麼講？
2. Zelniker 的 ASCVD／非 ASCVD 分層，是否足以讓您對「已有動脈粥狀硬化的病人」講不同的話？

**理想答案要點**
- 主要終點層級：DECLARE 共同主要終點之一 MACE（CV death/MI/缺血性中風）8.8% vs 9.4%，
  HR 0.93（0.84–1.03），p=0.17；正確講法是「MACE 未顯著下降」，並補上「非劣性達成」這半句。
  <!-- src:synthesis/CLAIMS_LEDGER.md#A1 -->
- 另一個共同主要終點才是陽性：CV death/HHF 4.9% vs 5.8%，HR 0.83（0.73–0.95），p=0.005，
  且完全由 HHF（HR 0.73, 0.61–0.88）驅動，CV death 單獨中性（HR 0.98, 0.82–1.17）。
  <!-- src:synthesis/CLAIMS_LEDGER.md#A2 -->
- 一句話定位：治療的是「心衰／腎臟軌」，不是「動脈粥狀硬化軌」。
  <!-- src:synthesis/MASTER_SYNTHESIS.md#1 -->
- 若要談 ASCVD 分層，必須標明是 **類別層級**：Zelniker 2019，ASCVD HR 0.86（0.80–0.93）
  vs 無 ASCVD 1.00（0.87–1.16），p-int 0.0501——而且 p-int 落在邊界，是分層觀察不是證實的交互作用。
  <!-- src:synthesis/CLAIMS_LEDGER.md#F1 -->
- 次級腎臟終點確實下降：cardiorenal 複合 HR 0.76（0.67–0.87），renal-specific 0.53（0.43–0.66），
  但 ESRD/renal death 僅 11 vs 27 事件，屬 prespecified secondary。
  <!-- src:synthesis/CLAIMS_LEDGER.md#A3 -->

**陷阱**
與談人容易滑向 ❌「dapagliflozin 預防心肌梗塞／中風」<!-- src:synthesis/CLAIMS_LEDGER.md#A1 -->，
或用陽性複合去講 ❌「降低心血管死亡」（DECLARE 層級）<!-- src:synthesis/CLAIMS_LEDGER.md#A2 -->。
另一種常見誤用是把 Zelniker 的類別數字冠名 dapagliflozin——❌ 不得冠名，一律標示 class-level。
<!-- src:synthesis/CLAIMS_LEDGER.md#F -->

---

## Q2. HbA1c 已達標的 T2D，什麼風險才構成「現在就開始」？

**問題本文**
一位 HbA1c 6.8%、只用 metformin 的 T2D 病人坐在您面前，血糖沒有加藥的理由——
請具體說出**哪一個可測量的心腎特徵**會讓您今天就加上 dapagliflozin，並說明您援引的是哪一個試驗的納入條件，
而不是「風險高」這種印象式判斷。 <!-- src:synthesis/CLAIMS_LEDGER.md#C1 -->

**主持人追問**
1. 這位病人 UACR 是 80 mg/g、eGFR 68——您還開嗎？您的證據在哪裡？
2. 台灣健保給付條件跟您剛才講的臨床適應症，落差在哪一段？

**理想答案要點**
- 起始理由來自器官保護軌，不是血糖軌：教學句是
  「Glycemic efficacy declines before cardiorenal efficacy disappears——HbA1c 降不多不等於藥物無效」；
  eGFR <45 降糖效果明顯減弱，但器官保護在試驗下限 25 仍成立。
  <!-- src:synthesis/MASTER_SYNTHESIS.md#2.4 -->
- 最強的起始依據是**蛋白尿 CKD**：DAPA-CKD n=4,304，納入 eGFR 25–75、UACR 200–5000，
  主要複合 9.2% vs 14.5%，HR 0.61（0.51–0.72），NNT 19（15–27），中位追蹤 2.4 年（提前中止）。
  <!-- src:synthesis/CLAIMS_LEDGER.md#C1 -->
- 全因死亡亦下降（次級終點）：4.7% vs 6.8%，HR 0.69（0.53–0.88），p=0.004。
  <!-- src:synthesis/CLAIMS_LEDGER.md#C2 -->
- 器官保護與糖尿病狀態脫鉤：DAPA-CKD T2D 層 HR 0.64（0.52–0.79）、非 T2D 層 0.50（0.35–0.72），
  p-int 0.24（預先規劃次族群）。可講「器官保護與降血糖脫鉤」。
  <!-- src:synthesis/CLAIMS_LEDGER.md#C3 -->
- UACR 80 的病人在 DAPA-CKD 納入條件之外——這是外推區，
  ❌ 不得外推至非蛋白尿 CKD。可以講的是 T2D 族群的 CV death/HHF 與次級腎臟終點（Q1 之數字）。
  <!-- src:synthesis/CLAIMS_LEDGER.md#C1 -->
- 台灣端：NHI §2.16（114/3/1）給付要求 eGFR 25–60 ＋ uACR 200–5000 ＋整合方案，eGFR<15 停付；
  「給付 ≠ 適應症 ≠ 實證邊界」三層要分開講，且此為 ⚠️TW 項目，引用時點須再獨立查證。
  <!-- src:synthesis/EVIDENCE_GAPS.md#G13 -->

**陷阱**
把 DAPA-CKD 的 NNT 19 套到所有 CKD 病人身上——這違反
❌「外推至非蛋白尿 CKD、eGFR<25、透析、移植、ADPKD」的禁令 <!-- src:synthesis/CLAIMS_LEDGER.md#C1 -->；
或把非 T2D 層點估計較低講成 ❌「非糖尿病獲益更大」（p-int 0.24，點估計差異非交互作用證據）。
<!-- src:synthesis/CLAIMS_LEDGER.md#C3 -->

---

## Q3. 對 HFpEF 病人，您賣的是「少住院」還是「多活幾年」？

**問題本文**
DELIVER 的主要複合 HR 0.82（0.73–0.92）是由 worsening HF（0.79）驅動、CV death 單獨 0.88（0.74–1.05）不顯著；
請您用**病人聽得懂的一句話**說出這個藥對 LVEF >40% 病人的承諾，並說清楚您那句話背後是單一試驗還是合併分析。
<!-- src:synthesis/CLAIMS_LEDGER.md#B3 -->

**主持人追問**
1. 如果病人的價值排序是「我不怕住院，我要活久一點」，您的建議會不會改變？
2. ESC 2023 給 Class I、AHA/ACC/HFSA 2022 給 Class 2a——這個差距要怎麼跟同事解釋？

**理想答案要點**
- 單一試驗可講的：DELIVER n=6,263（LVEF >40%、eGFR ≥25），16.4% vs 19.5%，
  HR 0.82（0.73–0.92），worsening HF 0.79（0.69–0.91），CV death 0.88（0.74–1.05）單獨不顯著，
  中位追蹤 2.3 年。✅ 措辭：「LVEF >40% 中減少心衰惡化事件；單一試驗未證明 CV 死亡下降」。
  <!-- src:synthesis/CLAIMS_LEDGER.md#B3 -->
- 死亡率主張必須改引 pooled：Jhund 2022 病人層級**預先規劃**合併分析（DAPA-HF+DELIVER, n=11,007），
  CV death HR 0.86（0.76–0.97）、all-cause 0.90（0.82–0.99）、total HF admissions RR 0.71（0.65–0.78）。
  死亡率一律引此，不引 DELIVER 單獨。 <!-- src:synthesis/CLAIMS_LEDGER.md#B4 -->
- 誠實版病人溝通句：「確定的是少住院、少惡化；死亡率下降來自合併分析、絕對獲益小」——
  病人價值排序（避免住院 vs 延長壽命）本身就是溝通重點。 <!-- src:synthesis/CONTROVERSIES.md#C3 -->
- 指引差異主要是 vintage 差異（ESC 2023 vs AHA/ACC/HFSA 2022），不是證據本身相反。
  <!-- src:synthesis/CONTROVERSIES.md#C3 -->
- 順帶界定：HFpEF 族群**沒有**腎臟硬終點保護——DELIVER kidney composite HR 1.08（0.79–1.49），
  只能講 eGFR slope 改善（surrogate）。 <!-- src:synthesis/CLAIMS_LEDGER.md#B6 -->

**陷阱**
❌「DELIVER 證明 HFpEF 死亡率下降」<!-- src:synthesis/CLAIMS_LEDGER.md#B3 -->——
把 pooled 的 0.86 講成 DELIVER 的結果，或反過來用 DELIVER 的 0.88 否定 pooled。
另一個陷阱是用 slope 改善宣稱腎保護：❌ 以 slope 改善宣稱腎保護。
<!-- src:synthesis/CLAIMS_LEDGER.md#B6 -->

---

## Q4. 專屬試驗陰性、類別統合陽性——出院前您開不開？

**問題本文**
DAPA ACT HF-TIMI 68 是這個問題上**最大的、也是唯一 agent-specific 的**試驗，主要終點未達
（HR 0.86, 0.68–1.08, P=0.20）；同一篇內嵌的類別統合卻是 HR 0.71，J Card Fail 2026 的 TSA
更給 all-cause RR 0.61 且判定為 firm——請問您在出院醫囑上落筆時，採哪一層證據，理由是什麼？
<!-- src:synthesis/CLAIMS_LEDGER.md#D1 -->

**主持人追問**
1. 「統合裡包含 open-label 小試驗、追蹤 ≤2 個月」這件事，會不會改變您的權重？
2. 如果您決定開，您跟病人說的獲益是「這個藥」的獲益，還是「這一類藥」的獲益？

**理想答案要點**
- 主要終點層級：DAPA ACT n=2,401 急性 HF 住院（71.5% LVEF≤40%），
  2 個月複合 10.9% vs 12.7%，HR 0.86（0.68–1.08），P=0.20——**主要終點未達**。
  <!-- src:synthesis/CLAIMS_LEDGER.md#D1 -->
- all-cause death HR 0.66（0.43–1.00）是**次級／假說產生**層級，不可獨立宣稱效益。
  <!-- src:synthesis/CLAIMS_LEDGER.md#D1 -->
- ✅ 標準答法要拆成兩句：「住院內起始『安全、可行』有專屬 RCT 支持；
  『早期硬結局效益』目前是類別層級統合的主張」——兩句話分開講。
  <!-- src:synthesis/CONTROVERSIES.md#C1 -->
- 類別層級數字須標名：embedded meta HR 0.71（0.54–0.93）；J Card Fail 2026 TSA all-cause RR 0.61（0.47–0.81）。
  <!-- src:synthesis/CLAIMS_LEDGER.md#F4 -->
- 反方論據也要說得出來：最大的單一試驗即 DAPA ACT 本身且中性；統合含 open-label 小試驗、
  追蹤 ≤2 月；agent-specific 的硬結局證據不存在。 <!-- src:synthesis/CONTROVERSIES.md#C1 -->
- 缺口定性：這是「已測未證（主要終點）＋僅類別（統合）」，且目前沒有新的 dapagliflozin
  急性 HF 結局試驗會來補。 <!-- src:synthesis/EVIDENCE_GAPS.md#G5 -->

**陷阱**
兩個方向都是過度解讀：❌「DAPA ACT 證明早期死亡效益」（拿次級 0.66 當結論），
以及 ❌「陰性故應放棄住院起始」（把主要終點未達講成證明無效）。
<!-- src:synthesis/CLAIMS_LEDGER.md#D1 -->

---

## Q5. 「住院內開始」的最低穩定條件，是規則還是習慣？

**問題本文**
請您具體列出您心中「可以在住院期間起始」的門檻——收縮壓、是否已停 IV inotrope、利尿劑仍在靜脈或已轉口服、
腎功能下限——然後請誠實回答一個後設問題：這些數字有沒有任何一個是**隨機分派研究界定**出來的？
<!-- src:synthesis/CONTROVERSIES.md#C1 -->

**主持人追問**
1. 症狀性低血壓在 DAPA ACT 是 3.6% vs 2.2%——這個差距會不會改變您在 SBP 100 的病人身上的決定？
2. 如果病人今天還在靜脈利尿劑，您是「現在開」還是「出院當天開」？兩者的證據差別在哪？

**理想答案要點**
- 誠實前提：啟動門檻（血壓、停 inotrope、容積狀態）是**沿用試驗納入條件**，
  ❌ 不得宣稱有 RCT 界定的最低穩定標準。 <!-- src:synthesis/CONTROVERSIES.md#C1 -->
- 可引用的邊界來自各試驗的排除條件，而非療效比較：DAPA-HF 排除 eGFR<30、SBP<95（⚠️ 待全文核）；
  其適用族群是門診慢性 HFrEF，不含急性失代償、hypotensive、eGFR<30。
  <!-- src:synthesis/CLAIMS_LEDGER.md#B1 -->
- 住院端的安全數據來自 DAPA ACT：symptomatic hypotension 3.6% vs 2.2%——
  這是可講的安全性觀察，不是療效門檻。 <!-- src:synthesis/CLAIMS_LEDGER.md#D1 -->
- 利尿情境的證據停在 surrogate：DICTATE-AHF 主要利尿效率終點未達，OR 0.65（0.41–1.02），P=0.06；
  次級 decongestion surrogates 正向。✅「支持早期使用之安全性與利尿增益（surrogate）」。
  <!-- src:synthesis/CLAIMS_LEDGER.md#D2 -->
- 支持住院內起始的另一條論證是 therapeutic inertia（出院處方率），屬實務論證而非療效證據。
  <!-- src:synthesis/CONTROVERSIES.md#C1 -->

**陷阱**
把 DICTATE-AHF 的 decongestion surrogate 當臨床結局——❌ 不得當作臨床結局證據
<!-- src:synthesis/CLAIMS_LEDGER.md#D2 -->；
以及把個人習慣的門檻（例如「SBP 一定要 >110」）講成試驗界定的標準，
違反 C1「不得宣稱有 RCT 界定的最低穩定標準」。 <!-- src:synthesis/CONTROVERSIES.md#C1 -->

---

## Q6. DapaTAVI 之後，TAVI 病房要不要改成常規開藥？

**問題本文**
DapaTAVI 的複合終點是陽性的（15.0% vs 20.1%，HR 0.72, 0.55–0.95），
但納入的是**高心衰風險**的 TAVI 後病人、開放標籤、單一國家——
請問您會把這個結果用在哪些病人身上、明確排除哪些病人，
以及在 82–85 歲族群您怎麼跟 NNT 與 NNH 同時對話？ <!-- src:synthesis/CLAIMS_LEDGER.md#D3 -->

**主持人追問**
1. 死亡率跟 KCCQ 在這個試驗的結果是什麼？您跟病人談獲益時會不會提到「生活品質沒有增益」？
2. 一位剛做完 TAVI、沒有心衰病史、腎功能正常的低風險病人，您的答案一樣嗎？

**理想答案要點**
- 可講的：n=1,222 高 HF 風險 TAVI 後（西班牙、open-label），1 年複合 15.0% vs 20.1%，
  HR 0.72（0.55–0.95）；驅動者是 worsening HF，subHR 0.63（0.45–0.88）。
  ✅「高風險 TAVI 後降低死亡或心衰惡化複合，由心衰惡化驅動」。
  <!-- src:synthesis/CLAIMS_LEDGER.md#D3 -->
- 不可講的：all-cause death HR 0.87（0.59–1.28）未達顯著；KCCQ 無增益；
  genital infection 與 hypotension 較多。 <!-- src:synthesis/CLAIMS_LEDGER.md#D3 -->
- 適用邊界的裁定措辭：「支持『符合 DapaTAVI 入選條件的高風險 TAVI 後病人』起始；
  不支持全體 TAVI 常規。」 <!-- src:synthesis/CONTROVERSIES.md#C5 -->
- 機轉層次的說明句：介入已除瓣膜阻塞，殘餘心衰風險（纖維化、HFpEF 生理、AF、CKD）才是治療標的。
  <!-- src:synthesis/CONTROVERSIES.md#C5 -->
- 缺口定性：全體 TAVI 與介入前重度 AS 屬「未測」，且沒有試驗在路上——不外推。
  <!-- src:synthesis/EVIDENCE_GAPS.md#G7 -->

**陷阱**
❌「降低 TAVI 後死亡率」，以及外推至全體 TAVI 或未處理之重度 AS。
<!-- src:synthesis/CLAIMS_LEDGER.md#D3 -->
在 82–85 歲族群只講 NNT 不講 NNH（低血壓、生殖器感染）同樣是選擇性呈現。
<!-- src:synthesis/CONTROVERSIES.md#C5 -->

---

## Q7. Win ratio 1.34：統計陽性，臨床上陽性在哪裡？

**問題本文**
DAPA-MI 的 win ratio 是 1.34（1.20–1.50），聽起來是一個乾淨的陽性試驗；
但同一批病人的 CV death/HHF 是 HR 0.95（0.64–1.40）——
請您解釋這兩個數字為什麼可以同時存在，並回答：這樣的陽性足不足以改變 post-MI 的 standard care？
<!-- src:synthesis/CLAIMS_LEDGER.md#D4 -->

**主持人追問**
1. 階層複合把死亡與 ≥5% 減重放進同一個終點，您接受嗎？
2. 如果您真的要在 post-MI 病人開這個藥，您開的理由是心血管適應症還是代謝適應症？

**理想答案要點**
- 族群限定：n=4,017 急性 MI、**無糖尿病、無慢性心衰**。
  <!-- src:synthesis/CLAIMS_LEDGER.md#D4 -->
- 兩層數字並陳：win ratio 1.34（1.20–1.50）；CV death/HHF HR 0.95（0.64–1.40）；
  新發 T2D 於 prediabetes 層 HR 0.74（0.55–0.99）但屬 **post hoc**。
  <!-- src:synthesis/CLAIMS_LEDGER.md#D4 -->
- ✅ 正確措辭：「改善 cardiometabolic 結果（防新發糖尿病、減重）；未降低 CV death/HHF」。
  <!-- src:synthesis/CLAIMS_LEDGER.md#D4 -->
- 方法學要點要說得出來：階層複合把死亡與 ≥5% 減重放同一終點、分析計畫期中修改、
  驅動者是低階層 cardiometabolic 分項。 <!-- src:synthesis/CONTROVERSIES.md#C4 -->
- 定性一句：Statistically positive ≠ hard-outcome positive；DAPA-MI 支持的是 post-MI 病人的
  代謝風險管理，不是心血管二級預防適應症。 <!-- src:synthesis/CONTROVERSIES.md#C4 -->
- 缺口性質特別註明：G6 是 **negative-evidence floor，不是 data gap**——
  不能用「還沒研究清楚」去替效益留門。 <!-- src:synthesis/EVIDENCE_GAPS.md#G6 -->

**陷阱**
❌「DAPA-MI 顯示心血管保護」<!-- src:synthesis/CLAIMS_LEDGER.md#D4 -->。
次一級的陷阱是把 post hoc 的 prediabetes 層 HR 0.74 當成預先規劃的次族群結論。
<!-- src:synthesis/CLAIMS_LEDGER.md#D4 -->

---

## Q8. eGFR 掉多少還可以繼續？什麼時候該懷疑是別的事？

**問題本文**
起始後兩週回診，eGFR 從 42 掉到 36——請您當場說出您的處置，
並說明您用來判斷「這是預期的血行動力學 dip」而不是「真正腎損傷」的**具體門檻與檢查**，
以及您援引的是試驗數據還是指引的 practice point。 <!-- src:synthesis/CLAIMS_LEDGER.md#C5 -->

**主持人追問**
1. 如果 dip 超過 10%，長期結局是不是比較差？您有數字嗎？
2. 什麼情況下您真的會停藥，而不是繼續觀察？

**理想答案要點**
- 預期幅度的數字：DAPA-CKD 2 週 dip −2.61（T2D）／−2.01（非 T2D）；DAPA-HF −4.2 vs −1.1；
  總 slope +0.95/年。實務上可講「預期 −2 至 −4 mL/min」。
  <!-- src:synthesis/CLAIMS_LEDGER.md#C5 --> <!-- src:synthesis/MASTER_SYNTHESIS.md#3 -->
- 大於 10% 的 dip 結局不劣：HR 0.73（0.59–0.91）——注意此為 **post hoc** 層級
  （Adamson 2022；Jongs 2022 屬性 ⚠️ 待核）。 <!-- src:synthesis/CLAIMS_LEDGER.md#C5 -->
- ✅ 措辭：「預期性 dip 非停藥指徵（KDIGO practice point）；持續或 >30% 下降須找其他原因」；
  實務上要查容積狀態、併用藥（利尿劑／RASi／NSAID）與其他病因。
  <!-- src:synthesis/CLAIMS_LEDGER.md#C5 --> <!-- src:synthesis/MASTER_SYNTHESIS.md#3 -->
- AKI 的方向要講清楚：DECLARE AKI HR 0.69（0.55–0.87）⚠️（轉載來源，待全文核）；
  類別層級 SMART-C RR 0.77（0.70–0.84）。✅「大型試驗未見 AKI 增加；class 統合顯示 AKI 較少」。
  <!-- src:synthesis/CLAIMS_LEDGER.md#E4 -->
- 個案層級的例外（滲透性腎病變）只能當 teaching signal，不能當發生率。
  <!-- src:synthesis/CLAIMS_LEDGER.md#E4 -->

**陷阱**
❌「eGFR 下降代表腎損傷、應停藥」<!-- src:synthesis/CLAIMS_LEDGER.md#C5 -->；
反向的陷阱是把「dip 不預示較差結局」講成「怎麼掉都不用管」——
>30% 或持續下降仍須查因。 <!-- src:synthesis/MASTER_SYNTHESIS.md#3 -->

---

## Q9. 透析與腎移植：小型安全性研究能不能撐起 off-label？

**問題本文**
DARE-ESKD-2 收 80 位慢性透析病人做 24 週、INFINITI 收 52 位穩定腎移植受者做 12 週，
兩者都「安全」但主要終點都沒有達成——
請問「安全但無效」與「安全所以可以試試看」之間，您劃在哪裡，
以及您會用什麼理由跟病人解釋這是 off-label？ <!-- src:synthesis/CLAIMS_LEDGER.md#D5 -->

**主持人追問**
1. DAPA-CKD 那個 dialysis-initiation 的 post hoc aHR 0.47，能不能拿來支持您的決定？
2. 如果病人自己讀到「SGLT2i 保護腎臟」而要求開，您怎麼談？

**理想答案要點**
- 透析：DARE-ESKD-2 n=80、24 週；NT-proBNP 差 −155 pg/ml（−327 至 −33）但**調整後 P=0.065**；
  KCCQ／6MWT／echo 均中性；安全。CI 與 P 不一致必須在引用該數字時一併註記。
  ✅「安全但未證實 surrogate 改善；硬終點待 Renal Lifecycle」。
  <!-- src:synthesis/CLAIMS_LEDGER.md#D5 -->
- 移植：INFINITI n=52、12 週；SBP 主要終點未達（wk12 −2.9，−8.9 至 3.1）；GFR dip 保留；短期安全。
  ✅「機轉與短期安全資料；無臨床結局證據」。 <!-- src:synthesis/CLAIMS_LEDGER.md#D6 -->
- 對稱的裁定句：「中性 surrogate ≠ 證明無效；觀察性死亡訊號 ≠ 證明有效。
  兩個都不能拿來做臨床決策；Renal Lifecycle 是唯一將回答此問題的試驗。」
  <!-- src:synthesis/CONTROVERSIES.md#C7 -->
- DAPA-CKD 透析起始 post hoc aHR 0.47 由 non-CV death 驅動，屬**觀察性級**，
  只能當假說產生，永遠不進入效益主張。 <!-- src:synthesis/EVIDENCE_GAPS.md#G2 -->
- 樣本量的誠實講法：「52 人 12 週不能排除感染風險，更不能證明保護 graft」。
  <!-- src:synthesis/EVIDENCE_GAPS.md#G3 -->
- Renal Lifecycle（NCT05374291）同時回答 eGFR ≤25／透析／移植三層；截至 2026-08-27 無主要結果。
  <!-- src:synthesis/EVIDENCE_GAPS.md#1 -->

**陷阱**
❌「已證明透析無效」或 ❌「DAPA-CKD 延伸至透析」——兩個相反方向都被禁止。
<!-- src:synthesis/CLAIMS_LEDGER.md#D5 -->
順帶一提 eGFR 20–25 的類似陷阱：KDIGO ≥20 的 1A 建議其證據主體是 EMPA-KIDNEY（類別），
dapagliflozin 沒有 20–25 的隨機起始資料，且「起始」與「續用」必須分開講。
<!-- src:synthesis/CONTROVERSIES.md#C2 -->

---

## Q10. 非糖尿病使用者要開刀了——誰負責提醒停藥、驗酮體、決定重開？

**問題本文**
一位因心衰或蛋白尿 CKD 而用藥、**沒有糖尿病**的病人下週要做手術：
請問在您的院內流程裡，是誰在術前門診說出「停三天」這句話、誰負責在術日早上驗血酮、
誰有權決定術後何時重啟——以及您剛才講的「三天」是哪一級的證據？
<!-- src:synthesis/CLAIMS_LEDGER.md#E3 -->

**主持人追問**
1. 如果這位病人同時在用 GLP-1 RA 或 tirzepatide，而且最近食慾很差，您的門檻會不會不同？
2. 病人血糖只有 180 mg/dL 而且沒有糖尿病史——這能不能讓您排除 DKA？

**理想答案要點**
- 規則層級要先講清楚：FDA/ADA/TFDA ≥3 天 vs 英國「術前一日＋當日」vs 澳紐「共 3 天」——
  這是 label／共識級，**最適天數無比較證據**。 <!-- src:synthesis/CLAIMS_LEDGER.md#E3 -->
- ✅ 核心措辭：「停藥期是風險降低而非保證；術日晨血酮是更可靠的安全網」；
  可搭配 ADS/ANZCA 行動閾值（1.0／1.7 mmol/L）。
  <!-- src:synthesis/CLAIMS_LEDGER.md#E3 --> <!-- src:synthesis/MASTER_SYNTHESIS.md#3 -->
- 藥效延長的事實：停藥後糖尿可持續 3 天、上市後報告至 2 週；個案顯示停藥 5 天後仍發生 euDKA。
  <!-- src:synthesis/CLAIMS_LEDGER.md#E3 -->
- 非糖尿病族群的風險定性：DAPA-CKD 非 DM 層 0 例、DAPA-HF 非 DM 層 0 例，
  但上市後個案已證實可發生（共同誘因為攝食下降；治療核心為給糖）。
  ✅「試驗中未見，上市後個案已見——機率低但表現易被忽略」。
  <!-- src:synthesis/CLAIMS_LEDGER.md#E2 -->
- 血糖不能用來排除：血糖 <250 mg/dL 不排除 DKA。 <!-- src:synthesis/MASTER_SYNTHESIS.md#3 -->
- 三個規則缺口要誠實承認：最適停藥天數無前瞻研究（ADA 自承）；DKA 後重啟無系統性證據、屬個別化決定；
  非糖尿病使用者的酮體篩檢策略指引未分化——實務作法是高風險情境（禁食／手術／攝食下降）主動驗血酮。
  <!-- src:synthesis/EVIDENCE_GAPS.md#G9 --> <!-- src:synthesis/EVIDENCE_GAPS.md#G10 --> <!-- src:synthesis/EVIDENCE_GAPS.md#G11 -->
- 合併 GLP-1 RA/tirzepatide 的 euDKA 目前只有個案叢集、無量化風險；
  實務提示為避免同日起始（case-signal 層級）。 <!-- src:synthesis/EVIDENCE_GAPS.md#G12 -->

**陷阱**
❌「非糖尿病不會發生酮酸中毒」，以及用個案去估發生率。
<!-- src:synthesis/CLAIMS_LEDGER.md#E2 -->
另一個是把三天講成經證實的安全界線——❌ 不得將 3 天描述為經證實之安全界線。
<!-- src:synthesis/CLAIMS_LEDGER.md#E3 -->

---

## 主持人用備忘（一頁）

| # | 題名 | 逼出的證據層級判斷 |
|---|---|---|
| Q1 | DECLARE MACE 中性下的藥物定位 | 共同主要終點之一為陰性；陽性複合的驅動分項；class-level 不冠名 |
| Q2 | HbA1c 已達標時的起始門檻 | 納入條件 vs 外推；預先規劃次族群 vs 交互作用；給付 ≠ 適應症 |
| Q3 | HFpEF 的價值主張 | 單試驗 vs 病人層級 pooled；surrogate slope 不等於腎保護 |
| Q4 | DAPA ACT 單試驗 vs 統合 | 主要終點未達 vs 次級死亡訊號；agent-specific vs class-level |
| Q5 | 住院內起始的最低穩定條件 | 試驗納入條件被誤當作 RCT 界定門檻；surrogate 利尿終點 |
| Q6 | DapaTAVI 的外推邊界 | 複合陽性 vs 分項；open-label 單一國家；NNT 與 NNH 並陳 |
| Q7 | DAPA-MI win ratio | 階層複合的驅動層；post hoc；negative-evidence floor |
| Q8 | 可接受的 eGFR dip | 預期血行動力學現象 vs 腎損傷；post hoc 結局分析；class-level AKI |
| Q9 | 透析／移植 off-label | 中性 surrogate 與觀察性訊號的雙向禁令；等待 Renal Lifecycle |
| Q10 | 非糖尿病者的圍術期責任鏈 | label／共識級規則 vs RCT；零事件 ≠ 零風險；個案不估發生率 |

> ⚠️ 標記說明：CLAIMS_LEDGER 中帶 ⚠️ 之數值（DECLARE 安全表 HR、DAPA-HF 排除條件、
> Jongs 2022 屬性、DARE-ESKD-2 之 CI/P 不一致、台灣 TFDA/NHI 條文時點）
> 尚待 methods auditor 或全文核對；主持人若追到這些數字，與談人應主動說明其來源層級。
> <!-- src:synthesis/MASTER_SYNTHESIS.md#5 -->
