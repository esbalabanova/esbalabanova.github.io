---
title: "Елизавета Балабанова"
type: landing

sections:
  - block: resume-biography-3
    content:
      username: me
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle

  - block: markdown
    content:
      title: 'Обо мне'
      text: |-
        Студентка РУДН.
        
        **Интересы:**
        - DevOps и CI/CD
        - Автоматизация
        - Open Source
        - Hugo
        
        **Образование:**
        - Закончила школу, в данный момент учусь на 1 курсе в РУДН
    design:
      columns: '1'

  - block: collection
    content:
      title: "Мои посты"
      filters:
        folders:
          - post
    design:
      view: article-grid
      columns: 2
