# Slot 檢查表 GitHub Pages 專案

這是一個可線上預覽的機台設定值檢查表網站。

## 功能說明

- 可選擇機台並載入各自設定表
- 移除簽名與 PDF 下載功能
- 支援 GitHub Pages 部署

## 結構

```
setting-check-full/
├─ index.html              ← 首頁（無簽名版）
├─ assets/
│  ├─ b_boy.htm            ← B Boy 表單
│  ├─ sheet001.htm         ← Jumbo Slot 表單
│  ├─ stylesheet.css
│  ├─ tabstrip.htm
│  └─ filelist.xml
```

## 部署方式

1. 將所有檔案上傳至 GitHub Repository
2. 開啟 GitHub Pages（Branch: `main`，Folder: `/root`）
3. 開啟網址 `https://你的帳號.github.io/專案名稱/` 預覽頁面
