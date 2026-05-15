# 2028 LA Olympics Design System

此文件記錄了在 2028 洛杉磯奧運靜態網頁概念設計中所使用的設計規範，包含色彩系統與字體設定。

## 色彩系統 (Color Palette)

配色方案擷取自漸層影像，營造出具備未來感與高質感的夜間氛圍。

- **Primary (深紫)**: `#3b286a` - 適用於主背景或漸層起始色。
- **Secondary (亮紫)**: `#79208a` - 適用於輔助背景或過渡漸層。
- **Accent 1 (桃紅)**: `#d64e9a` - 適用於主要按鈕或強調文字。
- **Accent 2 (亮粉)**: `#ff68c4` - 適用於懸停效果 (Hover)、動態高光與文字漸層。

## 輔助色彩 (Utility Colors)

- **Text Main**: `#ffffff` (純白)
- **Text Muted**: `rgba(255, 255, 255, 0.7)`
- **Background Dark**: `#120a1f` (極深紫黑)
- **Glass Background**: `rgba(255, 255, 255, 0.05)`
- **Glass Border**: `rgba(255, 255, 255, 0.1)`

## 排版與字體 (Typography)

- **字體家族**: `Outfit`, sans-serif (由 Google Fonts 載入)
- **標題字重 (Headings)**: `800` (Extra Bold)
- **內文字重 (Body)**: `300` (Light) 至 `400` (Regular)
- **按鈕字重 (Buttons)**: `600` (Semi Bold)

## 視覺效果 (Visual Effects)

- **毛玻璃 (Glassmorphism)**: 結合半透明白色背景 (`Glass Background`)、微亮邊框 (`Glass Border`) 與背景模糊 (`backdrop-filter: blur(10px)`) 實作。
- **漸層文字**: 使用 `linear-gradient` 搭配 `-webkit-background-clip: text` 達成。
