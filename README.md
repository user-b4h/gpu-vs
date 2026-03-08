# NVIDIA GPU Performance Comparison Tool

NVIDIAの歴代GPU、全69モデルの相対性能を瞬時に比較できる、軽量・高機能なWebツールです。3DMark Time Spyのスコアをベースに、アーキテクチャやVRAM、TDPなどのスペックを横並びで確認できます。

## 🚀 特徴

* **豊富なデータベース**: 最新の RTX 50シリーズ（予測値）から、懐かしの GTX 600シリーズまで、計69モデルを網羅しています。
* **直感的なUI**: Tailwind CSSを使用したモダンなダークデザインで、モバイル・PC両方のブラウザに対応しています。
* **リアルタイム比較**: 2つのGPUを選択するだけで、性能差（倍率やパーセント）を動的なバーチャートで可視化します。
* **詳細スペック表**: アーキテクチャ、ビデオメモリ（VRAM）、消費電力（TDP）の主要項目を直接比較可能です。

## 📊 収録データシリーズ

* GeForce RTX 50 Series (Blackwell - 予測値含む)
* GeForce RTX 40 Series (Ada Lovelace)
* GeForce RTX 30 Series (Ampere)
* GeForce RTX 20 Series (Turing)
* GeForce GTX 16 Series (Turing)
* GeForce GTX 10 Series (Pascal)
* GeForce GTX 900 Series (Maxwell)
* GeForce GTX 700 Series (Kepler/Maxwell)
* GeForce GTX 600 Series (Kepler)

## 🛠 テクノロジー

* **Frontend**: HTML5, JavaScript (Vanilla JS)
* **Styling**: [Tailwind CSS](https://tailwindcss.com/)

## 📖 使い方

1. `index.html` をブラウザで開きます。
2. 「GPU A (基準)」と「GPU B (比較対象)」をドロップダウンメニューから選択します。
3. 選択すると即座に、相対性能グラフとスペック表が更新されます。

## ⚠️ 注意事項

* 性能スコアは **3DMark Time Spy Graphics Score** に基づいた相対的な推定値です。実際の環境（CPUやゲームの種類）により結果は異なります。
* RTX 50シリーズおよび一部未発売モデルの仕様は、現時点での予測値を含みます。

## 📄 ライセンス

このプロジェクトは MIT ライセンスの下で公開されています。
