# Dapagliflozin 臨床實作檢核表（Implementation Checklist）

> 檢索截止日 2026-08-27。供門診／住院起始與追蹤使用；每項附權威來源。
> 台灣健保給付項目以 ⚠️TW 標記——依專案規範，**台灣法規與給付項目須另行獨立查證**
> （官方 PDF 已存 `evidence/safety/sources/`，惟給付規定隨時修訂）。
> 圍術期與生病日之完整流程見 `PERIOPERATIVE_SICK_DAY_ALGORITHM.md`；
> 個案教學警訊見 `CASE_REPORT_FAILURE_MODES.md`；證據總表見 `SAFETY_EVIDENCE_MATRIX.md`。

---

## A. 起始前（Initiation checklist）

### A1. 適應症與腎功能門檻（美國 FDA 仿單 rev. 06/2026；台灣 TFDA 仿單 2024-04-10 同旨）
- [ ] 確認適應症：T2D 血糖控制／T2D 心血管風險降低／CKD／心衰竭（台灣仿單心衰竭適應症
      **無 LVEF 限制**，全 EF 範圍）。
- [ ] **血糖控制**目的：eGFR <45 不建議（機轉性無效；FDA "likely to be ineffective"、EMA：
      GFR <45 需考慮加其他降糖藥）。起始 5 mg 可上調 10 mg（血糖適應症）；其他適應症一律
      10 mg QD。
- [ ] **CKD／HF／CV** 目的：eGFR ≥25 直接用 10 mg QD；**eGFR <25 不建議起始**（FDA/EMA/TFDA
      一致），但治療中降至 <25 **可續用**（FDA §2.2/§2.3）。
- [ ] KDIGO 2024（與仿單不同、較寬）：eGFR ≥20 起始（Rec 3.7.1/3.7.2, 1A）；已用藥者
      即使 eGFR <20 亦合理續用直到透析或不耐受（Practice Point 3.7.1【verbatim 已核對】）。
- [ ] 排除：T1D（DKA 風險，FDA §5.1/EMA §4.4）；多囊腎；腎病正在或近期使用免疫抑制治療
      （FDA Limitation of Use；TFDA 仿單 §2.4 同）。
- [ ] 懷孕：第二、三孕期避免（TFDA 仿單 §6.1；FDA 8.1）。
- [ ] 嚴重肝功能不全：EMA 起始 5 mg（耐受再上調）；FDA 無劑量調整但要求個別風險效益評估
      ——兩仿單規定**不同**，向聽眾說明。

### A2. 容積與血壓
- [ ] 評估容積狀態；**容積不足者先矯正再起始**（FDA §2.1【verbatim 已核對】）。
- [ ] 高風險族群確認：eGFR <60、老年人、loop diuretic 使用者（FDA §5.2 列名之容積耗竭
      高風險群）；降壓藥多重併用、姿位性低血壓病史（EMA §4.4）。
- [ ] TSOC 2023 HF 共識實務門檻：SBP ≥95 mmHg、eGFR ≥20 可用（Acta Cardiol Sin 2023;39:361–390,
      DOI 10.6515/ACS.202305_39(3).20230301A；經 AI 摘要取得，逐字引用前宜核對原文）。

### A3. DKA 風險分層（EMA SmPC §4.4 高風險群【verbatim 已核對】＋ FDA §5.1）
- [ ] 低 β 細胞儲備：低 C-peptide、LADA、**胰臟炎或胰臟手術史**（EMA；FDA 亦列 pancreatic
      disorders 為危險因子）→ 慎用或避免；胰臟炎後糖尿病之個案警訊見 CASE_REPORT #20–21。
- [ ] 進食受限或嚴重脫水狀態、胰島素減量中、急病／手術／酗酒致胰島素需求上升（EMA）。
- [ ] 生酮／極低碳飲食（FDA §5.1 誘因列名；ADA 2026 rec 5.26/9.39 對高風險者勸阻生酮飲食
      ——該條文字經 Guideline Central 轉錄，引用前核對原文）。
- [ ] 併用 GLP-1 RA／tirzepatide 且攝食下降：**避免與 SGLT2i 同日同時起始**（個案警訊
      CASE_REPORT #16–18；無 RCT 證據，屬 case-report signal）。⚠️TW 注意：健保規定
      reimbursed GLP-1 RA 不得與 SGLT2i 併用（NHI §5.1.3.2），自費併用仍常見。
- [ ] 曾於 SGLT2i 治療中發生 DKA：原則**不重啟**，除非另有明確且已解除之誘因（EMA §4.4
      【verbatim 已核對】）。

### A4. 感染面
- [ ] 泌尿生殖道感染史（複發性 GU 感染者更易再發，FDA §5.3）；Fournier 壞疽衛教對象。
- [ ] 未控制之庫欣氏症等免疫受損狀態：個案警訊（CASE_REPORT #25）。

### A5. 低血糖共病用藥
- [ ] 併用胰島素或磺醯脲類：預先**減量**考量（FDA §5.4：\"a lower dose of insulin or insulin
      secretagogue may be required\"；TFDA 仿單 §5.1.4 同）。Dapagliflozin 單用不增加重度低血糖
      （試驗數據見 SAFETY_EVIDENCE_MATRIX.md）。

### A6. ⚠️TW 健保給付檢核（來源：NHI 藥品給付規定 §2.16（114/3/1 生效版）與 §5.1.5；
official PDF 已存 sources/；**引用前須再查證現行版本**）
- [ ] **HFrEF**（111/5/1 起）：NYHA II–IV＋LVEF ≤40%（一年內影像）＋ACEI/ARB＋β-blocker
      最大耐受劑量穩定 ≥4 週仍有症狀。
- [ ] **HFmrEF**（114/3/1 起）：NYHA II–IV＋LVEF 41–49%＋同上背景治療條件＋（曾因 HF 住院
      或經心臟專科醫師診斷 HF）。
- [ ] **CKD**（114/3/1 起）：限「初期 CKD 照護整合方案」或「Pre-ESRD 計畫」收案者＋最大
      耐受 ACEI/ARB 穩定 ≥4 週＋起始 eGFR 25–60＋uACR 200–5000 mg/g；排除 T1D、多囊腎、
      狼瘡性腎炎、ANCA 血管炎、6 個月內腎病免疫抑制治療、器官移植史、12 週內 AMI／不穩定
      心絞痛／中風／TIA／冠狀動脈血運重建。**治療中 eGFR <15 停止給付**。每日限 1 粒。
- [ ] **T2D**：限 metformin 最大耐受劑量仍控制不佳者；SGLT2i 與 DPP-4i 宜擇一使用
      （NHI §5.1）。
- [ ] 不符給付條件者：評估自費使用之臨床效益（仿單適應症較給付規定寬）。

---

## B. 起始時（衛教與處方）

- [ ] **DKA 症狀衛教**：噁心、嘔吐、腹痛、極度口渴、呼吸困難、意識混亂、異常倦怠——
      **血糖正常也可能是 DKA**（EMA §4.4【verbatim 已核對】；FDA §5.1：可 <250 mg/dL）。
- [ ] **生病日卡（SADMANS）**：嘔吐腹瀉無法進食進水或急性腎功能下降時暫停
      SGLT2i（及 SU、ACEI、利尿劑、metformin、ARB、NSAID）（Diabetes Canada 2018 Appendix 8,
      DOI 10.1016/j.jcjd.2017.10.045【verbatim 已核對】）；恢復進食進水正常後再恢復用藥。
- [ ] **高風險者提供血酮監測工具**（血中 β-hydroxybutyrate 優於尿酮：EMA §4.4、ADA 2026
      rec 5.26/9.39）。
- [ ] **擇期手術／需禁食檢查前告知醫師**：大手術術前 3 天停藥（TFDA 仿單【verbatim 已核對】；
      流程詳見 PERIOPERATIVE_SICK_DAY_ALGORITHM.md）。
- [ ] **會陰部衛生與警訊**：外陰部疼痛壓痛、紅腫＋發燒倦怠 → 立即就醫（Fournier 壞疽，
      FDA §5.3【verbatim 已核對】）。
- [ ] **預期性 eGFR 下降衛教**：起始後 2 週 eGFR 平均多降約 3–4 mL/min/1.73 m²（DAPA-HF
      post hoc：−4.2 vs −1.1 placebo, Adamson, Circulation 2022, PMID 35442064）——可逆、
      非停藥指徵（KDIGO 2024 PP 3.7.3【verbatim 已核對】）。
- [ ] 併用胰島素／SU 者：依血糖預防性減量（見 A5）。
- [ ] 台灣院所系統面（MOHW TPR No.186 建議）：CPOE「重大手術前3天停藥」警示、藥袋
      警語、手術排程 4 步驟提醒卡。

---

## C. 追蹤（Monitoring checklist）

- [ ] **腎功能**：起始後依常規追蹤即可——KDIGO 2024 PP 3.7.3：SGLT2i 起始**不需**改變 CKD
      監測頻率；初始可逆性 eGFR 下降一般非停藥指徵。早期下降 >10% 者於 DAPA-HF/DAPA-CKD
      分析中不預示較差結局、且不伴隨較多 SAE（Adamson 2022 post hoc；Jongs JASN 2022,
      PMID 35977807——皆為次要分析）。持續性或超乎預期之下降（如 >30%）→ 查容積、
      併用藥（NSAID、顯影劑）、腎動脈狹窄等原因，非反射性歸因於藥物。
- [ ] **容積／血壓**：老年、loop diuretic 併用、eGFR<60 者早期回診；腸胃炎等間發疾病時
      評估容積（理學檢查、血壓、血比容、電解質，EMA §4.4）；容積不足 → 暫停至矯正
      （EMA【verbatim 已核對】）。
- [ ] **Loop diuretic 調整**：SGLT2i 之利尿／利鈉特性「可能允許減少 loop diuretic 需求」
      （ESC 2021 §5.3.5【verbatim 已核對】——機轉推論性敘述）；DAPA-HF 中多數病人利尿劑
      劑量未變、兩組平均劑量無差異（Jackson, Circulation 2020, PMID 32673497——次要分析）。
      實務：euvolemic 且血壓偏低者起始時可考慮減利尿劑；充血未解者不減。
- [ ] **感染追蹤**：生殖器黴菌感染（女 8.4% vs 1.5%、男 2.8% vs 0.3%，FDA §6.1 T2D pool）
      ——多數輕症、局部治療可解，通常無需停藥（仿單無停藥要求）；腎盂腎炎／尿路敗血症
      治療期間**考慮暫停**（EMA §4.4）。嚴重 UTI 觀察性資料未見增加（Dave, Ann Intern Med
      2019, PMID 31357213）。
- [ ] **老年／衰弱**：不因年齡調整劑量（FDA §8.5/EMA §4.2）；但 ≥65 歲低血壓比例較高
      （FDA §8.5）、跌倒／意識改變等非典型 euDKA 表現（CASE_REPORT #7）；DELIVER 衰弱
      預先設定分析：各衰弱層之不良反應未較安慰劑多（Butt, Circulation 2022, PMID 36029465）。
      多重用藥（thiazide＋statin）交互警訊：CASE_REPORT #29。
- [ ] **持續尿糖之解讀**：停藥後尿糖持續 3 天（FDA §12.2/§5.1）、上市後報告
      酮酸中毒／糖尿可 >6 天甚至 2 週（FDA §5.1【verbatim 已核對】）——停藥後 1–2 週內之
      尿糖或酮症勿誤判為「與藥無關」。

---

## D. 暫停與重啟（摘要；詳見 PERIOPERATIVE_SICK_DAY_ALGORITHM.md）

- [ ] 暫停觸發：手術／延長禁食、急性重症住院、嘔吐腹瀉無法進食、腸道準備、大量飲酒、
      容積不足、腎盂腎炎／尿路敗血症治療中。
- [ ] 重啟：臨床穩定＋恢復正常進食（FDA）；建議加驗血酮 <0.6 mmol/L（英國 2025 共識）；
      DKA 後原則不重啟除非誘因明確且解除（EMA）。

---

## E. 系統層面（給演講「如何在醫院落地」段落）

1. CPOE／處方系統：SGLT2i 開立時自動掛入手術前停藥提醒與藥袋警語（MOHW TPR No.186
   實例：3 件台灣真實通報——未停藥致手術延期、取消、改局麻）。
2. 麻醉術前評估單納入「SGLT2i？最後服藥日？當日血酮？」欄位（ADS/ANZCA 行動表）。
3. 急診／ICU：陰離子間隙代謝性酸中毒鑑別清單納入「用 SGLT2i？→ 測血酮」（敗血症/AKI
   遮蔽警訊：CASE_REPORT #26–27）。
4. 出院準備：住院中暫停者，出院醫囑明確寫「恢復日期與條件」，避免永久漏開（HF/CKD
   實證用藥中斷之風險）與過早重啟（藥效延長警訊）兩種錯誤。
5. 通報文化：SGLT2i 相關 DKA 屬應通報 ADR（台灣 02-2396-0100, adr.fda.gov.tw；英國
   Yellow Card——JBDS 2023【verbatim 已核對】）。

---

## 引用注意（給 methods auditor）

- 本檔所有【verbatim 已核對】條目之原文均見於 `evidence/safety/sources/` 內之對應 PDF/文字檔。
- ⚠️TW 條目均出自官方 PDF（NHI/TFDA/MOHW），但依專案規範仍須於引用時點再查證現行版本。
- ADA 2026 rec 5.26/9.39、TSOC 2023 共識、AACE 2016、STICH 協定組成：轉錄自二手來源，
  已逐條標注；逐字引用前須核對原文。
- 個案編號（CASE_REPORT #n）指向 `CASE_REPORT_FAILURE_MODES.md`，均為 teaching signal，
  不得作為發生率證據。
