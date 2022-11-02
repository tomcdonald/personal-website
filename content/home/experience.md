---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 50

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
  - title: Research Scientist Intern
    company: Spotify
    company_url: 'https://www.spotify.com/'
    company_logo: spotify_logo
    location: London, UK
    date_start: '2020-06-13'
    date_end: '2022-09-09'
    description: |2-
         * I spent the summer working within Tech Research at Spotify on a machine learning-based research project which is currently in submission at a conference venue.

  - title: Graduate Teaching Assistant (GTA)
    company: The University of Sheffield
    company_url: 'https://www.sheffield.ac.uk/'
    company_logo: uos_logo
    location: Sheffield, UK
    date_start: '2020-10-01'
    date_end: '2022-02-01'
    description: |2-
         * I have worked as a GTA on a number of different courses within the Faculty of Engineering, and currently
          assist with postgraduate-level courses focused on machine learning, handling data at scale using Spark and
          High Performance Computing infrastructure.
        
  - title: Pricing Analyst
    company: ENGIE Power Ltd.
    company_url: 'https://www.engie.co.uk/'
    company_logo: engie_logo
    location: Leeds, UK
    date_start: '2018-10-01'
    date_end: '2019-08-01'
    description: |2-
        * My role involved employing statistical modelling to forecast national non-commodity cost components and
          mitigate the level of risk involved in signing energy supply contracts.
        
        * Implemented seasonal ARIMA forecasting models in Python, with the models routinely returning <1%
          error on predictions made three months ahead of time.
        
        * Improved functionality of the VBA gas and electricity price matrices.

design:
  columns: '2'
---
