## Les 4 piliers du JS

Le minimum.

Voir plus [ici](https://developer.mozilla.org/fr/docs/Web/JavaScript)

### Les opérateurs

Affectation

```
var x = 1;
console.log(x); // 1
```

Affectation après opération

```
+= -= *= /= %=

var x = 1;
x += 1;
console.log(x); // 2
```

Opérateurs arithmétiques

```
+ - * / %

var x = 1;
console.log(x - 2); // -1
```

Egalité

```
1 == '1' // true
```

Egalité stricte

```
1 === '1' // false
```

Inégalité

`!=`

Inégalité stricte

`!==`

Supérieur

`>`

Supérieur ou égal

`>=`

Inférieur

`<`

Inférieur ou égal

`<=`

Incrémentation

```
++

var x = 1;
x++;
console.log(x); // 2
```

Décrémentation

`--`

ET logique

```
&&

1 < 2 && false // false
```

OU logique

```
||

1 < 2 || false // true
```

NON logique

```
!

!true // false
```

Concaténation de chaîne de charactères

```
+

console.log("coucou " + "balthazar"); // "coucou balthazar"
```

Renvoyer le type

```
typeof

console.log(typeof 1) // number
```

[Opérateurs](https://developer.mozilla.org/fr/docs/Web/JavaScript/Guide/Expressions_et_Op%C3%A9rateurs)

### Conditions

If.. else

```
if (condition)
   instruction1
[else
   instruction2]
```

Switch

```
switch (expression) {
  case valeur 1:
    blablabla
  case valeur 2:
    blablabla
}
```

[Switch](https://developer.mozilla.org/fr/docs/Web/JavaScript/Reference/Instructions/switch)

Opérateur ternaire

`condition ? val1 : val2`

### Boucles

For

`for (var i = 0; i < 5; i++)`

While

```
var i = 0;
while (i < 5) {
  blablabla;
  i++;
}
```

Do ... while

```
var i = 0;
do {
  blabla
  i++
} while (i < 5);
```

For in et for of

```
for (variable in objet) {
  blabla
}
```

[for in](https://developer.mozilla.org/fr/docs/Web/JavaScript/Reference/Instructions/for...in)
[for of](https://developer.mozilla.org/fr/docs/Web/JavaScript/Reference/Instructions/for...of)

### Types

Nul

`null`

Non défini

`undefined`

Nombre

`var x = 1`

String

`var truc = "caca"`

Booléen

`var oui = true`

Array

`var animeaux = ["poule", "cochon", "cacahouètes"]`

Objet

```
var balthazar = {
  chips: true,
  manger: function() {
    console.log("miam !");
  }
}
```
