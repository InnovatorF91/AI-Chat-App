# 📁 リリース版をダウンロードするには、以下にアクセスしてください。 https://github.com/InnovatorF91/AI-Chat-App/releases/tag/v1.0.0-beta

# 🧠 AI Chat App – UnityのマルチモーダルAI対話システム。

AIチャットアプリはUnityで作られたAIチャットアプリケーションで、テキスト、画像生成、画像のドラッグ＆ドロップ表示、モデル切り替えをサポートし、OpenAI APIを統合してデスクトップアプリケーションとして独立して動作します。

## ✨ 機能性 Features

- 💬 **ChatGPT / DeepSeek AIとの対話**
- 🖼️ **DALL-Eピクチャー・ジェネレーションのサポート**（純粋な説明, アップロード画像（UnityEditorだけ）, アップロード+説明）
- 📁 **ファイルエクスプローラーからローカル画像を選択可能**
- 🖱️ **写真をドラッグしてピクチャーバブルを作る。** （UnityEditorでのみ利用可能）
- 🧠 **ワンクリックモデル切り替え（各モデルボタン使用）**
- 🎨 **ピクチャーバブルとダイアログバブルは自動的にサイズに合わせられます。**
- 🚀 **Unityビルド後のスタンドアロン**
- 💬 **様々な言語でコミュニケーションする（日本語、英語、中国語など）**

---

## 🖼️ プレビュー Screenshots

| 対話画面 | 画像生成 | モデル切り替え |
|----------|----------|----------|
| ![image](https://github.com/user-attachments/assets/4342f476-f3b8-4910-9251-d224bb94694d)|![image](https://github.com/user-attachments/assets/07f03056-041e-40af-ba01-39a26e6b96d4)|![image](https://github.com/user-attachments/assets/119f8ee2-fdad-48a8-8977-ed661c73972a)|

---

## 🛠️ 開発と運用 How to Run

### 環境条件 Requirements

- ✅ Unity 2020.3+ (建議使用 Unity Hub)
- ✅ 一組 [OpenAI API Key](https://platform.openai.com/account/api-keys)

### クイックスタート Quick Start

```bash
1.このプロジェクトをクローンするか、zipをダウンロードする
2.Unityを使ってプロジェクトを開く
3.`Main.unity`シーンを開く
4.`ChatGPTService.cs`にAPI Keyを記入する
5.https://github.com/srcnalt/OpenAI-Unity。リポジトリ内の対応するライブラリをロードする必要があるかもしれません。具体的なロード方法については、リポジトリの Readme を参照してください。
6. 再生ボタンをクリックすると、AI との会話が始まります。

### 特別感謝　Special Thanks
OpenAi-Api by srcnalt https://github.com/srcnalt
DeepSeek-Api by yagizeraslan https://github.com/yagizeraslan
