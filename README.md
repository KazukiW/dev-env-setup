# 開発環境整備計画

## 目的
このドキュメントは、マルチプラットフォームに対応した開発環境を整備するための手順をまとめたものです。

---

## フェーズ1：Windowsベースでの基本環境

### 1. Visual Studioの準備
- [x] VsVim をマーケットプレイスからインストール
- [ ] C#拡張機能の導入（例：Roslynator）
    - [ ] Roslynator 2022
- [ ] プロジェクトテンプレートの整備

### 2. フォント設定
- [x] HackGen フォントをインストール
- [ ] VS・PowerShell・Neovimに設定

### 3. Markdown記述環境の整備
- [ ] Markdownプレビュー機能（Markdown All in One など）
- [ ] markdownlint導入
- [ ] 記法ルールをチームで統一

### 4. VsVim設定
- [ ] `.vsvimrc` の作成とカスタマイズ（例：`jj` で Esc）

---

## フェーズ2：macOS対応

### 5. ターミナルとNeovimの整備
- [ ] iTerm2 + HackGen
- [ ] PowerShell Coreインストール
- [ ] Neovimに`packer.nvim`で各種プラグイン導入

---

## フェーズ3：その他の整備（全環境共通）

### 6. Git + GitHubの運用
- [ ] GUIツールまたはCLIの整備
- [ ] リポジトリルールの策定（main/devブランチなど）

### 7. ドキュメントと図解
- [ ] Markdownで各設定の記録
- [ ] MermaidやPlantUMLで構成図を図示
