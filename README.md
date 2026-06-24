# AI Model Musume

AI 模型娘化角色圖像資料集。收錄多個主流 AI 模型（LLM / 圖像生成）的角色設定卡片與桌布圖像，按模型分類整理。

![ChatGPT_Main_1](ChatGPT/ChatGPT_Main_1.png)

## 收錄模型

| 資料夾 | 模型 |
|--------|------|
| ChatGPT | OpenAI ChatGPT (GPT) |
| ChatGPT_GPT-OSS | OpenAI ChatGPT GPT-OSS |
| Claude_Fable | Anthropic Claude (Fable) |
| Claude_Opus | Anthropic Claude Opus |
| Claude_Sonnet | Anthropic Claude Sonnet |
| DeepSeek | DeepSeek |
| Doubao | 豆包 |
| Gemini | Google Gemini |
| Gemma | Google Gemma |
| GLM | 智譜 GLM |
| Grok | xAI Grok |
| Kimi | Moonshot Kimi |
| Llama | Meta Llama |
| Mimo | Mimo (獨立資料夾) |
| Minimax | MiniMax |
| Mistral | Mistral AI |
| Nemotron | NVIDIA Nemotron |
| Phi | Microsoft Phi |
| Qwen | 阿里通義千問 |
| Seedance | Seedance |
| Stable Diffusion | Stable Diffusion |

## 命名規則

每個模型資料夾的圖像依用途命名：

### 角色設定卡（每模型 3 張）
- `{Model}_繁體中文_角色設定.png` — 繁體中文版
- `{Model}_日文_角色設定.png` — 日文版
- `{Model}_English_角色設定.png` — 英文版

### 一般編號卡
- `{Model}_Main_1.png`、`{Model}_Main_2.png` ... — 僅有編號與模型名稱的簡單卡片

### 桌布
- `{Model}_Wallpaper_1.png` — 橫向桌布
- `Mobile_Wallpaper_1.png` — 直向桌布（跨資料夾統一流水號）

### 未分類
- `Unknown/` — 尚未識別來源的圖像

## 語言識別

角色設定卡的三種語言版本透過 EasyOCR 自動識別：
- **繁體中文**：內容以繁體中文書寫
- **日文**：含日文字元（性格/ロール等）
- **English**：內容為英文

## 如何使用

直接瀏覽各模型資料夾即可查看對應的角色圖像。所有檔案均為 PNG 格式。

## 附註

- 本專案的 .py 腳本僅用於自動化分類與重新命名，未納入版本控制
- 角色設定卡由 ChatGPT 生成，每張都包含角色名稱、代號、陣營、核心能力等資訊
