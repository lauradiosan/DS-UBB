Raportul trebuie sa includa informatii despre:

**Membrii echipei**
1. Date de identificare (nume, prenume, email, grupa)
2. skills and rolls
3. performed tasks (Gannt diagram)

**Introducere**
1. Ideea de baza a proiectului
2. Motivatie (accent pe necesitatea folosirii unui algoritm inteligent) 

**Problema stiintifica abordata**
1. Descrierea (plastica si formala) a problemei stiintifice care trebuie rezolvata
2. Adaugarea unui abstract grafic (o diagrama care sa reflecte pasii efectuati in aplicatie si rolul/ideea de baza a lor) - un exemplu gasiti [aici](https://ars.els-cdn.com/content/image/1-s2.0-S0010482519303014-fx1_lrg.jpg)

**Metode existente de rezolvare a problemei (related work)**
Pentru fiecare lucrare referita mentionati urmatoarele aspecte: 
- scurta descriere a datelor pe care s-a lucrat, 
- scurta descriere a algoritmului cu care s-a lucrat, 
- rezultatele obtinute

**Metode efectiv folosite pentru rezolvarea problemei**
Descrierea algoritmilor inteligenti folositi, a procesului de invatare/optimizare implicat, a metricilor folosite pentru aprecierea calitatii rezolvarii problemei

**Descrierea solutiei propuse din punct de vedere tehnologic**
1. Versioning tools (general ones or some specialized ones?)
- Code versioning
i.	DVC https://dvc.org/ (a CLI tool)
ii.	Pachyderm https://www.pachyderm.io/open_source.html
iii.	MLflow Projects https://www.mlflow.org/docs/latest/projects.html  (API and CLI tool)
- Data versioning https://emilygorcenski.com/post/data-versioning/

2. SW design
- Type of the high-level architecture (e.g. Fixed or flexible, distributed or not, architectural pattern, etc.)
- Component/module coupling (low coupled / highly coupled)
- AI component serving (serializable - pickle, MLleap http://mleap-docs.combust.ml/ -, xml format – PMML http://dmg.org/pmml/v4-3/GeneralStructure.html, json format – PFA http://dmg.org/pfa/docs/motivation/ -, H2O (POJO object http://docs.h2o.ai/h2o/latest-stable/h2o-docs/productionizing.html), 
i.	Embedded component
ii.	Component as a [micro]service
iii.	Intelligent component published as data
iv. other (which one)
- details about training (static/off-line or dynamic/online)
- details about inference (static or dynamic)

3.	SW pipeline
- Pipeline's diagram (in order to better visualise the most important steps and components of the project)
- Iterative perspective (for AI component) – how do these iterations roll and how do they affect the SW developping process?

4.	SW code
-	Usage of external/specialized ML libraries or not
- Debugging and bug identification (how?)
- Testing (how? which components have been tested?)

5.	Model deployment
6.	Continuous delivery 
a.	Process
b.	Used tools 



**Rezultate experimentale obtinute**
Descrierea seturilor de date folosite (sursa datelor, clasificarea/tipologia datelor). Elemente care pot ajuta descrierea datelor:
1. How the data was collected?
2. How the data was stored? (please justify your choice)
- Data warehouse
- Data streams
- Data lake
- Data mesh
- other (which one)
3. How the data could be visualized and analysed?
- FACETS https://pair-code.github.io/facets/
- PyViz https://pyviz.org/
- Altair https://altair-viz.github.io/
- Embedded projector http://projector.tensorflow.org/
- Code examples: https://github.com/parulnith/Data-Visualisation-libraries

Metodologia experimentala (care sunt întrebările la care ar trebui să răspundă exeperimentele efectuate)  si parametrii algoritmilor

Rezultatele obtinute (măsurile de performanţă calculate ca urmare a aplicării celor 2 algoritmi inteligenti pentru rezolvarea problemei

Analiza statistica a rezultatelor obtinute si posibilele surse de eroare sau threats.

**Philosofical aspects**
1. Social impact of your project & results
2. Ethics in your ML-based projects
3. Fairness of your intelligent algorithm
- https://cloud.google.com/blog/products/ai-machine-learning/building-ml-models-for-everyone-understanding-fairness-in-machine-learning
- https://developers.google.com/machine-learning/fairness-overview


**Concluzii si posibile imbunatatiri**
Incercati sa raspundeti la intrebari precum:
- Daca s-a reusit rezolvarea problemei considerate? Cat de bine?
- Care sunt avantajele (punctele forte) si dezavantajele (punctele slabe) abordarii propuse?
- Cum se mai poate dezvolta abordarea curenta?

**Referinte** (formatate, adica editate in acelasi stil)





	
**Pipeline**
