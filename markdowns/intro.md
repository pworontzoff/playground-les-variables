# Exercices sur les variables (et les opérations / calculs de base)

Cette série d'exercice est à résoudre avec Code::Blocks disponible gratuitement (https://www.codeblocks.org/downloads/binaries/)

*Attention à bien installer une version de codeblocks avec le compilateur "mingw" qui n'est a priori pas la première version proposée !! (#fautscrollerunpeu)*

Une fois codeBlocks installé, vous pouvez créer un projet par exercice :
1) File > New > Projetcs...
1) Console application > Go
1) C > Next
1) Project title : exerciceX (remplacer X par le numéro de l'exercice)
1) Folder to create Project in: > choisir son emplacement avec le bouton "..."
1) Next
1) Vérifier que le compilateur est bien GNU GCC Compiler
1) Finish
1) Dans le volet "Manager" à gauche, vous voyez votre projet, cliquez sur les plus pour arriver à main.c. En double-cliquant celui-ci, vous pouvez le modifier dans la partie principale. Au départ vous avez un programme "hello world!" :
```c
#include <stdio.h>
#include <stdlib.h>

int main()
{
    printf("Hello world!\n");
    return 0;
}
```
Vous pouvez alors remplacer `cprintf("Hello world!\n");` par les instructions et commentaires de votre solution.
