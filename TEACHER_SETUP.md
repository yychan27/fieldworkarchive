# 教師設定指南

## 啟用 GitHub Pages

1. 進入 repository。
2. 打開 **Settings → Pages**。
3. 在 **Build and deployment** 的 Source 選擇 **Deploy from a branch**。
4. Branch 選 `main`，Folder 選 `/(root)`。
5. 按 **Save**。
6. 網站網址為 `https://hsurae.github.io/fieldworkarchive/`。

第一次發布可能需要約 10 分鐘。

## 把 repository 設為模板

1. 打開 **Settings → General**。
2. 在 repository 名稱下方找到 **Template repository**。
3. 勾選它。
4. 回到 repository 首頁後，應會看到綠色的 **Use this template** 按鈕。

## 給學生的唯一命名規則

所有學生都將自己的 repository 命名為 `fieldworkarchive`。帳號不同，因此不會衝突。這使 `_config.yml` 中的網址設定可以直接沿用，不需每人修改程式。

## 之後修改每週題目

- 首頁卡片文字：修改 `index.md`。
- 每週內容：修改 `weeks/week-XX.md`。
- 顏色與版面：修改 `assets/css/style.css`。
- 課程名稱與網址設定：修改 `_config.yml`。

