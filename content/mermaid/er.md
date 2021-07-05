---
title: "ER図"
date: 2021-07-05T19:51:34+09:00
draft: true
---

```text
erDiagram
    category ||--|{ production : category_id
    production ||--o{ stock : production_id
    production ||--o{ production_detail : production_id
    category {
        string category_id
        string name
        int order
    }
    production {
        string production_id
        string category_id
        string name
        string product_number
        int order
    }
    stock {
        string production_id
        string individual_number
        date production_date
    }
    production_detail {
        string production_id
        string maker_cd
        string description
    }
```

{{<mermaid align="left">}}
erDiagram
    category ||--|{ production : category_id
    production ||--o{ stock : production_id
    production ||--o{ production_detail : production_id
    category {
        string category_id
        string name
        int order
    }
    production {
        string production_id
        string category_id
        string name
        string product_number
        int order
    }
    stock {
        string production_id
        string individual_number
        date production_date
    }
    production_detail {
        string production_id
        string maker_cd
        string description
    }
{{< /mermaid >}}
