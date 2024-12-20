# Microservices

> ❌ A travailler

> ✔️ Auto validation par l'étudiant

## 🎓 J'ai compris et je peux expliquer

- les différences avec l'architecture monolithique ✔️
  - Le client communique avec une API gateway qui va rediriger vers tous les services
  - on divise tous les services en micro services indépendants qui vont communiquer grâce à la queue
  - permet d'utiliser différent language de programmation et BDD (on peut développer un algo en python et une backend en nodejs)
  - on peut augmenter les capacités (cpu, disque dur, etc) d'un seul micro-service, plus économique
  - on est sur du scaling horizontal
- la communication asynchrone entre services ✔️
  - J'ai compris qu'en passant par une architecture micro-services, il reste des singles points of failure qu'il faut documenter et surveiller, mais sinon on passe par la queue qui va gérer les différents messages et transmettre entre chaque micro service
- le deploiement d'un cluster ❌ / ✔️

## 💻 J'utilise

### Un exemple personnel commenté ❌ / ✔️

### Utilisation dans un projet ❌ / ✔️

[lien github](...) Good corner

Description : On a transformé l'application Good Corner en micro services avec Docker / nginx. Cela nous a permis de rajouter un micro service pour l'upload d'image qui n'est pas accessible en GraphQL. On a pu créer un autre serveur en express et on l'a ajouté dans notre docker + dans notre fichier nginx pour la configuration.

### Utilisation en production si applicable❌ / ✔️

[lien du projet](...)

Description :

### Utilisation en environement professionnel ❌ / ✔️

Description :

## 🌐 J'utilise des ressources

### Titre

- lien
- description

## 🚧 Je franchis les obstacles

### Point de blocage ❌ / ✔️

Description:

Plan d'action : (à valider par le formateur)

- action 1 ❌ / ✔️
- action 2 ❌ / ✔️
- ...

Résolution :

## 📽️ J'en fais la démonstration

- J'ai ecrit un [tutoriel](...) ❌ / ✔️
- J'ai fait une [présentation](...) ❌ / ✔️
