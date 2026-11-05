# 輔英科技大學 111–115 學年度生源變化分析戰情看板 & IR 招生預測對策系統 (`STUDENT-ENROLLED-2-ND`)

## 🌐 GitHub Pages 線上系統入口 (Live Dashboards)

1. **📊 111–115 學年度生源變化分析戰情看板（主看板，含第 5 階段「進階 IR 四大決策引擎」）**
   - 🔗 **線上網址**：https://laisiff-dev.github.io/STUDENT-ENROLLED-2-ND/
   - 🔗 **備用路徑**：https://laisiff-dev.github.io/STUDENT-ENROLLED-2-ND/生源變化分析戰情看板.html
2. **🎯 IR 招生預測對策系統（116 報到率推估 ＋ 外部人口變數 ＋ 事中動態預警 ＋ 流失質化歸因 ＋ 系主任待辦清單）**
   - 🔗 **線上網址**：https://laisiff-dev.github.io/STUDENT-ENROLLED-2-ND/IR招生預測對策系統.html
3. **📖 ELI5 系統運作邏輯與公式視覺化圖解（HTML Visual Explainer，含 F01–F16 完整公式定義）**
   - 🔗 **線上網址**：https://laisiff-dev.github.io/STUDENT-ENROLLED-2-ND/ELI5_系統運作邏輯與公式視覺化圖解.html

---

## 🚀 四大進階 IR 決策引擎升級重點

1. **🌐 整合外部環境變數與人口結構 (`F13` Macro Demographic & Competitor Adjustment Model)**：
   - 將教育部「全國高中職應屆畢業生人數預測（少子化基數變化 $\alpha_{\text{demo}}$）」、各縣市適齡人口係數（高屏核心區 vs 中南部跨區 $\beta_{\text{reg}}$）及周邊同儕與國立競校招生名額磁吸壓力（$\gamma_{\text{comp}}$）納入 116 預測推估引擎。
   - 支援預設情境下拉切換（教育部116基準 / 少子化斷崖壓力測試 / 競校擴招激戰 / 純校內歷史模型）與即時拉桿模擬，防止在少子化斷崖年過度樂觀依賴歷史均值。
2. **🚨 建立招生期間的動態預警機制 (`F14` In-Flight Real-Time Enrollment Monitoring)**：
   - 開發「事中監控」模組，於二階報名或繳費期間（D-14 至 D-0）即時對照歷年同期每日累積進度基準線 $P_{\text{hist}}(d)$。
   - 自動計算進度達成比 $\text{PI}_i(d)$：當 $\text{PI} < 80\%$ 跌破安全區間時即時亮起 🔴 **紅燈預警**，列出「一階過篩未繳費可催繳池」並觸發 24 小時緊急電話關懷與針對性廣告投放指令。
3. **🔍 流失節點的質化歸因分析 (`F15` Qualitative Attrition Attribution Matrix)**：
   - 結合電話訪談與問卷數據，將考生於「節點A：一階過篩未報二階」與「節點B：錄取確認後放棄報到」之理由標準化為 6 大標籤（`TAG-1` 國立與名校磁吸、`TAG-2` 跨區通勤距離與住宿、`TAG-3` 選系不選校跨領域轉移、`TAG-4` 學雜費與競校獎學金挖角、`TAG-5` 二階備審負荷與面試撞期、`TAG-6` 臨床實習與國考壓力）。
   - 交叉診斷高報名低轉換生源學校（如道明高中、國立溪湖高中、屏東女中、左營高中、巨人高中、屏東高中、中山工商）之核心流失痛點與獎學金調整對策。
4. **📋 依決策角色的分眾行動清單 (`F16` Role-Based Actionable To-Do Dashboard)**：
   - 提供「系主任 / 學院院長 / 校長與招生處長 / 第一線招生種子教師」四種決策角色切換。
   - **14 系「系主任專屬行動化儀表板」**：選擇任一學系即可直接檢視 **① 本系急需拜訪的 5 所潛力生源校**、**② 高報名低轉換觀望校搶救名單與學生屬性特徵**、**③ 登入即可勾選執行之本週待辦清單 (Interactive Checklists)**。
