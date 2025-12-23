# 📚 Text Mining – Histoire et culture du rap (1980–2025)

**Mymolyvann SAM**  
Master **D2SN** – Analyse textuelle / Text mining

---

## 🧠 Présentation du projet
Ce projet propose une **analyse textuelle approfondie** d’un vaste corpus consacré à l’histoire et à la culture du rap, couvrant la période **1980–2025**.

Le corpus étudié se compose de **plus de 3000 documents** (livres, articles académiques, chapitres d’ouvrages, thèses, etc.).  
L’objectif est d’explorer comment le **discours sur le rap** a évolué au fil du temps, en mobilisant des outils de text mining à différentes échelles d’analyse.

---

## 🎯 Objectifs de l’analyse
- Étudier l’évolution temporelle du discours sur le rap  
- Identifier les **thématiques dominantes** et émergentes  
- Mettre en évidence les **champs lexicaux** et leurs cooccurrences  
- Analyser le **positionnement grammatical** du rap dans les textes  
- Comprendre la transformation du rap en tant qu’objet culturel et académique

---

## 🗂️ Description du corpus
- **Période couverte** : 1980–2025  
- **Volume** : +3000 documents  
- **Types de documents** :
  - Articles académiques et de presse
  - Chapitres d’ouvrages
  - Livres
  - Thèses et mémoires
  - Guides, encyclopédies et autres formats

Répartition approximative :
- Articles : ~60 %
- Chapitres d’ouvrages : ~16 %
- Livres : ~7 %
- Thèses et mémoires : ~4 %
- Autres formats : ~5 %

---

## ⏱️ Exploration temporelle et structurelle
L’analyse chronologique montre une **augmentation très marquée des publications après les années 2000**, avec un pic dans les années 2010.

- Années 1980–1990 : production faible
- Années 2000–2020 : explosion du nombre de publications

Cette évolution témoigne de la **légitimation progressive du rap** comme objet culturel et académique.

La longueur des documents est hétérogène :
- Majorité de textes courts (articles, chapitres)
- Quelques documents très volumineux (livres, thèses)

<img width="560" height="499" alt="Capture d’écran 2025-12-23 061600" src="https://github.com/user-attachments/assets/b73e942b-237a-4fa2-87f1-3c71a6f8abbe" />


---

## 🔤 Analyse lexicale
L’analyse lexicale repose sur :
- La construction de **matrices de cooccurrence**
- La visualisation sous forme de **heatmaps**
- La création de **clustermaps hiérarchiques**

Cette approche permet d’identifier des **dictionnaires implicites** et des **champs sémantiques** structurant le discours sur le rap.

<img width="703" height="373" alt="Capture d’écran 2025-12-23 061705" src="https://github.com/user-attachments/assets/c6a654c8-61e8-4308-aaeb-9f79b592bfa0" />


### Exemples d’associations fortes :
- *hip* – *hop*
- *African* – *American*
- *rap* – *music*
- *rap* – *culture*

La normalisation des matrices permet de faire émerger des relations sémantiques fines, indépendamment des fréquences brutes.

---

## 🧩 Structuration thématique
Les documents et sources ont été regroupés selon leurs profils lexicaux afin d’identifier des **communautés discursives**.

<img width="710" height="432" alt="Capture d’écran 2025-12-23 061950" src="https://github.com/user-attachments/assets/921e6cff-7726-4899-95cd-468a11b79886" />

Trois grands axes se dégagent :
- **Musicologique** : son, genre musical, pratiques artistiques
- **Socio-culturel** : identité, race, politique, société
- **Interdisciplinaire** : croisement musique / culture / sciences sociales

La normalisation par source révèle les **spécificités éditoriales** de chaque revue ou éditeur.

---

## 🗺️ Cartographie thématique
Une cartographie circulaire met en évidence quatre grands axes :
- **Bleu** : identité et culture afro-américaine (axe dominant)
- **Orange** : dimension technique et technologique
- **Vert** : mondialisation et circulation géographique du rap
- **Violet / Rose** : thématiques émergentes (genre, linguistique, éducation)

<img width="437" height="303" alt="Capture d’écran 2025-12-23 062135" src="https://github.com/user-attachments/assets/bb1aebb5-3410-436d-a453-27ab97b8ac51" />


Cette visualisation montre un **écosystème thématique interconnecté**, sans cloisonnement strict.

---

## 🧠 Analyse syntaxique et grammaticale
L’analyse syntaxique s’intéresse au rôle grammatical du mot **« rap »** dans les phrases :
- Rap comme **sujet** (acteur culturel)
- Rap comme **objet** (objet d’étude, de commerce, d’analyse)

<img width="402" height="526" alt="Capture d’écran 2025-12-23 062516" src="https://github.com/user-attachments/assets/32d8d7b4-5ae0-4e14-b642-4f26bf1ae4fb" />

Sur cette matrice, chaque ligne correspond à un verbe qui apparaît avec rap dans au moins une phrase,
et chaque colonne indique un rôle syntaxique de rap par rapport à ce verbe (nsubj = sujet, nsubjpass =
sujet passif, dobj = objet direct, pobj = objet d’une préposition, etc.). Les couleurs plus claires
indiquent une fréquence plus élevée de la configuration correspondante dans le corpus. La partie
supérieure de la figure montre la matrice brute, tandis que la partie inférieure la réordonne après un
clustering pour regrouper les verbes aux profils similaires.


### Deux perspectives complémentaires :
- **Ce que le rap fait** : exprimer, représenter, émerger, servir
- **Ce que l’on fait du rap** : vendre, utiliser, étudier, caractériser

<img width="595" height="558" alt="Capture d’écran 2025-12-23 062331" src="https://github.com/user-attachments/assets/9629eadf-d6e2-4a19-9bec-3a76b8de55ea" />


Cette dualité révèle une évolution discursive majeure :
> le rap est à la fois **acteur symbolique** et **objet socio-culturel**.

---

## 📌 Conclusion
L’analyse multiscalaire du corpus met en évidence :
- La **massification** et la **légitimation académique** du rap
- Une **diversification thématique** croissante
- Une **segmentation des discours** selon les communautés
- Un changement de posture : le rap devient un **acteur culturel à part entière**

Le rap apparaît ainsi non plus comme un simple genre musical, mais comme un **phénomène culturel, social et académique multidimensionnel**, documenté sur plus de quarante années.

---

## 🛠️ Outils et méthodes
- Python  
- Text mining  
- Cooccurrences lexicales  
- Clustering hiérarchique  
- Analyse syntaxique (dépendances)  
- Visualisations (heatmaps, clustermaps, graphes)
