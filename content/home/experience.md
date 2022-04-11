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
  - title: 'Research Assistant'
    company: 'HMS'
    company_url: ''
    company_logo: hms
    location: Cambridge
    date_start: '2021-11-10'
    date_end: ''
    description: '
    • Develop diversity viewmaker networks, which are generative models with stochastic boundaries for data augmentations, via Pytorch Lightning, to adversarially auto       learn and generate augmentations on 12-lead electrocardiogram (ECG) sensor data for self-supervised learning tasks, so as to reduce the rigorous trial and error       by human experts. 
    
    • Develop self-distillation with no labels algorithms for 12-lead ECG data using Convolutional Neural Networks and Vision Transformers. 
    
    • Investigate and compare the performance of viewmaker networks to those of other previous contrastive methods, in particular whether viewmaker networks learned         views that are medically sensible, and whether they are more robust to corruptions commonly observed in ECG data collection settings.'

  - title: 'Analyst'
    company: 'Credit Suisse'
    company_url: ''
    company_logo: cs
    location: New York
    date_start: '2020-07-01'
    date_end: '2021-06-01'
    description: '
    • Served as developer & business analyst for Investment Banking Division, building Airflow automated data ETL pipelines and constructing a centralized Azure cloud      data platform for bonds and credit default swaps. 
    
    • Served as project manager for the PoC of a firm-wide chat platform that leverages NLP to assist sales & trading team to a competitive edge. 
    
    • Collected big data streams and performed deep learning time series predictions on stock trends.'


design:
  columns: '2'
---
