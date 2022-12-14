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
         --- Viewmakers: Learning Neural Augmentations for Electrocardiograms in Self-supervised Learning ---

        * Developed generative diversity-viewmaker networks budgeted by stochastic L1 boundaries to adversarially learn SSL augmentations on 12-lead electrocardiogram;           Viewmakers eliminate the manual expert augmentation process and perform spurious feature suppression.
    
        * Developed self-distillation with no labels algorithms to improve performance for the CNN and ViT encoders.
    
         --- BenchMD: A Benchmark for Modality-Agnostic Learning on Medical Images and Sensors ---

        * Designed BenchMD, a modality-agnostic benchmark that tests how different architectures and training techniques (SSL & SL) perform on domain-shift medical     tasks; This benchmark covers 19 publicly available datasets for 7 diverse medical modalities, ranging from 1D sensor data, 2D images, to 3D volumetric scans.

        * Designed three SSL techniques (Emix, Shed, Agnostic MAE) and evaluated their few-shot and zero-shot performance on OOD medical data; beat SOTA AUROC in EEG and Dermatology.

  - title: Graduate Student Researcher for Capstone
    company: SANA Lab, MIT
    company_url: ''
    company_logo: sana
    location: Cambridge, MA
    date_start: '2022-09-01'
    date_end: ''
    description: |2-
        --- De-identifying Retinal Fundus Images for MIMIC ---
        
        * Develop multi-objective algorithms to de-identify retinal fundus images without hurting down- stream disease classification performance; Integrate a new Brazilian retinal fundus dataset into MIMIC following HIPAA privacy regulations.
        
        * Successfully decreased the gender identification accuracy from 81% to 64%, while maintaining the diabetic retinopathy classification accuracy at 95%.
        
        --- Interpretable multimodal deep learning to predict breast cancer stage --
        
        *Develop multi-modal models to combine attention-based multiple-instance learning on biopsy images and self-normalized networks on structured clinical metadata to predict breast cancer staging. Achieved Cohen Kappa of 71% and AUROC of 80% over 5-fold cross validation.

  - title: Research Assistant
    company: DtaK Lab
    company_url: 'https://dtak.github.io/'
    company_logo: bw
    location: Cambridge, MA
    date_start: '2022-02-01'
    date_end: ''
    description: |2-
        --- A Case Study of the Challenges of Applied Machine Learning in Assisted Reproductive Technology ---
        
        * Proposed and implemented two improved methods to overcome the existing limitations of machine learning application in the In Virto Fertilization domain.
        * Explored limitations in current literature including zero external validation, data leakage, heterogeneity and lack of timeliness.
        * Developed Phase-by-phase model to provide interpretable and progressive assistance for clinicians at different IVF stages, and developed Subgroup model to cope with data heterogeneity.
        * Collaborated with clinicians to outline a standardized data selection, preprocessing and modeling pipeline.
        * Used mixed effects models and mixtures of regressions to interpret predictors contributing to successful pregnancies and live births.
        
  - title: Research Assistant
    company: Learning, Information & Technology Lab
    company_url: 'https://lit.gse.harvard.edu/'
    company_logo: rgb
    location: Cambridge, MA
    date_start: '2021-09-01'
    date_end: ''
    description: |2-
    
        --- Multimodal Learning Analytics (MMLA) for Makerspaces ---
    
        * Developed computer vision 3D gaze detection and facial segmentation pipelines for student collaborative learning behaviors in the Harvard Makerspace using Pytorch.
    
        * Performed gaze and pose data re-projections into the 3D simulated lab space to generate better visualizations.
    
        * Collect and analyze student behavior data in Makerspace by leveraging multimodal pipelines to understand social learning aspects like student collaboration and self-efficacy.
        
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
