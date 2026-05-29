# Formation CNRS - Introduction au machine learning et au deep learning avec Python

## Description de la formation du 10 au 12 juin 2026

Cette [formation](https://cnrsformation.cnrs.fr/catalogue/formation/269/introduction-au-machine-learning-et-au-deep-learning-avec-python/) sera encadrée par:

- Tabea Rebafka
- Daphné Giorgi
- Vincent Lemaire 

Les cours se dérouleront 

- de **9h00 à 17h30** du mercredi 10 au vendredi 12 juin 2026
- en **salle 113, couloir 16-26**, au 4, place Jussieu, 75005
- avec sessions théoriques suivies de travaux pratiques.


| Horaire     | Sujet             | Salle     |
| ----------- | ----------------- | --------- |
| 8:30-9:00   | Accueil café      | 16-26 113 |
| 9:00-12:00  | Formation         | 16-26 113 |
| 12:00-13:00 | Pause déjeuner    | --------- |
| 13:00-17:00 | Formation         | 16-26 113 |

Les objectifs de la formation sont
- Comprendre les concepts mathématiques des méthodes de l'apprentissage statistique supervisé (régression et classification)
- Connaître les principaux algorithmes du deep learning
- Savoir utiliser les librairies Python pour la mise en œuvre des méthodes de machine learning et de deep learning
- Savoir choisir les algorithmes adaptés aux cas d'usages
- Savoir interpréter les résultats des algorithmes et identifier leurs limites

## Prérequis

Il est demandé aux participants d'être équipés d'un ordinateur portable et il est fortement recommandé d'installer en avance les logiciels et outils nécessaires à la formation.

Une version de python supérieure à 3.13 est requise, pour vérifier votre version : 

```shell
python3 --version
```

L'idéal est de créer un environement virtuel, pour éviter tout conflit avec d'autres installations de paquets.

```shell
cd TPs
python3 -m venv .venv
source .venv/bin/activate 
```
Les paquets Python nécessaires à la formation sont listés dans le fichier `requirements.txt`. Pour les installer depuis la console, il suffit de taper la commande :

```shell
pip install -r requirements.txt
```

Les travaux pratiques se feront sur des notebook Python. Pour vérifier que les dépendances ont été correctement installées, lancer un `jupyterlab` depuis le répertoire `TPs` en tapant la commande

```shell
jupyter lab
```

et exécuter le notebook `test.ipynb`.

## Matériel

Les transparents des cours se trouveront dans le répertoire `Cours`.

Les notebook pour les travaux pratiques se trouveront dans le répertoire `TPs`.

> [!IMPORTANT]  
> Afin de garantir un démarrage fluide de la formation et d’éviter les ralentissements liés à des téléchargements simultanés le jour J, merci de télécharger l’ensemble des fichiers et ressources nécessaires en amont de la session.

Les fichiers de données du 2ème jour sont à télécharger [ici](https://sdrive.cnrs.fr/s/LLDbRWrbmAfRBkK) et à copier dans le répertoire `TPs/data`. 

```shell
cd TPs 
wget https://sdrive.cnrs.fr/public.php/dav/files/LLDbRWrbmAfRBkK/\?accept\=zip -O data.zip
unzip data.zip
```
