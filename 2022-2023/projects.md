# Data Science projects 2022-2023

1. [Project **Image processing for prostate cancer**](#image-processing-for-prostate-cancer)
2. [Project **Classification of prostate biopsy**](#histopathological-image-analysis)
3. [Project **POSE estimation**](#chronic-rhinosinusitis-with-nasal-polyps)

## Image processing for prostate cancer

### Aim

- characterisation of prostate tumours in MRI images

### Main idea

- The characterization of cancerous tissues in the prostate (through automatic non-invasive methods) contributes to the establishment of a personalized treatment and better recovery of the patient. The classification of different lessions based on radiomic features extracted from prostate MRIs. Radiomic features refer to the way certain parameters reproduce the heterogeneity or complexity of the texture. The higher the Gleason/ISUP score for a nodule, the more heterogeneous the appearance on the image will be, with large differences in contrast between neighboring pixels and between the textures of neighboring subregions in that nodule, differences sometimes even visible to the naked eye. The most used radiomic features are GLCM, secondary GLRLM and GLSZM matrices.


### TODOlist

1. Data analysis for the extracted features.
2. Binary classification of lessions in different groups (ISUP-1 vs. others and ISUP-1 vs. normal) by using an ML algorithm
    - Evolutionary algorithms (e.g. [Multi Expression Programming](http://mepx.org/))
    - Decision Trees
    - Support Vector Machine
    - Artificial Neural Networks
    - other ML algorithms
3. Evaluation of predictions by the binary classifier
4. Multi-class classification of lessions in different groups (ISUP-1 vs. ISUP-2 vs. ISUP-3 vs. ISUP-4 vs. ISUP-5) by usinf an ML algorithm
5. Evaluation of predictions by the multi-class classifier


### Data
- Cluj Hospital dataset of radiomic features extracted from 35 MRI images [link](DS-2022-2023\Data\radiomicFeatsCluj35.zip)
- 26 MR datasets - https://wiki.cancerimagingarchive.net/display/Public/PROSTATE-MRI#327726088352fbd47ff4147b574d72f5b596e4a
- https://promise12.grand-challenge.org/ - great challenge, one can check methods, articles
- https://prostatemrimagedatabase.com/ - 230 datasets - I have no info about quality


### Bibliografy
- Oltean, M. (2022). Multi Expression Programming for solving classification problems [link](https://www.researchgate.net/publication/359261779_Multi_Expression_Programming_for_solving_classification_problems)
- Afshar, P., Mohammadi, A., Plataniotis, K. N., Oikonomou, A., & Benali, H. (2019). From handcrafted to deep-learning-based cancer radiomics: challenges and opportunities. IEEE Signal Processing Magazine, 36(4), 132-160.
- L. Jing, Y. Tian, Self-supervised visual feature learning with deep neural networks: A survey, IEEE Transactions on pattern analysis and machine intelligence (2020)
- theory -> prostate imaging
    - https://www.slideshare.net/abd_ellah_nazeer/presentation1-mri-imaging-of-the-prostate
    - https://www.slideshare.net/abd_ellah_nazeer/presentation1pptx-radiological-imaging-of-prostatic-diseases - sl48/49
    - Kato Zoltan - linear registration of medical data - http://www.inf.u-szeged.hu/rgvc/demos.php?did=affbinregdemo
    - 3D - http://www.inf.u-szeged.hu/rgvc/demos.php?did=affbin3dregdemo



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



## Chronic rhinosinusitis with nasal polyps

### Aim

- estimate the POSE values for each control and thereby predict the reformation of the chronic rhinosinusitis with nasal polyps

### Main idea
- Chronic rhinosinusitis with nasal polyps (CRSwNP) is an inflammatory sinus disease in which there is a degeneration of the mucosa with the formation of polyps at the level of the sinuses, and over time, they expand into the nasal cavities, being able to completely occupy their volume. The incidence of this disease is 2.1-4.3% of the general population in Europe, and the patients who present this pathology have a very low quality of life. The etiology of CRSwNP is multi-factorial and the evolution/ aggressiveness of this pathology differs from patient to patient. The treatment of this condition is medical-surgical and aims to keep nasal inflammation under control and prevent the recurrence of nasal polyps. For this reason, the aim of this study is to identify the possibility of predicting the course of the disease and the response to treatment by using several clinical variables (scores of the disease, imaging investigations, blood tests, etc.).

### TODOlist

1. Data analysis for the extracted features.
2. POSE estimation by using an ML algorithm
    - Evolutionary algorithms (e.g. [Multi Expression Programming](http://mepx.org/))
    - Decision Trees
    - Support Vector Machine
    - Artificial Neural Networks
    - other ML algorithms
3. Evaluation of predictions 


### Data
- dataset description [link](DS-2022-2023\Data\polipozaDescription.docx)
- dataset [link](DS-2022-2023\Data\polipozaData.docx)

### Bibliografy
- C Morse, J., Miller, C., & Senior, B. (2021). Management of chronic rhinosinusitis with nasal polyposis in the era of biologics. Journal of Asthma and Allergy, 873-882. [link](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8285230/)
- Wright, E. D., & Agrawal, S. (2007). Impact of perioperative systemic steroids on surgical outcomes in patients with chronic rhinosinusitis with polyposis: evaluation with the novel Perioperative Sinus Endoscopy (POSE) scoring system. The Laryngoscope, 117(S115), 1-28. [link](https://onlinelibrary.wiley.com/doi/pdf/10.1097/MLG.0b013e31814842f8?casa_token=Z4SDfzZiFbIAAAAA:lEQa6OiSdL3QuN6q5Usw_yLjdU9c13AYe-UuTxlGGG2duz-xnDfPiOVnHeOxiZk9cNaZNyfz2AuhhZ4)