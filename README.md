# Greeting Builder

Un petit projet JavaScript pour pratiquer la manipulation de fonctions et de chaînes de caractères, basé sur une idée de [roadmap.sh](https://roadmap.sh/projects/js-greeting-builder).

## Objectif

Créer un assistant de salutations. La fonction principale, `createGreeting`, prendra en entrée le prénom, le nom, et le moment de la journée, puis retournera une chaîne de salutation appropriée.

## Fonctions à écrire

- **formatName(firstName, lastName)**  
  Retourne le prénom et le nom rassemblés dans une chaîne (ex: `"Ava Stone"`).

- **getGreeting(timeOfDay)**  
  Retourne `"Good morning"`, `"Good afternoon"` ou `"Good evening"` selon le moment de la journée fourni (`'morning'`, `'afternoon'` ou `'evening'`).

- **createGreeting(firstName, lastName, timeOfDay)**  
  Utilise les deux fonctions précédentes pour produire le message final de salutation.

## Exemple d’utilisation

```js
console.log(createGreeting('Ava', 'Stone', 'morning'));
console.log(createGreeting('Noah', 'Kim', 'evening'));
console.log(createGreeting('Mina', 'Patel', 'afternoon'));
```

### Résultat attendu

```
Good morning, Ava Stone
Good evening, Noah Kim
Good afternoon, Mina Patel
```
