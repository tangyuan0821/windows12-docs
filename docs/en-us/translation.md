---
title: Translation Guide
layout: default
parent: English
nav_order: 4
lang: en-us
permalink: /en-us/translate
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
# Translation Contribution Guidelines
Currently **only English is required**, other languages will be discussed once the system is improved.

Before starting translation, **please contact us and get approval**, to understand if someone is already working on the translation, to avoid duplicate work and merge conflicts.

## Requirements
1. Basic knowledge of Chinese
2. Good knowledge of the target language / Willingness to set your Windows 11 system to the target language
3. Basic coding skills

## Methods
The project uses the i18n library to implement multilingual support. You can look it up online or research the already translated parts.

### Existing Resources
0. It's crucial to understand the language processing part at the beginning of `desktop.js` and become familiar with the principles
1. The `trans.py` in this directory - those with Python knowledge can research it themselves
2. In `desktop.js`, there's `lang(txt,id)`, see comments for details

### Notes
Some code is structured like this:
```html
<a class="btn">
    <i class="bi"></i> Text
</a>
```
This may make it difficult to set attributes. You can add a `<span>` tag to the plain text part, for example:

```html
<a class="btn">
    <i class="bi"></i>
    <span data-i18n="sth">Text</span>
</a>
```

Please also improve the `lang_zh_cn` file simultaneously, which would be greatly appreciated.

### Bonus Points
1. For parts consistent with Windows 11, they should match the latest version of the native language content (as much as possible)
2. For inconsistent parts, machine translation should be avoided

## Content to Translate
1. Various pages in Settings except for "Personalization"
2. Task Manager
3. JavaScript code parts, such as right-click menus, dropdown menus, and notifications
4. The win12_title attribute of elements in HTML

## Compensation
Only includes:
1. GitHub contribution points
2. Heartfelt thanks from the developers >u-)o
