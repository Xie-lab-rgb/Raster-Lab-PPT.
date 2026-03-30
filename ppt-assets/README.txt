Raster Lab 簡報截圖（ppt-bright.html 使用）

重新產生截圖（需已 npm install）：
  node capture-ppt-screenshots.mjs

會產生：
  - 全畫面：01-main、02-dropzone、03～07 各模式
  - 局部特寫 callout-01～06：側欄、拖放區、模式格、Style 圖標、效果圖層、主預覽區（Glitch）

輸出 PDF（建議，含 14 頁與列印樣式）：
  node export-ppt-pdf.mjs        → Raster-Lab-Design-Deck.pdf（英文介面）
  node export-ppt-pdf.mjs zh      → Raster-Lab-Design-Deck-ZH.pdf（中文介面）

或手動：Chrome / Edge 開啟 ppt-bright.html → 列印 → 另存為 PDF → 橫向。
