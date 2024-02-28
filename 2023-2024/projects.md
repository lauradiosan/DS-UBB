# Data Science projects 2023-2024

1. [Project **Classification of prostate biopsy**](#histopathological-image-analysis)



## Histopathological image analysis

### Aim
-  classify the severity of prostate cancer from microscopy scans of prostate biopsy samples

### Main idea
-  Diagnosis of prostate cancer (PCa) is based on the grading of prostate tissue biopsies. These tissue samples are examined by a pathologist and scored according to the Gleason grading system. The grading process consists of finding and classifying cancer tissue into so-called Gleason patterns (3, 4, or 5) based on the architectural growth patterns of the tumor (Fig. 1). After the biopsy is assigned a Gleason score, it is converted into an ISUP grade on a 1-5 scale. The Gleason grading system is the most important prognostic marker for PCa, and the ISUP grade has a crucial role when deciding how a patient should be treated. There is both a risk of missing cancers and a large risk of overgrading resulting in unnecessary treatment. However, the system suffers from significant inter-observer variability between pathologists, limiting its usefulness for individual patients. This variability in ratings could lead to unnecessary treatment, or worse, missing a severe diagnosis.


### TODOlist

1. Data analysis 
2. Binary classification of biopsies in different groups (ISUP-1 vs. others and ISUP-1 vs. normal) by using an ML algorithm
    - Evolutionary algorithms (e.g. [Multi Expression Programming](http://mepx.org/))
    - Decision Trees
    - Support Vector Machine
    - Artificial Neural Networks
    - other ML algorithms
3. Evaluation of predictions by the binary classifier
4. Multi-class classification of lessions in different groups (ISUP-1 vs. ISUP-2 vs. ISUP-3 vs. ISUP-4 vs. ISUP-5) by usinf an ML algorithm
5. Evaluation of predictions by the multi-class classifier


### Data
- Grand Challenge Data [link](https://www.kaggle.com/competitions/prostate-cancer-grade-assessment/data)


### Bibliografy
- Bulten, W., Kartasalo, K., Chen, P. H. C., Ström, P., Pinckaers, H., Nagpal, K., ... & Eklund, M. (2022). Artificial intelligence for diagnosis and Gleason grading of prostate cancer: the PANDA challenge. Nature medicine, 28(1), 154-163. [link](https://www.nature.com/articles/s41591-021-01620-2#Abs1)
- Lazar, A. J., & Demicco, E. G. (2022). Human and machine: Better at pathology together?. Cancer cell, 40(8), 806-808. 
- theory -> prostate imaging
    - https://www.slideshare.net/abd_ellah_nazeer/presentation1-mri-imaging-of-the-prostate
    - https://www.slideshare.net/abd_ellah_nazeer/presentation1pptx-radiological-imaging-of-prostatic-diseases - sl48/49
    - Kato Zoltan - linear registration of medical data - http://www.inf.u-szeged.hu/rgvc/demos.php?did=affbinregdemo
    - 3D - http://www.inf.u-szeged.hu/rgvc/demos.php?did=affbin3dregdemo


