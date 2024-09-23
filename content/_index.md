---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: mcity.jpg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  # - block: collection
  #   id: papers
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     view: article-grid
  #     columns: 2
  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     view: article-grid
  #     columns: 1
  - block: markdown
    id: news
    content:
      title: News
      #subtitle: A subtitle
      text: |- 

        {{% callout note %}}
        I am actively seeking a tenure-track assistant professor position related to transportation research, including transportation engineering, industrial engineering, and data science!
        {{% /callout %}}

        - **09/2024**: I co-organized the work shop [Vehicle Trajectory Data Camp](https://i24motion.org/camp) at ITSC 2024 at Edmonton. Come and join our discussion! I will serve as the moderator for the second half of this session and am looking foward to meeting you at Edmonton!
        - **09/2024**: I am incredibly honored to share that my PhD dissertation has been awarded the **INFORMS TSL Best Dissertation Award**. This award is the oldest and most prestigious recognition for doctoral dissertations in the transportation science and logistics area, and I am deeply humbled to receive it. I will give a talk regarding this during 2024 INFORMS Annual Meeting, in the session titled MD35 - TSL Dissertation Award. The session is scheduled on Monday, October 21 at 2:15 pm in room Summit-427. Looking forward to seeing you in Seattle!
        - **08/2024**: I am glad to share that my PhD dissertation was selected as the finalist of IEEE ITSS Best Dissertation Award. 
        - **06/2024**: Our work ["Traffic light optimization with low penetration rate vehicle trajectory data"](https://www.nature.com/articles/s41467-024-45427-4) has been featured in [The Wall Street Journal](https://www.wsj.com/tech/personal-tech/google-green-light-traffic-light-optimization-992e4252)! "They use data gathered directly from new, internet-connected vehicles or from navigation apps on their drivers’ phones to help municipalities adjust the timing of their traffic lights, making them more responsive to real-world traffic patterns."
        - **05/2024**: Zachary and Zihao presented our work ("Traffic light optimization with low penetration rate vehicle trajectory data") and earned the first place of the CCAT 2024 student poster competition!
        - **02/2024**: Our paper ["Traffic light optimization with low penetration rate vehicle trajectory data"](https://www.nature.com/articles/s41467-024-45427-4) was recently accepted and is now online in *Nature Communications*. See the news from [University of Michigan](https://news.umich.edu/improving-traffic-signal-timing-with-a-handful-of-connected-vehicles/), [AP News](https://apnews.com/article/smarter-traffic-signals-north-carolina-michigan-757d6151e85565e9656d7b95c6e72490). 
        - **02/2024**: My new personal webiste is online! 
        - **08/2023**: I successfully defended my Dissertation titled ["Traffic Signal Optimization with Connected Vehicle Trajectories"](https://deepblue.lib.umich.edu/handle/2027.42/177983) advised by Dr. Henry Liu.
  - block: collection
    content:
      title: Recent Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
  # - block: collection
  #   id: news
  #   content:
  #     title: Recent News
  #     subtitle: ''
  #     text: ''
  #     # Page type to display. E.g. post, talk, publication...
  #     page_type: post
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: date-title-summary
  #     # Reduce spacing
  #     spacing:
  #       padding: [0, 0, 0, 0]
  - block: cta-card
    demo: true # Only display this section in the Hugo Blox Builder demo site
    content:
      title: 👉 Build your own academic website like this
      text: |-
        This site is generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

        <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>

        Easily build anything with blocks - no-code required!
        
        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
      button:
        text: Get Started
        url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
