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
  - **Apprentissage Non Supervisé** : Utilisation de techniques comme le clustering spectral pour identifier les différents comportements et rôles au sein de la colonie.
  - **Apprentissage Supervisé** : Entraînement de modèles tels que la Régression Logistique, les Arbres de Décision et les Réseaux de Neurones Convolutifs (CNN) pour classer les interactions et les comportements individuels.
  - **Utilisation de Roboflow** : Annotation manuelle des images et utilisation de Roboflow combiné avec des CNN (comme YOLO) pour suivre et détecter les fourmis dans différents environnements, y compris à l'intérieur du nid.
  - **Analyse des Interactions** : Étude des interactions entre les différentes catégories de fourmis, incluant l'analyse de la connectivité et de la fréquence des interactions.

## Résultats
- Identification et suivi des fourmis dans des vidéos de colonies, avec distinction des différents rôles et comportements.
- Construction de réseaux d'interactions pour étudier les dynamiques sociales et l'impact de la pollution sur le comportement des fourmis.
- Détection et classification des différents types d'interactions au sein de la colonie.

## Rapports
- **Description du Projet** : Pour une vue détaillée de la problématique, consultez [description.pdf](./projet.pdf).
- **Rapport Complet** : Le rapport final du stage détaillant les méthodes, analyses, et résultats est disponible dans [rapport_de_stage.pdf](./rapport_de_stage.pdf).

## Auteurs
- Koceila KEMICHE

## Encadrement
- Jean-Noël Vittaut, LIP6 – Sorbonne Université
- Marie Gressler, Institut d’Écologie et des Sciences de l’Environnement – Sorbonne Université
- Mathieu Molet, Institut d’Écologie et des Sciences de l’Environnement – Sorbonne Université

## Licence
Indiquez ici la licence sous laquelle le projet est distribué, par exemple MIT, GPL, etc.
