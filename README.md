# HEEEHABABY 買家前台（LINE LIFF）

- `index.html`：前台本體（單檔）。預設 `CFG.mock=false`，經 `/api/v1` 連後端 japan-system；改成 `true` 為示範模式，不連任何後端。
- `vercel.json`：禁止搜尋引擎收錄等安全標頭。
- 正式模式載不到資料時顯示「系統維護中」或「資料載入失敗」，不會退回示範資料。

API 規格見 japan-system 的 BUYER_API_CONTRACT.md。
