# 股票新手完整課程

給完全沒碰過股票的朋友的三堂互動教材。繁體中文（台灣，台股為主）。

- 第 1 堂 觀念：股票是一道菜，ETF 是一個便當
- 第 2 堂 動手：開戶與你的第一筆下單
- 第 3 堂 盤點：熱門 ETF 大盤點

## 怎麼放上 GitHub Pages

1. 把這個資料夾裡的**所有檔案**上傳到 repo 的根目錄（五個 .html/.js 檔缺一不可）。
2. Settings → Pages → Source 選 `Deploy from a branch`，分支選 `main`、資料夾選 `/ (root)`，Save。
3. 等一兩分鐘，網址會是 `https://<你的帳號>.github.io/<repo名稱>/`。

## 檔案說明

| 檔案 | 用途 |
| --- | --- |
| `index.html` | 課程首頁與切換列（會載入下面三堂） |
| `lesson1.dc.html` | 第 1 堂 |
| `lesson2.dc.html` | 第 2 堂 |
| `lesson3.dc.html` | 第 3 堂 |
| `support.js` | 執行所需，不要刪 |

三堂也可以單獨開，例如 `.../lesson2.dc.html`。首頁切換課程時網址會帶 `#l1` `#l2` `#l3`，可以直接分享某一堂。

## 注意

- 一定要透過網址開（GitHub Pages 或本機起一個 server），直接用檔案總管點開 `index.html` 會因為瀏覽器安全限制而載不到三堂內容。
  本機預覽：在資料夾裡執行 `python3 -m http.server`，然後開 `http://localhost:8000`。
- 字體是從 Google Fonts 載的，需要連網。

## 免責

本教材為觀念與流程說明，不是投資建議，提到的商品皆為分類舉例，不保證任何報酬。
