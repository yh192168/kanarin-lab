# かなりん研究所 Version 1 Starter

静的サイト骨格です。外部通信、AI自動公開、BBSバックエンドはまだ有効化していません。

## ローカル起動

```sh
python3 -m http.server 8000
```

`http://localhost:8000/enter.html` を開きます。`file://` ではJSON取得が制限されるため、HTTPサーバーを使用してください。

## GitHub Pages

リポジトリ直下へ内容を配置し、Settings > Pages でbranchを公開します。リンクは相対パスなのでProject Pagesでも動作します。

## 安全上の状態

- AI自動公開: 無効
- BBS/訪問帳/Web拍手: 閲覧用プレースホルダー
- 外部API: 未接続
- APIキー: なし
- Animation: ボタンまたはprefers-reduced-motionで停止可能
