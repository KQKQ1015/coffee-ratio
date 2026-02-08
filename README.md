# ☕ Coffee Ratio Calculator

毎日のコーヒー抽出をサポートする、シンプルで高速なWebアプリです。
自宅のキッチンで「水650ml : 豆32g」の黄金比率を瞬時に計算するために作成しました。

## 📱 使い方 (Access)

スマホのカメラで以下のQRコードを読み取るか、リンクをクリックしてください。
キッチンにQRコードを貼っておくと便利です。

👉 **[アプリを開く (Launch App)](https://[YOUR_USERNAME].github.io/coffee-ratio/)**

<p align="left">
  <img src="images/qr.png" width="150" alt="QR Code">
</p>

## ✨ 特徴

* **双方向計算:** * 「水」を入力 → 必要な「豆」を算出
    * 「豆」を入力 → 必要な「水」を算出
* **カップモード (Cup Mode):** * マグカップ (250ml) とデミタスカップ (120ml) の杯数を入力して計算可能。
    * 「マグ1杯 + デミタス1杯」のような組み合わせ計算にも対応。
* **最適化された数値:** * 豆は **1g単位**（整数）で表示
    * 水は **10ml単位** で表示
    * キッチンスケールで計りやすい数値に自動で丸めます。
* **入力ガード:** * マイナス値や小数の入力を防ぐUI設計。

## 📸 スクリーンショット

| アプリ画面 |
| --- |
| <img src="images/ui_main.png" width="300" alt="UI Screenshot"> |

## 🛠️ 技術スタック

* **HTML5**
* **JavaScript (ES6)**
* **Bootstrap 5** (Responsive UI)
* **GitHub Pages** (Hosting)

## 📝 黄金比設定

現在の設定比率は以下の通りです。

| 水 (Water) | 豆 (Beans) | Ratio |
| --- | --- | --- |
| 650 ml | 32 g | approx 1 : 20.3 |

---
&copy; 2026 Yura Nishihara