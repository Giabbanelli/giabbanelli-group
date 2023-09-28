---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

---

sections:
  - block: slider
    content:
      slides:
      - title: 👋 Welcome to the group
        content: 120+ papers, 10+ theses, and counting!
        align: center
        background:
          image:
            filename: coders.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'
      - title: Research Impact
        content: 5 nominations and best paper awards from our group
        align: left
        background:
          image:
            filename: contact.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'
      - title: Let's talk about AI/ML research!
        content: Interested in collaborating or joining the group?
        align: right
        background:
          image:
            filename: welcome.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: Contact us
          url: contact/
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 2000

---
