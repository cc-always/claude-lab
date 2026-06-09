# Mia Chen — Freelance Graphic Designer Landing Page

自由接案平面設計師 Mia Chen 的個人作品集網站，採用深色主題搭配金色主色調，呈現專業、質感的品牌形象。

## 網站功能

- **Hero 區塊**：大標題動畫搭配主要 CTA 按鈕（與我聯繫 / 觀看作品）
- **精選作品集**：三張專案卡片，展示品牌識別、編輯設計與 UI 設計等代表作
- **響應式導覽列**：Sticky 頂部導覽，桌機版顯示完整選單連結
- **背景環境光球**：三顆浮動光暈（gold / rose / teal）提升視覺層次
- **流暢捲動 & 動畫**：淡入上滑 (fadeUp) 進場動畫，hover 互動效果

## 使用技術

| 技術 | 說明 |
|------|------|
| HTML5 | 語意化標籤結構 |
| CSS3 | 自訂變數、Flexbox、CSS Grid、動畫、backdrop-filter |
| Google Fonts | Inter 字型（300–900 字重） |

無任何 JavaScript 框架或外部 CSS 函式庫，純 HTML / CSS 實作。

## RWD 手機版優化

- 斷點：`max-width: 640px`
- 導覽列選單隱藏，保留 Logo
- Hero 標題縮放為 `3.75rem`，長字自動換行
- CTA 按鈕改為垂直堆疊、滿版寬度
- 作品卡片切換為單欄排列
- Footer 置中對齊

## 如何開啟

直接在瀏覽器開啟，不需任何伺服器或建置工具：

1. 下載或 clone 此專案
2. 在檔案總管中找到 `index.html`
3. 雙擊 `index.html`，即會以預設瀏覽器開啟

或透過終端機：

```bash
# macOS
open index.html

# Windows
start index.html

# Linux
xdg-open index.html
```

建議使用 Chrome / Firefox / Edge 等現代瀏覽器，以確保 `backdrop-filter` 等 CSS 特性正常顯示。
