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
        padding: ["0", "0", "0", "0"]  # 垂直30px/水平0

      width: "full"          # 关键参数
    content:
      text: |
        <img src="static/media/ICCV_intro.svg"  style="width: 100%; height: auto;" ></center>

# sections:
#   - block: markdown
#     id: section-1
#     background:
#     image:
#       # Name of image in `assets/media/`.
#       filename: ICCV_intro.svg
#       # Apply image filters?
#       # filters:
#       #   # Darken the image? Range 0-1 where 1 is transparent and 0 is opaque.
#       #   brightness: 0.6
#       #  Image fit. Options are `cover` (default), `contain`, or `actual` size.
#       size: cover
#       # Image focal point. Options include `left`, `center` (default), or `right`.
#       position: center
#       # Use a fun parallax-like fixed background effect on desktop? true/false
#       parallax: false
#       # Text color (true=light, false=dark, or remove for the dynamic theme color).
#       text_color_light: true
    

# sections:
#   - block: collection
#     id: posts
#     content:
#       title: Recent Posts
#       subtitle: ''
#       text: 'Check out my recent blog posts below!'
#       # Choose how many pages you would like to display (0 = all pages)
#       count: 5
#       # Filter on criteria
#       filters:
#         # The folders to display content from
#         folders:
#           - post
#         author: ""
#         category: ""
#         tag: ""
#         publication_type: ""
#         featured_only: false
#         exclude_featured: false
#         exclude_future: false
#         exclude_past: false
#       # Choose how many pages you would like to offset by
#       # Useful if you wish to show the first item in the Featured widget
#       offset: 0
#       # Field to sort by, such as Date or Title
#       sort_by: 'Date'
#       sort_ascending: false
#     design:
#       # Choose a listing view
#       view: card

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
