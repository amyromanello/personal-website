---
title: 'Experience'
date: 2023-10-24
type: landing

design:
  spacing: '2rem'

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: resume-experience
    content:
      username: admin
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: false
  - block: resume-skills
    content:
      title: Skills & Hobbies
      username: admin
      text: |-
        
    design:
      show_skill_percentage: false
#  - block: resume-awards
#    content:
#      title: Awards
#      username: admin
#  - block: resume-languages
#    content:
#      title: Languages
#      username: admin
  - block: markdown
    content:
      title: 
      text: |
        <div class="mb-6 text-3xl font-bold text-gray-900 dark:text-white" style="text-align: center">Languages</div>
        English: Native | German: A2
      username: admin
      design:
        css_style: 'text-center'

---
