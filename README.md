<div align=center><img src="https://github.com/user-attachments/assets/cdf990fb-cf03-4370-a402-844f87b2fab8" width="256px;"></div>
<div align=center><img src="https://img.shields.io/github/v/release/neavo/LinguaGacha"/>   <img src="https://img.shields.io/github/license/neavo/LinguaGacha"/>   <img src="https://img.shields.io/github/stars/neavo/LinguaGacha"/></div>
<p align='center'>使用 AI 能力一鍵翻譯小說、遊戲、字幕等文本內容的新世代文本翻譯器</p>

## README 🌍
- [ [中文](./README.md) ] | [ [English](./README_EN.md) ] | [ [日本語](./README_JA.md) ]

## 概述 📢
- [LinguaGacha](https://github.com/neavo/LinguaGacha) (/ˈlɪŋɡwə ˈɡɑːtʃə/)，使用 AI 技術的新世代文本翻譯器
- 開箱即用，（幾乎）不用設定，強大的功能，不需要透過繁瑣的設定來體現
- 支援 `中` `英` `日` `韓` `俄` `德` `法` `義` 等 16 種語言的一鍵互譯
- 支援 `字幕`、`電子書`、`遊戲文本` 等多種文本類型與文本格式
- 支援 `Claude`、`ChatGPT`、`DeepSeek`、`SakuraLLM` 等各種本機或線上 API

> <img src="https://github.com/user-attachments/assets/99f7d74e-ab5b-4645-b736-6f665782b4af" style="width: 80%;">

> <img src="https://github.com/user-attachments/assets/c0d7e898-f6fa-432f-a3cd-e231b657c4b5" style="width: 80%;">

## 特別聲明 ⚠️
- 如果您在翻譯過程中使用了 [LinguaGacha](https://github.com/neavo/LinguaGacha)，請在作品資訊或發布頁面的顯眼位置進行說明！
- 如果您的專案涉及任何商業行為或商業收益，在使用 [LinguaGacha](https://github.com/neavo/LinguaGacha) 前，請先與作者聯繫以取得授權！

## 功能優勢 📌
- 極快的翻譯速度，十秒鐘一份字幕，一分鐘一本小說，五分鐘一部遊戲
- 自動產生詞彙表，確保角色姓名等專有名詞在整部作品中的譯名統一　`👈👈 獨家絕活`
- 最優的翻譯品質，無論是旗艦模型 `例如 DeepSeek-R1` 還是本機小模型 `例如 Qwen2.5-7B`
- 同類應用中最强的樣式與程式碼保留能力，顯著減少後期工作量，是製作内嵌中文化的最佳選擇
  - `.md` `.ass` `.epub` 格式幾乎可以保留所有原有樣式
  - 大部分的 `WOLF`、`RenPy`、`RPGMaker`、`Kirikiri` 引擎遊戲無需人工處理，即翻即玩　`👈👈 獨家絕活`

## 配置需求 💻
- 相容 `OpenAI` `Google` `Anthropic` `SakuraLLM` 標準的 AI 大型語言模型 API
- 相容 [KeywordGacha](https://github.com/neavo/KeywordGacha)　`👈👈 使用 AI 能力一鍵產生詞彙表的新世代工具`

## 基本流程 🚀
- 從 [發布頁面](https://github.com/neavo/LinguaGacha/releases) 下載應用程式
- 取得一個可靠的 AI 大型語言模型 API，建議選擇其一：
  - [ [本機 API](https://github.com/neavo/OneClickLLAMA) ]，免費，需至少 8G 顯示記憶體的獨立顯示卡，Nvidia 顯示卡為佳
  - [ [火山引擎](https://github.com/neavo/LinguaGacha/wiki/VolcEngine) ]，需付費但便宜，速度快，品質高，無顯示卡要求　`👈👈 推薦`
  - [ [DeepSeek](https://github.com/neavo/LinguaGacha/wiki/DeepSeek) ]，需付費但便宜，速度快，品質高，無顯示卡要求 `👈👈 白天不穩定，備選`
- 準備要翻譯的文本
  - `字幕`、`電子書` 等一般不需要預先處理
  - `遊戲文本` 需要根據遊戲引擎選擇合適的工具進行提取
- 雙擊 `app.exe` 啟動應用程式
  - 在 `專案設定` 中設定原文語言、譯文語言等必要資訊
  - 將要翻譯的文本檔案複製到輸入資料夾（預設為 `input` 資料夾），在 `開始翻譯` 中點擊開始翻譯

## 使用教學 📝
- 綜合
  - [基礎教學](https://github.com/neavo/LinguaGacha/wiki/BasicTutorial)　`👈👈 手把手教學，有手就行，新手必看`
  - [Google Gemini 免費 API](https://github.com/neavo/LinguaGacha/wiki/GoogleGeminiFree)
  - [高品質翻譯 WOLF 引擎遊戲的最佳實踐](https://github.com/neavo/LinguaGacha/wiki/BestPracticeForWOLF)
  - [高品質翻譯 RenPy 引擎遊戲的最佳實踐](https://github.com/neavo/LinguaGacha/wiki/BestPracticeForRenPy)
  - [高品質翻譯 RPGMaker 系列引擎遊戲的最佳實踐](https://github.com/neavo/LinguaGacha/wiki/BestPracticeForRPGMaker)
- 影片教學
  - [How to Translate RPGMV with LinguaGacha and Translator++ (English)](https://www.youtube.com/watch?v=wtV_IODzi8I)
- 功能說明
  - [命令行模式](https://github.com/neavo/LinguaGacha/wiki/CLIMode)
  - [詞彙表](https://github.com/neavo/LinguaGacha/wiki/Glossary)　　[文本保護](https://github.com/neavo/LinguaGacha/wiki/TextPreserve)　　[文本取代](https://github.com/neavo/LinguaGacha/wiki/Replacement)　　
  - [補充翻譯](https://github.com/neavo/LinguaGacha/wiki/IncrementalTranslation)　　[MTool 優化器](https://github.com/neavo/LinguaGacha/wiki/MToolOptimizer)
  - [百寶箱 - 批次修正](https://github.com/neavo/LinguaGacha/wiki/BatchCorrection)　　[百寶箱 - 部分重翻](https://github.com/neavo/LinguaGacha/wiki/ReTranslation)　　[百寶箱 - 姓名字段提取](https://github.com/neavo/LinguaGacha/wiki/NameFieldExtraction)
- 您可以在 [Wiki](https://github.com/neavo/LinguaGacha/wiki) 找到各項功能的更詳細介紹，也歡迎在 [討論區](https://github.com/neavo/LinguaGacha/discussions) 分享您的使用心得

## 文本格式 🏷️
- 在任務開始時，應用程式將讀取輸入資料夾（及其子目錄）內所有支援的檔案，包括但不限於：
  - 字幕（.srt .ass）
  - 電子書（.txt .epub）
  - Markdown（.md）
  - [RenPy](https://www.renpy.org) 匯出遊戲文本（.rpy）
  - [MTool](https://mtool.app) 匯出遊戲文本（.json）
  - [SExtractor](https://github.com/satan53x/SExtractor) 匯出遊戲文本（.txt .json .xlsx）
  - [VNTextPatch](https://github.com/arcusmaximus/VNTranslationTools) 匯出遊戲文本（.json）
  - [Translator++](https://dreamsavior.net/translator-plusplus) 專案檔案（.trans）
  - [Translator++](https://dreamsavior.net/translator-plusplus) 匯出遊戲文本（.xlsx）
  - [WOLF 官方翻譯工具](https://silversecond.booth.pm/items/5151747) 匯出遊戲文本（.xlsx）
- 具體範例可見 [Wiki - 支援的檔案格式](https://github.com/neavo/LinguaGacha/wiki/%E6%94%AF%E6%8C%81%E7%9A%84%E6%96%87%E4%BB%B6%E6%A0%BC%E5%BC%8F)，更多格式將持續新增，您也可以在 [ISSUES](https://github.com/neavo/LinguaGacha/issues) 中提出您的需求

## 近期更新 📅
- 20250603 v0.29.1
  - 修正 - 继续任务功能

- 20250602 v0.29.0
  - 新增 - [命令行模式](https://github.com/neavo/LinguaGacha/wiki/CLIMode)
  - 调整 - 更准确的请求超时时间控制
  - 调整 - 接口测试时打印失败的密钥

- 20250515 v0.27.0
  - 新增 - 任務完成時開啟輸出資料夾
  - 調整 - 優化了一些互動細節

- 20250506 v0.26.0
  - 新增 - 專家模式，啟用將開啟一系列進階功能：
    - 專家設定
    - 進階日誌資訊
    - [自訂文本保護規則](https://github.com/neavo/LinguaGacha/wiki/TextPreserve)

## 常見問題 📮
- [LinguaGacha](https://github.com/neavo/LinguaGacha) 與 [AiNiee](https://github.com/NEKOparapa/AiNiee) 的關係
  - `LinguaGacha` 的作者是 `AiNiee v5` 的主要開發與維護者之一
  - `AiNiee v5` 及沿用至 `AiNiee v6` 的 UI 框架也是由作者主要負責設計和開發的
  - 這也是兩者 UI 相似的原因，因為作者已經沒有靈感再重新設計一套了，求放過 🤣
  - 不過 `LinguaGacha` 並不是 `AiNiee` 的分支版本，而是在其經驗上開發的全新翻譯器應用
  - 相對作者主力開發的 `AiNiee v5`，`LinguaGacha` 有一些獨有的優勢，包括但不限於：
    - 零設定，全預設設定下即可實現最佳的翻譯品質與翻譯速度
    - 更好的效能優化，即使 512+ 並行任務時電腦也不會卡頓，實際翻譯速度也更快
    - 原生支援 `.rpy` `.trans`，大部分 `WOLF`、`RenPy`、`RPGMaker`、`Kirikiri` 遊戲即翻即玩
    - 對檔案格式的支援更好，例如 `.md` `.ass` `.epub` 格式幾乎可以保留所有原有樣式
    - 更完善的預處理、後處理和結果檢查功能，讓製作高品質翻譯的校對工作量顯著減少

## 問題回報 😥
- 執行時的日誌保存在應用程式根目錄下的 `log` 等資料夾
- 回報問題的時候請附上這些日誌檔案
- 您也可以來群組討論與回報
  - QQ - 41763231⑥
  - Discord - https://discord.gg/pyMRBGse75