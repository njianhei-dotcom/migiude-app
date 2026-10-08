# 右腕

今日の予定・ToDo、ジムの営業時間、トレーニング記録と種目の参考リンクを、ネットなしで見られる自分用アプリ。

- データはスマホのブラウザの中（localStorage / IndexedDB）だけに保存される。このリポジトリには個人データを入れない。
- `index.html` を変えたら `sw.js` の `VERSION` を上げる（スマホが新しい版を取り込むため）。
- 取り込み形式：`{"migiude":1,"events":[],"todos":[],"days":[],"exercises":[],"schedules":[],"delete":{}}`
