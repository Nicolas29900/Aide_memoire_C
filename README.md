# Aide_memoire_C
Groupe TP12A

## Variables

``` c
type nom_variable;
``` 

Types possibles:
* int (entier)
* float (réel)
* char (caractère)

## Entrées / Sorties

### Affichage

``` c
printf("ma valeur=%d",variable);
```

Indicateur en fonction du type de variable
* %d: int
* %f: float
* %c: char
* %s: char []

### Lecture

``` c
scanf("%d",&variable);
```
## Structure de contrôle

### Tests

``` c
if (condition)
{
  //liste d'instructions
}
else
{
  //liste d'instructions
}
```

``` c
switch (variable)
{
  case valeur1: {
    //liste d'instructions
    }
  break;
  case valeur2: {
    //liste d'instructions
    }break;
  default: {
    //liste d'instructions
    }
}
```

### Boucles

``` c
for (indice=0;indice<10;indice++)
{
  //liste d'instructions
}
```

``` c
while(condition)
{
  //liste d'instructions
}
```

``` c
do
{
  //liste d'instructions
}while(condition);
```
