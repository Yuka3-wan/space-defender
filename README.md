# Space Defender - ブラウザシューティングゲーム

シンプルなブラウザベースのシューティングゲームです。

## 特徴

- 🚀 カスタムロケット画像
- 💥 パーティクルエフェクト
- 🌟 動く星空の背景
- ❤️ 3つのライフシステム
- 📈 スコアに応じた難易度上昇
- 🛡️ 被弾後の無敵時間

## 操作方法

- **←→** : 左右移動
- **SPACE** : 弾を発射

## プレイ方法

1. ファイルを直接ブラウザで開く
   ```
   shooting-game.html
   ```

2. または、HTTPサーバーを起動
   ```bash
   python3 -m http.server 8000
   ```
   ブラウザで `http://localhost:8000/shooting-game.html` にアクセス

## ファイル構成

- `shooting-game.html` - ゲーム本体（HTML/CSS/JavaScript）
- `rocket.png` - プレイヤーのロケット画像

## 技術スタック

- HTML5 Canvas
- Vanilla JavaScript
- CSS3（アニメーション、グラデーション）