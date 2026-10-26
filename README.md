# PCK Studio Web

ブラウザでPCKファイル（Minecraft Legacy Console Edition 形式）を編集できるWebツールです。
テクスチャやオーディオを含まない、スキンパックの編集・作成向けです。

[Web PCK Editor](https://github.com/HINATIR/Web-PCK-Editor)（HINATIR 作）を改変したものです。

## 追加・変更した点

- スキンの複製（一覧の ⧉ ボタン、右クリックメニュー、スキン設定パネル）。複数個まとめて複製でき、ID は自動で振り直します
- スキン設定パネル（名前・テーマ名・スキンID・ANIM の編集、画像の置き換え）。変更は .loc にも反映されます
- 他のPCKからのプロパティのコピー（プレビュー付き）
- 他のPCKからのアセットの取り込み（プレビュー付き。ID の重複は自動で振り直し、マントと名前も一緒に取り込めます）
- PCK内（Skins.pck など）のスキンのプロパティ編集が保存されない問題の修正

## 使い方

`index.html`（公開時は `index.html` などにリネーム）をブラウザで開きます。

## ライセンス

GNU General Public License v3.0 (GPL-3.0) です。詳細は [LICENSE](LICENSE) を参照してください。

## 元のプロジェクトと参考資料

- **Web PCK Editor** (GPL-3.0) — https://github.com/HINATIR/Web-PCK-Editor
- **PCK-Studio** (GPL-3.0) — https://github.com/LCERD/PCK-Studio
  Authors: PhoenixARC, MayN-L, NessieHax, EternalModz, and contributors
- **OMI-Filetype-Library** (GPL-3.0) — https://github.com/LCERD/OMI-Filetype-Library
  Authors: NessieHax, PhoenixARC, MayN-L, Bagietas
