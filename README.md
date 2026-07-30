# PenaUtilityTool

> 『ペナントシミュレーション3』のセーブデータを、外部からもっと便利に扱うための非公式デスクトップツールです。
> 選手データの確認・編集、CSV出力、装備、ガチャ、再建モード、AI連携、ブックメーカーなど、遊び方を広げる機能をまとめています。

## 主な機能

- 選手能力や成績の検索・確認・編集
- 成績CSV、選手紹介、選手名鑑の出力
- オリジナル選手と監督の作成
- 引退選手の削除・現役復帰
- 装備の作成・管理・ガチャ
- 打順自動編成と再建モード
- ブックメーカーと収支管理
- CSVやJSONを利用したAI連携

## ダウンロード

[Releases](https://github.com/Munchi369/PenaUtilityTool/releases)から、最新版のZIPファイルをダウンロードしてください。

[最新版をダウンロード](https://github.com/Munchi369/PenaUtilityTool/releases/latest)

バージョンごとの追加機能、変更点、修正内容もReleasesで確認できます。

## 導入方法

### 1. ZIPファイルを解凍

ダウンロードしたZIPファイルを解凍します。

### 2. ゲーム本体と同じ階層に配置

解凍してできた `PenaUtilityTool` フォルダを、`penanto3` フォルダと同じ階層に配置してください。

```text
ペナントシミュレーションのフォルダ/
├── penanto3/                   ← セーブデータフォルダ
├── ペナントシミュレーション.exe
└── PenaUtilityTool/            ← ここに配置
```

### 3. ゲームを終了してツールを起動

ゲーム本体を終了し、バックアップを取ってからPenaUtilityToolを起動します。

ゲーム本体は、がらくた様のホームページからダウンロードしてください。

[がらくたのペナントシミュレーション](http://garakutapsg.web.fc2.com/)

## 使用前の注意

> [!WARNING]
> 本ツールはセーブデータを直接操作します。
> 使用前にゲームを終了し、必ず `penanto3` フォルダをバックアップしてください。

- 非公式ツールです
- 『ペナントシミュレーション3』`ver3.4.11` にのみ対応しています
- 操作内容によっては、ゲーム進行やセーブデータに影響する可能性があります

本ツールの使用によって発生したセーブデータの破損、ゲーム進行への影響、その他のトラブルについて、ツール作者は責任を負いかねます。

## AI連携

成績CSVをAIへ添付してチーム分析やスポーツ新聞風の記事を作成したり、AIで作成した選手JSONをツールへ読み込んだりできます。

- [ペナントアナライザー](https://gemini.google.com/gem/1xP2v2rdmKMHDbgBi32vhxhaXjpyG7ixg?usp=sharing)
- [ペナスポ新聞](https://gemini.google.com/gem/1MArcXqowWeQMXKRYBxOdGmEOKDdj9C51?usp=sharing)
- [新規選手作成クン](https://gemini.google.com/gem/1dTLW9VlQrbvZ231JUcHUcMAzdK8QRcoP?usp=sharing)

Gemini Gemの利用にはGoogleアカウントが必要です。AIが生成した選手データは、登録前にチーム、ポジション、能力、プロフィールを確認してください。

## 詳しい使い方

各機能の操作方法、AI連携、トラブル時の復旧方法、上級者向けの装備仕様はWikiにまとめています。

[PenaUtilityTool Wiki](https://github.com/Munchi369/PenaUtilityTool/wiki)

- [はじめに・導入](https://github.com/Munchi369/PenaUtilityTool/wiki/getting-started)
- [選手関連機能](https://github.com/Munchi369/PenaUtilityTool/wiki/player-features)
- [成績・CSV機能](https://github.com/Munchi369/PenaUtilityTool/wiki/stats-and-csv)
- [選手・監督作成](https://github.com/Munchi369/PenaUtilityTool/wiki/player-and-manager-creation)
- [装備・ガチャ](https://github.com/Munchi369/PenaUtilityTool/wiki/equipment-and-gacha)
- [編成・再建モード](https://github.com/Munchi369/PenaUtilityTool/wiki/lineup-and-rebuild)
- [ブックメーカー](https://github.com/Munchi369/PenaUtilityTool/wiki/bookmaker)
- [AI連携](https://github.com/Munchi369/PenaUtilityTool/wiki/ai-integration)

## 問題が起きた場合

通常の画面操作で解決できない装備・旧データの問題は、Wikiの[データベースメンテナンス](https://github.com/Munchi369/PenaUtilityTool/wiki/database-maintenance)を確認してください。

データ削除やテーブル再構築を含むため、内容が分からない場合は実行せず、バックアップを保持してください。

## 禁止事項

以下の行為は禁止されています。

- 本ツールの逆コンパイル
- 改変
- 再配布
