# Travel Wallet｜旅遊資料夾

手機優先的旅遊資料管理 PWA。

## 第一版功能
- 多趟旅行建立與切換
- 航班、住宿、票券／QR Code、網路／eSIM、餐廳、交通、重要文件、其他分類
- 新增、編輯、刪除資料
- 網址、備註、圖片／PDF 附件
- 相機拍照入口（支援的手機瀏覽器）
- 搜尋、使用狀態管理
- JSON 備份匯出
- PWA 基礎離線快取

## 目前限制
此 MVP 將資料存在瀏覽器 localStorage，附件限制 3MB。資料不會跨裝置同步。正式雲端同步需另行設定 Firebase Authentication、Firestore、Storage 與安全規則。

## 部署
GitHub Pages 可將此 Repository 的 Pages Source 設為 Deploy from a branch，選擇 main / root。
