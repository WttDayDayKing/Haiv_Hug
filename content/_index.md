---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "4rem"

# Note: `username` refers to the user's folder name in `content/authors/`
# Page sections
sections:
  - block: markdown
    id: section-1
    design:
      spacing:
        padding: ["0", "0"]  # 垂直30px/水平0
        margin: ["0", "0"]   # 上下0/左右居中
    content:
      text: |
        <img src="static/media/ICCV_intro.svg"  style="width: 200%; height: auto;" >

  # - block: image
  #   image:
  #     path: "static/media/ICCV_intro.svg"
  #   design:
  #     width: full  # 关键参数
  #     spacing: none  # 移除内外边距
  
  # - block: biography
  #   # content:
  #     # username: admin
  #     # Show a call-to-action button under your biography? (optional)
  #     # button:
  #     #   text: Download Résumé
  #     #   url: uploads/resume.pdf
  #   design:
  #     banner:
  #       # Upload your cover image to the `assets/media/` folder and reference it here
  #       filename: ICCV.jpg
  #       size: "cover"  # 关键参数！可选值：contain/cover/auto
  #       # filename: kalen-emsley-Bkci_8qcdvQ-unsplash.jpg
  #     # biography:
  #     #   # Customize the style of your biography text
  #     #   style: 'text-align: justify; font-size: 0.8em;'
  # - block: experience
  #   content:
  #     username: admin
  #   design:
  #     # Hugo date format
  #     date_format: 'January 2006'
  #     # Education or Experience section first?
  #     is_education_first: false
  # - block: skills
  #   content:
  #     title: Skills & Hobbies
  #     username: admin
  # - block: awards
  #   content:
  #     title: Awards
  #     username: admin
  # - block: languages
  #   content:
  #     title: Languages
  #     username: admin
---
