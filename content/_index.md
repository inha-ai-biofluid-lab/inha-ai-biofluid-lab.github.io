---
title: ''
summary: ''
type: landing

sections:
  - block: hero
    id: introduction
    content:
      eyebrow: 'Department of Mechanical Engineering · Inha University'
      title: 'AI / Bio Fluid Engineering Laboratory'
      text: |-
        **AI바이오유체공학연구실**

        We investigate biofluid phenomena through computational,
        experimental, and data-driven approaches.
      primary_action:
        text: 'Research Areas'
        url: '/research/'
        icon: 'beaker'
        style: 'gradient'
      secondary_action:
        text: 'Meet Our Team'
        url: '/members/'
        icon: 'user-group'
        style: 'ghost'
    design:
      css_class: 'dark'
      background:
        color: '#0B2C4D'
        gradient_mesh:
          enable: true

  - block: resume-biography-3
    id: professor
    content:
      username: kyung-eun-lee
      text: ''
      headings:
        about: 'Professor'
        education: ''
        interests: ''
    design:
      name:
        size: md
      avatar:
        size: medium
        shape: rounded
    
  - block: focus-areas
    id: quick-links
    content:
      title: 'Quick Links'
      subtitle: 'Explore Our Laboratory'
      items:
        - name: 'Publications'
          description: 'Explore journal articles and conference presentations.'
          icon: 'hero/document-text'
          url: '/publications/'
          gradient: 'from-blue-500 to-cyan-400'

        - name: 'Research'
          description: 'Discover our current research areas and projects.'
          icon: 'hero/beaker'
          url: '/research/'
          gradient: 'from-cyan-500 to-teal-400'

        - name: 'Notice'
          description: 'View laboratory announcements and recent news.'
          icon: 'hero/megaphone'
          url: '/board/#notice'
          gradient: 'from-indigo-500 to-blue-400'

        - name: 'Contact'
          description: 'Find our laboratory location and contact information.'
          icon: 'hero/map-pin'
          url: '/introduction/#contact'
          gradient: 'from-violet-500 to-cyan-400'
    design:
      layout: cards
    
  - block: markdown
    id: members
    content:
      title: 'Members'
      subtitle: 'Our Team'
      text: |-
        대학원생, 학부연구생 및 졸업생 정보를 소개합니다.

        [View all members →](/members/)
    design:
      columns: '1'

  - block: markdown
    id: publications
    content:
      title: 'Publications'
      subtitle: 'Selected Publications'
      text: |-
        연구실의 국제학술지 논문, 국내학술지 논문 및 학회 발표 실적을
        정리합니다.

        [View all publications →](/publications/)
    design:
      columns: '1'

  - block: focus-areas
    id: research
    content:
      title: 'Research'
      subtitle: 'Research Areas'
      text: 'We study biological flow phenomena using computational and data-driven approaches.'
      items:
        - name: 'Biofluid Mechanics'
          description: 'Investigation of fluid-mechanical phenomena in biological systems.'
          icon: 'hero/beaker'
          gradient: 'from-blue-500 to-cyan-400'

        - name: 'Cardiovascular Hemodynamics'
          description: 'Analysis of blood flow and vascular hemodynamics in cardiovascular systems.'
          icon: 'hero/heart'
          gradient: 'from-cyan-500 to-teal-400'

        - name: 'Computational Fluid Dynamics'
          description: 'Numerical modeling and simulation of complex biological flows.'
          icon: 'hero/cpu-chip'
          gradient: 'from-indigo-500 to-blue-400'

        - name: 'AI-Driven Engineering'
          description: 'Application of artificial intelligence and data-driven methods to engineering problems.'
          icon: 'hero/sparkles'
          gradient: 'from-violet-500 to-cyan-400'
    design:
      layout: cards

  - block: markdown
    id: board
    content:
      title: 'Board'
      subtitle: 'Notice and News'
      text: |-
        연구실 공지사항, 연구 성과, 학회 참석 및 연구실 소식을 게시합니다.

        [View notices and news →](/board/)
    design:
      columns: '1'

  - block: markdown
    id: contact
    content:
      title: 'Contact'
      subtitle: 'Visit Our Laboratory'
      text: |-
        **AI Biofluid Engineering Laboratory**  
        Department of Mechanical Engineering  
        Inha University

        [Contact and directions →](/introduction/#contact)
    design:
      columns: '1'
---
