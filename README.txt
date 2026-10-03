數學遊戲入口網站

目錄結構：
index.html：入口網站
games.json：遊戲清單
games/fraction-warrior/index.html：分數勇者

之後新增遊戲：
1. 建立新資料夾，例如 games/multiplication-race/
2. 把新遊戲的 index.html 放進去
3. 只在 games.json 加一筆資料，不需要修改入口 index.html 的程式

games.json 範例：
{
  "id": "multiplication-race",
  "title": "乘法賽車",
  "description": "九九乘法競速遊戲",
  "icon": "🏎️",
  "path": "games/multiplication-race/index.html",
  "grade": "小學三年級",
  "subject": "乘法",
  "enabled": true
}
