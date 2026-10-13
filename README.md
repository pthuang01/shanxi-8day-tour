# 晉善晉美・山西全覽 8 日深度探索之旅 ｜ 專屬行程網頁

> 🏛️ 專為 GitHub Pages 設計的單一高質感響應式旅遊體驗網頁，融合東方美學與現代編輯設計，完整收錄航班資訊、8日每日行程、精選住宿與實景攝影

---

## 🌟 網頁核心特色

1. **東方古典奢華美學（Oriental Luxury Aesthetics）**：
   - 採用黛墨黑、青瓦灰、硃砂紅與帝王金配色體系
   - 導入 Google Fonts 的古典書法襯線字體（`Noto Serif TC`）搭配現代易讀字體（`Noto Sans TC`）
2. **實景風光相簿與全螢幕燈箱（Lightbox Gallery）**：
   - 完整收錄雲岡石窟、懸空寺、應縣木塔、雁門關、五台山、晉祠、平遙古城、黃河壺口瀑布等代表性高解析度實景照片
   - 點擊任一張照片即可開啟互動燈箱大圖欣賞
3. **直覺化交通與航班儀表板**：
   - 去回程航班時刻（起飛/抵達時間、班次、航線進度條）清晰視覺化
   - 標示第 7 天「高鐵體驗」與「大件行李專車直送太原」的貼心安排
4. **互動式 8 日時光軸與天數懸浮導覽（Sticky Day Nav）**：
   - 頂部設有天數快速跳轉按鈕，畫面滾動時自動高亮當前瀏覽日程
   - 每日行程皆詳細列出餐食規劃（早、中、晚）與當日下榻之五星級標準酒店參考
5. **本地實景圖庫架構（Zero External Dependency）**：
   - 所有圖片均內建於專案 `images/` 目錄，推送至 GitHub Pages 即可直接加載，無外部防盜鏈風險

---

## 🚀 如何部署至 GitHub Pages

依照以下步驟，即可將此網頁發布為公開的網站：

### 方法一：透過 Git 指令（推薦）

1. 開啟終端機（Terminal / PowerShell），進入本專案資料夾：
   ```bash
   cd "C:\Users\pthua\Downloads\山西全覽8日"
   ```

2. 初始化 Git 倉庫並提交：
   ```bash
   git init
   git add .
   git commit -m "feat: 初次發布山西全覽8日行程網頁"
   ```

3. 在 GitHub 上建立一個新的公開倉庫（Repository，例如命名為 `shanxi-8day-tour`）

4. 將本機倉庫與 GitHub 遠端關聯並推送：
   ```bash
   git remote add origin https://github.com/<您的GitHub帳號>/<您的專案名稱>.git
   git branch -M main
   git push -u origin main
   ```

5. 開啟 GitHub 倉庫的 **Settings** ➔ 點選左側選單的 **Pages**：
   - 在 **Branch** 選擇 `main` 分支，資料夾選擇 `/ (root)`
   - 點擊 **Save**
   - 等待約 1~2 分鐘，即可獲得您的專屬網址：
     `https://<您的GitHub帳號>.github.io/<您的專案名稱>/`

---

### 方法二：透過 GitHub 網頁直接上傳

1. 登入 GitHub 並建立新倉庫（如 `shanxi-8day-tour`）
2. 點擊 **"uploading an existing file"**
3. 將資料夾中的 `index.html`、`images` 與 `README.md` 拖曳上傳並 Commit
4. 進入 **Settings ➔ Pages**，在 Branch 選擇 `main` / `root` 並存檔，即完成發布
