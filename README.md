# Système de pointage basé sur la reconnaissance faciale

Projet réalisé dans le cadre de l'EEIA 2024. Il porte sur la conception d'un
système de gestion des présences capable de détecter et d'identifier des
personnes en temps réel à partir de leur visage.

## Objectifs

- Automatiser la gestion des présences et du pointage ;
- détecter les visages dans un flux vidéo ;
- identifier les personnes reconnues en temps réel ;
- afficher automatiquement les personnes identifiées sur un tableau de bord ;
- étudier les étapes de constitution des données, d'entraînement et
  d'évaluation d'un modèle de reconnaissance faciale.

## Approche retenue

Le projet s'appuie sur une chaîne de traitement composée des étapes suivantes :

1. **Constitution du jeu de données** : collecte et organisation des images
   associées aux personnes à reconnaître ;
2. **Traitement des données** : préparation des images avant l'entraînement ;
3. **Détection des visages** : localisation des visages présents dans les
   images ou le flux vidéo ;
4. **Reconnaissance** : classification des visages détectés à l'aide d'un
   réseau de neurones convolutif (CNN) développé pour le projet ;
5. **Évaluation** : suivi de la précision et de la perte afin d'évaluer la
   qualité du modèle ;
6. **Affichage** : restitution des personnes identifiées dans un tableau de
   bord destiné au suivi des présences.

Le modèle a été entraîné pendant **100 epochs**. Les supports du projet
indiquent une convergence du modèle, une précision significative et une perte
faible.

## Contenu du dépôt

| Fichier | Description |
| --- | --- |
| `1-Introduction_a_la_reconnaissance_Faciale_EEIA.pdf` | Document d'introduction et de présentation de la reconnaissance faciale |
| `POSTER SYSTÈME DE RECONNAISSANCE FACIALE.pptx` | Poster de présentation du projet |

> Ce dépôt contient actuellement les documents de présentation du projet. Le
> code source du modèle, les données d'entraînement et l'application de
> pointage ne sont pas inclus.

## Résultats et applications

Le système présenté est destiné à détecter et identifier des visages en temps
réel. Les applications envisagées comprennent notamment :

- la gestion des présences ;
- le pointage automatisé ;
- le suivi des personnes autorisées ;
- certaines applications de sécurité, sous réserve du respect des règles
  applicables en matière de protection des données personnelles.

## Équipe

- AGBAMAHOU Onel Charbel
- AGONGNON S. Kevin
- AÏFA Aristidina
- DALKO Narcisse
- DEGBEY Emmanuel Durkheim
- GBOZO Livingstone O. M.
- GOHOUNGO Denis
- GOUSSOU Timothé
- HOUENOU Renaud
- HOUNDJI I. M. Serge
- HOUNGBE Ulrich D. G. M.
- HOUNSAMENOU Nicaise
- OUSMANE Aymane
- TCHABI Kolawolé Hubert

### Encadrement

- Ing. Sidoine Romaric AGUE
- Mlle Joaïda AKOTENOU
- Ing. Vincent WANNOU

## Limites et bonnes pratiques

La reconnaissance faciale peut produire des erreurs et des résultats
différents selon la qualité des images, l'éclairage, l'angle du visage et la
représentation des personnes présentes dans le jeu de données. Toute
utilisation réelle doit prévoir un consentement approprié, une protection
rigoureuse des données et une solution de vérification humaine en cas
d'incertitude.

## Licence

Aucune licence n'est actuellement déclarée dans ce dépôt.
