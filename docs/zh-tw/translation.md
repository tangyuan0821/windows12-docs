---
title: 翻譯指南
layout: default
parent: 繁體中文
nav_order: 4
lang: zh-tw
permalink: /zh-tw/translate
---

<details close markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
- TOC
{:toc}
</details>

---
# 翻譯貢獻指南
暫時**只需英語**，其他語言待完善後再說。

開始翻譯前，**務必聯繫我們，並徵得同意**，以了解是否還有人正在翻譯，避免重複勞動和合併衝突。

## 條件
1. 有中文基礎
2. 有一定的目標語言基礎 / 願意將自己的 Windows 11 系統調成目標語言
3. 有代碼基礎

## 方法
項目使用 i18n 庫實現多語言，可上網查閱，或自行研究已有翻譯的部分

### 已有成果
0. 務必理解 `desktop.js` 開頭語言處理部分，熟悉原理
1. 此目錄下的 `trans.py`，有 Python 基礎者自行研究
2. `desktop.js` 中有 `lang(txt,id)`，詳見註釋

### 注意
部分代碼形如
```html
<a class="btn">
    <i class="bi"></i> 文本
</a>
```
可能不便於設置屬性，可對純文本部分添加 `<span>` 標籤，例如可改為

```html
<a class="btn">
    <i class="bi"></i>
    <span data-i18n="sth">文本</span>
</a>
```

順便把 `lang_zh_cn` 文件一同完善，感激不盡。

### 加分項
1. 與 Windows 11 一致的部分，應符合（盡量）最新版的原生語言內容
2. 不一致的部分，應避免機器翻譯

## 待翻譯的內容
1. 設置中除「個性化」外的各個頁面
2. 任務管理器
3. js 代碼部分，如右鍵菜單、下拉菜單和通知（notice）
4. html 中元素的 win12_title 屬性

## 酬勞
有且僅有
1. Github 貢獻點
2. 來自開發者的由衷感謝 >u-)o