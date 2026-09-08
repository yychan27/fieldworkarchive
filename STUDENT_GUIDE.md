# 學生操作指南｜只使用 GitHub 網頁版

## 第一次建立網站

1. 打開老師提供的模板網址。
2. 按右上方綠色的 **Use this template**。
3. 選擇 **Create a new repository**。
4. Repository name 必須填入 `fieldworkarchive`。
5. 選擇 **Public**，再按 **Create repository**。
6. 進入自己的 repository 後，打開 **Settings → Pages**。
7. 在 **Build and deployment** 中選擇 **Deploy from a branch**。
8. Branch 選 `main`，Folder 選 `/(root)`，按 **Save**。
9. 網站網址會是 `https://你的帳號.github.io/fieldworkarchive/`。

網站第一次發布或更新可能需要約 10 分鐘。

## 每週修改文字

1. 進入 repository 的 `weeks` 資料夾。
2. 打開本週檔案，例如 `week-01.md`。
3. 按右上角鉛筆圖示 **Edit this file**。
4. 替換提示文字。
5. 按 **Commit changes…**。
6. Commit message 寫清楚，例如 `Update week 01 fieldnote`。
7. 再按一次綠色的 **Commit changes**。

## 上傳圖片

1. 回到 repository 首頁。
2. 打開 `assets/images`。
3. 按 **Add file → Upload files**。
4. 上傳圖片後按 **Commit changes**。
5. 圖片檔名請使用英文、數字與連字號，例如 `w01-classroom-map.jpg`，不要使用空格。
6. 回到本週 `.md` 檔案，在適當位置加入：

```markdown
![圖片說明]({{ '/assets/images/w01-classroom-map.jpg' | relative_url }})
```

把檔名換成自己剛上傳的檔名。每張圖片都要寫出具體的圖片說明。

## 每週內容

- `TRACE｜痕跡`：1–3 張圖片。
- `FRICTION｜摩擦`：描述一個沒有如預期發生的瞬間。
- `CONNECTION｜連結`：以本週閱讀中的一個概念重新理解它。
- `NEXT MOVE｜下一步`：說明下一個創作測試。

每週約 150–300 字即可。這不是完成作品的展示，而是保存思考如何改變的過程。

## 公開紀錄倫理

- 未經同意，不得公開可辨識的田野參與者。
- 不得公開私人地址、敏感位置或可造成傷害的資訊。
- 必要時應模糊、裁切、匿名，或使用另外製作的圖像替代。
- 上傳前先問：這張圖片是否只有我有權決定公開？

