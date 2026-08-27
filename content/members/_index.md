---
title: 'Members'
summary: 'Members of the AI Biofluid Engineering Laboratory'
type: landing

sections:
  - block: hero
    content:
      eyebrow: 'AI Biofluid Engineering Laboratory'
      title: 'Members'
      text: |-
        Meet the researchers and students of our laboratory.
    design:
      css_class: 'dark'
      background:
        color: '#0B2C4D'
        gradient_mesh:
          enable: true

  - block: team-showcase
    id: graduate-students
    content:
      title: 'Graduate Students'
      subtitle: 'Our Team'
      user_groups:
        - Graduate Students
      sort_by: weight
      sort_ascending: true
    design:
      show_role: true
      show_organizations: false
      show_interests: false
      show_social: true
      show_empty_groups: false
      align: center
      max_columns: 3

  - block: team-showcase
    id: undergraduate-researchers
    content:
      title: 'Undergraduate Researchers'
      subtitle: 'Our Team'
      user_groups:
        - Undergraduate Researchers
      sort_by: weight
      sort_ascending: true
    design:
      show_role: true
      show_organizations: false
      show_interests: false
      show_social: true
      show_empty_groups: false
      align: center
      max_columns: 3

  - block: team-showcase
    id: alumni
    content:
      title: 'Alumni'
      subtitle: 'Former Members'
      user_groups:
        - Alumni
      sort_by: weight
      sort_ascending: true
    design:
      show_role: true
      show_organizations: false
      show_interests: false
      show_social: false
      show_empty_groups: true
      align: center
      max_columns: 3
---
