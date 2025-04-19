# 📁 下載Release版請移步 https://github.com/InnovatorF91/AI-Chat-App/releases/tag/v1.0.0-beta

# 🧠 AI Chat App – Unity製作的多模態AI對話系統

AI Chat App 是一款使用 Unity 製作的 AI 對話應用，支援文字、圖片生成、圖片拖入顯示與模型切換，並整合 OpenAI API，可作為桌面應用獨立運行。

> This project is designed as a professional showcase for interviews and demonstration purposes.

---

## ✨ 功能特點 Features

- 💬 **與 ChatGPT / DeepSeek AI 對話**
- 🖼️ **支援 DALL·E 圖片生成**（純描述、上傳圖片、上傳+描述）
- 📁 **可從 File Explorer 選擇本地圖片**
- 🖱️ **拖入圖片即生成圖片泡泡** （僅在UnityEditor中可用）
- 🧠 **模型一鍵切換（初始化面各個模型按鈕為入口）**
- 🎨 **圖片泡泡、對話泡泡皆自動適配尺寸**
- 🚀 **Unity Build 後可獨立運行**
- 💬 **可使用各種語言進行交流**

---

## 🖼️ 預覽 Screenshots

| 對話畫面 | 圖片生成 | 模型切換 |
|----------|----------|----------|
| ![image](https://github.com/user-attachments/assets/4342f476-f3b8-4910-9251-d224bb94694d)|![image](https://github.com/user-attachments/assets/07f03056-041e-40af-ba01-39a26e6b96d4)|![image](https://github.com/user-attachments/assets/119f8ee2-fdad-48a8-8977-ed661c73972a)|

---

## 🛠️ 開發與運行 How to Run

### 環境需求 Requirements

- ✅ Unity 2020.3+ (建議使用 Unity Hub)
- ✅ 一組 [OpenAI API Key](https://platform.openai.com/account/api-keys)

### 快速開始 Quick Start

```bash
1. Clone 本專案或下載 zip
2. 使用 Unity 開啟專案
3. 開啟 `Main.unity` 場景
4. 在 `ChatGPTService.cs` 中填入你的 API Key
5. 可能需要在https://github.com/srcnalt/OpenAI-Unity 倉庫加載相應的庫。具體加載流程請參考該倉庫的Readme
6. 點擊 Play 鍵即可開始與 AI 對話

### 特別感謝 Special Thanks
OpenAi-Api 作者 srcnalt https://github.com/srcnalt
DeepSeek-Api 作者 yagizeraslan https://github.com/yagizeraslan
