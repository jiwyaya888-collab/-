# NAI 生圖腳本：pkppkq 相容版

基於 [sanmingyue/tavern_dist nai-v1.0.1](https://github.com/sanmingyue/tavern_dist/tree/nai-v1.0.1) 的 NAI 生圖腳本修改，原作者 sanmingyue。本倉庫提供第三方相容修改，非官方發布。

酒館助手腳本內容可填入：

```js
import 'https://testingcf.jsdelivr.net/gh/jiwyaya888-collab/-@main/nai-pkppkq.js';
```

不要同時啟用原版。開啟「NAI設置 → 設置」，點「使用 pkppkq 共享站」，填入該站提供的 API Key，使用 Bearer 鑑權，再按「測試生圖」。測試會送出實際請求，可能消耗額度。

新增站點切換、Base URL 補全、跨站切換清空 Key，以及錯誤診斷提示。保留原版的提示詞、角色構圖、快取、重繪及下載功能。

已通過 JavaScript 語法與端點補全／Key 切換檢查，並確認共享站端點的無 Key 請求回傳 401 及跨域預檢可用。尚未使用有效 Key 驗證出圖；支援原版 PNG/WebP/ZIP 回應。

Key 由使用者在本機設定，程式不內含任何個人 Key。共享站費用以網站規則為準，無法保證避免帳號封禁。詳細說明見「使用說明.txt」。