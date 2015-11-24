## Les 4 piliers du JS

### Les opérateurs

Affectation

`=`

Affectation après opération

`+= -= *= /= %=`

Opérateurs arithmétiques

`+ - * / %`

Egalité

`==`

Egalité stricte

`===`

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

`++`

Décrémentation

`--`

ET logique

`&&`

OU logique

`||`

NON logique

`!`

Concaténation de chaîne de charactères

`+`

Renvoyer le type

`typeof`

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