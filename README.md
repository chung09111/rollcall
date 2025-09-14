
# 安和點名（整頁滾動＋控制區可捲走 版）

這個版本：
- 使用瀏覽器右側整頁捲軸（不限制表格高度）。
- 移除 sticky/fixed，控制區會跟著捲走消失。
- 具備動態監看，避免控制區被 JS 重新設成 sticky。

## GitHub Pages 部署
1. 建立公開 repo（例如 `anhe-attendance-fullpage`）。
2. 上傳 `index.html` 與 `README.md` 到 **repo 根目錄**。
3. 進 repo → **Settings → Pages**：
   - Source：**Deploy from a branch**
   - Branch：選 `main`（或 `master`），資料夾選 `/`（root）
4. 等待數十秒，會出現網址：`https://<你的帳號>.github.io/anhe-attendance-fullpage/`

## Google Sites 內嵌建議
- 內嵌區塊高度拉到 **900–1200px**，可同時看到工具列與多列名單。
- 名單再長都用整頁捲軸滑動。

## 使用
- 開頁面 → 按「從雲端載入名單」→ 選日期/場次 → 按「啟用雲端同步」。
- 權限在試算表 `Roles` 分頁設定（`admin`/`marker`/`viewer`）。
