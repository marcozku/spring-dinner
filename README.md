# 春茗晚宴工具 - GitHub Pages 部署指南

## 📁 文件位置
所有文件已準備在：
```
/Users/myopenclaw/.openclaw/app/public/spring-dinner/
├── counter.html (收買佬記數器)
└── bingo.html (Bingo 抽獎器)
```

---

## 🚀 部署步驟（5 分鐘完成）

### 方案 1：使用 GitHub 網頁界面（推薦）

1. **登入 GitHub**
   - 訪問：https://github.com/login
   - 使用你的 GitHub 帳號登入

2. **創建新倉庫**
   - 點擊 "New repository"
   - 倉庫名稱：`spring-dinner`
   - 設置為 Public
   **✅ 勾選 Initialize this repository with a README**
   - 選擇 "Code" 選項
   - 上傳這兩個 HTML 文件

3. **上傳文件**
   - 點擊 "uploading an existing file"
   - 上傳 `counter.html` 和 `bingo.html`

4. **啟用 GitHub Pages**
   - 進入 Settings → Pages
   - 點擊 "Enable GitHub Pages"
   - Source: `main` 分支
   - Root: `/` (根目錄)
   - 點擊 "Save"

5. **等待部署**
   - 幾分鐘後獲得 URL
   - `https://mxxkm.github.io/spring-dinner/`

---

### 方案 2：使用 Git CLI（熟悉 Git）

```bash
cd /Users/myopenclaw/.openclaw/app/public/spring-dinner
git init
git add .
git commit -m "Add 春茗晚宴工具"
git branch -M main
git remote add origin https://github.com/mxxkm/spring-dinner.git
git push -u origin main
```

---

## ✅ 部署完成後

你會獲得：
- 🔗 **收買佬記數器：** `https://mxxkm.github.io/spring-dinner/counter.html`
- 🎱 **Bingo 抽獎器：** `https://mxxkm.github.io/spring-dinner/bingo.html`
- 🌐 **全球 CDN 加速**
- 🔒 **HTTPS 加密**
- 💰 **完全免費**

---

## 📱 測試工具

部署後請測試：
1. 能否正常選擇 3 張枱計分
2. 能否正常抽獎 Bingo 號碼
3. 手機版是否正常顯示

如果一切正常，就可以將 URL 分享俾賓客使用！

---

## 📝 備注
- 如果需要自訂域名，可以在 GitHub Pages 設置中添加 CNAME
- 建議使用 `spring-dinner` 作為倉庫名稱，簡潔易記
- 所有工具都係離線可用，無需網絡連接