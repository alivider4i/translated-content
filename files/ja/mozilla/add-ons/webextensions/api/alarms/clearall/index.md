---
title: alarms.clearAll()
slug: Mozilla/Add-ons/WebExtensions/API/alarms/clearAll
tags:
  - API
  - Add-ons
  - Extensions
  - Method
  - Non-standard
  - Reference
  - WebExtensions
  - alarms
  - clearAll
translation_of: Mozilla/Add-ons/WebExtensions/API/alarms/clearAll
---
{{AddonSidebar()}}

予約されたアラームすべてを解除します。

## 構文

```js
browser.alarms.clearAll(
  function(wasCleared) {...}   // 関数
)
```

### 引数

- `callback`

  - : `function`. この関数には以下の引数が渡ります。

    - `wasCleared`
      - : `boolean`. アラームが解除された場合は `true` が、それ以外の場合は `false` が入ります。Chrome の場合は常に `true` が入ることに注意してください。

## ブラウザーの互換性

{{Compat("webextensions.api.alarms.clearAll")}}

{{WebExtExamples}}

> **Note:** この API は Chromium の [`chrome.alarms`](https://developer.chrome.com/extensions/alarms) API に基づいています。
