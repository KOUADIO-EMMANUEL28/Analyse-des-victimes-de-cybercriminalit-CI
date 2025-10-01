# Analyse-des-victimes-de-cybercriminalité-CI

## Table des matières

-[Description](#description)

-[Sources des données](#sources-des-données)

-[Outils](#ouils)

-[Préparation des données](#préparation-des-données)

-[Analyse exploratoire des données](#analyse-exploratoire-des-données)

-[Analyse des données](#analyse-des-données)

-[Résultats](#résultats)

-[Interprétation](#interprétation)

-[Recommandations](#recommandations)

-[Bon à savoir](#bon-à-savoir)


## Description

Ce projet traite des victimes de cybercriminalités en Côte d'Ivoire(2015). En l'analyse de ces données a pour but de mettre en évidence le lien entre les victimes ,les préjudices, les mis en cause et les différentes catégorie d'âge.



### Source de des données


Le datatest utilisé pour cette analyse est le fichier "tranche-d'age-des-victimes-et-des-mis-en-cause.csv", téléchargé sur le site de l'Agence National de Statistiques ANSAT.

### Outils


-PowerBi pour le traitement , l'analyse des données et la création de rapport. 


#### Préparation des données


Nous avons suivi cette démarche

1.Chargement et inspection des données

2.Suppression des doublons

3.Suppression des colonnes pas inutiles pour notre étude 

4.Création de nouvelles colonnes

#### Analyse exploratoire des données


L'analyse exploratoire des données consistait à explorer les données afin de répondre à des questions clés comme:

-Quelle est la tranche d'âge la plus vulnérable à la cybercriminalité , et pourquoi?

-Quelle est la tranche d'âge des présumés coupables?

-Comment mieux lutter contre ce fléau?


#### Analyse des données


Tout le travail s'est fait essentiellement sur PowerBi avec des options comme création de colonnes à partir d'exemples, Les filtres, et les différents histogramme.

#### Résultats

##### Répartition des victimes (nombre de dossiers) :

<img width="862" height="482" alt="nbr victim" src="https://github.com/user-attachments/assets/e140aeed-58b2-4704-9e2e-f3b6ab1f0898" />


<img width="890" height="420" alt="Frequence" src="https://github.com/user-attachments/assets/6f80c677-53db-43b1-bb95-ac260cb90ca0" />


29,3%  des dossiers sont des victimes de 26 à 35 ans.
27,95% des dossiers sont des victimes de 36 à 45.
17,6%  des dossiers sont des victimes de de 46 à 55 ans.
15,94%  des dossiers sont des victimes de 50 à 90 ans
8,28%  des dossiers sont des victimes de 18 à 25 ans
0,93%  des dossiers sont des victimes de moins de 18 ans


 ##### Répartition des préjudices par tranche d'âge des victimes

<img width="861" height="484" alt="prjt" src="https://github.com/user-attachments/assets/cd57aba2-02b8-4642-adf6-baeb3f73bcf5" />

<img width="882" height="472" alt="prjcfq" src="https://github.com/user-attachments/assets/825b6769-99d6-42f9-8d1d-5e19082ec219" />

<img width="863" height="471" alt="Capture d'écran 2025-09-29 202323" src="https://github.com/user-attachments/assets/5078ab5d-5b0b-4473-80ef-57da79d3c99e" />

<img width="891" height="480" alt="prjdcconsr" src="https://github.com/user-attachments/assets/457ec083-df9c-40f1-b0a9-ae049b675462" />


57% du montant total des préjudices tentés ont des victimes de 50 à 90 ans
19% du montant total des préjudices tentés ont des victimes de 36 à 45 ans
13% du montant total des préjudices tentés ont des victimes de 26 à 35 ans
9% du montant total des préjudices tentés ont des victimes de 46 à 55 ans
2% du montant total des préjudices tentés ont des victimes de 18 à 25 ans
0,07% du montant total des préjudices tentés ont des victimes de moins de 18 ans 




##### Mis en cause Interpellés

<img width="864" height="487" alt="interp" src="https://github.com/user-attachments/assets/a15f2488-0c09-427e-9e9d-8e0d78b9b47a" />

<img width="864" height="485" alt="interpR" src="https://github.com/user-attachments/assets/410bae6e-f437-42f9-9b26-f4072d84f1ba" />


32% des mis en cause interpellés ont l'âge qui varie entre 23 et 27 ans
31% des mis en cause interpellés ont l'âge qui varie entre 18 et 22 ans
21% des mis en cause interpellés ont l'âge qui varie entre 28 et 33 ans
11% des mis en cause interpellés ont l'âge qui varie entre 33ans et plus
5% des mis en cause interpellés ont l'âge qui varie entre 0 et 18 ans



##### Mis en cause déférés

<img width="868" height="486" alt="defr" src="https://github.com/user-attachments/assets/dbdc278d-d6c0-42b0-a89e-fd9cf7411dea" />

<img width="865" height="468" alt="defrr" src="https://github.com/user-attachments/assets/cc599b51-30d7-431f-93a4-1d56ff912e94" />


33% des mis en cause déférés ont l'âge qui varie entre 18 et 22 ans
32% des mis en cause déférés ont l'âge qui varie entre  23 et 27 ans
20% des mis en cause déférés ont l'âge qui varie entre 28 et 33 ans
12% des mis en cause déférés ont l'âge qui varie entre 33ans et plus
5% des mis en cause déférés ont l'âge qui varie entre 0 et 18 ans


#### Interprétation 

-Concernant les victimes:

Les tranches 26–35 ans (29,3%) et 36–45 ans (27,95%) regroupent plus de la moitié des victimes en termes de fréquence.

Les jeunes 18–25 ans (8,28%) et les mineurs (<18 ans : 0,93%) sont moins représentés en nombre.

Les plus âgés (50–90 ans) représentent 15,94% des dossiers mais subissent les préjudices financiers les plus lourds (57%).


Les adultes actifs (26–45 ans) sont les plus exposés aux attaques car ils sont très connectés (réseaux sociaux, e-commerce, transferts financiers en ligne).

Les personnes âgées (50–90 ans), bien que moins touchées en nombre, sont les plus vulnérables financièrement car ils  manquent généralement de compétences numériques, ils ont une confiance élevée dans les interlocuteurs en ligne, et ont un patrimoine financier plus conséquent.

Les jeunes (<25 ans) sont plus familiers avec Internet et les outils numériques, ce qui réduit leur exposition, mais ils restent une cible (arnaques sentimentales, jeux en ligne, crypto, etc.).


-Concernant les  mis en cause


Mis en cause interpellés :

32% ont entre 23–27 ans

31% ont entre 18–22 ans

21% ont entre 28–33 ans

Donc 84% ont entre 18 et 33 ans.

Mis en cause déférés :

33% (18–22 ans), 32% (23–27 ans), 20% (28–33 ans)

Même logique : 85% ont entre 18 et 33 ans.


La grande majorité des cybercriminels interpellés sont jeunes adultes (18–33 ans).

Cela peut s’expliquer premièrement par le fait que les jeunes adultes sont ceux qui maitrisent les plus les outils numériques.

Ensuite , on peut évoquer le chômage élevé des jeunes diplômés et sous-diplômés, les incitant à chercher des revenus alternatifs.

La culture de la cybercriminalité parfois banalisée dans certains milieux sociaux et l’absence de contrôle parental et institutionnel sur les usages numériques dès l’adolescence peuvent aussi servir d'explication.





#### Recommandations 

Mener des campagnes de sensibilisation sur le danger que représente la cybercriminalité tout en appelant les uns et les autres à vigilance.

Accompagner les personnes âgées dans leurs usages numériques puisque ceux sont elles les plus vulnérables d'après les statistiques.

Programmes de prévention et d’éducation numérique dès le lycée : expliquer les risques légaux et sociaux de la cybercriminalité.

Insertion professionnelle et entrepreneuriat numérique : orienter les jeunes vers des opportunités légales (freelance, e-commerce, développement web).

Sanctions adaptées et accompagnement : combiner répression et réinsertion pour les jeunes cybercriminels.




#### Bon à savoir

 Une grande partie des observation(près de 50%) était dans la tranche d'âge "non défini" , Nous n'avons donc pas pris en compte cette catégorie dans notre travail.
Raison pour laquelle nous avons préféré travailler avec les fréquences , histoire d'avoir une vue en terme de proportion.


