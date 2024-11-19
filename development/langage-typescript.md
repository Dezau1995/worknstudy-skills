# TypeScript

> ❌ A travailler

> ✔️ Auto validation par l'étudiant

## 🎓 J'ai compris et je peux expliquer

### l'intéret de TypeScript dans l'IDE ❌ / ✔️
  TypeScript améliore l'expérience de développement grâce à une meilleure intégration avec l'IDE :

- Autocomplétion : Les types définis permettent à l'IDE de suggérer automatiquement les propriétés et méthodes disponibles.
- Détection d'erreurs : TypeScript détecte les erreurs à la compilation avant l'exécution du code, réduisant les bugs.
- Documentation implicite : Grâce aux annotations de type, le code est auto-documenté, rendant la collaboration plus facile.

### les types de bases ❌ / ✔️
TypeScript enrichit JavaScript avec des types statiques :

Primitifs : string, number, boolean, null, undefined.
Exemple :
`let age: number = 30;
let name: string = "Alice";
`

Tableaux : définis avec type[] ou Array<type>.
`let scores: number[] = [10, 20, 30];
`

Objets : définis avec des types spécifiques ou génériques.
Tuples : pour des tableaux de tailles fixes avec des types définis.
`let tuple: [string, number] = ["Alice", 25];
`
Enums : permettent de gérer des ensembles de valeurs constantes.
`
enum Direction { North, South, East, West }
let dir: Direction = Direction.North;
`


### comment et pourquoi étendre une interface ❌ / ✔️
Étendre une interface permet de réutiliser et de combiner des structures de données tout en respectant la typage statique.

Comment : Avec le mot-clé extends.
`interface Person {
  name: string;
  age: number;
}
interface Employee extends Person {
  role: string;
}
const employee: Employee = {
  name: "Alice",
  age: 30,
  role: "Developer"
};`

Pourquoi :
- Favorise la réutilisation de code.
- Simplifie la maintenance en regroupant des propriétés communes.
- Permet de structurer des objets complexes de manière claire.


### les classes et les decorators ❌ / ✔️
- Classes :
Les classes en TypeScript suivent un modèle orienté objet pour structurer le code.

Exemple de classe avec propriétés et méthodes :
`
class Person {
  name: string;
  age: number;
  constructor(name: string, age: number) {
    this.name = name;
    this.age = age;
  }
  greet() {
    console.log(`Hello, I'm ${this.name}`);
  }
}
`

- Décorateurs :
Les décorateurs sont des fonctions qui modifient les classes ou leurs membres.
Exemple de décorateur sur une méthode :

`
function Log(target: any, propertyKey: string, descriptor: PropertyDescriptor) {
  console.log(`${propertyKey} was called`);
}
class Calculator {
  @Log
  add(a: number, b: number): number {
    return a + b;
  }
}
const calc = new Calculator();
calc.add(2, 3); // Log s'exécutera.
`

- Pourquoi utiliser les décorateurs ?

Pour appliquer des comportements réutilisables (logging, validation, etc.).
Ils facilitent les métaprogrammations dans des frameworks comme Angular ou NestJS.




## 💻 J'utilise

### Un exemple personnel commenté ❌ / ✔️

### Utilisation dans un projet ❌ / ✔️

[https://github.com/Dezau1995/TGC]

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
