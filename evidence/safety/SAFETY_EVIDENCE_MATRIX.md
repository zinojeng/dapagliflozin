# Dapagliflozin 安全性證據矩陣（SAFETY EVIDENCE MATRIX）

> 檢索截止日 2026-08-27（protocol/SEARCH_PROTOCOL.md）。
> 證據類型標籤：**RCT-1°**（試驗主要安全性結果／裁定事件）、**RCT-2°**（次要結果）、
> **RCT-presp**（預先設定分析）、**RCT-posthoc**（事後分析）、**pooled**（RCT 匯總）、
> **meta**（統合分析）、**obs**（觀察性世代）、**FAERS**（藥物警戒通報，無分母）、
> **label**（仿單／法規）、**GL**（指引）、**case**（個案警訊，非發生率證據）、
> **registry**（ClinicalTrials.gov 結果資料庫之 MedDRA 詞條統計——與論文裁定端點系統性不同）。
> ⚠️ = 數字未能自一手來源核實（詳見文末「未核實清單」）；引用前須回到原始論文表格確認。
> 方法學註記：NEJM 主論文全文為付費牆，DECLARE 安全表多數 HR 取自開放取用回顧文章
> （Cardiovasc Diabetol 2019, PMC6683461）之轉載並與摘要／二次分析交叉比對——此為本檔
> 最大之系統性限制，methods auditor 應優先複核。

---

## 主要試驗基本盤（安全性脈絡用）

| 試驗 | 族群 | N | 追蹤 | 比較 | PMID / DOI |
|---|---|---|---|---|---|
| DECLARE-TIMI 58 | T2D＋CVD 或多重危險因子 | 17,160 | 中位 4.2 年 | dapa 10 mg vs placebo | 30415602 / 10.1056/NEJMoa1812389 |
| DAPA-HF | HFrEF（LVEF ≤40%），55% 無糖尿病（2,605/4,744；Petrie PMC7157181） | 4,744 | 中位 18.2 月 | 同上 | 31535829 / 10.1056/NEJMoa1911303 |
| DELIVER | HF LVEF >40% | 6,263 | 中位 2.3 年 | 同上 | 36027570 / 10.1056/NEJMoa2206286 |
| DAPA-CKD | CKD eGFR 25–75＋UACR 200–5000，32.5% 無 T2D | 4,304 | 中位 2.4 年 | 同上 | 32970396 / 10.1056/NEJMoa2024816 |
| DAPA-MI | 急性 MI＋LV 功能受損，無糖尿病史無慢性 HF | 4,017 | 約 1 年 | 同上（registry-based RCT） | 38320489 / 10.1056/EVIDoa2300286 |
| DICTATE-AHF | 急性失代償 HF 住院早期起始 | 240 | 至第 5 天／出院 | dapa vs 常規結構化利尿 | 38569758 / 10.1016/j.jacc.2024.02.009 |
| DAPA ACT HF-TIMI 68 | HF 住院 24 h–14 d 內隨機分派 | 2,401 | 60 天 | dapa vs placebo | 40884036 / 10.1161/CIRCULATIONAHA.125.076575 |
| DEFINE-HF | HFrEF | 263 | 12 週 | 同上 | 31524498 / 10.1161/CIRCULATIONAHA.119.042929 |

---

## 1. 酮酸中毒（DKA／euDKA）

| 主張 | 證據 | 數值 | 類型 | 來源／locator |
|---|---|---|---|---|
| T2D 長期使用使 DKA 風險約增一倍，但絕對風險極低 | DECLARE-TIMI 58（裁定事件） | 27 (0.3%) vs 12 (0.1%)；HR 2.18 (95% CI 1.10–4.30), P=0.02 | RCT-2°（安全性端點） | %/P：NEJM 摘要（PMID 30415602）；件數：Cahn, Diabetes Obes Metab 2020（PMID 32239659）摘要；⚠️HR/CI 取自 PMC6683461 轉載表 |
| HFrEF 族群 DKA 罕見且僅見於糖尿病者 | DAPA-HF | 3 vs 0（0.06%），全部為 T2D 病人 | RCT-presp（Petrie, JAMA 2020, PMID 32219386, PMC7157181 全文已核） | Petrie Table；NEJM 摘要稱組間無差異 |
| HFpEF/HFmrEF 族群 DKA 罕見 | DELIVER | 裁定 2 vs 0（registry SAE 詞條 3 vs 3——口徑不同） | RCT-2°＋registry | PMC9800271 Table 3（分層加總）；NCT03619213 |
| CKD 族群（含 1/3 非糖尿病）dapagliflozin 組無任何 DKA | DAPA-CKD | 0 vs 2（兩例皆 placebo 組 T2D 病人）；**非糖尿病者 0 例** | RCT-presp（Persson, Diabetes Care 2021, PMID 34183431, PMC8385469 全文已核） | Persson 內文 verbatim；registry 0 vs 3（口徑差異） |
| 急性期住院起始未見 DKA 訊號 | DAPA-MI；DICTATE-AHF；DAPA ACT HF-TIMI 68 | registry serious DKA 1 vs 0；0 vs 0；paper Table 3：0 vs 0 | RCT-2°／registry | NCT04564742；NCT04298229；PMC12910484 Table 3 |
| 真實世界（vs DPP-4i）DKA 風險近 3 倍；dapagliflozin 分子別估計較低 | CNODES 多中心世代（20.9 萬對 PS 配對） | 2.03 vs 0.75 /1000 py；HR 2.85 (1.99–4.08)；dapagliflozin HR 1.86 (1.11–3.10) | obs | Douros, Ann Intern Med 2020, PMID 32716707, DOI 10.7326/M20-0289 |
| 住院病人服藥後酮體上升常見、生化性酮酸中毒少見 | 單中心回溯世代（n=1,511 住院 T2D） | 首劑後酮體 >1 mmol/L 12.6%、>3 mmol/L 2.8%；生化性酮酸中毒 0.7%；聚集於手術、敗血症、攝食下降、重症 | obs | Gao, Diabetes Obes Metab 2025, PMID 40785508 |
| 心臟手術後生化性酮酸中毒在未停藥者常見 | 前瞻小型世代（n=107） | 54.8% (17/28) vs 10.1% (8/79)，p<0.001（生化端點、樣本小——訊號層級） | obs（小型） | Ginestal-Calvo, J Cardiothorac Vasc Anesth 2026, PMID 41365754 |
| 圍術期個案報告已達三位數規模 | 系統性回顧（個案報告） | 128 例（93 篇）；71% 因果性「likely/possible」 | case（系統性彙整） | Snel, Acta Anaesthesiol Scand 2026, PMID 42130079 |
| FAERS 早期訊號（法規行動之依據） | FDA DSC 2015-05-15 | 20 例（2013-03–2014-06），全部急診／住院，中位發病 2 週，部分血糖 <200 mg/dL | FAERS | sources/fda_2015_dsc.txt（Archive 存證）；FDA DSC 2015-12-04：73 例（dapa 21） |
| 血糖正常不排除 DKA；停藥後糖尿持續 3 天、上市後報告 >6 天至 2 週 | FDA 仿單 | §5.1 verbatim 已核 | label | sources/farxiga_s035.pdf（rev. 06/2026） |
| T1D 禁用／不建議 | FDA §5.1、EMA §4.4、TFDA §2.4 | T1D 中 DKA「common frequency」（EMA） | label | 三仿單一致 |
| 高風險群定義 | EMA SmPC §4.4 | 低 β 細胞儲備（低 C-peptide、LADA、胰臟炎史）、攝食受限／嚴重脫水、胰島素減量、急病手術酗酒 | label | sources/forxiga_smpc.pdf |
| 圍術期發生率 0.17%（非急症）／1.1%（急症） | 綜述引用 | ⚠️ 一手來源未核實（Wen 2025, PMID 40414168 為 review/infographic） | — | 不建議引用 |

**確定性評註**：「dapagliflozin 增加 DKA 風險（T2D、長期）」為高確定性（RCT＋大型觀察性
一致）；絕對風險 <0.5%/4 年。「非糖尿病使用者風險極低」在 RCT 為零事件（DAPA-CKD/
DAPA-HF 非糖尿病層），但個案報告已證實可發生（見 CASE_REPORT #8–11）——「極低」≠「零」。

## 2. 非糖尿病者之酮酸中毒

| 主張 | 證據 | 類型 | 來源 |
|---|---|---|---|
| RCT 非糖尿病層零 DKA 事件（DAPA-CKD 1,398 人、DAPA-HF 2,605 人非糖尿病） | Persson PMC8385469；Petrie PMC7157181 | RCT-presp | 上表 |
| 但臨床上確可發生，誘因均為攝食下降；治療核心為葡萄糖供給、幾乎不需胰島素 | 首兩例：Umapathysivam, Diabetes Care 2024, PMID 37988720；另見 Miyazaki 2024（PMID 38985686）、Gutiérrez-Baena 2025（PMID 40889029）、Prasad 2025/2026（PMID 41625235） | case | CASE_REPORT_FAILURE_MODES.md #8–11 |
| 演講句建議：「試驗中未見，上市後個案已見——非糖尿病者不是免疫於酮酸中毒，只是機率低且表現更容易被忽略。」 | — | 綜合 | — |

## 3–4. 手術、延長禁食與生病日管理

完整規則對照與流程 → `PERIOPERATIVE_SICK_DAY_ALGORITHM.md`。證據基礎摘要：

| 規則 | 權威 | 類型 |
|---|---|---|
| 術前停藥 ≥3 天（dapa；ertugliflozin 4 天） | FDA PI §2.4（rev. 06/2026）；FDA DSC 2020-03-19；ADA 2026 §16；TFDA 仿單（2024-04-10）；台灣 MOHW TPR No.186 | label＋GL（無 RCT；源自 FAERS＋機轉） |
| 術前一日＋當日停藥（較短） | 英國 CPOC 2021/2023 路線；El-Boghdadly, Anaesthesia 2025, DOI 10.1111/anae.16541 | GL（共識） |
| 共 3 天（前 2 天＋當日）；日間手術僅停當日；血酮 1.0／1.7 mmol/L 行動閾值 | 澳紐 ADS/ADEA/ANZCA/NZSSD Alert May 2023 | GL（共識） |
| 生病日暫停（SADMANS） | Diabetes Canada 2018 App 8；ADA 2026 §16；KDIGO 2024 PP 3.7.2；EMA §4.4 | GL＋label |
| 住院中 HF 適應症可續用／起始（有適應症且無禁忌） | ADA 2026 Rec 16.11（grade A）；安全性佐證：DICTATE-AHF、DAPA ACT HF-TIMI 68（symptomatic hypotension 3.6% vs 2.2%、worsening kidney function 5.9% vs 4.7%、DKA 0 vs 0——主要效益端點 HR 0.86 (0.68–1.08) **未達顯著**，勿描述為住院起始「有效」之證據；其安全表為可引用之安全證據） | GL＋RCT | PMC12690180；PMC12910484 Table 3 |

## 5. 停藥後延長糖尿／酮症

| 主張 | 證據 | 類型 | 來源 |
|---|---|---|---|
| 停藥後尿糖排泄持續 3 天 | FDA 仿單 §5.1/§12.2（verbatim 已核） | label | sources/farxiga_s035.pdf |
| 上市後報告：停藥後酮酸中毒／糖尿 >6 天、最長 2 週 | FDA 仿單 §5.1（verbatim 已核） | label（上市後） | 同上 |
| 酮酸中毒可比血漿半衰期預期持續更久；可能涉及與藥物無關之因素（胰島素缺乏） | EMA SmPC §4.4（verbatim 已核） | label | sources/forxiga_smpc.pdf |
| PK 基礎：半衰期 12.9–17 h；無「停藥後糖尿持續天數」之專門 PK/PD 研究可檢得 | Kasichayanula 2014（PMID 24105299）；Komoroski 2009（PMID 19129748/19129749） | PK | 檢索確認缺口 |
| 停藥 5 天後仍術後 euDKA；停藥後第 8 天復發、第 11 天仍糖尿酮尿 | Bobba（PMID 41221013）；Alheijani（PMID 40970040）；Chen（PMID 39923447） | case | CASE_REPORT #12–14 |

## 6. 容積耗竭與低血壓

| 主張 | 證據 | 數值 | 類型 | 來源 |
|---|---|---|---|---|
| HFrEF：容積耗竭 AE 組間無統計差異 | DAPA-HF | 7.5% (178) vs 6.8% (162)（非糖尿病層 7.3 vs 6.1%、糖尿病層 7.8 vs 7.8%） | RCT-2°／presp | NEJM 摘要 verbatim「did not differ」；Petrie PMC7157181（分層數字已核；全試驗合計為分層加總） |
| LVEF>40%：嚴重／致停藥容積耗竭數字上略多，論文結論「AE 相近」 | DELIVER | 合計 42 vs 32（HFimpEF 1.7 vs 1.4%；LVEF>40% 1.3 vs 0.9%）——分層加總，⚠️ 全試驗印刷值未核 | RCT-presp 分層 | PMC9800271 Table 3 |
| 住院急性期：症狀性低血壓數字上較多 | DAPA ACT HF-TIMI 68 | 3.6% (43) vs 2.2% (26)（Table 3；全文已核） | RCT-2° | PMC12910484 |
| 急性 HF 併積極利尿：嚴重低血壓罕見且平衡 | DICTATE-AHF | severe hypotension 1 vs 1 | RCT-2°／registry | NCT04298229 |
| T2D 24 週匯總：容積耗竭 AE 平衡 | Jabbour pooled | 「balanced」（數值在全文，⚠️ 未核） | pooled | PMID 28950419 摘要 |
| 高風險群：eGFR<60、老年、loop diuretic | FDA §5.2（verbatim 已核）；EMA §4.4 | — | label | sources/ |
| 老年多重用藥之協同傷害、滲透性腎病變 | 個案 | — | case | CASE_REPORT #29, #30 |

## 7. Loop diuretic 調整

| 主張 | 證據 | 數值 | 類型 | 來源 |
|---|---|---|---|---|
| 效益不因基線利尿劑劑量而異；試驗中多數病人利尿劑劑量未變、兩組平均劑量無差異 | DAPA-HF 次分析 | 主要結局 HR：無利尿劑 0.57 (0.36–0.92)；<40 mg 0.83 (0.63–1.10)；40 mg 0.77 (0.60–0.99)；>40 mg 0.78 (0.63–0.97)；P-int 0.61 | RCT-2°（subgroup；勿當交互作用證明） | Jackson, Circulation 2020, PMID 32673497 |
| 急性 HF：dapagliflozin 減少累積 loop diuretic 用量、增加尿鈉尿量 | DICTATE-AHF | 累積劑量 560 vs 800 mg, P=0.006；24h 尿鈉 P=0.03（主要端點利尿效率 OR 0.65 (0.41–1.02) P=0.06 未達顯著） | RCT-2°（主要端點陰性試驗之次要結果） | PMID 38569758 |
| 「可能允許減少 loop diuretic 需求」 | ESC 2021 §5.3.5（verbatim 已核） | — | GL（機轉推論） | sources/esc2021.pdf |
| 實務：euvolemic／低血壓傾向者起始時考慮減利尿劑；充血未解者不減 | 綜合（作者判斷，非指引原文） | — | — | IMPLEMENTATION_CHECKLIST.md §C |

## 8. 預期 eGFR 下降 vs AKI

| 主張 | 證據 | 數值 | 類型 | 來源 |
|---|---|---|---|---|
| 起始後 2 週 eGFR 急性下降約 3 mL/min（比 placebo 多） | DAPA-HF | −4.2 (95% CI −4.6 至 −3.9) vs −1.1 | RCT-posthoc | Adamson, Circulation 2022, PMID 35442064 |
| 下降 >10% 者比例；且 >10% 下降不預示較差結局 | DAPA-HF | dapa 組 >10%/>20%/>30%：38.2%/12.6%/3.4%；>10% 下降者主要結局 HR 0.73 (0.59–0.91)（效益保留） | RCT-posthoc | 同上 |
| CKD：急性 dip 幅度（vs placebo） | DAPA-CKD | T2D −2.26；非 T2D −1.29 mL/min/1.73 m²；慢性斜率獲益 0.95 (0.63–1.27)/年 | RCT-presp | Heerspink, Lancet Diabetes Endocrinol 2021, PMID 34619108 |
| 急性 >10% dip 常見且與後續 SAE 無關、與 CKD 進展無關；dip 越大長期斜率越平 | DAPA-CKD | >10% dip：49.4% vs 23.7% | RCT-2°（⚠️ presp 標註待核） | Jongs, JASN 2022, PMID 35977807 |
| AKI 反而較少（T2D） | DECLARE | HR 0.69 (0.55–0.87), P=0.002（⚠️ 件數印刷值不一致，取自轉載表；registry SAE AKI 94 vs 127 同向） | RCT-2° | PMC6683461＋NCT01730534 |
| 大型試驗均未見 AKI 風險增加；dip 可逆、非停藥指徵、不需增加監測頻率 | KDIGO 2024 §3.7 implementation text＋PP 3.7.3（verbatim 已核） | — | GL | sources/kdigo2024.pdf |
| registry AKI 詞條（方向一致：不增加或較少） | DAPA-HF 23 vs 46；DELIVER 54 vs 63；DAPA-CKD 39 vs 52；DAPA-MI 14 vs 16 | serious AKI, n | registry | 各 NCT |
| 例外警訊：脫水下滲透性腎病變（切片證實）；sick-day 停藥之理據 | 個案 | — | case | CASE_REPORT #30 |

## 9. 生殖泌尿道感染

| 主張 | 證據 | 數值 | 類型 | 來源 |
|---|---|---|---|---|
| 生殖器黴菌感染顯著增加（最一致的 AE） | FDA 仿單 §6.1（T2D 12 試驗 pool） | 女 8.4% vs 1.5%；男 2.8% vs 0.3% | label（pool） | sources/farxiga_s035.pdf |
| 嚴重或致停藥之生殖器感染 | DECLARE | 0.9% vs 0.1%, P<0.001；⚠️HR 8.36 (4.19–16.68) 取自轉載表 | RCT-2° | NEJM 摘要＋PMC6683461 |
| 24 週 pool：genital infection 5.5% vs 0.6% | Jabbour pooled | — | pooled | PMID 28950419 |
| class-level RR 3.30 (2.74–3.99)（77 RCTs） | Liu, Sci Rep 2017 | — | meta | PMID 28588220 |
| **嚴重 UTI 不增加** | DECLARE：1.5% vs 1.6%（⚠️HR 0.93, 0.73–1.18 轉載表）；Dave 世代：vs DPP-4i HR 0.98 (0.68–1.41)、vs GLP-1 RA HR 0.72 (0.53–0.99) | — | RCT-2°＋obs | PMID 31357213 |
| 腎盂腎炎／尿路敗血症警語；治療期間考慮暫停 | FDA §5.3；EMA §4.4；FDA DSC 2015-12-04（19 例 FAERS，dapa 9） | — | label＋FAERS | sources/ |
| Fournier 壞疽：FAERS 55 例（2013-03–2019-01；清創全數、死亡 3）；DSC 2018-08-29 稿 12 例 vs 其他降糖藥 34 年 6 例 | Bersoff-Matcha, Ann Intern Med 2019, PMID 31060053；FDA DSC | 無分母——訊號非發生率 | FAERS | sources/fda_2018_dsc.txt |
| Fournier 在試驗中極罕見 | DAPA-HF registry 0 vs 1；DAPA-CKD registry 1 vs 0；⚠️DECLARE「1 vs 5」流傳值未核實 | — | registry | 各 NCT |
| 非糖尿病 CKD 病人亦有 FG 個案 | Heidegger, PMID 38707800（⚠️ 僅標題層級） | — | case | CASE_REPORT #23 |

## 10. 低血糖

| 主張 | 證據 | 數值 | 類型 | 來源 |
|---|---|---|---|---|
| dapagliflozin 本身不增加重度低血糖；DECLARE 中反而較少 | DECLARE | 0.7% vs 1.0%；⚠️HR 0.68 (0.49–0.95) 轉載表 | RCT-2° | PMC6683461 |
| HFrEF：major hypoglycemia 4 vs 4，全部為糖尿病者 | DAPA-HF（Petrie 已核） | — | RCT-presp | PMC7157181 |
| CKD：severe hypoglycemia 較少且非糖尿病者零事件 | DAPA-CKD（Persson 已核） | T2D 14 vs 28；非 T2D 0 | RCT-presp | PMC8385469 |
| 併用胰島素／SU 時風險升高 → 預防性減量 | FDA §5.4；EMA §4.4 | — | label | sources/ |

## 11. 截肢與骨折（供「已排除的疑慮」段落）

| 主張 | 證據 | 數值 | 類型 | 來源 |
|---|---|---|---|---|
| dapagliflozin 無截肢訊號 | DECLARE（裁定）＋PAD 次分析 | 1.4% vs 1.3%；HR 1.09 (0.84–1.40), P=0.53 | RCT-2°＋posthoc | Bonaca, Circulation 2020, PMID 32795086 |
| 訊號屬 canagliflozin（CANVAS）特異 | meta：See 2022（PMID 34942623）無差異；Heyward 2020（PMID 32502190）class RR 1.28 (0.93–1.76)、cana RR 1.59 (1.26–2.01)；Sridharan 2025 NMA（PMID 38967475）cana OR 1.6 (1.1–2.4)、dapa 無訊號 | — | meta | — |
| 骨折：DECLARE 5.3% vs 5.1%（⚠️轉載表）；pool「balanced」；低 eGFR 層 13 vs 0（小樣本，FDA §8.6 已核） | 多來源 | Sridharan 2025 曾報 dapa 骨折 OR 1.1 (1.0–1.2)——與 Admani 2025（PMID 41473904, OR 0.85, 0.74–0.98）方向相反，屬離群值，引用須並陳 | RCT-2°＋meta | — |

## 12. 老年與衰弱

| 主張 | 證據 | 數值 | 類型 | 來源 |
|---|---|---|---|---|
| ≥75 歲效益保留、AE 未比 placebo 多 | DAPA-HF 年齡分析 | ≥75 y HR 0.68 (0.53–0.88)（4 分類年齡層⚠️視為 posthoc；AE 數值未在摘要） | RCT-posthoc | Martinez, Circulation 2020, PMID 31736328 |
| 最衰弱層效益最大、各衰弱層 AE 未比 placebo 多 | DELIVER 衰弱分析（Rockwood FI，presp） | most frail HR 0.74 (0.61–0.91) | RCT-presp | Butt, Circulation 2022, PMID 36029465 |
| CKD 高齡（≥80）無異質性 | DAPA-CKD 年齡×性別分析 | ≥80 y 腎複合 3.0 vs 1.2 /100 py（AE 分層值⚠️未核） | RCT-presp | Yu, J Gen Intern Med 2024, PMID 38097862 |
| 仿單：老年不調劑量；≥65 歲低血壓比例較高；三大結局試驗中 >65 歲安全性相近 | FDA §8.5（verbatim 已核） | — | label | sources/farxiga_s035.pdf |
| 非典型表現（跌倒）、多重用藥協同傷害、UTI→敗血性休克 | 個案 | — | case | CASE_REPORT #7, #28, #29 |

## 13. 台灣法規與給付（⚠️TW 全區塊須於引用時點再獨立查證）

| 項目 | 內容 | 來源（官方 PDF 已存 sources/） |
|---|---|---|
| TFDA 仿單 | 衛部藥輸字第026476號；適應症 T2D／CKD／HF（無 LVEF 限制）；「至少3天前暫時中斷」verbatim 已核；eGFR 規則同 FDA | TFDA_Forxiga_10mg_insert_2024-04-10.pdf |
| NHI HFrEF（111/5/1）；HFmrEF（114/3/1）；CKD（114/3/1，eGFR 25–60＋uACR 200–5000＋整合方案收案；eGFR<15 停付）；T2D（metformin 後線；SGLT2i/DPP-4i 擇一） | 詳細條文見 IMPLEMENTATION_CHECKLIST.md §A6 | NHI_2.16_...pdf；NHI_Section5_...pdf |
| TFDA 2015 SGLT2i DKA 風險溝通表；無獨立圍術期公告（規則載於仿單）；MOHW TPR No.186（2024-12）為全國性圍術期停藥系統建議 | — | TFDA_2015_...pdf；MOHW_TPR_No186_...pdf |
| 在地指引：TSOC 2023 HF 共識（SBP ≥95、eGFR ≥20）；2024 台灣 DKD 指引（PMID 40841287，僅摘要層級）；DAROC 2022 指引全文未取得 | ⚠️ 逐字引用前核對原文 | — |

---

## 未核實清單（methods auditor 優先複核）

1. **DECLARE 安全表 HR/CI 多數取自 PMC6683461（開放取用回顧）之轉載**：DKA 2.18、genital
   8.36、major hypo 0.68、UTI 0.93、fracture 1.04、SAE 0.91、disc. 1.15——須回 NEJM Table 3 核對。
2. DECLARE：Fournier「1 vs 5」、volume-depletion composite（流傳 ~2.5% vs 2.4%）、AKI 印刷
   件數（1.5% vs 2.0%）——未核實；AKI 轉載表件數自相矛盾。
3. 「DECLARE 27 例 DKA 中 22 例用胰島素」——無可引用來源，勿用。
4. DAPA-CKD 論文層級之截肢／容積耗竭／停藥率——付費牆，僅新聞層級。
5. DELIVER 全試驗安全表印刷值——本檔為兩分層（PMC9800271）之加總。
6. DAPA-MI 詳細安全表與確切中位追蹤——付費牆；僅「no safety concerns」＋registry。
7. 圍術期 DKA 發生率 0.17%/1.1%（Wen 2025 綜述引用）——一手來源未核。
8. Jongs JASN 2022 之 presp/posthoc 屬性；Martinez 4 分類年齡層屬性；Yu 2024 AE 分層值。
9. Jabbour pooled 之容積耗竭確切數值；Li D 2017 dapa genital OR 3.21 之劑量歸屬。
10. ADA 2026 rec 5.26/9.39、STICH 組成、AACE 2016「24 小時」、ESC 2023 focused update、
    CPOC 原始 PDF——均經二手轉錄（詳 PERIOPERATIVE_SICK_DAY_ALGORITHM.md 與其標注）。
11. FDA DSC 日期：圍術期標示變更公告存證日期為 **2020-03-19**（非流傳之 03-15）。

## 未解問題（依 SEARCH_PROTOCOL 要求）

1. 最適術前停藥天數（3–4 天 vs 英國 36–52 小時）無比較性證據；停藥後藥效可延長至 2 週
   （label＋case），現行停藥期是風險降低而非消除。
2. DKA 後重啟之安全性與時機——僅個案與 EMA 原則性建議。
3. 非糖尿病 HF/CKD 使用者之酮體篩檢策略（圍術期與 sick-day）——指引尚未針對此族群分化。
4. GLP-1 RA/tirzepatide 併用時代之 euDKA 風險量化——目前僅個案警訊，無世代研究檢得。
5. 住院急性 HF 起始之硬結局效益（DAPA ACT 主要端點未達顯著）與 60 天後最適銜接策略。
6. 台灣給付條件（uACR 上下限、整合方案收案）與 KDIGO 2024 適應症之落差對實務用藥之影響。
