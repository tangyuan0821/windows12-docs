---
title: AI Copilot 後端介紹
layout: default
parent: 繁體中文
nav_order: 2
lang: zh-tw
permalink: /zh-tw/ai
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
> 本 AI 及文件來自 github@NB-Group

# AI Copilot 後端介紹
## 介紹
AI Copilot 是一款基於 AI 的文本生成工具，採用 LLAMA 模型，能夠自動生成文字內容。
本 AI 部署於 Cloudflare 平台所提供的 Worker AI 服務，能夠接收來自前端頁面的請求，並回傳所生成的文字。

但目前由 Cloudflare 部署的 AI 服務受到限制，無法直接存取，因此需要使用 VPN 才能訪問。
我已在 pythonanywhere 上部署了一個轉發程式，將請求轉發至 Cloudflare。

Cloudflare AI 伺服器的具體程式碼可在 [這裡](https://github.com/tjy-gitnub/win12/blob/main/scripts/AI%20Copilot%20service/Cloudflare%20AI.js) 查看