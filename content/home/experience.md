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
        * ---Viewmakers: Learning Neural Augmentations for Electrocardiograms in Self-supervised Learning---

        * Developed generative diversity-viewmaker networks budgeted by stochastic L1 boundaries to adversarially learn SSL augmentations on 12-lead electrocardiogram;           Viewmakers eliminate the manual expert augmentation process and perform spurious feature suppression.
    
        * Developed self-distillation with no labels algorithms to improve performance for the CNN and ViT encoders.
    
        * ---BenchMD: A Benchmark for Modality-Agnostic Learning on Medical Images and Sensors---

        * Designed BenchMD, a modality-agnostic benchmark that tests how different architectures and training techniques (SSL & SL) perform on domain-shift medical     tasks; This benchmark covers 19 publicly available datasets for 7 diverse medical modalities, ranging from 1D sensor data, 2D images, to 3D volumetric scans.

        * Designed three SSL techniques (Emix, Shed, Agnostic MAE) and evaluated their few-shot and zero-shot performance on OOD medical data; beat SOTA AUROC in EEG and Dermatology.
        
  - title: Research Assistant
    company: Learning, Information & Technology Lab
    company_url: 'https://lit.gse.harvard.edu/'
    company_logo: rgb
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
    company_logo: bw
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
   
  - title: Undergraduate Research Assistant
    company: University of Rochester Medical Center
    company_url: 'https://www.urmc.rochester.edu/'
    company_logo: ur
    location: Rochester, NY
    date_start: '2019-05-01'
    date_end: '2021-08-01'
    description: |2-
        * Utilized unsupervised machine learning algorithms to cluster nursing homes based on the percentage of residents with dementia, depression, and serious               mental illness, and detected previously unknown patterns of resident case-mix and staffing in nursing homes. Predicted deficiency scores of nursing homes on a         longitudinal basis with supervised learning algorithms. 
        
        * Developed text association and pattern mining algorithms to classify cancer therapies. Combined synthetic minority oversampling Technique (SMOTE) with               supervised learning techniques to deal with unbalanced caregiver datasets and help clinicians identify potential mental and physical health risk factors for           caregivers of the elder people. Implemented Local Interpretable Model-Agnostic Explanations (LIME) to give a non-black-box explanation for ML results in a             clinical setting.

  - title: Undergraduate Research Assistant
    company: Social Cognition & Psychopathology Lab
    company_url: 'https://labsites.rochester.edu/scplab/'
    company_logo: ur
    location: Rochester, NY
    date_start: '2019-04-01'
    date_end: '2021-08-01'
    description: |2-
        * Performed sentiment and topic analysis on text behavioral data in a functional neuroimaging study to better understand the relationship between brain                 functional connectivity and social anhedonia.
        * Applied machine vision techniques including semi-supervised CNNs, optical flow and open face, on video datasets to analyze group differences in nonverbal             synchrony during social interactions among people with schizophrenia and controls. Currently studying patterns of combinations of facial actions to evaluate           the effect of oxytocin on patients' social abilities.
   
   
design:
  columns: '2'
---
