# 杯杯啵啵 Cup Cup Pop 遊戲公告檔

遊戲每次打開首頁、打開信箱、輸入兌換碼時，會讀這裡的 `notice.json`。改完 push 到 main，大約 5 分鐘內生效，不用重新送審。

- `notice`：首頁跳出的公告（同一個 id 每台裝置只顯示一次）
- `minVersion`：低於這個版本的 App 會跳「有新版本囉」
- `codes`：兌換碼（每個碼一個存檔限用一次）
- `mail`：遊戲信箱的信（有 coins／deco 就能領取，每封限領一次）

完整欄位範例見遊戲專案的 `tools/notice-example.json`。
注意：這個 repo 是公開的，裡面的兌換碼任何人都看得到。
