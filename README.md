# TriNetX CSV 檢視與摘要工具

這是一個可直接部署到 GitHub Pages 的純前端網頁工具。使用者上傳 TriNetX 匯出的 CSV 後，可以在瀏覽器內檢視欄位摘要、缺失值、資料預覽與常見值圖表，並匯出 ZIP 或 Word 摘要。

## 線上部署方式

1. 建立一個 GitHub repository。
2. 將這個資料夾內的檔案全部上傳到 repository 根目錄。
3. 到 GitHub repository 的 `Settings` → `Pages`。
4. `Build and deployment` 選擇 `Deploy from a branch`。
5. Branch 選 `main`，資料夾選 `/root`，按 `Save`。
6. GitHub Pages 產生網址後，就能像 `https://帳號.github.io/repository-name/` 一樣線上使用。

## 隱私說明

CSV 檔案只會在使用者自己的瀏覽器中解析，不會上傳到伺服器。若資料含有個資或敏感醫療資訊，仍建議先使用去識別化資料。

