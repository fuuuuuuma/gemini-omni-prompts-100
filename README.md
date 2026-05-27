# Gemini Omni プロンプト100選 — 動画編集 (Video-to-Video) 特化

Gemini Omni（動画編集特化のマルチモーダルAIモデル）向けに、video-to-video編集の現場で使えるプロンプト100選をジャンル別にまとめました。

## このリポジトリは何？

- **対象モデル**: Gemini Omni（動画編集・video-to-video特化）
- **件数**: 100件（10ジャンル × 10プロンプト）
- **言語**: プロンプト本文は日本語
- **用途**: 既存の動画素材を編集・変換する video-to-video の現場プロンプト集

## ジャンル一覧

| # | ジャンル | 軸 | リンク |
|---|---------|-----|--------|
| 01 | スタイル変換 (Style Transfer) | 絵柄・質感の入れ替え | [01-style-transfer.md](prompts/01-style-transfer.md) |
| 02 | シーン拡張・延長 (Frame Extension) | フレームを足す | [02-frame-extension.md](prompts/02-frame-extension.md) |
| 03 | モーション・カメラワーク制御 (Motion / Camera) | 動きを足す・変える | [03-motion-camera.md](prompts/03-motion-camera.md) |
| 04 | 背景・環境置き換え (Background Replacement) | 空間を入れ替える | [04-background-replacement.md](prompts/04-background-replacement.md) |
| 05 | オブジェクト編集 (Object Edit) | 物を編集 | [05-object-edit.md](prompts/05-object-edit.md) |
| 06 | 人物編集 (Character Edit) | 人を編集 | [06-character-edit.md](prompts/06-character-edit.md) |
| 07 | カラーグレーディング (Color Grading / LUT) | 色を編集 | [07-color-grading.md](prompts/07-color-grading.md) |
| 08 | テンポ・速度操作 (Speed / Time Remap) | 時間を編集 | [08-speed-time-remap.md](prompts/08-speed-time-remap.md) |
| 09 | トランジション・継ぎ目編集 (Transition / Morph) | 接続を編集 | [09-transition-morph.md](prompts/09-transition-morph.md) |
| 10 | 短尺SNS向け編集 (Short-form 9:16) | フォーマット最適化 | [10-short-form.md](prompts/10-short-form.md) |

## プロンプトの統一フォーマット

各プロンプトは以下の6項目で統一しています：

| 項目 | 内容 |
|------|------|
| **タイトル** | 何をするプロンプトか |
| **ユースケース** | どんな場面で使うか |
| **入力** | どんな素材を入力するか |
| **プロンプト本文** | コピペで使える日本語プロンプト |
| **コツ** | パラメータ調整や注意点 |
| **ネガティブ** | 排除すべき要素 |

## 使い方

1. ジャンルから目的のプロンプトを選ぶ
2. プロンプト本文を Gemini Omni にコピー＆ペースト
3. 入力動画を添付
4. 必要に応じて数値や具体名を調整（被写体名・色・速度倍率など）

## ライセンス

商用利用可。引用・転載時は本リポジトリへのリンクを推奨します。

## 貢献

プロンプトの追加・修正提案は Issue / Pull Request で歓迎します。
