# Démystifions une architecture conteneurisée avec Kubernetes

Ce workshop s'adresse à toute personne souhaitant comprendre les bases du déploiement d'applications sur Kubernetes.  

## Pré-requis ✅
- Une connexion internet
- Un navigateur web
- Une connaissance de base des conteneurs

## Environnement 👩‍💻

Pour ce workshop, nous allons utiliser Gitpod, un environnement de développement en ligne basé sur VS Code.  
Pour démarrer votre environnement prêt à l'emploi : [![Environnement Gitpod](assets/gitpod.svg)](https://gitpod.io/?autostart=true#https://gitlab.com/codelab-kubernetes/workshop)  
Ouvrez le fichier `README.md` dans l'éditeur VS Code de Gitpod puis affichez la Preview du Markdown pour suivre les instructions. (Clic dans le contenu du fichier `README.md` puis `Ctrl + Shift + V`)

## Configuration 🔧

Configurez la variable d'environnement `PACKAGE_REGISTRY_PASSWORD` avec la valeur fournie.
```shell
export PACKAGE_REGISTRY_PASSWORD=<value>
```

Lancez le script `setup.sh` pour finaliser la configuration de votre environnement.
```shell
./setup.sh
```

## Prêt à commencer ? C'est parti [➡️](00-intro/README.md)
