# TypeScript

> ❌ A travailler

> ✔️ Auto validation par l'étudiant

## 🎓 J'ai compris et je peux expliquer

- l'intéret de TypeScript dans l'IDE ✔️
  permet de mieux structurer les projets, d'éviter les erreurs de syntax (meilleure gestion des gestions), de mieux maintenir le projet et d'avoir des suggestions/auto-complétions

- les types de bases ✔️
  les types de base sont : string, number, [], boolean, null, void, enum

- comment et pourquoi étendre une interface ✔️
  On étend une interface pour éviter de se repeter et pouvoir récupérer dans une autre interface / des unions

  ```typescript
  interface Person {
    name: string;
    age: number;
  }

  interface Employee extends Person {
    employeeId: string;
  }
  ```

- les classes et les decorators ✔️

Une class reprend les mêmes propriétés qu'une class en JS mais permet d'étendre ses capacités, comme le typage des propriétés de la class / methode de la class / permettre l'héritage avec extends / permet de servier d'interface/type pour autre chose

Un decorator lui agit comme une fonction qui s'applique à une class pour les modifier. On utilise le decorator @ObjectType sur une entité et la class TYPEORM pour signaler que cela sera aussi un schema en graphQL

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
