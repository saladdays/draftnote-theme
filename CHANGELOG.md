# Change Log

All notable changes to the "draftnote" extension will be documented in this file.

Check [Keep a Changelog](http://keepachangelog.com/) for recommendations on how to structure this file.

## [0.0.24] - 2026-03-04
### Fixed
- ツールチップやホバーウィジェットの文字が読めない問題を修正しました。
- チャット内のインラインコードのコントラスト比が低い問題を修正しました。
- リンクテキストの視認性が低い問題を修正しました。
- サイドバーのツールバーアイコンが見えにくい問題を修正しました。

### Added
- エディタウィジェット (`editorWidget`, `editorHoverWidget`, `editorSuggestWidget`) の色を明示的に定義しました。
- テキストリンク (`textLink`) の色を定義しました。
- チャットUI (`chat.requestBackground` 等) の色を定義しました。
- コードブロック・整形済みテキスト (`textCodeBlock`, `textPreformat`) の色を定義しました。

## [0.0.19] - 2025-06-22
### Changed
- テーマのベースを、よりモダンなVS Codeの標準テーマ (`light-modern`, `dark-modern`) に変更しました。

## [0.0.16] - 2025-06-22
### Added
- ダークモードに対応しました。(`draft note dark`)
- GitHub Actionsによる自動公開ワークフローを追加しました。

### Fixed
- 拡張機能のデバッグが失敗する問題を修正しました。
- リリースプロセスがCI/CD上で失敗する問題を修正しました。

## [0.0.1 ~ 0.0.15] - 2025-06-07 ~ 2025-06-20
### Added
- 最初のバージョンを公開しました。
- プレーンテキストファイル (`.txt`) でも執筆モードが適用されるようになりました。

### Changed
- `README.md`にスクリーンショットや使い方を追加し、内容を全体的に改善しました。
- ハイライトや選択範囲の色を調整しました。
- 拡張機能のアイコンを追加しました。
