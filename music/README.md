# 配樂庫

這個資料夾放 IP神剪「配樂庫」要用的音樂（mp3）。

- `manifest.json`：歌單。每種風格有一個 `tracks` 陣列，格式：`{ "file": "party-01.mp3", "name": "活力派對 01" }`
- 音樂檔直接放在這個資料夾，檔名和 manifest 裡的 `file` 一致。
- APP 只在學生按「使用」時才下載那一首，所以不會讓 APP 變大。
- 新增歌曲：放入 mp3、在 manifest 補一行，不用更新 APP 版本。
