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
  - title: Senior Software Engineer
    company: ASUS-AICS
    company_url: ''
    company_logo: org-aics
    location: Taipei
    date_start: '2020-05-17'
    date_end: ''
    description: |2-
        * Developed cross device tracking model, which achived 0.75 F1-score, and data pipeline to process and inference 20 millions of web logs within 5 hours per day, by using Azure Databricks and Apache Spark.
        
  - title: AI Engineer
    company: Umbo Computer Vision
    company_url: ''
    company_logo: org-umbo
    location: Taipei
    date_start: '2019-08-16'
    date_end: '2020-05-16'
    description: |2-
        * Developed deep learning training pipeline with Kubeflow Pipeline, GKE \& TWCC, to scale up capacity and efficiency of model production.
        * Studied and evaluated false alarm filter algorithm, to improve precision of product and to support over ten thousand events.
        * Maintained CV services \& tracking business application (Tailgating), including builed monitoring system pipeline, to support thousand of camera streams.
  
  - title: Computer Vision Engineer
    company: Viscovery
    company_url: ''
    company_logo: org-vis
    location: Taipei
    date_start: '2018-05-01'
    date_end: '2019-08-15'
    description: |2-
        * Developed smart-checkout system with the algorithms including Metric Learning, Object Detection \& Segmentation, to more than 5 clients and more than 5 demo exhibition, with over 0.9 accuracy.
        * Leaded a 2-person team to work on Bread Recognition algorithms, such as bread's topping augmentation, hierarchical \& fine-grained classification and instance segmentation.
        * Implemented cut-paste based data generation tools with tranditional computer vision algorithms, including contour extraction, data augmentation, bluring and color space processing, to increase quantity and variety of training data, while reduce cost of data collection.
        * Studied, and evaluated new and the cutting-edge method, especially Generative Model, to improve feature representation and performance of new products recognition in smart-checkout system without retraining model.
  
  - title: Research Assistant
    company: Academia Sinica - Data Insights Research Lab
    company_url: ''
    company_logo: org-dirl
    location: Taipei
    date_start: '2016-07-01'
    date_end: '2018-04-30'
    description: |2-
        * Implemented more than 10 Machine Learning Projects to clients, for example, using text mining and XGBoost to model book sales prediction with 0.77 F1-score and applying multi-label classification and deep neural network to model dye selection and optimization with 0.99 Top-10 Accuracy.
        * Leaded a 5-person team to work on Governance satisfaction analysis with App's data, such as apps logs preprocessing, text mining, data analysis, regression model.
        * Preprocessed and analyzed more than 100 millions / 100GB scales of data, for example, e-commerce's transaction logs, and applied Apriori algorithm on it to figure out which products or categories combination was the best seller.
        * Taught more than 200 students in the courses of Deep Neural Network, Convolutional Neural Network, Natural Language Preprocessing, and assisted them to work on Machine Learning Projects, for example, using text mining to model artical classification and applying XGBoost and LSTM to model stock price prediction.
        * Consulted several departments and companies to define Machine Learning application fields.

design:
  columns: '2'
---
