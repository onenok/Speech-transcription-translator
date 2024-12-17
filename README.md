# 語音轉寫翻譯器

[English README](README_EN.md)

[目錄](tableOfContents.md)

[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

一個簡單的網頁應用程序，可以將語音（默認為英文）實時轉寫為文本，並將其翻譯為其他語言（默認為繁體中文）。

## 功能

- 實時語音識別
- 實時翻譯
- 實時音量視覺化，顯示實時音量水平
- 支持直接編輯源文本，並自動更新翻譯
- 支持橫屏和豎屏方向
- 離線使用，無需安裝，直接在瀏覽器中運行

## 如何使用

1. 打開網站 [網站鏈接](https://onenok.github.io/Speech-transcription-translator/)
2. 點擊 "Start Listening" 按鈕
3. 允許瀏覽器麥克風訪問
4. 開始說話，文本將出現在源文本框中
5. 翻譯將出現在目標文本框中
6. 您可以直接編輯文本，翻譯將自動更新

## 系統要求

- 推薦使用 Google Chrome
- 麥克風訪問
- 互聯網連接（用於語音識別）

## 注意事項

- MyMemory API 有使用限制
- LibreTranslate 需要 API Key
- 語音識別準確性取決於麥克風質量和環境噪音
- 建議在非嘈雜環境中使用

## 技術細節

- 使用 Web Speech API 進行語音識別
- 使用多個 API 進行翻譯
- 使用 Web Audio API 進行音量視覺化
- 使用 React 框架構建
- 前端實現，無需後端