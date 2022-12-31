---
widget: slider
weight: 15
active: true
headless: true

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: '400px'
  is_fullscreen: false
  # Automatically transition through slides?
  loop: false
  # Duration of transition between slides (in ms)
  interval: 3000

content:
  slides:
    - title: Schendel Group
      content: December 2022
      align: right
      background:
        position: middle
        color: '#2F325B'
        brightness: 0.8
        media: group_photo_dec2022.png
        media_size: auto 100%
      link:
        icon: user
        icon_pack: fas
        text: Meet the Team
        url: people
    ## publication highlights below: adjust title, content, media, and url fields
    - title: Quant. 2D-NMR 
      content: "HSQC for Arabinoxylans"
      align: right
      background:
        position: left
        color: '#19554B'
        brightness: 0.8
        media: fpls-13-951705-g003.jpg
        media_size: auto 100%
      link:
        icon: graduation-cap
        icon_pack: fas
        text: Read the paper
        url: 'publication/schendel-NMR-2022'

    


---
