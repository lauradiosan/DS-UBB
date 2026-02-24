

# DataScience - Intelligent Modeling 2025-2026


## Lectures

1. Opening :)

2. TBA

3. TBA

## About projects

The project you have to do is an opportunity to explore an Artificial Intelligence (AI) problem in the context of real data. The project will be evaluated both during the semester and at the end of the semester, when each team will have to present to the teaching staff the corresponding iterations of the application and the related technical report.


**Project components**
- short description 
- team (max 3 members)
- problem solving by AI/ML-based algorithms
- application development and AI/ML integration
    - Problem definition (details about inputs and outputs)
    - Exploratory data analysis
    - AI development and performance evaluation 
    - Improvements (in terms of prediction quality and in terms of model's interpretability or explainability)
- documentation (report)
- final presentation
### TODOlist
1. 
**Performance of the AI models**
1. Performance
    - qualitative (errors, accuracy, precision, IoU, Dice, etc.)
    - complexity (time, space/memory, FLOPs, hardware resources, etc.)
2. Explainability
    - [link](https://christophm.github.io/interpretable-ml-book/index.html)
    - [link](https://ema.drwhy.ai/preface.html)
3. Sustainability
    - CO2 footprint of AI models

**Application development**
- using any programming language and technologies 
- codebases must be submitted [here](https://classroom.github.com/a/wRjthGYY), before deadlines
- [good tips](https://www.deeplearningbook.org/)

**Technical report**
- must follows this template [link](https://github.com/lauradiosan/DS-UBB/tree/main/2025-2026/Report/texModel/model.tex) and the recommended structure [link](https://github.com/lauradiosan/DS-UBB/tree/main/2025-2026/Report/readme.md). 


**Final presentation**
- teaser (a short video presentation)
- slides (or other presentation support)
- project defense (oral presentation of aprox. 15 minutes based on the prepared slides/support)


**Evaluation**
- [criteria and points](Eval/readme.md)


# Proposed projects



<details>
    <summary> 1. Nasopharyngeal carcinoma  </summary>

### Aim 

Nasopharyngeal carcinoma (NPC) is rare in Europe, but emerging evidence suggests that Caucasian patients may have poorer outcomes compared with Asian populations. This highlights the need for region-specific prognostic tools tailored to European cohorts. Inflammation-based biomarkers have demonstrated potential for risk stratification, while advances in AI and machine learning provide new opportunities for predicting survival and long-term complications, including second primary malignancies. Despite this, ML-based prognostic models for NPC remain largely unexplored in Caucasian populations. A key objective of this project is to develop a predictive model capable of identifying patients at increased risk of disease recurrence during the follow-up period.

### Data

TBA

### Bibliografy
1. National Cancer Institute. Surveillance, epidemiology, and end results (seer) program, 2025. 

2. American College of Surgeons Commission on Cancer. National cancer database (ncdb), 2025.

3. Jianing Luo, Xiaonan Hu, and Xiaofeng Ge. Conditional survival nomogram for monitoring real-time survival of young non-metastatic nasopharyngeal cancer survivors. Journal of Cancer Research and Clinical Oncology, 149(12):10181-10188, 2023

4. Lei Qiu, Yinjiao Fei, Yuchen Zhu, Kexin Shi, Jinling Yuan, Gefei Jiang, Xingjian Sun, Yuandong Cao, Weilin Xu, and Shu Zhou. Development and validation of a machine learning model for predicting 3-year overall survival in metastatic nasopharyngeal carcinoma: a seer database and web visualization study. Translational Cancer Research,
14(10):7037-7052, 2025

</details>

<details>
    <summary> 2. Lung Nodule Prognostics </summary>

### Aim 
Lung nodules detected through low-dose CT screening have highly variable clinical significance: some remain indolent for years, while others rapidly progress to malignancy. Clinicians typically rely on multiple heterogeneous attributes—radiomic features, volumetric growth patterns, and patient clinical data—to stratify risk and decide monitoring vs. intervention strategies.
Multi-task learning (MTL) is an emerging paradigm that can jointly predict related clinical endpoints, improving generalization by leveraging shared information. Recent architectural innovations introduce cross-talk mechanisms between task-specific branches, allowing tasks to influence one another through attention, message passing, or shared latent embeddings - especially useful when modeling the progression of lung cancer, where risk factors are biologically interdependent. This project aims to develop an MTL model with cross-talk (e.g., cross-stitch units, sluice networks, co-attention) that jointly predicts:
- T1: Nodule malignancy risk (benign vs. malignant)
- T2: 2-year progression probability (stable vs. progressive)
- T3: Radiological subtype classification (solid, part-solid, ground-glass)

Additionally, the model should provide interpretable outputs, including SHAP explanations, feature importances for each task, and an analysis of task interactions.

### Data
- LIDC-IDRI - Lung CT Scans with radiologist annotations [link](https://www.cancerimagingarchive.net/collection/lidc-idri/)

- LNDb - Lung Nodule Database (European cohort; includes malignancy likelihood scores) [link](https://lndb.grand-challenge.org/)


### Bibliografy
1. Crawshaw, M. (2020). Multi-task learning with deep neural networks: A survey. arXiv preprint arXiv:2009.09796.

2. Zhang, Y., & Yang, Q. (2021). A survey on multi-task learning. IEEE transactions on knowledge and data engineering, 34(12), 5586-5609.

1. Silva, F.A. et al. LNDb: A Lung Nodule Database on Computed Tomography. IEEE Transactions on Medical Imaging, 2020

</details>

<details>
    <summary> 3. Rhetorical Drift Modeling in Parliamentary Speech Networks </summary>

### Aim 

Rhetorical drift—gradual changes in how MPs frame political issues—is a key early signal of democratic backsliding. MPs who begin to echo anti-democratic or extremist narratives often influence their peers through discourse networks, leading to contagion-like patterns of rhetoric adoption.
Despite the availability of parliamentary transcripts and political speech corpora, few ML models explicitly track how rhetoric spreads across MP networks over time. This project aims to develop a machine-learning pipeline that:
- Constructs a dynamic speech-similarity graph/network where nodes are MPs and edges reflect semantic similarity between their speeches.
- Uses node classification to identify MPs adopting anti-democratic rhetoric (binary classification - democratic-norm-supporting vs. anti-democratic rhetoric - or multi-class classification - populist, authoritarian, anti-institutional, etc.) or link prediction to forecast which MPs will become rhetorically aligned or community detection to identify clusters where rhetoric becomes homogenized.
- Evaluates rhetorical drift: how changes in speech features propagate through the graph/network or community 
- Updates risk scores in a simplified network, signaling when rhetoric clusters begin to resemble early-warning patterns of democratic erosion.


### Data

- [PolData](https://github.com/erikgahner/PolData?tab=readme-ov-file)

- [Political Speech Datasets](https://www.kaggle.com/datasets?tags=11121-Politics)

- [V-Dem](https://v-dem.net/data/)

### Bibliografy

1. Sermpezis, P., Karamanidis, S., Paraschou, E., Dimitriadis, I., Yfantidou, S., Kouskouveli, F. I., ... & Vakali, A. (2025). AgoraSpeech: A multi-annotated comprehensive dataset of political discourse through the lens of humans and AI. arXiv preprint arXiv:2501.06265.

2. Mochtak, M., Rupnik, P., Kuzman, T., & Ljubešić, N. (2025). Parlasent: mapping sentiment in political discourse with large language models. Political Research Exchange, 7(1), 2508377.

3. Deshwal, K., & Sharma, D. (2024, July). Political Speech Analysis Using Machine Learning and Deep Learning: A Comprehensive Literature Review. In Biennial International Conference on Future Learning Aspects of Mechanical Engineering (pp. 205-215). Singapore: Springer Nature Singapore.

4. Sawhney, R., Wadhwa, A., Agarwal, S., & Shah, R. (2020, December). GPolS: A contextual graph-based language model for analyzing parliamentary debates and political cohesion. In Proceedings of the 28th international conference on computational linguistics (pp. 4847-4859).

</details>

<details>
    <summary> 4. Government Agency Scenario </summary>

### Aim 

A large company decides to deploy an LLM for:
- product review sentiment analysis,
- internal HR survey classification,
- customer chat summarization.
Domains differ massively. Recently, the model produced an embarrassing PR incident due to poor domain generalization. 
Help the company to determine which models generalize across use cases,
recommend training strategies, quantify failure risk.

Or, in other words, Large Language Models perform impressively in zero-shot settings, but their real-world reliability often depends on robustness to domain shift. Fine-tuning can improve in-domain accuracy but sometimes harms generalization (catastrophic overfitting). Compare the performance of zero-shot LLMs, fine-tuned LLMs and some smaller baselines for a text mining task. Evaluate the generalisation capacity of various LLMs by using different datasets. 

### Data

- [SST, IMDB, Yelp, SemEval](https://github.com/DrJZhou/Datasets-for-Sentiment-Analysis)
-

### Bibliografy

1. Liu, Z., Guan, L., Nie, Y., Zhang, K., Hao, Z., Chen, L., ... & Zhang, N. (2026). Paying Less Generalization Tax: A Cross-Domain Generalization Study of RL Training for LLM Agents. arXiv preprint arXiv:2601.18217.

2. Pei, A., Yang, Z., Zhu, S., Cheng, R., & Jia, J. (2025, January). Selfprompt: Autonomously evaluating llm robustness via domain-constrained knowledge guidelines and refined adversarial prompts. In Proceedings of the 31st International Conference on Computational Linguistics (pp. 6840-6854).

3. Li, Y., Wang, J., Sundaram, H., & Liu, Z. (2025). A zero-shot generalization framework for llm-driven cross-domain sequential recommendation. arXiv e-prints, arXiv-2501.

4. Calderon, N., Porat, N., Ben-David, E., Chapanin, A., Gekhman, Z., Oved, N., & Reichart, R. (2024, November). Measuring the robustness of NLP models to domain shifts. In Findings of the Association for Computational Linguistics: EMNLP 2024 (pp. 126-154).

</details>


<details>
    <summary> 5. Designing a Tokenizer for a Morphologically Rich Language </summary>

### Aim 

The Romanian Academy asks your team to develop a tokenizer that preserves the integrity of the Romanian language in AI applications. Current multilingual tokenizers butcher Romanian morphology, leading to poorer performance in speech assistants, government services, and educational tools. Your mission is to build and evaluate a new tokenizer capable of representing Romanian efficiently and accurately.

In other words, most LLMs today use multilingual tokenizers (BPE, SentencePiece, WordPiece, Unigram), which were trained primarily on English-heavy corpora. For languages like Romanian, this creates problems:
- morphologically rich words get over-segmented (e.g., neîndemânatic → 5-7 tokens). 
- useful morphemes (ne-, -îndemân-, -atic, etc.) are not preserved.
- the LLM “wastes” context window on one word split into many pieces.
- downstream tasks suffer because the model fails to encode morphology cleanly.
The project aim is to build, train and evaluate a tokeniser tailor to Romanian and compare it against standard multi-lingual tokenizers. 

### Data

[LiRo](https://lirobenchmark.github.io/)
[LaRoSeDa](https://www.mdpi.com/2673-2688/7/2/61)

### Bibliografy

1. Nitu, M., & Dascalu, M. (2022). Natural Language Processing Tools for Romanian–Going Beyond a Low‑Resource Language. Interaction Design & Architecture (s), special issue. DOI, 10.

2. Suryanto, T. L. M., Wibawa, A. P., Hariyono, H., & Nafalski, A. (2025). Comparative performance of transformer models for cultural heritage in NLP tasks. Advance Sustainable Science Engineering and Technology, 7(1), 02501015-02501015.

3. Guțu, B. M., & Popescu, N. (2025). From Dataset to Model: A Romanian–English Corpus and Fine-Tuned Cross-Lingual Embeddings for Text and Tabular Retrieval. Applied Sciences, 15(22), 12219.

4. Vasiu, M. A., & Potolea, R. (2020, September). Enhancing tokenization by embedding Romanian language specific morphology. In 2020 IEEE 16th International Conference on Intelligent Computer Communication and Processing (ICCP) (pp. 243-250). IEEE.

5. Toraman, C., Yilmaz, E. H., Şahinuç, F., & Ozcelik, O. (2023). Impact of tokenization on language models: An analysis for turkish. ACM Transactions on Asian and Low-Resource Language Information Processing, 22(4), 1-21.

6. Tepei, M., & Bloem, J. (2025, September). A linguistically-informed comparison between multilingual BERT and language-specific BERT models: The case of differential object marking in Romanian. In Proceedings of the 15th International Conference on Recent Advances in Natural Language Processing-Natural Language Processing in the Generative AI Era (pp. 1271-1281).

</details>

<!--
<details>
    <summary> 5.  </summary>

### Aim 


### Data


### Bibliografy

</details> -->
