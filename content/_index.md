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
      title: Amsterdam Policy Hackathon
      text: bottom text
      primary_action:
        text: Sign Up
        url: https://docs.google.com/forms/d/e/1FAIpQLSc6jM8kdDcWxt-Su7DlmraSccM4ZTA4pDgFGnEHH880IyugiA/viewform?usp=dialog
        icon: 📝
      # secondary_action:
      #   text: Read more
      #   url: https://docs.hugoblox.com
      # announcement:
      #   text: "Announcing the release of version 1."
      #   link:
      #     text: "Read more"
      #     url: "/blog/"
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        color: "navy"
        image:
          # Add your image background to `assets/media/`.
          filename: bg-amsterdam.jpg
          filters:
            brightness: 0.5
  - block: markdown
    id: main-page-content
    content:
      title: About
      text: In the Amsterdam Policy Hackathon, teams of participants develop policy solutions to pressing societal issues from govermental and industry actors in a data-driven manner.
  - block: markdown
    id: main-page-challenges
    content:
      title: Challenges
      text: To be announced, stay tuned!
  - block: cta-card
    content:
      title: Register now!
      text: Deadline April XXth, 2025
      button:
        text: Apply ➡️
        url: https://docs.google.com/forms/d/e/1FAIpQLSc6jM8kdDcWxt-Su7DlmraSccM4ZTA4pDgFGnEHH880IyugiA/viewform?usp=dialog
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
