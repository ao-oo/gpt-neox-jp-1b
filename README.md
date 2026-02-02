#gpt-neox-jp-1b

## 概要
本リポジトリは、日本語GPT系言語モデル（GPT-NeoXアーキテクチャ）を
継続事前学習（CPT）およびSFTの検証目的で構築したものです。

## 特徴
- GPT-NeoX ベース（約1Bパラメータ）
- 日本語CPT（Wikipedia / Wikibooks 等）
- FP16 + Gradient Checkpointing による省メモリ学習
- Kaggle T4 ×2 環境での学習実績

## 学習設定
- hidden_size: 1536
- layers: 24
- heads: 16
- context length: 1024

## 学習状況
- 初期PPL: 約20000
- 30分学習後: 約5000

## 注意
本モデルは研究・学習目的であり、商用利用は想定していません。
※2026年2月2日の時点ではまだ完成していません。完成までお待ちください。
