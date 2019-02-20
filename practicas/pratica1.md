## Objetivo 
Crear dos llamadas a sistema una para apagar y otra para reiniciar. Y crear sus respectivos programas.

## Herramientas
git,
make,
gcc

## Conceptos 
1) Llamadas a sistema 
+ La forma que el kernel (SO) da acceso al HW
+ Se implementa mediante interrupciones de software (trap), ie,
la aplicacion se interrumpe para que el kernel se ejecute

2) Modo Kernel
+ Es bit/registro que activa el CPU para acceder el HW
+ Solo hay un programa que se ejecuta con este bit, es el kernel

3) Interrupciones
+ Es la forma que el HW interactua con el CPU

## Que aprendi:
Se crearon los metodos juntos con los archivos necesario para poder interactuar con el sistema operativo 
y poder dar los comandos para hacer un reinicio y un apagado de nuestro sistema, con esto tambien vimos de que 
manera hacer la investigacion para poder conocer el comando y la direccion de memoria que se tenia que modificar 
para poder realizar dichas llamadas al sistema.


## URL del commit:

https://github.com/OscarEduardo/Sistemas-operativos/commit/f64f42f3e9ee1a1edc28aa6afc4449760d3ecdb5
