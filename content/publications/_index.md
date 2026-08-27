---
title: 'Publications'
summary: 'Publications of the AI Biofluid Engineering Laboratory'
type: landing

sections:
  - block: hero
    content:
      eyebrow: 'AI Biofluid Engineering Laboratory'
      title: 'Publications'
      text: |-
        Journal articles, conference presentations, and other
        academic outputs from our laboratory.
    design:
      css_class: 'dark'
      background:
        color: '#0B2C4D'
        gradient_mesh:
          enable: true

  - block: markdown
    id: overview
    content:
      title: 'Research Publications'
      subtitle: 'Academic Outputs'
      text: |-
        연구실의 국제학술지 논문, 국내학술지 논문 및 학회 발표 실적을
        정리하는 페이지입니다.

        실제 논문 목록은 연구실 자료를 확인한 후 추가할 예정입니다.
    design:
      columns: '1'

  - block: collection
    id: publication-list
    content:
      title: 'Publication List'
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation
---
