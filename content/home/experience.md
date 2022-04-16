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
  - title: Research Assistant
    company: Rajpurkar Lab, Harvard Medical School
    company_url: 'https://rajpurkarlab.hms.harvard.edu/'
    company_logo: hms
    location: Cambridge, MA
    date_start: '2021-11-01'
    date_end: ''
    description: |2-
        * Develop diversity viewmaker networks, which are generative models with stochastic boundaries for data augmentations, via Pytorch Lightning, to adversarially         auto learn and generate augmentations on 12-lead electrocardiogram (ECG) sensor data for self-supervised learning tasks, so as to reduce the rigorous trial and         error by human experts. 
    
        * Develop self-distillation with no labels algorithms for 12-lead ECG data using Convolutional Neural Networks and Vision Transformers. 
    
        * Investigate and compare the performance of viewmaker networks to those of other previous contrastive methods, in particular whether viewmaker networks                 learned views that are medically sensible, and whether they are more robust to corruptions commonly observed in ECG data collection settings.
        
  - title: Research Assistant
    company: Learning, Information & Technology Lab
    company_url: 'https://lit.gse.harvard.edu/'
    company_logo: HGSE
    location: Cambridge, MA
    date_start: '2021-09-01'
    date_end: ''
    description: |2-
        * Develop real time 3D gaze detection (Gaze360) and facial recognition algorithms via Pytorch for Harvard Makerspace, reconstruct gaze predictions in a 3D             space, and integrate the tracking system into the Multimodal learning analytics cloud data pipeline
    
        * Perform 3D lab scence reconstruction along with gaze and pose data into a simulated 3D point clouds environment.
    
        * Collect data of student behavior in Makerspace lab sessions by leveraging the Multimodal learning analytics pipeline, and perform analysis to understand             social learning aspects like collaboration and student attention.
        
  - title: Research Assistant
    company: DtaK Lab
    company_url: 'https://dtak.github.io/'
    company_logo: SEAS
    location: Cambridge, MA
    date_start: '2022-02-01'
    date_end: ''
    description: |2-
        * Quantify the data heterogeneity and characterize the uncertainty in large, heterogeneous data collected by Boston IVF Clinic using bayesian machine learning         networks.
 
  - title: Analyst
    company: Credit Suisse
    company_url: 'https://www.credit-suisse.com/us/en.html'
    company_logo: cs
    location: Cambridge, MA
    date_start: '2019-06-01'
    date_end: '2021-06-01'
    description: |2-
        * Served as developer & business analyst for Investment Banking Division, building Airflow automated data ETL pipelines and constructing a centralized Azure         cloud data platform for bonds and credit default swaps. 
      
        * Served as project manager for the PoC of a firm-wide chat platform that leverages NLP to assist sales & trading team to a competitive edge. 
       
        * Collected big data streams and performed deep learning time series predictions on stock trends.
   
design:
  columns: '2'
---
