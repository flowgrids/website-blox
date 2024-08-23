---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: We use AI to accelerate the energy transition.
      text: "Our vision is to create a sustainable society supplied by 100% renewable energy."
      primary_action:
        text: Contact us
        url: mailto:info@flowgrids.de
        icon: rocket-launch
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        color: "black"
        image:
          # Add your image background to `assets/media/`.
          filename: bg1.svg
          #  Image fit. Options are `cover` (default), `contain`, or `actual` size.
          size: 75%
          # Image focal point. Options include `left`, `center` (default), or `right`.
          position: right
          # Use a fun parallax-like fixed background effect on desktop? true/false
      parallax: true
---
