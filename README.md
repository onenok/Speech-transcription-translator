[English README](README_EN.md)

# 語音轉錄翻譯器

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

一個簡單的網頁應用程式，可以將語音（預設為英語）即時轉換為文字並翻譯成其他語言（預設為繁體中文）。

## 功能特點

- 即時語音識別
- 即時翻譯
- 視覺化音量，顯示即時音量大小
- 支援直接編輯原文並自動更新翻譯
- 支援橫向和直向螢幕
- 離線使用，無需安裝，可直接在瀏覽器中使用

## 使用方法

1. 開啟網頁：[網站連結](https://onenok.github.io/Speech-transcription-translator/)
2. 點擊「開始聆聽」按鈕
3. 允許瀏覽器使用麥克風
4. 開始說話，文字會自動出現在原文框框
5. 翻譯結果會自動顯示在譯文框框
6. 可以直接編輯的文字，翻譯會自動更新

## 系統需求

- 建議使用 Google Chrome 瀏覽器
- 需要麥克風權限
- 需要網際網路連線（用於翻譯功能）

## 注意事項

- MyMemory API 有使用限制
- LibreTranslate 需要 API Key
- 語音識別準確度取決於麥克風品質和環境噪音
- 建議在不吵雜的環境中使用

## 技術說明

- 使用 Web Speech API 進行語音識別
- 使用多種 API 進行翻譯
- 使用 Web Audio API 實現音量視覺化
- 使用 React 框架開發
- 純前端實現，無需後端服務

## 授權

本專案採用 MIT 授權條款
