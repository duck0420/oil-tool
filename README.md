# ☕ 油資申請工具

外勤人員的油資計算與報表自動化工具 — 日曆式登錄、自動統計、一鍵匯出 Excel。

**[🎨 線上示範](https://duck0420.github.io/oil-tool/demo.html)** | **[🔗 使用工具](https://duck0420.github.io/oil-tool/)**

## 功能

- 📅 日曆式外勤登錄，預設路線一鍵套用
- 🚗 汽機車獨立里程計算，自動切換
- 📊 月結自動統計：工作天數、總里程、預估油資
- 📥 一鍵匯出 Excel（外勤工作表＋申請差旅費，含簽名欄）
- 🖨️ 直接列印申請差旅費報表
- ☁️ Firebase 即時雲端同步（跨裝置自動更新）
- 👥 多人支援，獨立資料儲存

## 技術棧

| 技術 | 用途 |
|------|------|
| 純 HTML/CSS/JS | 零框架單頁應用 |
| SheetJS (xlsx) | Excel 匯出（樞紐格式） |
| Firebase Realtime DB | 跨裝置即時同步 |
| GitHub Pages | 免費部署 |
| localStorage | 離線快取 |

## 使用

直接開啟 `index.html` 或訪問 GitHub Pages。

示範頁面 `demo.html` 內含虛構資料，可直接體驗功能。
