+++
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
date = '{{ .Date }}'
draft = true
categories = ["山行記録"]
tags = []
+++

### テーマ・目的



---

| 項目 | 内容 |
| :--- | :--- |
| **記録日** | {{ .Date.Format "2006年1月1日" }} |
| **天候** | 晴れ |
| **パーティ** | 単独 |
| **アクセス** |  |
| **行程** |  |

---

### コースタイム

* 

---

### コースマップ

{{< gpx "" >}}

---

### 山行記録

#### 

---

{{< auto-gallery dir="{{ .Date.Format "20060102" }}" >}}