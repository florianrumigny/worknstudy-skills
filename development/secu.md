# Sécurité dans le développement Web

> ❌ A travailler

> ✔️ Auto validation par l'étudiant

## 🎓 J'ai compris et je peux expliquer

- Le rôle de l'OWASP ✔️
  l'OWASP est l'organisation qui permet d'être informé des dernières failles de sécurité et mettre l'accent sur la protection des données de l'utilisateur. C'est eux qui donnent les indicateurs sur les failles les plus importantes en ce moment et mettre l'accent sur la protection.

- Les injections SQL ✔️
  Les injections SQL permettent à un utilisateur malveillant d'injecter du SQL directement dans un formulaire et potentiellement de supprimer ou récupérer des informations de la BDD. Pour éviter cela, on fait des requetes paramétrées (les ORMs s'en chargent pour nous) en utilisant le ? à la place des valeurs. Ne jamais inscrire des données en dur ou les échapper.

- XSS ✔️
  La faille Cross Site Scripting permet d'injecter du javascript / du contenu dans la page par un utilisateur malveillant. Il faut échaper / valider les données avec de les afficher en HTML. Ne jamais utiliser innerHTML, plutôt textContent. Et on peut nettoyer les données de l'utilisateur avec des librairies comme sanitize.

- CRSF ✔️

La faille de Cross Site REquest Forgery permet à un utilisateur malveillant d'accéder à des informations d'un autre domaine. On va utiliser les CORS pour s'en protéger, on utilise aussi des tokens avec des délais d'expirations et on configure nos cookies avec l'attribut SameSite

## 💻 J'utilise

### Un exemple personnel commenté ❌ / ✔️

### Utilisation dans un projet ❌ / ✔️

[lien github](...)

Description :

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
