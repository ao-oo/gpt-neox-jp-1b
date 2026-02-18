## gpt-neox-jp-1b

## 概要
本リポジトリは、日本語GPT系言語モデル（GPT-NeoXアーキテクチャ）を
継続事前学習（CPT）およびSFTの検証目的で構築したものです。

## 特徴
- GPT-NeoX ベース（約1Bパラメータ）
- 日本語CPT（Wikipedia / Wikibooks / c4 / JaMARD）
- Kaggle T4 ×2(GPU)
- Kaggle v5e-8(TPU) 環境での学習

## モデル構成（概要）
- Architecture: GPT-NeoX
- Parameters: ~1B
- Hidden size: 1536
- Layers: 24
- Attention heads: 16
- Context length: 1024

## 注意
- 本モデルは研究・学習目的であり、商用利用は想定していません。

## ステータス
- 本モデルは現在も学習および調整途中です。
研究検証を目的として公開しており、
今後も更新される可能性があります。

## ライセンス
- 本リポジトリのコードは MIT License です。
学習済みモデルについては研究目的での利用を想定しています。
