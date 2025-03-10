

# DataScience - Intelligent Modeling 2024-2025


## Lectures

Week1: Opening :)

Week2: [Introduction](ML_intro.ppt)

Week3: ML [regression](ML_regression.ppt) [example1](Examples/MLalgorithms.ipynb) [example2](Examples/MLopenCourse.ipynb)


## About projects

The project you have to do is an opportunity to explore an Artificial Intelligence (AI) problem in the context of real data. The project will be evaluated both at the end of the semester and during the semester, when each team will have to present to the teaching staff the corresponding iterations of the application and the related technical report.


**Project components**
- problem definition
- team (max 3 members)
- problem solving by AI-based algorithms
- application development and AI integration
- documentation (report)
- final presentation


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
- must follows this template [link](https://github.com/lauradiosan/DS-UBB/tree/main/2024-2025/Report/texModel/model.tex) and the recommended structure [link](https://github.com/lauradiosan/DS-UBB/tree/main/2024-2025/Report/readme.md). 


**Final presentation**
- teaser (a short video presentation)
- slides (or other presentation support)


**Evaluation**
- [criteria and points](Eval/readme.md)


# Proposed topics

<details>
    <summary> 1. Uterine cervical cancer </summary>

### Aim
- automatic identification of lessions in MRI images of uterine cervical cancer.

### TODOlist
1. Problem definition (details about inputs and outputs)
2. Exploratory data analysis
3. AI development and performance evaluation 
4. Improvements

### Data
- dataset1 [link](https://synthrad2023.grand-challenge.org/)
- dataset2 [link](https://github.com/SynthRAD2023/preprocessing)

### Bibliografy
- Bourgioti, C., Chatoupis, K., & Moulopoulos, L. A. (2016). Current imaging strategies for the evaluation of uterine cervical cancer. World journal of radiology, 8(4), 342. [link](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4840192/)
- Zaki, N., Qin, W., & Krishnan, A. (2023). Graph-based methods for cervical cancer segmentation: Advancements, limitations, and future directions. AI Open. [link](https://www.sciencedirect.com/science/article/pii/S2666651023000086)
- Kurata, Y., Nishio, M., Moribata, Y., Kido, A., Himoto, Y., Otani, S., ... & Nakamoto, Y. (2021). Automatic segmentation of uterine endometrial cancer on multi-sequence MRI using a convolutional neural network. Scientific Reports, 11(1), 14440.[link](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8280152/#MOESM1)
- Lin, Y. C., Lin, Y., Huang, Y. L., Ho, C. Y., Chiang, H. J., Lu, H. Y., ... & Lin, G. (2023). Generalizable transfer learning of automated tumor segmentation from cervical cancers toward a universal model for uterine malignancies in diffusion-weighted MRI. Insights into Imaging, 14(1), 14. [link](https://insightsimaging.springeropen.com/articles/10.1186/s13244-022-01356-8)
- Afshar, P., Mohammadi, A., Plataniotis, K. N., Oikonomou, A., & Benali, H. (2019). From handcrafted to deep-learning-based cancer radiomics: challenges and opportunities. IEEE Signal Processing Magazine, 36(4), 132-160. [link](https://arxiv.org/pdf/1808.07954.pdf)

</details>

<details>
    <summary> 2. Entity resolution </summary>

### Aim 
Entity resolution (also known as entity matching, record linkage, or duplicate detection) is the task of finding records that refer to the same real-world entity across different data sources (e.g., data files, books, websites, and databases).

### TODOlist
1. Problem definition (details about inputs and outputs)
2. Exploratory data analysis
3. AI development and performance evaluation 
4. Improvements

### Data

[Abt-Buy](https://paperswithcode.com/dataset/abt-buy)
[Amazon-Google](https://paperswithcode.com/dataset/amazon-google)

### Bibliografy

Christophides, V., Efthymiou, V., Palpanas, T., Papadakis, G., & Stefanidis, K. (2019). End-to-end entity resolution for big data: A survey. arXiv preprint arXiv:1905.06397. [link](https://arxiv.org/pdf/1905.06397)
Barlaug, N., & Gulla, J. A. (2021). Neural networks for entity matching: A survey. ACM Transactions on Knowledge Discovery from Data (TKDD), 15(3), 1-37. [link](https://arxiv.org/pdf/2010.11075)

Li, Y., Li, J., Suhara, Y., Doan, A., & Tan, W. C. (2020). Deep entity matching with pre-trained language models. arXiv preprint arXiv:2004.00584. [link](https://arxiv.org/pdf/2004.00584) [code](https://github.com/megagonlabs/ditto)

Peeters, R., Steiner, A., & Bizer, C. (2023). Entity matching using large language models. arXiv preprint arXiv:2310.11244. [link](https://arxiv.org/pdf/2310.11244v4) [code](https://github.com/wbsg-uni-mannheim/matchgpt)


</details>

<details>
    <summary> 3. Emotion recognition in economical behaviours </summary>

### Scop

Development of an intelligent system that allows the identification of emotions in the communications of official persons based on the written text associated with the communication, the vocal message associated with the communication, or the facial expressions of the person delivering the communication. 

### Ideea de baza
It is planned to develop a system with 3 components:
- a component that analyzes emotions in written text
- a component that analyzes emotions in the vocal message
- a component that analyzes emotions in the facial expressions of the person delivering the communication.

In the end, the three components will be merged.

### TODOlist
1. Problem definition (details about inputs and outputs)
2. Exploratory data analysis
3. AI development and performance evaluation 
4. Improvements

### Data

MELD dataset [link](https://affective-meld.github.io/)
Emory [link](https://github.com/emorynlp/character-mining)
FER [link](https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data)
AffWild [link](https://ibug.doc.ic.ac.uk/resources/aff-wild2/)


### Bibliografy

Curti, F., & Kazinnik, S. (2023). Let's face it: Quantifying the impact of nonverbal communication in FOMC press conferences. Journal of Monetary Economics, 139, 110-126. [link](https://www.sciencedirect.com/science/article/pii/S0304393223000740?casa_token=1glEZKEF3SsAAAAA:1N9OYe0N-WknNuD2jI9EZhvQ6abxYswddZYPgZ1_udhzWjIt8peIkZLDlM9sHAiR6s7yL4oIcQ)

Some models for emotion recognition in texts [model1](https://huggingface.co/michellejieli/emotion_text_classifier) [model2](https://huggingface.co/mrm8488/t5-base-finetuned-emotion)

Some models for emotion recognition in speech [model1](https://huggingface.co/r-f/wav2vec-english-speech-emotion-recognition)

Some models for emotion recognition in faces [model1](https://huggingface.co/ElenaRyumina/face_emotion_recognition) [model2](https://huggingface.co/trpakov/vit-face-expression)

</details>


<details>
    <summary> 4. ML for complex networks </summary>

### Aim 
Mapping key decision-making agents, their preferences and behavior. Estimate the future behaviour.


### TODOlist
1. Problem definition (details about inputs and outputs)
2. Exploratory data analysis
3. AI development and performance evaluation 
4. Improvements

### Data
- Overview of French parliamentary data (2017-2022) [2017-2022](https://data.assemblee-nationale.fr/archives-anterieures/archives-15e) [2022-2024](https://data.assemblee-nationale.fr/)
- Roll-call votes in the French Assembly (2017-2022) [2017-2022](https://data.assemblee-nationale.fr/archives-anterieures/archives-15e/scrutins) [2022-2024](https://data.assemblee-nationale.fr/archives-16e/votes)
- Dutch parliamentary data, including laws, amendments, and MP bios. Data coverage starts from 1995 and is continuously updated [Open Kamer](https://www.openkamer.org/)
- Hungarian and Czech parliamentary speeches, bills, and laws [link](https://parllawspeech.org/repository/)
- Parliamentary speeches dataset covering nine democracies, including Austria, Czech Republic, Germany, Denmark, Spain, Netherlands, New Zealand, Sweden, and the United Kingdom [link](https://dataverse.harvard.edu/dataverse/ParlSpeech)





### Bibliografy


Ding, J., Liu, C., Zheng, Y., Zhang, Y., Yu, Z., Li, R., ... & Li, Y. (2024). Artificial intelligence for complex network: Potential, methodology and application. arXiv preprint arXiv:2402.16887. [link](https://arxiv.org/pdf/2402.16887)
</details>

 
<details>
    <summary> 5. Market research </summary>

### Aim 

Word / text completion: as part of the analysis of a credit file, we have the section "competitive environment analysis" in the credit report (as in teh below example). The project aim is to develop an intelligent system that should search the WWW and bring what it finds about the respective field of activity and a few words about what the client actually does. The algorithm should bring what it finds about that market. 

Example for company "XYZ SRL – productia de bauturi alcolice si spirtoase"

![alt text](image.png)


### TODOlist
1. Problem definition (details about inputs and outputs)
2. Exploratory data analysis
3. AI development and performance evaluation 
4. Improvements

### Data
A consistent population of such examples: the company, the company's field of activity, and what the analyst wrote in the report. 

### Bibliografy

Example1 [link](https://www.analyticsvidhya.com/blog/2025/02/financial-market-analysis-ai-agent/)

Example2 [link](https://www.getdynamiq.ai/post/build-an-intelligent-agent-system-for-market-analysis-with-deepseek)


Competitive analysis [link](https://asana.com/resources/competitive-analysis-example)

Named Entity Recognition [link](https://asana.com/resources/competitive-analysis-example) [link](https://www.geeksforgeeks.org/named-entity-recognition/)
</details>


<!--
<details>
    <summary> 5.  </summary>

### Aim 

### TODOlist
1. Problem definition (details about inputs and outputs)
2. Exploratory data analysis
3. AI development and performance evaluation 
4. Improvements

### Data


### Bibliografy

</details> -->
