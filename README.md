# biodiversity_map
Biodiversity hotspots map of the Cape region of South Africa.

專案簡介

本網站為 2023 NASA Space Apps Challenge 之專案成果，主題為 「Exploring Biodiversity Hotspots with Imaging Spectroscopy」。
本研究運用光譜多樣性作為葉片特徵變異的指標，以探索植物物種的多樣性熱點。

網站共包含 五個主要頁面：簡介、互動式地圖、分析過程、參考資料及關於我們。

團隊成員（中文）：
賴泳在
段祥
陳薈筑
楊子緯

執行方式
發布版本

本網站已部署於 GitHub Pages，可透過以下連結直接開啟：

專案：Bio-Hotspots

開發版本

若需於本機執行，下載專案後直接開啟 index.html 即可，無需額外設定。

網站頁面說明
1. 簡介

介紹本專案所使用的 EMIT 光譜資料，以及主要研究範圍——南非 Cape 區域。

2. 互動式地圖

網站的核心頁面，提供多種可切換圖層，包括：

底圖：OpenStreetMap、Satellite

研究分析圖層：NDVI、NDWI、NDMI

最終 Z-score 結果：381–2492 nm 波段、700–1400 nm 波段

額外選項圖層：生物多樣性熱點、Cape 區域範圍

3. 分析過程

展示分析流程，包括原始資料、前處理步驟、使用方法與最終成果，使研究過程透明且可追溯。

4. 參考資料

列出本專案使用的資料來源、參考網站及相關學術文獻。

5. 關於我們

介紹團隊成員與其在專案中的主要貢獻。

分析程式碼

與資料處理與分析相關的程式碼放置於 /AnalysisProcess 資料夾中：

emit_tools.py：NASA 提供的正射影像處理模組

Demo-checkpoint.ipynb：包含完整分析流程的 Jupyter Notebook
