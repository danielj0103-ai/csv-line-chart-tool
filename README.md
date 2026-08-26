# CSV 折線圖產生器

單一自包含 HTML 的 CSV → 折線圖工具（Chart.js），雙擊 `CSV_折線圖產生器.html` 即可用瀏覽器開啟。

## 檔案

| 檔案 | 說明 |
|---|---|
| `CSV_折線圖產生器.html` | 主工具（所有功能都在這一檔） |
| `CSV_折線圖產生器_使用說明書.docx` | Word 使用手冊（8 章） |
| `CSV_折線圖產生器_使用教學.pptx` | 教學簡報（8 頁，含 Daniel 語音旁白） |
| `CSV_折線圖產生器_使用教學_auto.pptx` | 自動播放版（切頁即播旁白） |

## 功能速覽

- CSV 載入（Big5）、自動偵測時間/數值欄位、疊圖＋個別圖（2×2 分頁）
- 拖曳框選 XY 縮放、Shift 平移、TradingView 式多圖 X 軸同步、hover 十字準線同步
- 斜率迴歸、上下限警示、壓差曲線、Plotline 點擊讀值
- 深/淺色主題切換
- 雙擊 X 軸／Y 軸手動輸入顯示範圍；「↺ 重設」完整還原初始狀態

## 維護

- 修改前先讀 skill：`~/.config/opencode/skills/csv-chart-tool/`（內含 code-map.md 程式碼地圖）
- 此 repo 以白名單 .gitignore 只追蹤上述 4 個檔案，D:\OpenCode 下其他檔案一律不入庫
