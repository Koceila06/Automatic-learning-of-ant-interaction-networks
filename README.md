# Projet de Stage - Apprentissage Automatique des Réseaux d'Interactions chez la Fourmi *Temnothorax nylanderi*

Ce projet de stage porte sur l'étude des réseaux d'interactions sociales chez la fourmi *Temnothorax nylanderi* à l'aide de méthodes d'apprentissage automatique. L'objectif principal est d'identifier les changements de comportement au sein d'une colonie de fourmis en réponse à la pollution.

## Structure du Projet

Le projet se divise en deux parties principales :

### 1. Prétraitement des Données
- **Objectif** : Adapter des bibliothèques existantes pour analyser les enregistrements vidéo des colonies de fourmis et extraire les positions et orientations des individus sans l'utilisation de QR-codes.
- **Étapes** :
  - Utilisation de filtres gaussiens, de conversion en niveaux de gris, et de soustraction d'arrière-plan pour isoler les fourmis en mouvement.
  - Construction de séries temporelles de positions pour chaque individu dans la colonie.
  - Identification des zones importantes pour les comportements des fourmis (nourrissage, interaction avec la reine, etc.).

### 2. Analyse des Données et Apprentissage Automatique
- **Objectif** : Construire des réseaux d'interactions entre les individus et analyser ces réseaux à l'aide de méthodes d'apprentissage supervisé et non supervisé.
- **Étapes** :
  - **Utilisation de Roboflow** : Annotation manuelle des images et utilisation de Roboflow combiné avec des CNN (comme YOLO) pour suivre et détecter les fourmis dans différents environnements, y compris à l'intérieur du nid.
  - **Apprentissage Non Supervisé** : Utilisation de techniques comme le clustering spectral pour identifier les différents rôles au sein de la colonie.
  
  - **Analyse des Interactions** : Étude des interactions entre les différentes catégories de fourmis, incluant l'analyse de la connectivité et de la fréquence des interactions.

## Résultats
- Identification et suivi des fourmis dans des vidéos de colonies, avec distinction des différents rôles et comportements.
- Construction de réseaux d'interactions pour étudier les dynamiques sociales et l'impact de la pollution sur le comportement des fourmis.
- Détection et classification des différents types d'interactions au sein de la colonie.

## Rapports
- **Rapport Complet** : [rapport_de_stage.pdf](https://github.com/user-attachments/files/17028631/rapport_de_stage.pdf)


## Auteurs
- Koceila KEMICHE

