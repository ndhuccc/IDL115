# 課程工具軟體清單

> 每個工具、每個平台各一個項目。agent 只會從此清單列出的來源下載。

## JianBauDau Player（簡報播放工具）

- 用途：開啟並播放課程簡報檔（`.json` 格式，見 `lectures/`）
- 版本：1.0.0
- 說明：免安裝的可攜版執行檔，下載後雙擊即可執行。

### Windows
- 下載網址：https://github.com/ndhuccc/IDL115/releases/download/player-v1.0.0/JianBauDau-Player-1.0.0.exe
- 檔名：`JianBauDau-Player-1.0.0.exe`
- 大小：112,184,619 bytes（約 107 MB）
- SHA256：`6D1F18FC3F1C126AC7D37CF7441FFAC25D449F89047920096916C81094AB67C1`
- 安裝說明：免安裝。下載後放在任意資料夾，雙擊執行；Windows SmartScreen 若出現警告，請確認檔案雜湊值相符後再選「仍要執行」。
- 驗證指令：`Get-FileHash "JianBauDau-Player-1.0.0.exe" -Algorithm SHA256`（比對上方 SHA256）
- 使用方式：開啟程式後載入簡報 `.json` 檔，可先用 `lectures/sample/backpropagation.json` 測試。

### macOS
- 目前未提供。

### Linux
- 目前未提供。

<!--
新增其他工具時，複製上面的區塊，填入：用途、版本、各平台的
下載網址、檔名、大小、SHA256、安裝說明、驗證指令。
-->
