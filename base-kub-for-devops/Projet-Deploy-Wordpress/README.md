# Création des variables d'environnement

Nous allons stockés l'ensemble des mot de passe dans les variables d'envrironnement

```bash
export password=password
export root_password=root_password
```

 ## Création du namespace

```bash
kubectl apply -f namespace.yml
```

## Création du service Wordpress

```bash
kubectl apply -f .
```bash

## Accéder à l'application Word

L'application est exposer sur le port 30008
