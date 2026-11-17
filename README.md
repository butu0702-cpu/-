# 玉隱 Jade Atelier

以原生 HTML、CSS 與 JavaScript 製作的響應式新中式飾品品牌首頁。無需建置步驟，可直接推送至 GitHub 並匯入 Vercel。

## 本機預覽

直接開啟 `index.html`，或使用任何靜態檔案伺服器預覽。

## 部署至 Vercel

1. 將此資料夾建立 GitHub repository 並推送。
2. 在 Vercel 選擇 **Add New → Project** 並匯入 repository。
3. Framework Preset 選 **Other**；Build Command 留白，Output Directory 設為 `.`，部署即可。

商品、購物車與會員入口目前是前端展示功能。購物車保存於使用者瀏覽器的 `localStorage`；會員登入/註冊、付款與訂單流程需要串接後端及金流服務。社群、LINE 與圖片網址為示意連結，正式上線前請替換成品牌帳號與授權素材。
