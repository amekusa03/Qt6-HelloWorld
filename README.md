# Qt6 HelloWorld サンプルアプリケーション

このリポジトリは Qt 6 を使用した最小構成の "Hello World" デスクトップアプリケーションです。

アプリを Qt Creator でビルドし、ウィンドウに `Hello World` と表示されるだけの簡単なサンプルです。

- 対象プラットフォーム: **Linux (Ubuntu にて動作確認済み)**
- 開発環境: Qt Creator と Qt 6.x
- リポジトリ: https://github.com/amekusa03/Qt6-HelloWorld

## Qiita記事

[本ツールの解説記事 (Qiita)](https://qiita.com/amekusa03/items/79fe702be160c37c06c8)

## 紹介動画

[![紹介動画](https://img.youtube.com/vi/v86BQykeWFY/maxresdefault.jpg)](https://youtu.be/v86BQykeWFY?si=ZmMB2RJrHV_AEl-Z)

## 🛠 動作確認手順

1. Qt Creator をインストールします（Qt 6.10.2 など）。
2. このリポジトリをクローンします。

```bash
git clone https://github.com/amekusa03/Qt6-HelloWorld.git
cd Qt6-HelloWorld
```

3. Qt Creator で `CMakeLists.txt` を開き、ビルド設定を行います。
4. デバッグ / リリースビルドを実行すると、ウィンドウが立ち上がり "Hello World" と表示されます。

## 📦 依存関係

Qt 6 ライブラリが必要です。Ubuntu では公式リポジトリまたは Qt のインストーラからインストールします。

## 📄 ライセンス

このプロジェクトは [MIT License](LICENSE) の下で公開されています。

Qt 関連のライブラリは [LGPLv3](https://www.gnu.org/licenses/lgpl-3.0.html) に準拠しています。

---

## 備考

簡易サンプルのためソースは `main.cpp` と `Main.qml` のみで構成されています。
ビルド済みバイナリはリポジトリに含まれていません。

ご自由にフォーク・改変して学習にお役立てください。

