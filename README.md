# UrKeyboard 官方網站

UrKeyboard Android 輸入法的官方介紹網站，透過 GitHub Pages 部署。

## 頁面結構

| 檔案 | 說明 |
|------|------|
| `index.html` | 產品首頁（Hero、功能介紹、比較表） |
| `guide.html` | 使用說明目錄（28 篇文章） |
| `privacy-policy.html` | 隱私權政策 |
| `css/style.css` | 共用樣式（行動優先） |
| `images/` | APP 截圖素材（待補） |

## 待補項目

- [ ] `images/` 目錄：APP 實機截圖（鍵盤、功能、主題）
- [ ] `index.html`：Hero 區截圖、主題輪播截圖
- [ ] Google Play 連結：確認 App ID 後更新各頁面的下載按鈕

## 本機預覽

直接用瀏覽器開啟 `index.html` 即可預覽，無需任何建置工具。

## 部署（GitHub Pages）

1. 在 GitHub 建立 `urkeyboard-website` repository（public）
2. 推送此目錄的所有內容
3. 前往 repo Settings → Pages → Source：選 `main` branch，根目錄 `/`
4. 啟用後網址為 `https://zhihmeng.github.io/urkeyboard-website/`

## 自訂網域設定

若要使用 `urkeyboard.molioapp.com`：

1. 在 DNS 管理介面（你的網域商）新增一筆記錄：
   ```
   類型：CNAME
   名稱：urkeyboard
   內容：zhihmeng.github.io
   ```
2. `CNAME` 檔案已設定為 `urkeyboard.molioapp.com`
3. 在 GitHub Pages 設定中填入自訂網域，等待 DNS 生效（通常 30 分鐘內）
4. 勾選「Enforce HTTPS」
