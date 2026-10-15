# 歐小麥老師的 AI 教學天地

課堂小遊戲首頁。學生掃 QR Code 進入首頁，再點遊戲卡片開始玩。

## 新增遊戲的方法
1. 新增資料夾 `games/你的遊戲英文名/`，把遊戲 `index.html` 放進去。
2. 打開首頁 `index.html`，找到 `const games = [`，加一筆：
```js
{ title: '遊戲名稱', emoji: '🍕', href: 'games/你的遊戲英文名/', desc: '簡介', tags: [['數學','#']] }
```
3. 重新部署即可。

## 本地預覽
直接用瀏覽器開啟 `index.html`。
