# GEMS 模板知識庫：PDF 文獻摘錄、Dataview 與投稿寫作

v3.4.4｜文獻摘錄優先、Dataview 精簡欄位、投稿寫作支援｜涵蓋 A–I 九類研究｜統一補上 A、B、C、D、I 類量表尺度與計分方式要求

---

## 一、用途

本檔作為 GEMS / Custom GPT 的知識庫檔案，提供 A–I 各類文獻的完整摘錄模板、精簡 Dataview 欄位、投稿寫作欄位與查詢範例。設計重點是：先完整整理研究，再讓筆記能被搜尋、比較與用於投稿。

---

## 二、通用筆記骨架

```markdown
---
title: ""
authors:
  - ""
year: 0000
journal: ""
doi: ""
pmid: ""
apa_citation: ""
source_file: "[[PDF檔名.pdf]]"
type: ""
study_design: ""
tags:
  - 論文筆記
status: 匯入

# Dataview 核心索引
population: ""
population_type: other
sample_size: unknown
country: ""
setting: ""
intervention: []
comparison: []
outcome: []
tool: []
construct: []
timepoint: not_applicable
key_finding: ""

# 投稿寫作索引
theoretical_framework: ""
manuscript_axis: []
writing_section: []
claim_supported: []
my_notes: ""
relevance_to_my_paper: medium
投稿稿件: ""
---

## [[實際篇名]]

### 1. 一句話定位
- **這篇文獻主要回答什麼問題**：
- **本文獻最適合用在我論文哪裡**：

### 2. 完整文獻摘錄
依文章類型使用下方 A–I 專用模板。

### 3. 理論架構與概念
- **作者明確使用的理論 / 模型 / 架構**：
- **與我研究可能連結的理論或概念**：
- **重要概念定義**：

### 4. 投稿寫作應用
- **可支援的投稿主軸**：
- **可放入章節**：前言 / 文獻回顧 / 方法 / 討論 / 限制 / 回覆審查意見
- **可支撐的 claim**：
- **可與哪些文獻比較**：
- **可改寫成論文句子的重點**：

### 5. APA 引用與個人筆記
- **APA 7th 引用格式**：
- **個人筆記**：
- **需要回查 PDF 的位置**：頁碼 / 表格 / 圖號 / 段落
```

---

## 三、A–I 類型專用摘錄模板

每次輸出筆記前，先從下列九類擇一判斷，並只套用一個對應模板：

- **A. 橫斷性研究**：Cross-sectional、盛行率、相關分析、單一時間點調查。
- **B. 實驗／類實驗研究**：RCT、Quasi-experimental、介入研究、單組前後測。
- **C. 世代追蹤／回溯研究**：Prospective cohort、Retrospective cohort、Case-control。
- **D. 系統性回顧／統合分析**：Systematic review、Meta-analysis。
- **E. 網路分析**：Network analysis、Bibliometric network、Social network。
- **F. Scoping Review**：範疇性回顧、概念地圖、領域盤點。
- **G. 論述／專論**：Commentary、Viewpoint、Position paper、Discussion paper、碩博士論文、政府部門刊物、理論性文章。
- **H. 質性研究**：Qualitative study、Interview study、Focus group、Phenomenology、Grounded theory、Ethnography、Thematic analysis、Content analysis、Narrative inquiry。
- **I. 混合研究／混合方法研究**：Mixed methods、Explanatory sequential design、Exploratory sequential design、Convergent parallel design、Embedded mixed methods。

---

## A. 橫斷性研究完整摘錄

### 1. 研究背景與缺口
- 研究問題出現的背景：
- 過去研究不足：
- 本研究要補上的缺口：

### 2. 研究目的 / 問題 / 假設
- 研究目的：
- 研究問題或假設：

### 3. 方法與樣本
- 研究設計：
- 國家 / 場域：
- 樣本數 N：
- 樣本特徵：年齡、性別、身分、臨床或教育背景
- 納入與排除條件：
- 抽樣方式：
- 資料蒐集時間：

### 4. 變項、工具與信效度
- 主要變項 / construct：
- 測量工具：工具全名、縮寫、題數、計分尺度（如 5 點 Likert）、分數範圍、計分方向（正向 / 反向計分）、Cronbach's α 或其他信效度指標（CVI、CFA 指標等）；文獻未提及者填「文獻未提及」
- 其他共變項或控制變項：

### 5. 統計分析與結果
- 描述性結果：平均數、SD、百分比、盛行率
- 相關分析：r、p、95% CI
- 迴歸或模型結果：β、OR、adjusted OR、p、95% CI、R²
- 重要表格 / 圖形重點：

### 6. 作者結論與限制
- 作者主要結論：
- 作者承認的限制：
- 解讀時注意：橫斷性研究只能描述變項間的關聯，不能推論因果方向。

---

## B. 實驗／類實驗研究完整摘錄

### 1. 介入背景與理論基礎
- 為什麼需要此介入：
- 介入背後的理論、模型或教學 / 臨床邏輯：

### 2. 研究目的與假設
- 自變項 IV：
- 依變項 DV：
- 研究假設：

### 3. 設計與樣本
- 研究設計：RCT / quasi-experimental / single-group pre-post / mixed design
- 分組方式：隨機 / 非隨機 / intact classes / convenience
- 樣本數：總 N、各組 n
- baseline equivalence：是否檢定，檢定結果
- attrition：退出人數、比例、原因
- 盲法：參與者 / 評分者 / 統計者是否盲法

### 4. 介入內容
- 實驗組介入：內容、劑量、頻率、時長、執行者、媒介
- 對照組條件：常規照護 / 傳統教學 / 等候名單 / 其他
- 追蹤時間點：pretest、posttest、follow-up

### 5. 工具與測量
- 主要工具：工具全名、縮寫、題數、計分尺度（如 5 點 Likert）、分數範圍、計分方向（正向 / 反向計分）、Cronbach's α 或其他信效度指標；文獻未提及者填「文獻未提及」
- 結果變項：
- 其他測量：

### 6. 統計分析與結果
- 組內變化：平均數、SD、t、p、Cohen's d
- 組間差異：F、t、p、95% CI、η² 或其他 effect size
- 交互作用或追蹤效果：time × group、GEE、LMM、ANCOVA 等
- 臨床或教育意義：效果量大小與實務意義

### 7. 作者結論與限制
- 作者主要結論：
- 實務應用：
- 作者承認的限制：
- 解讀時注意：若非隨機分派，需避免過度因果推論；attrition 比例高者結果需謹慎解讀。

---

## C. 世代追蹤／回溯研究完整摘錄

### 1. 研究背景與風險問題
- 欲探討的 exposure：
- 欲預測或解釋的 outcome：
- 為什麼需要長期追蹤或回溯資料：

### 2. 研究目的
- 主要目的：
- 次要目的：

### 3. 設計與資料來源
- 設計：prospective cohort / retrospective cohort / case-control
- 資料來源：病歷、資料庫、登錄資料、問卷追蹤
- 追蹤期間：起訖時間、追蹤次數、追蹤間隔
- 樣本數與族群定義：
- 匹配條件或分組條件：

### 4. Exposure、Outcome 與干擾變項
- Exposure 定義：
- Outcome 定義：
- Confounders / covariates：

### 5. 統計分析與結果
- 發生率 / 盛行率 / 累積發生率：
- OR / RR / HR 與 95% CI：
- adjusted estimates：調整哪些變項後的結果
- 敏感度分析或次群組分析：

### 6. 作者結論與限制
- 作者主要結論：
- 預測或預後意涵：
- 作者承認的限制：失訪、殘餘混雜、資料庫限制等。
- 解讀時注意：世代研究雖具時序性，但仍無法完全排除殘餘混雜，不宜直接等同因果實驗證據。

---

## D. 系統性回顧／統合分析完整摘錄

### 1. 核心問題與 PICO / PICo
- P：
- I / Issue：
- C / Context：
- O：

### 2. 檢索與篩選
- 資料庫：
- 檢索期間：
- 關鍵詞 / MeSH：
- 納入與排除條件：
- PRISMA 流程：初篩 n、去重 n、全文評估 n、最後納入 n

### 3. 納入研究特徵
- 研究設計分布：
- 國家 / 場域：
- 樣本數總計：
- 介入或暴露類型：
- 結果變項與工具：工具全名、縮寫、題數、計分尺度、分數範圍、計分方向；若納入研究工具不一致，需說明工具異質情形

### 4. 品質評估與偏差風險
- 品質評估工具：CASP / JBI / RoB 2 / ROBINS-I / AMSTAR 2 / NOS
- 整體品質或偏差風險：

### 5. 數據合成結果
- 是否做 meta-analysis：是 / 否
- 合併效應量：OR / RR / SMD / MD / Hedges' g 等與 95% CI
- 異質性：I²、Q、Tau²
- 模型：fixed-effect / random-effects
- 森林圖重點：
- 次群組分析：
- 敏感度分析：
- 發表偏誤：funnel plot、Egger's test

### 6. 作者結論與研究缺口
- 作者主要結論：
- 證據強度：
- 作者指出的研究缺口：
- 對未來研究的建議：
- 解讀時注意：系統性回顧的結論強度取決於納入研究的品質與異質性；I² 高者合併效應量需謹慎詮釋。

---

## E. 網路分析完整摘錄

### 1. 研究背景與網路觀點
- 為什麼使用網路分析：
- nodes 代表什麼：
- edges 代表什麼：

### 2. 資料來源與網路建構
- 資料來源：
- 樣本或節點數：
- 邊的定義與權重：
- 使用軟體或演算法：

### 3. 網路指標
- centrality：degree、betweenness、closeness、expected influence
- network density：
- modularity / community detection：
- bridge symptoms / bridge nodes：

### 4. 主要結果
- 最核心節點：
- 主要社群或模組：
- 網路圖的實質意義：

### 5. 作者結論與限制
- 作者主要結論：
- 實務或理論意涵：
- 作者承認的限制：
- 解讀時注意：網路分析呈現的是節點間的關聯結構，不代表因果關係；網路結構可能受樣本與工具選擇影響，結果不宜過度推論至其他族群。

---

## F. Scoping Review 完整摘錄

### 1. 範疇與研究動機
- 為什麼需要 scoping review：
- 欲界定的知識範疇：
- 採用框架：JBI / Arksey & O'Malley / Levac 等

### 2. 研究問題
- 研究問題 1：
- 研究問題 2：
- 研究問題 3：

### 3. 檢索與篩選
- 資料庫：
- 檢索期間：
- 納入與排除條件：
- 最終納入篇數：

### 4. 文獻特徵與概念映射
- 年份分布：
- 國家 / 場域分布：
- 研究設計分布：
- 主要概念分類：
- 族群、工具與結果變項：

### 5. 主要發現與研究缺口
- 已知知識：
- 尚未釐清之處：
- 作者提出的未來研究方向：
- 解讀時注意：Scoping review 重點是盤點範疇與繪製知識地圖，不評估證據品質，不宜據此推論介入效果。

---

## G. 論述／專論完整摘錄

### 1. 論述背景與問題意識
- 作者回應的社會、臨床、教育或學術問題：
- 作者立場：

### 2. 核心論點架構
- 論點一：
- 論點二：
- 論點三：

### 3. 理論架構與概念定義
- 使用或提出的理論 / 模型 / 框架：
- 關鍵概念定義：
- 與既有文獻的關係：

### 4. 實務建議或政策意涵
- 對臨床 / 教育 / 政策 / 研究的建議：
- 可能的應用場景：

### 5. 爭議、限制與可用性
- 可能的反對觀點：
- 尚未被實證支持的部分：
- 解讀時注意：論述性文章代表作者觀點，不等同實證研究結果，引用時需標明此為觀點或建議，而非研究發現。
- 可用於投稿的位置：前言問題意識 / 理論架構 / 討論延伸。

---

## H. 質性研究完整摘錄

### 1. 研究背景與質性探究焦點
- 研究問題出現的背景：
- 為什麼適合使用質性研究：
- 過去研究不足：
- 本研究想深入理解的經驗、觀點、歷程或意義：

### 2. 研究目的 / 研究問題
- 研究目的：
- 主要研究問題：
- 次要研究問題：
- 欲探索的核心現象或經驗：

### 3. 質性研究設計與取向
- 研究設計：phenomenology / grounded theory / ethnography / qualitative descriptive / case study / narrative inquiry / content analysis / thematic analysis / other
- 方法論取向：
- 作者明確使用的理論或概念框架（僅填文獻中明確引用者，不得自行推測）：
- 作者在討論中連結的概念（非主要框架，但用於解釋發現者，需標注「討論中提及」）：
- 核心方法論原則（若為現象學，需列出 bracketing、eidetic reduction、phenomenological description、intersubjectivity 等原則及其操作方式；若為其他取向，填該取向的核心步驟）：
- 選擇此質性取向的理由：

### 4. 研究場域與參與者
- 國家 / 場域：
- 參與者身分與特徵：年齡（平均數、SD、範圍）、性別、身分、教育背景
- 樣本數 N：
- 抽樣方式：purposive sampling / snowball sampling / theoretical sampling / convenience sampling / maximum variation sampling
- 篩選工具（若有）：工具全名、縮寫、題數、計分方式、信效度（Cronbach's α、CFA 結果）、篩選門檻（如前 20%）、樣本得分範圍
- 篩選流程（若有多階段）：第一階段方式 → 第二階段方式 → 最終確認方式
- 納入條件：
- 排除條件：
- 資料飽和：是否提及 saturation / information power，如何判定，第幾位後停止：

### 5. 資料蒐集方法
- 資料來源：半結構式訪談 / 深度訪談 / 焦點團體 / 觀察 / 文件分析 / 反思日誌 / 開放式問卷
- 訪談或資料蒐集時間：
- 每次訪談或資料蒐集長度：
- 訪談大綱或核心問題：
- 錄音、逐字稿與資料保存方式：
- 研究者角色與反身性說明：

### 6. 資料分析方法
- 分析方法：thematic analysis / content analysis / framework analysis / grounded theory coding / interpretative phenomenological analysis / narrative analysis
- 編碼流程：open coding / axial coding / selective coding / initial coding / focused coding
- 分析步驟：
- 是否使用質性分析軟體：NVivo / ATLAS.ti / MAXQDA / other
- 研究團隊如何討論與確認主題：
- 是否有成員檢核、同儕審查或專家檢核：

### 7. 嚴謹度與可信度

嚴謹度必須獨立完整記錄，不得分散於其他節。每項標準須填入作者的具體做法，不得只填「有」或「否」。

- 使用的嚴謹度框架：Lincoln and Guba / COREQ / SRQR / other
- 報告準則：是否依 COREQ checklist / SRQR / 其他準則報告
- Credibility 可信度（具體做法，例如 member checking、prolonged engagement、triangulation）：
- Transferability 可轉移性（具體做法，例如 thick description、maximum variation sampling）：
- Dependability 可靠性（具體做法，例如 double coding、audit trail、分析過程紀錄）：
- Confirmability 可確認性（具體做法，例如 audit trail、bracketing、reflexive diary）：
- 研究者反身性與偏見控制（資料蒐集前、蒐集中、分析後的具體做法）：
- 翻譯嚴謹度（若跨語言發表，填翻譯流程，例如 Brislin back-translation）：

### 8. 主要結果 / 主題

主題必須依原文層次展開，若原文有次主題，須逐一記錄。引文必須保留參與者原話，標注參與者編號（如 P1、P3），並附一句中文說明該引文支持哪個主題意義。禁止改為間接轉述（如「P12 表示……」）。

- 主題一：
  - 主題意義（以中文摘述作者詮釋）：
  - 次主題 1-1：
    - 說明：
    - 引文：P__：「原文」→ 中文說明
    - 引文：P__：「原文」→ 中文說明
  - 次主題 1-2：
    - 說明：
    - 引文：P__：「原文」→ 中文說明
    - 引文：P__：「原文」→ 中文說明
- 主題二：
  - 主題意義（以中文摘述作者詮釋）：
  - 次主題 2-1：
    - 說明：
    - 引文：P__：「原文」→ 中文說明
    - 引文：P__：「原文」→ 中文說明
  - 次主題 2-2：
    - 說明：
    - 引文：P__：「原文」→ 中文說明
    - 引文：P__：「原文」→ 中文說明
- 主題三：
  - 主題意義（以中文摘述作者詮釋）：
  - 次主題 3-1：
    - 說明：
    - 引文：P__：「原文」→ 中文說明
    - 引文：P__：「原文」→ 中文說明
  - 次主題 3-2：
    - 說明：
    - 引文：P__：「原文」→ 中文說明
    - 引文：P__：「原文」→ 中文說明
- 主題之間的關係：
- 作者是否提出模型、架構或概念圖：

### 8-1. 圖表重點摘錄

每份重要表格與圖形必須獨立摘錄，不得略過。

- Table 1（標題）：摘錄重點
- Table 2（標題）：摘錄重點（若為訪談大綱，列出核心問題）
- Table 3（標題）：摘錄重點（若為人口學，填年齡、性別、年級、篩選工具分數等）
- Table 4（標題）：摘錄重點（若為主題表，列出主題、次主題、編碼名稱）
- Figure 1（標題）：說明圖的內容與結構（若為招募流程，填各階段人數）
- Figure 2（標題）：說明圖的內容與結構（若為主題關係圖，說明各主題間的方向與連結）

### 9. 作者討論與詮釋
- 作者如何解釋主要發現：
- 與既有文獻相同之處：
- 與既有文獻不同之處：
- 可能原因（依作者原文，不得自行延伸）：
- 理論意涵：
- 實務或教育意涵：

### 10. 作者結論與限制
- 作者主要結論：
- 對臨床 / 教育 / 政策 / 研究的建議：
- 作者承認的限制：
- 未來研究方向：
- 解讀時注意：質性研究重點在於深入理解經驗、意義與脈絡，不宜推論盛行率、效果量或因果關係；結果代表特定情境下的詮釋，不宜過度類推至其他族群或場域。

### 11. 可用於投稿的位置

每個章節須填入具體可用的重點，不得只填「有」。最後必須提供 3–5 條可直接改寫為論文句子的英文概念句。

- **前言**：建立質性探究必要性、描述現象缺口；可用重點：
- **文獻回顧**：呈現現有質性證據、比較研究取向；可用重點：
- **方法**：引用支持研究設計選擇（取向、抽樣、分析、嚴謹度）的文獻；可用重點：
- **討論**：對照本研究主題與此文獻發現的異同；可用重點：
- **限制**：說明質性研究的可轉移性邊界；可用重點：
- **回覆審查意見**：當審查者質疑研究設計或結果詮釋時的支撐文獻；可用重點：
- **可直接改寫於投稿中的概念句**（英文，3–5 條，每條可修改後直接放入稿件）：
  1.
  2.
  3.

---

## I. 混合研究／混合方法研究完整摘錄

### 1. 研究背景與混合方法使用理由
- 研究問題出現的背景：
- 為什麼單用量化或質性方法不足：
- 使用混合方法的必要性：
- 本研究想同時理解的「效果 / 關係 / 趨勢」與「經驗 / 意義 / 脈絡」：

### 2. 研究目的 / 研究問題
- 整體研究目的：
- 量化研究問題：
- 質性研究問題：
- 混合研究問題：
- 本研究欲整合回答的核心問題：

### 3. 混合方法設計類型
- 混合方法設計：explanatory sequential / exploratory sequential / convergent parallel / embedded / multiphase / other
- 設計流程：
  - 量化階段：
  - 質性階段：
  - 整合階段：
- 量化與質性資料的優先順序：量化優先 / 質性優先 / 同等權重
- 資料蒐集順序：sequential / concurrent
- 選擇此設計的理由：

### 4. 研究場域與樣本
- 國家 / 場域：
- 量化樣本數與特徵：
- 質性參與者數與特徵：
- 量化抽樣方式：
- 質性抽樣方式：
- 質性參與者是否來自量化樣本：
- 納入條件：
- 排除條件：

### 5. 量化資料蒐集與測量
- 量化研究設計：
- 主要變項 / construct：
- 測量工具：工具全名、縮寫、題數、計分尺度（如 5 點 Likert）、分數範圍、計分方向（正向 / 反向計分）、Cronbach's α 或其他信效度指標（CVI、CFA 指標等）；文獻未提及者填「文獻未提及」
- 資料蒐集時間點：
- 其他共變項或控制變項：

### 6. 質性資料蒐集
- 質性資料來源：訪談 / 焦點團體 / 開放式問卷 / 觀察 / 文件分析
- 訪談或資料蒐集時間：
- 訪談大綱或核心問題：
- 錄音、逐字稿與資料保存方式：
- 研究者角色與反身性說明：

### 7. 資料分析方法
- 量化分析方法：描述統計 / 相關 / 迴歸 / ANCOVA / GEE / LMM / 其他
- 量化主要結果指標：
- 質性分析方法：thematic analysis / content analysis / framework analysis / grounded theory coding / other
- 質性編碼與主題形成流程：
- 是否使用分析軟體：SPSS / R / NVivo / ATLAS.ti / MAXQDA / other

### 8. 混合整合策略
- 整合發生階段：設計階段 / 資料蒐集階段 / 分析階段 / 解釋階段
- 整合方法：
  - merging（合併）：同時蒐集量化與質性資料後並列比較
  - connecting（連結）：用量化結果決定質性樣本或問題
  - building（建構）：用質性結果發展量化工具或假設
  - embedding（嵌入）：將一種資料嵌入另一主要設計
- 是否使用 joint display（聯合呈現圖表）：
- 量化與質性結果是否一致：
- 若不一致，作者如何解釋：

### 9. 主要結果
- 量化主要發現：
  - 描述性結果：
  - 推論統計結果：
  - 效果量或信賴區間：
- 質性主要主題：
  - 主題一（以中文摘述）：
  - 主題二（以中文摘述）：
  - 主題三（以中文摘述）：
- 混合整合後的核心發現（meta-inference）：
- 作者是否提出模型、架構或實務建議：

### 10. 嚴謹度與品質評估
- 量化部分信效度：
- 質性部分可信度：credibility / transferability / dependability / confirmability
- 混合方法品質：是否清楚說明整合邏輯、設計合理性與 meta-inference
- 是否使用報告準則：GRAMMS / MMAT / COREQ / STROBE / other
- 研究者如何處理偏差與反身性：

### 11. 作者討論、結論與限制
- 作者如何整合解釋量化與質性結果：
- 與既有文獻相同之處：
- 與既有文獻不同之處：
- 理論意涵：
- 實務或教育意涵：
- 作者承認的限制：
- 未來研究方向：
- 解讀時注意：混合研究的核心價值在於兩類資料的整合詮釋（meta-inference），而非單純並列量化與質性結果；若整合策略說明不清，需在筆記中標注。

### 12. 可用於投稿的位置
- 前言：建立混合方法必要性、說明量化與質性各自的不足
- 文獻回顧：呈現既有混合研究設計的多樣性與缺口
- 方法：引用支持混合設計選擇、抽樣策略、整合邏輯的文獻
- 討論：對照本研究混合發現與其他研究的異同
- 限制：說明兩類資料整合的限制與可轉移性邊界

---

## 四、Dataview 欄位受控詞彙建議

| 欄位 | 建議值 | 說明 |
|---|---|---|
| status | 匯入 / 閱讀中 / 已完成 / 需補全 | 筆記完成度。 |
| population_type | preterm / general_postpartum / antenatal / nicu_infant / nursing_student / nurse / educator / patient / older_adult / other | 族群分類可依研究主題擴充，但需維持一致。 |
| timepoint | pregnancy / early_postpartum / nicu_stay / post_discharge / long_term / mixed / not_applicable | 適用於追蹤、產後或介入研究。 |
| construct（量化）| depression / anxiety / parenting_stress / self_efficacy / critical_thinking / self_directed_learning / metacognition / clinical_reasoning | 以工具實際測量的變項為準，小寫底線。 |
| construct（質性）| lived_experience / coping_process / meaning_making / illness_experience / role_transition / decision_making_experience / support_seeking / stigma_experience | 以研究探索的核心現象為準，小寫底線。 |
| writing_section | 前言 / 文獻回顧 / 方法 / 討論 / 限制 / 回覆審查意見 | 可讓 Dataview 依投稿章節整理。 |
| relevance_to_my_paper | high / medium / low | 與目前投稿主題的關聯。 |
| type | A. 橫斷性研究 / B. 實驗／類實驗研究 / C. 世代追蹤／回溯研究 / D. 系統性回顧／統合分析 / E. 網路分析 / F. Scoping Review / G. 論述／專論 / H. 質性研究 / I. 混合研究／混合方法研究 | 文獻類型分類。 |
| study_design | cross-sectional study / RCT / quasi-experimental study / cohort study / systematic review / meta-analysis / qualitative descriptive study / phenomenological study / grounded theory study / explanatory sequential mixed methods study / convergent parallel mixed methods study 等 | 可填更細的研究設計。 |
| tags | 論文筆記 + 3–8 個內容標籤 | 必須保留「論文筆記」，並依文獻內容補上文獻類型、研究族群、主要主題、核心構念或介入；不加 #，避免只填泛稱。產生 tags 時必須優先使用 `Tag_受控詞表.md` 中既有標籤；若確實需要新增 tag，需使用英文底線格式，並避免與既有 tag 同義。 |

### Dataview 填寫範例

```yaml
# 量化研究
type: "A. 橫斷性研究"
study_design: "cross-sectional study"
construct: ["depression", "self_efficacy"]
```

```yaml
# 質性研究
type: "H. 質性研究"
study_design: "qualitative descriptive study"
construct: ["lived_experience", "coping_process"]
tool: ["semi-structured_interview"]
```

```yaml
# 混合研究（說明型序列設計）
type: "I. 混合研究／混合方法研究"
study_design: "explanatory sequential mixed methods study"
construct: ["self_directed_learning", "lived_experience"]
```

```yaml
# 混合研究（收斂平行設計）
type: "I. 混合研究／混合方法研究"
study_design: "convergent parallel mixed methods study"
```

---

## 五、Dataview 查詢範例

### 1. 文獻總覽

```dataview
TABLE authors, year, type, population_type, construct, key_finding
FROM #論文筆記
SORT year DESC
```

### 2. 依投稿主軸整理文獻

```dataview
TABLE authors, year, key_finding, writing_section, claim_supported
FROM #論文筆記
WHERE contains(manuscript_axis, "你的投稿主軸")
SORT year DESC
```

### 3. 找出可放入前言的文獻

```dataview
TABLE authors, year, key_finding, claim_supported, apa_citation
FROM #論文筆記
WHERE contains(writing_section, "前言")
SORT year DESC
```

### 4. 找出可放入討論的文獻

```dataview
TABLE authors, year, key_finding, claim_supported, my_notes
FROM #論文筆記
WHERE contains(writing_section, "討論")
SORT relevance_to_my_paper ASC, year DESC
```

### 5. 依 construct 查詢

```dataview
TABLE authors, year, population, tool, key_finding
FROM #論文筆記
WHERE contains(construct, "depression")
SORT year DESC
```

### 6. 依工具查詢

```dataview
TABLE authors, year, sample_size, population_type, key_finding
FROM #論文筆記
WHERE contains(tool, "EPDS")
SORT sample_size DESC
```

### 7. 理論架構清單

```dataview
TABLE authors, year, theoretical_framework, manuscript_axis, claim_supported
FROM #論文筆記
WHERE theoretical_framework != "" AND theoretical_framework != "文獻未提及"
SORT year DESC
```

### 8. APA 引用清單

```dataview
TABLE apa_citation, writing_section, claim_supported
FROM #論文筆記
WHERE apa_citation != ""
SORT year ASC
```

### 9. 找出質性研究文獻

```dataview
TABLE authors, year, study_design, population, key_finding, writing_section
FROM #論文筆記
WHERE type = "H. 質性研究"
SORT year DESC
```

### 10. 找出混合研究文獻

```dataview
TABLE authors, year, study_design, population, key_finding, writing_section
FROM #論文筆記
WHERE type = "I. 混合研究／混合方法研究"
SORT year DESC
```

### 11. 找出所有質性與混合研究（跨類型比較）

```dataview
TABLE authors, year, type, study_design, key_finding, writing_section
FROM #論文筆記
WHERE type = "H. 質性研究" OR type = "I. 混合研究／混合方法研究"
SORT year DESC
```

### 12. 找出所有量化實證研究（A、B、C 類）

```dataview
TABLE authors, year, type, sample_size, key_finding, writing_section
FROM #論文筆記
WHERE type = "A. 橫斷性研究" OR type = "B. 實驗／類實驗研究" OR type = "C. 世代追蹤／回溯研究"
SORT year DESC
```

### 13. 找出可用於方法章節的文獻

```dataview
TABLE authors, year, type, study_design, key_finding, claim_supported
FROM #論文筆記
WHERE contains(writing_section, "方法")
SORT year DESC
```

---

## 六、投稿寫作應用規則

- 寫**前言**時，優先使用 writing_section 包含「前言」且 claim_supported 清楚的文獻；不要只是堆疊單篇摘要。
- 寫**文獻回顧**時，依 construct、population_type、tool 或 study_design 分群比較；量化與質性文獻可分開呈現或對照整合。
- 寫**方法**時，需引用文獻支持自己的研究設計選擇：
  - 量化研究：引用支持測量工具、分析方法的文獻。
  - 質性研究：引用支持取向選擇（如 phenomenology）、抽樣策略（如 purposive sampling）、嚴謹度標準（如 Lincoln & Guba）的文獻。
  - 混合研究：引用支持混合設計類型（如 explanatory sequential）、整合邏輯與 meta-inference 說明的文獻。
- 寫**討論**時，依「本研究發現 → 與既有文獻相同或不同 → 可能原因 → 理論或實務意涵 → 限制」整合；質性與混合文獻需依脈絡詮釋，不得直接比較數字。
- **回覆審查委員**時，優先找 claim_supported 與審查問題相符的文獻，並使用 APA 引用。
- theoretical_framework 欄位只填作者明確使用或文獻可明確支持的理論；若是使用者自己的延伸想法，放在 my_notes。
- my_notes 是個人筆記，不等於作者原文結果；不得與「主要結果」混寫。

---

## 七、APA 引用格式規則

- 若 PDF 提供完整作者、年份、篇名、期刊、卷期、頁碼與 DOI，請產生 APA 7th 格式。
- 若資料不足，apa_citation 填「文獻資訊不足，需補全」，不得杜撰。
- 中文筆記內可保留 APA 英文格式，方便日後直接放入投稿稿件或參考文獻管理。
- 若 DOI 存在，APA 結尾使用 https://doi.org/xxxxx。


## 八、v3.4.4 相容性附則
- 主指令 v11.1 負責唯一 YAML、輸出、續寫與驗證；本知識庫負責 A–I 專屬摘錄細項。
- YAML 同時保留 `pmid` 與 `投稿稿件`；缺值填空字串。
- `tags` 固定包含 `論文筆記`，另加 3–8 個原文支持的標籤；優先受控詞表，否則英文小寫底線，不使用 PascalCase 同義標籤。
- 正文只使用主指令的 12 個外層章節，本知識庫各類細項作為子標題融入，避免重複與漏項。
- 類型判斷依實際研究設計；非介入的比較不自動歸 B，含政策討論的實證研究不自動歸 G。九類不完全適配時應揭露。
- 未提供的附錄、圖表、量表資訊標示未提供或無法核實，不得自行補造。

