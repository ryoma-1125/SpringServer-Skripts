# SpringServer-Skripts

![Minecraft Version](https://img.shields.io/badge/Minecraft-1.21.11-green.svg)
![License](https://img.shields.io/badge/License-MIT-blue.svg)

`mc.sps-server.net` で実際に運用されている、独自の便利機能や移動ギミックを実装した Skript 集です。
サーバー運営の効率化や、プレイヤーへ新しい移動体験を提供することを目的として作成・公開しています。

## 収録スクリプト紹介

### 1. IronElevator (鉄ブロックエレベーター)
鉄ブロックを垂直に配置するだけで、スムーズな上下移動が可能になります。
- **上昇**: 鉄ブロックの上でジャンプ
- **下降**: 鉄ブロックの上でスニーク
- **特徴**: 上下100ブロックの範囲にある鉄ブロックを自動探索し、テレポートします。

### 2. JumpPad (ジャンプパッド)
感圧版の下に特定のブロックを設置することで、移動アクションを発動します。
着地するまで落下ダメージが無効化されるため、安全に高速移動が可能です。
- **金ブロック**: 垂直方向に大きく上昇
- **鉄ブロック**: 視線に左右されない強力な水平加速
- **ダイヤモンド**: 視線の方向へ高速移動（ベクトル移動）
- **エメラルド**: 空中浮遊と緩やかな滑空
- **石炭**: 小さな垂直ジャンプ

---

## 導入方法

1. サーバーに [Skript](https://github.com/SkriptLang/Skript/releases) プラグインが導入されていることを確認してください。
2. 本リポジトリから必要な `.sk` ファイルをダウンロードします。
3. `/plugins/Skript/scripts/` フォルダの中にファイルを配置します。
4. サーバー内で `/sk reload <ファイル名>` を実行すれば完了です。

---

## 実機での体験
これらの機能は、私が運営するサーバーにて実際に体験することが可能です。
- **Server IP**: `mc.sps-server.net`
- **Official Site**: [sps-server.net](https://sps-server.net)

---

## ライセンス
このプロジェクトは **MIT License** の下で公開されています。
改変、再配布、商用利用など、自由にご利用いただけます。

## 作者
- **Name**: ryoma_1125
- **X (Twitter)**: [@ryoma_1125](https://x.com/ryoma_1125)
- **GitHub**: [ryoma-1125](https://github.com/ryoma-1125)

ご質問やバグ報告は X の DM までお寄せください。
