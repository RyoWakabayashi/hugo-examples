---
title: "ガントチャート"
date: 2021-07-05T19:51:34+09:00
draft: true
---

{{<mermaid align="left">}}
gantt
    title WBS
    dateFormat  YYYY-MM-DD
    section バージョン1
    設計   :a1, 2021-08-01, 4w
    開発   :a2, after a1  , 8w
    テスト  :after a2  , 20d
    section バージョン2
    設計   :b1, 2021-12-01, 2w
    開発   :b2, after b1  , 10d
    テスト  :after b2  , 5d
{{< /mermaid >}}
