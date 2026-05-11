## Bienvenue sur mon Github

Bonjour, je suis Damien THAI, ingénieur en IA générative et passionné par l'application de l'IA pour la résolution de problèmes concrets. Sur ce github sont présentés mes projets scolaires accompagnés de leur code ainsi que des articles détaillant mes projets professionnels. 

À travers ces projets, j’ai pu utiliser une variété de technologie d’IA couvrant l’analyse de données, le NLP, l’utilisation personnalisée de LLM, des systèmes agentiques, de computer vision et d’IA génératrice d’images. Les résultats de ces projets sont alors des articles et/ou des applications complètes (avec UI) et déployées. 


## Projets Scolaires

### Projet kit big data
Ce projet est une analyse exploratrice de données portant sur un dataset Kaggle de recettes (176 287) issues de food.com. Cette analyse explore les tendances de popularités du site et se conclut par des recommandations afin d’améliorer le trafic sur le site.  

**Résultats** :  
GitHub : [kit big data](https://github.com/thaid27/projet_Kit_Big_Data)
Résultats de l'analyse (PDF) : [Première page du site web(PDF)](https://github.com/thaid27/projet_Kit_Big_Data/blob/main/EDA_results.pdf)    
Lien de la webapp : [Application streamlit](https://projetkitbigdataipja7lrnugkzoh5way2ngf.streamlit.app)

**Technologies utilisées** : 
- Environnement : python
- stack data pour la visualisation de données : pandas, matplotlib, seaborn
- UI et webapp : Streamlit, Streamlit Cloud
- maintenance et partage de code : github (tests et pipeline CI/CD)

---

### Reproducibility Challenge : Visual Jenga
Ce projet cherche à reproduire et à approfondir les résultats d’un papier de recherche. L’article traité étudie comment la suppression d’objets dans une image par IA peut apporter des informations sur sa structure logique.

**Résultats** :  
GitHub : [visual jenga](https://github.com/thaid27/visual_jenga)  
Article : [Reproduction Challenge : Visual Jenga](https://github.com/thaid27/visual_jenga/blob/main/reproducibility_visual_jenga.pdf)

**Technologies utilisées** : 
- Environnement : python, Kaggle
- MOLMO : modèle multimodal utilisé pour localiser les objets dans une image
- SAM: modèle de segmentation et de création de masque 
- Stable Diffusion inpainting: modèle génératif d’image

---

### Projet NLP
Ce projet propose une étude thématique d’une série d’articles (627) traitant de l’éthique de l’IA. Plusieurs méthodes de NLP sont alors utilisées afin de regrouper et de trouver les thèmes communs présents dans cette liste d’articles. 

**Résultats** :  
GitHub : [projet NLP](https://github.com/thaid27/projet_NLP)  
Rapport du projet : [Visualisation and analysing AI ethics charters & manifestos with clustering](https://github.com/thaid27/projet_NLP/blob/main/Rapport%20projet%20NLP%20clustering.pdf)

**Technologies utilisées** : 
- Embeddings : SVD et variantes, GloVe, TF-IDF, RoBERTA.
- Clustering : Kmeans, gaussien, hiérachique.
- Topic modeling : LDA, BERTopic, GPT-4o-mini.

---

### Projet Drone
Ce projet utilise un modèle de vision afin d’orienter le pilotage d’un drone. Un modèle CLIP interprète les images de la caméra de drone naviguant devant une série d’images et se pose devant celle contenant l’objet correspondant au prompt utilisateur.  

**Résultats** :  
GitHub : [projet drone](https://github.com/thaid27/projet_NLP)  
Présentation du projet : [lien de la présentation (PDF)](https://github.com/thaid27/Projet_Drone/blob/main/Projet_drone_presentation.pdf)

**Technologies utilisées** : 
- python et bibliothèque propriétaire pour le contrôle du drone
- Embedding texte/image : CLIP
- Analyse de similarité par cosinus

---

## Projets Professionnels

### Agent de veille technologique 
Cet agent vise à automatiser le processus de veille technologique en générant une newsletter hebdomadaire sur les nouveaux outils de génération IA sortis dans la semaine. 
Il est relié à une base de données stockant toutes les descriptions d'outils générées.

**Résultats** :  
GitHub : [agent newsletter](https://github.com/thaid27/agent_veille_tech_N8N)  
Exemple de newsletters : [newsletter](https://thaid27.github.io/agent_veille_tech_N8N/assets/newsletter_example.html)  
Workflow n8n : [workflow](workflow/agent_veille_tech.json)


**Technologies utilisées** :
- Workflow agentique : n8n
- LLM sur le cloud : Azure AI
- Base de données vectorielle sur le cloud : Azure Search 
- API Google : YouTube Data API (web scraping),  Gmail API (distribution)
- API externe : RapidAPI (web scraping)

---

## Usage de l'IA dans le milieu créatif
Cet article explore les usages des modèles génératifs dans le domaine créatif et dans un cadre commercial, couvrant une variété de supports tels que l'image, la vidéo, l'audio ou la 3D.

**Résultats** :  
GitHub : [IA générative créative](https://github.com/thaid27/IA_generative_creative) 

**Technologies utilisées** :
- Environement local : ComfyUI (workflow génératif nodale), python
- Enviroment cloud : Krea
- modèle d'images : Flux (krea, klein), Z-image, Qwen-Edit, Nano banana, Seedream 
- modèle de video : Veo3, Wan, Kling, LTX, Seedance 








