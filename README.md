# Google Verifiable QCC 技術ガイド

「Google Verifiable Quantum Circuit Compilation — KickMixの3課題を理解する」のPDFと紹介ページを公開する専用リポジトリです。

- 紹介ページ: https://forest1040.github.io/google-verifiable-qcc-guide/
- PDF: https://forest1040.github.io/google-verifiable-qcc-guide/Google_Verifiable_QCC_Technical_Guide.pdf
- 日本語・109ページ・2026年11月13日改訂
- 公開回路の取得日: 2026年10月30日・11月4日・11月13日

invsqrt・dqi・dfthcsos の数学的背景、KickMix回路の構造、回路最適化、費用分析、再現と検証を解説します。詳細な出典・比較条件はPDF本文と付録を参照してください。

## 2026年11月13日改訂

- invsqrtの46量子ビット版、DQIのcutoff、dfthcsosの符号制約を使ったテーブルとローダーの同時設計を追補。
- 11月4日・13日の比較表、検証条件、出典、付録Fの改訂履歴を追加。
- 紹介ページに改訂内容を掲載し、各章と改訂履歴へのPDFリンクを更新。

## 公開・更新

GitHub Pagesで `main` ブランチのルートを配信します。外部依存やビルドは不要です。

PDFを更新する場合は `Google_Verifiable_QCC_Technical_Guide.pdf` を差し替え、紹介ページの改訂日・ページ数・ファイルサイズも更新して `main` にpushしてください。

PDFの元ファイル: `Q-FORGE/docs/book/Google_Verifiable_QCC_Technical_Guide.pdf`。この公開用リポジトリにはPDFと紹介ページのみを収録しています。
