# Langage Javascript

> ❌ A travailler

> ✔️ Auto validation par l'étudiant

## 🎓 J'ai compris et je peux expliquer

### les `structures` de base du langage ❌ / ✔️

JavaScript est un langage dynamique avec des structures de base simples :

- Variables : on utilise let ou const pour déclarer des variables. (var est déprécié) Par exemple : let age = 25;.
- Structures conditionnelles : comme if, else, ou switch pour gérer les flux logiques.
- Boucles : for, while et for...of permettent de répéter des instructions.
- Fonctions : elles peuvent être déclarées via function nom() ou comme expressions fléchées : const addition = (a, b) => a + b;.


### les normes `ecmascript` ❌ / ✔️

ECMAScript (ES) définit les spécifications du langage JavaScript.

Chaque version (comme ES6, ES7) introduit de nouvelles fonctionnalités, comme :
- ES6 (2015) : flèches (=>), classes (class), modules (import/export), et le mot-clé let et const.
- ES8 (2017) : async/await pour une gestion plus simple de l'asynchrone.
- ES2021 : méthodes comme String.prototype.replaceAll() ou opérateurs logiques comme ??.
Ces évolutions garantissent une syntaxe moderne et de meilleures performances.


### l'utilisation de l'`asynchrone` ❌ / ✔️

JavaScript est conçu pour gérer l'asynchronisme efficacement, notamment pour des tâches non bloquantes.

- Callbacks : fonctions passées en paramètre, mais difficiles à maintenir (callback hell).
- Promises : permettent de gérer des tâches asynchrones proprement avec .then() et .catch().Exemple :
fetch('url').then(response => response.json()).catch(error => console.error(error));

- Async/Await : une syntaxe simplifiée pour travailler avec des Promises. Exemple :
const fetchData = async () => {

  try {
  
    const response = await fetch('url');
  
    const data = await response.json();
  
    console.log(data);
  
  } catch (error) {
  
    console.error(error);
  
  }
};


### les spécifités du mot-clef `this` ❌ / ✔️

Le mot-clé this en JavaScript fait référence au contexte d'exécution de la fonction. Sa signification varie :

Dans un objet : this fait référence à l'objet parent.
const obj = {

  nom: 'Alice',
  
  afficheNom() {
  
    console.log(this.nom); // 'Alice'
    
  }
};
Dans une fonction classique : dépend de son invocation, souvent undefined en mode strict.
Dans une fonction fléchée : this est lexical et ne change pas de contexte.
const arrow = () => console.log(this); // hérite de `this` du parent


## 💻 Je code en Javascript

### Un exemple de code commenté ❌ / ✔️

```javascript
(e) => mc2;
```

### Utilisation dans un projet ❌ / ✔️

[[lien github]([...](https://github.com/Dezau1995/Soundwave))]

Description :

### J'ai utilisé ce langage en production ❌ / ✔️

[lien du projet]([...](https://github.com/Dezau1995/Soundwave))

Description :

### J'ai utilisé ce langage en environement professionnel ❌ / ✔️

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

