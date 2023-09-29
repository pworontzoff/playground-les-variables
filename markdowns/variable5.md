# Exercice 5

Earane, la doyenne du village, a souhaité apprendre à programmer afin de pouvoir ensuite transmettre ce savoir à ses nombreux petits-enfants. Cependant, en dépit des quelques cours que vous lui avez donnés, elle n'arrive pas à terminer son premier programme. Pouvez-vous l'aider à corriger ses erreurs ?

## Que doit faire votre programme

Votre programme doit être une version corrigée du programme ci-dessous, sachant qu'il vous faut changer le moins de choses possible.

```c
#include <stdio.h>
int main()
{
	int ageCadet;
	int ageAine;
	scanf("%d", ageCadet);
	scanf(&ageAine);
	int difference = ageAine - ageDuCadet;
	printf("%d\n", difference);
}
```

La doyenne aimerait arriver à ce résultat :
```
age du fils cadet : 5
age du fils aine : 10
Difference d'age : 5
```