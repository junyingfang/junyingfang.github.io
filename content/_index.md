---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "1.5rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: CV
        url: uploads/JunyingFang_CV_2026Aug.pdf
    design:
      spacing:
        # Half of the default 1.5rem section spacing
        padding: ["0.75rem", "0", "0.75rem", "0"]
  - block: collection
    id: papers
    content:
      title: Publications
      sort_by: weight
      sort_ascending: true
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: pub-row
  - block: markdown
    id: awards
    content:
      title: Awards
      subtitle: ''
      text: |-
        - Oral presentation award at the 101st Annual Meeting of American Meteorological Society, 2021
        - First-class PhD scholarship of Sun Yat-sen University, 2019
        - Oral presentation award at the 35th Annual Meeting of Chinese Meteorological Society, 2018
        - Oral presentation award at the Atmospheric Science Graduate Academic Forum, 2018
    design:
      columns: '1'
  - block: markdown
    id: teaching
    content:
      title: Teaching
      subtitle: ''
      text: |-
        - Aug. 2020 – Jan. 2021: Teaching assistant for Synoptic Meteorology, Sun Yat-sen University
        - Feb. 2021 – Jul. 2021: Teaching assistant for Climate Change, Sun Yat-sen University
        - Aug. 2021 – Jan. 2022: Teaching assistant for Climate Impacts, Adaptation and Mitigation, Sun Yat-sen University
    design:
      columns: '1'
  - block: markdown
    id: service
    content:
      title: Service
      subtitle: ''
      text: |-
        **Journal Review:** Geophysical Research Letters, Journal of the Atmospheric Sciences, Journal of Geophysical Research: Atmospheres, International Journal of Climatology, Ocean-Land-Atmosphere Research, Journal of Meteorological Research, Earth and Space Science

        **Journal Editorial Intern:** The Innovation
    design:
      columns: '1'
---
