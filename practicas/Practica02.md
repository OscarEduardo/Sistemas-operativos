## Objetivo

Modificar el programa sh.c para ejecuar el comando anterior

## Herramientas

git
make
gcc

## Conceptos
1) Como se crean nuevos procesos
+ un programa padre (sh.c) ejecuta la llamada a sistema fork
+ la llamada a sistema fork clona al proceso padre
+ el proceso hijo manda a llamar a exec para ejecutar otro codigo

## Que aprendi
Se realizo las modificiaciones necesarias en el codigo para poder tener un comando anterior que su funcionalidad seria ejecutar de manera automatica el comando que anteriormente se habia llamado


## Url del commit
https://github.com/OscarEduardo/Sistemas-operativos/commit/8de14cc805f389867d6df923594df20b68a06d54
