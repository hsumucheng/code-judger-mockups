# Code Judger — AI 導師額度管理 UI 模擬

這裡存放 AI 導師額度管理相關功能的前端模擬畫面，供開發時參考；皆為純展示，未串接真實資料與後端 API。


## 檔案對應說明

| 檔名 | 對應畫面 | 說明 | 線上預覽 |
|---|---|---|---|
| `quota-page-mockup.html` | 課程 AI 額度管理（課程列表頁） | 頂部加入總額度 / 已分配 / 未分配三張數據卡片，取代原本純文字列 | [開啟](https://hsumucheng.github.io/code-judger-mockups/quota-page-mockup.html) |
| `quota-ai-tutor-mockup.html` | AI 導師額度管理（單一課程成員列表） | 頂部加入總額度 / 已分配 / 未分配三張數據卡片，取代原本純文字列 | [開啟](https://hsumucheng.github.io/code-judger-mockups/quota-ai-tutor-mockup.html) |
| `disable-ai-tutor-modal.html` | 停用單位 AI 導師 — 防呆視窗（可互動） | 完整三階段流程：選擇是否回收額度（單選）→ 二次確認（含 disabled 防呆邏輯）→ 結果畫面。可直接點擊測試 | [開啟](https://hsumucheng.github.io/code-judger-mockups/disable-ai-tutor-modal.html) |

## 補充

- 配色、字型、元件樣式沿用現有網站的視覺系統（navy / teal / orange / pink），供開發時對照參考。
- `disable-ai-tutor-modal.html` 內建的 Token 數值（例如「本次一併回收 1,000 Token」）為示範用固定值，程式碼裡有加註解標示，實際串接時請帶入真實資料。
