# ONE PIECE 角色競標大戰

這個版本將原本嵌入 `index.html` 的 81 張角色圖片拆成獨立檔案。

## 結構

```text
one-piece-auction/
├── index.html
├── assets/
│   └── images/
│       ├── Miss_Goldenweek.jpg
│       └── ...
└── README.md
```

## 使用方式

直接用瀏覽器開啟 `index.html` 即可。

若放到 GitHub Pages，將整個資料夾內容推送到 repository 後即可由 Pages 提供網站。

## 注意

遊戲仍使用 PeerJS CDN，因此多人連線功能需要能連到網路。
角色圖片已改為相對路徑，不再以 Base64 方式塞進 HTML。
