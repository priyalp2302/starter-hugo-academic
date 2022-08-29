---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Researcher
    company: {{< staticref "https://theluminositylab.com" "newtab" >}}The Luminosity Lab{{< /staticref >}}, Arizona State University
    company_url: ''
    company_logo: org-gc
    location: Tempe, Arizona
    date_start: '2022-06-01'
    date_end: ''
    description: |2-
    
        * Working on developing the Rodel Arizona Futures Stimulator, an interactive simulator that provides enhanced decision-making using ReactJS and Python. Responsible for analyzing the effects of business decisions based on past data of around 30 years.
        * Testing the performance of aggregation of data and improving it using Python to display the stimulation state on the front end.

  - title: Professor of Semiconductor Physics
    company: University X
    company_url: ''
    company_logo: org-x
    location: California
    date_start: '2016-01-01'
    date_end: '2020-12-31'
    description: Taught electronic engineering and researched semiconductor physics.

design:
  columns: '2'
---
