# 紫微排盤小工具

這是一個獨立的靜態 HTML 小工具，使用 [`iztro`](https://github.com/SylarLong/iztro) 在前端直接產生紫微斗數命盤。

## 功能

- 支援陽曆與農曆輸入
- 支援農曆閏月
- 顯示陽曆、農曆、生肖、星座、命宮、身宮
- 顯示十二宮主星與部分副星資訊
- 可直接部署到 GitHub Pages

## 本機使用

直接開啟 `index.html` 即可使用，或在資料夾內啟動靜態伺服器：

```powershell
python -m http.server 4173
```

然後打開 `http://localhost:4173`

## 技術說明

- 單頁 `HTML + CSS + JavaScript`
- 透過 CDN 載入 `iztro@2.5.8`
- 不依賴後端
