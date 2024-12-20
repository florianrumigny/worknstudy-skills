# Docker

> ❌ A travailler

> ✔️ Auto validation par l'étudiant

## 🎓 J'ai compris et je peux expliquer

- la création d'une image docker ✔️
  - pour créer une image Docker, on a besoin d'un Docker file à la base du service/projet et on a besoin de construire l'image en ligne de commande avec "docker build -t my app".
- l'éxécution d'un container ✔️
  - pour lancer un container, on a besoin d'avoir construit l'image et on peut utiliser la commande "docker run -d hello app", le flag -d permet de lancer le container de façon détachée. on peut voir les logs des containers avec docker logs -f container-id
- l'orchestration de containers avec docker-compose ✔️
  - docker compose permet de lancer simultanément plusieurs containers dans un seul container, ce qui évite la répétition de RUN chaque image. Il faut faire un fichier docker-compose en yml, qui permettra de définir chaque service, ses ports d'utilisation, et on orchestre avec depends_on qui indique à docker dans quel ordre lancer chaque container (le backend, puis la bdd, puis le front par exemple). On peut également faire des healthcheks pour être vérifier que le service a bien démarré avant de lancer le suivant.

## 💻 J'utilise

### Un exemple personnel commenté ❌ / ✔️

### Utilisation dans un projet ❌ / ✔️

[lien github](...) GOOD CORNER

Description : on a mis en place deux dockers files dans good corner pour le frontend et le backend. On a créé un docker compose pour relier les deux services et créer aussi la base de données avec postgres (initialement sur sqlite).

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
