# 2026 名古屋・伊勢志摩 旅程網站

把這三個檔案（index.html / support.js / trip-data.js）推上 GitHub 後，開啟 GitHub Pages 即可。

## 部署步驟
1. 解壓縮這個 zip
2. 在資料夾內執行：
   ```
   git init
   git add index.html support.js trip-data.js
   git commit -m "japan travel site"
   git branch -M main
   git remote add origin https://github.com/MJJackson0414/japan_travel.git
   git push -u origin main
   ```
3. 到 GitHub repo → Settings → Pages → Source 選「Deploy from a branch」→ Branch 選 main、資料夾選 /(root) → Save
4. 等 1–2 分鐘，網址就是 https://mjjackson0414.github.io/japan_travel/

## 更新行程
之後行程有變動，只要改 trip-data.js 再 push 就會更新（或回來找我同步 Google Sheet）。
