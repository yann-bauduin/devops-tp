# Projet DevOps 2024

## Description du Projet
Ce projet est conçu pour démontrer et mettre en pratique mes compétences en DevOps, en utilisant des outils comme Git, Bash, et GitHub, ainsi que la personnalisation de l'environnement de développement avec GitPod et Docker.

## Prérequis
Pour utiliser ce projet, vous aurez besoin de :
- Un compte GitHub
- GitPod avec l'extension GitPod installée dans votre navigateur

## Installation
Pour commencer à travailler avec ce projet, suivez ces étapes :
1. Clonez ce dépôt sur votre machine locale ou ouvrez-le directement dans GitPod en utilisant le lien suivant :
git clone https://github.com/yann-bauduin/devops-tp.git

2. Assurez-vous que toutes les dépendances nécessaires sont installées, comme spécifié dans le fichier `.gitpod.Dockerfile`.

## Structure du Projet
- `personnages.sh` : Un script pour créer des répertoires avec des noms basés sur la date et l'heure actuelles.
- `.gitpod.Dockerfile` : Fichier Docker utilisé pour configurer un environnement GitPod personnalisé.
- `.gitpod.yml` : Fichier de configuration GitPod pour l'utilisation de l'image Docker personnalisée.

## Utilisation
Pour utiliser les scripts inclus dans ce projet, positionnez-vous dans le répertoire du projet et exécutez les commandes correspondantes. Par exemple, pour exécuter `personnages.sh` :
bash personnages.sh "nom_du_répertoire"


## Contribuer
Si vous souhaitez contribuer à ce projet, voici comment procéder :
1. **Fork** ce dépôt.
2. **Créez une nouvelle branche** pour vos changements :
git checkout -b votre_branche

3. **Apportez vos modifications** et faites un commit :
git commit -am 'Ajoutez une description des modifications'

4. **Poussez votre branche** et ouvrez une Pull Request :
git push origin votre_branche

## Licence
Ce projet est distribué sous la licence MIT, qui permet une grande flexibilité pour sa réutilisation et sa distribution. Consultez le fichier `LICENSE` pour plus de détails.
