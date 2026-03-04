# 個人網頁專案 - Hong Hui Shan

這是一個以純前端技術（HTML/CSS/JavaScript）打造的單頁面個人網站（Personal Webpage）。專案採用了高品質的視覺設計，結合「深色模式 (Dark Mode)」與「毛玻璃效果 (Glassmorphism)」等現代網頁設計趨勢，營造出極具質感的數位名片體驗。

## 完成內容與特色

1. **現代化視覺設計 (Modern Aesthetic)**: 
   - 採用極致深色主題的沈浸式背景。
   - 帶有毛玻璃（Glassmorphism）效果的中央資訊卡片，營造出高質感的視覺層次與模糊透視感，並具有邊緣高光與陰影細節。

2. **動態背景 (Dynamic Ambient Background)**:
   - 於背景層實現了漸變色彩（藍色與紫色）的「動態模糊漸層光暈 (Blur Blobs)」。無需使用額外的圖片資源，單純以 CSS 動畫 (Keyframes) 達到緩慢漂浮與縮放的呼吸感，使靜態網頁充滿生命力而不干擾閱讀。

3. **質感字體編排 (Typography)**:
   - 引入了 Google Fonts 現代幾何無襯線字體 **Outfit**。
   - 標題名稱部分特別使用了細緻的文字漸層遮罩效果（Text Gradient），增加畫面的視覺重心。

4. **即時時間小工具 (Real-Time Clock Widget)**:
   - 運用 JavaScript 實作了一個高解析度的數位時鐘小部件。
   - 實時獲取並每秒更新目前的當地時間（時：分：秒 AM/PM）與詳細日期。
   - 時間顯示採用無襯線等寬數字樣式，整體小部件也加入了平滑的互動懸浮特效 (Hover effect)，提升互動體驗。

## 檔案結構

- `index.html`: 負責網站的結構骨架，引入字體資源，並包含實時時鐘更新的 JavaScript 邏輯。
- `style.css`: 掌管所有的視覺設計，包含毛玻璃樣式、背景動態發光體動畫、色彩變數管理與響應式設計 (RWD)，確保在不同裝置上都有良好的跨度表現。

## 如何執行

這是一個純靜態網頁，只需將專案 Clone 下來並在瀏覽器中雙擊開啟 `index.html`，即可完整顯示與運作。亦可透過任何本機靜態網頁伺服器（例如：`python -m http.server`, `Live Server`）進行預覽播放。
