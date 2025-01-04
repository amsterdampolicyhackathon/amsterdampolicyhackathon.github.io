---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: Amsterdam Policy Hackathon
      text: bottom text
      cta:
        label: Get Started
        url: https://docs.google.com/forms/d/e/1FAIpQLSc6jM8kdDcWxt-Su7DlmraSccM4ZTA4pDgFGnEHH880IyugiA/viewform?usp=dialog
        # icon: 📝
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark min-h-screen"
      background:
        color: "navy"
        image:
          # Add your image background to `assets/media/`.
          filename: bg-amsterdam.jpg
          filters:
            brightness: 0.5
  
  - block: markdown
    id: about
    content:
      title: About
      text: In the Amsterdam Policy Hackathon, teams of participants develop policy solutions to pressing societal issues from govermental and industry actors in a data-driven manner. Are you motivated to work together in a team of motivated, interdisciplenary peers to solve some of Europe's most pressing challenges? Then apply below!
  - block: markdown
    id: challenges
    content:
      title: Challenges
      text: To be announced, stay tuned!
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="https://docs.google.com/forms/d/e/1FAIpQLSc6jM8kdDcWxt-Su7DlmraSccM4ZTA4pDgFGnEHH880IyugiA/viewform?usp=dialog" cta_text="Register now! →" %}}
    design:
      columns: '1'
---
