---
id: muhammet
title: muhammet
---
***bu bir kod yamly ile sayfa belirleme*** 

```yaml
  # Alt klasörler için ayrı koleksiyonlar
  - name: tutorial_basics
    label: "Tutorial Basics"
    folder: docs/tutorial-basics
    create: true
    slug: "{{slug}}"
    fields:
      - { name: id, label: "ID", widget: "string", required: true }
      - { name: title, label: "Title", widget: "string" }
      - { name: body, label: "Body", widget: "markdown" }
```
