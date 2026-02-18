# MES 專業製造執行系統 Landing Page

一個為製造業打造的專業級 MES (Manufacturing Execution System) 著陸頁面，協助企業展示數位轉型解決方案。

## 🎯 專案特色

- **現代化設計**：採用深工業藍配色，呈現專業科技感
- **響應式佈局**：完美適應桌面、平板與手機裝置
- **核心功能展示**：
  - 即時生產監控
  - 全程品質追溯
  - 大數據分析
  - 系統無縫整合
- **純淨技術棧**：HTML5 + CSS3 + Vanilla JavaScript，無需建構工具

## 📁 專案結構

```
mes-landing/
├── index.html      # 主頁面
├── styles.css      # 樣式表
├── main.js         # 互動腳本
└── README.md       # 本檔案
```

## 🚀 快速開始

### 本地預覽

直接開啟 `index.html`：
```bash
open index.html
```

或使用本地伺服器：
```bash
# 使用 Python
python3 -m http.server 8000

# 或使用 Node.js
npx serve
```

然後前往 `http://localhost:8000`

## 🎨 自訂設定

### 修改配色

編輯 `styles.css` 中的 CSS 變數：

```css
:root {
    --primary-color: #0056b3;    /* 主色調 */
    --secondary-color: #6c757d;  /* 次要色調 */
    --accent-color: #00d1b2;     /* 強調色 */
}
```

### 修改內容

直接編輯 `index.html` 中的文字內容，所有文案均使用繁體中文。

## 📦 部署

### GitHub Pages

1. 進入倉庫 Settings → Pages
2. 選擇 `main` branch 作為來源
3. 訪問 `https://yourusername.github.io/ClawAI168/`

### 其他平台

此為靜態網站，可部署至任何靜態託管服務：
- Netlify
- Vercel
- Cloudflare Pages

## 📝 授權

本專案為開源學習用途，歡迎自由修改使用。

---

**建立者**: ClawAI  
**最後更新**: 2026-02-18
