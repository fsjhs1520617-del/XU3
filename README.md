# 🏃 Flow State Parkour Studio | 跑酷流暢度極致修煉場

![Platform Showcase](https://img.shields.io/badge/Platform-Web_HTML5-8d72b8?style=for-the-badge)
![CSS3](https://img.shields.io/badge/Styling-Tailwind_CSS-38bdf8?style=for-the-badge)
![Audio Engine](https://img.shields.io/badge/Audio-Web_Audio_API_%2B_Suno_AI-a084ca?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-emerald-500?style=for-the-badge)

> **克服障礙高牆 ‧ 理解物理力學 ‧ 掌握極致心流 (Flow State)**
> 
> 一款結合 **2D 像素街機跑酷**、**慢動作關節物理模擬器**、**Suno AI 輕音樂原聲帶** 與 **一頁式互動學習介面** 的亮色灰紫系 Web 展示平台。

---

## 📖 目錄 (Table of Contents)
- [專案簡介 (Overview)](#-專案簡介-overview)
- [創作緣由與動機 (Origin & Motivation)](#-創作緣由與動機-origin--motivation)
- [核心特色 (Key Features)](#-核心特色-key-features)
- [關卡設計與修煉場 (Level System)](#-關卡設計與修煉場-level-system)
- [開發歷程 (Development Journey)](#-開發歷程-development-journey)
- [技術棧與架構 (Tech Stack)](#-技術棧與架構-tech-stack)
- [快速開始 (Quick Start)](#-快速開始-quick-start)
- [Suno AI 主題曲配置 (Theme Song Setup)](#-suno-ai-主題曲配置-theme-song-setup)

---

## 💡 專案簡介 (Overview)

在跑酷（Parkour）與越障運動中，「流暢度 (Flow State)」是區分初學者與專業選手的核心指標。初學者常因為對障礙物的心理恐懼或發力方向誤區，導致過牆時產生停頓與卡頓。

**Flow State Parkour Studio** 將複雜的生物力學發力拆解為視覺化的 2D 骨架拋物線，並結合帶有子彈時間（Bullet-Time）與賽博無人機追逐的 2D 像素遊戲，讓學習者能同時在「理性物理分析」與「感性遊戲體驗」中，理解動能轉移與時機掌控。

---

## 🎯 創作緣由與動機 (Origin & Motivation)

### 📌 緣由 (Background)
在練習翻越（Vault）與落地滾翻（Safe Roll）的過程中，發現許多人（包含創作者自身）面臨相同的瓶頸：
1. **心理障礙 (Psychological Barrier)**：臨近高牆時容易猶豫減速，破壞原本累積的水平動能。
2. **發力方向誤區 (Biomechanical Misunderstanding)**：習慣「往上抓」而非「向下按壓」，忽視了牛頓第三定律的反作用力。
3. **招式銜接斷層 (Flow Interruption)**：無法順暢連貫落地與下一次起跳。

### 📌 動機 (Motivation)
為了打破「純理論教學過於枯燥」與「實體練習難以即時看清關節軌跡」的痛點，本專案旨在打造一個：
- **視覺化 (Visualized)**：即時繪製推力向量與人體質心拋物線。
- **遊戲化 (Gamified)**：將時機練習轉化為分數、Combo 與子彈時間回饋。
- **低門檻 (Accessible)**：無需下載安裝，任何瀏覽器打開即能體驗與學習。

---

## ✨ 核心特色 (Key Features)

### 🎮 1. 2D 像素超速跑酷引擎
- **完整招式系統**：支援跳躍 (Jump)、翻越 (Vault)、滾翻 (Safe Roll) 與 **[E] 鍵特技空翻 (Trick Flip)**。
- **子彈時間 (Bullet-Time)**：連續達成 Combo 時觸發 slow-motion 定格與彩虹殘影，大幅提升操作張力。
- **賽博追逐無人機 (Cyber Pursuit Drone)**：若過障卡頓致 Flow 值歸零，後方無人機會逼近並鎖定雷射，增添緊張刺激感。

### 🔬 2. 慢動作關節物理模擬器
- **參數動態調控**：自由調整助跑水平速度、雙手向下推力與髖關節起跳角度。
- **軌跡與 AI 診斷**：即時計算人體質心拋物線（綠色/紅色軌跡），並給出過牆成功率回饋。

### 🎵 3. Web Audio Synth & Chill Synth 原聲帶
- **全原生 Web Audio 音效**：無需外部音檔即可發出跑酷跳躍、過牆與特技音效。
- **Suno AI Chill Flow 輕音樂**：調配出專屬 Instrumental 鬆弛電音提示詞，適合邊思考物理軌跡邊練習。

### 🎨 4. 優雅亮色灰紫系 UI (Soft Gray-Purple Theme)
- 使用 `#f4f0f8` 淺紫灰作為基底，搭配 `#8d72b8` 灰紫主色與 `#2d2438` 質感暗字，擺脫暗色系沉重感，呈現清爽現代的視覺質感。

---

## 🗺️ 關卡設計與修煉場 (Level System)

| 關卡 (Stage) | 區劃主題 | 核心練習目標 | 障礙物組合 |
| :--- | :--- | :--- | :--- |
| **Stage 01** | 🌅 屋頂初體驗 | 基礎 Vault 翻越時機與動能建立 | 低牆 (Low Wall)、深溝 (Gap) |
| **Stage 02** | 🌆 霓虹暗巷過障 | 高牆壓手提髖與 [A] 滾翻銜接 | 低牆、高牆 (High Wall)、低桿 |
| **Stage 03** | 🏗️ 工業高空降落 | 高落差 Precision Jump 與落地緩衝 | 高牆、深溝、高落差平台 |
| **Stage 04** | 🌧️ 雨夜速流衝刺 | 動態雨景 + 無人機追擊極速反應 | 全障礙 + 無人機對焦雷射 |
| **Stage 05** | 👑 流暢大師考驗 | 高分 Combo 串聯與特技空翻釋放 | 綜合超高密度賽道 |

---

## 🛠️ 開發歷程 (Development Journey)

```
[ Phase 01: 瓶頸分析 ] ──> [ Phase 02: 物理建模 ] ──> [ Phase 03: 街機引擎 ] ──> [ Phase 04: 平台整合 ]
  - 紀錄翻越卡頓點       - 導入牛頓第三定律      - Web Audio 音效開發    - 亮色灰紫系介面
  - 拆解障礙物恐懼       - 關節軌跡與向量圖      - 子彈時間與Combo系統    - 5大關卡與展演網頁
```

1. **Phase 1 ── 瓶頸分析與痛點定義**：研究跑酷常見卡頓原因，發現「手部向下推力不足」與「髖關節未抬升」為兩大核心主因。
2. **Phase 2 ── 生物理學與向量建模**：運用 HTML5 Canvas 模擬質心拋物線，建立手部按壓力與助跑速度對應的軌跡演算法。
3. **Phase 3 ── 遊戲化與Procedural Audio**：設計街機跑酷邏輯，結合 Web Audio API 實現無需載入檔的音效系統。
4. **Phase 4 ── 介面設計與展示整合**：採用美觀清爽的亮色灰紫系風格，建構一頁式 GitHub Showcase 展示頁面。

---

## 💻 技術棧與架構 (Tech Stack)

- **Frontend Core**: HTML5, JavaScript (ES6+)
- **Styling**: Tailwind CSS (JIT mode)
- **Canvas Rendering**: HTML5 Canvas 2D Context (Pixelated rendering)
- **Audio Engine**: Web Audio API (OscillatorNode, GainNode) + Suno AI (Prompt Tuning)
- **Design System**: Bright Gray-Purple Theme (`#f4f0f8`, `#8d72b8`, `#2d2438`)

---

## 🚀 快速開始 (Quick Start)

本專案為獨立式單檔可運行應用 (Single-file Web Application)，無需安裝 Node.js 或建置繁瑣環境。

### 執行步驟：
1. **Clone 本儲存庫**：
   ```bash
   git clone https://github.com/your-username/flow-state-parkour-studio.git
   ```
2. **開啟專案**：
   直接使用任何現代瀏覽器（Chrome, Edge, Firefox, Safari）雙擊打開 `index.html` 即可開始體驗！

---

## 🎵 Suno AI 主題曲配置 (Theme Song Setup)

若想重現本平台原聲帶音樂，可在 [Suno AI](https://suno.com) 使用以下設定：

- **Mode**: Custom Mode
- **Instrumental**: `ON` (開啟純音樂)
- **Style of Music**:
  ```text
  chill synthwave, smooth retrowave, lo-fi chiptune, relaxing arcade background music, soft synth leads, steady rhythmic bass, 80s nostalgia, instrumental, smooth flow
  ```
- **Title**: `Flow State - Pure Focus`

---

## 📄 授權條款 (License)

本專案採用 [MIT License](LICENSE) 條款授權，歡迎自由學習、修改與延伸創作。
